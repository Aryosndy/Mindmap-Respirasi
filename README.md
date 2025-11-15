<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Infografis Uji Fitokimia Steroid</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            background: #f0f0f0;
            padding: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .infographic {
            width: 800px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            border-radius: 20px;
            overflow: hidden;
            box-shadow: 0 20px 60px rgba(0,0,0,0.3);
        }

        .header {
            background: linear-gradient(135deg, #0077BE, #00BCD4);
            padding: 40px;
            text-align: center;
            color: white;
            position: relative;
            overflow: hidden;
        }

        .header::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: repeating-linear-gradient(
                45deg,
                transparent,
                transparent 10px,
                rgba(255,255,255,0.05) 10px,
                rgba(255,255,255,0.05) 20px
            );
            animation: wave 20s linear infinite;
        }

        @keyframes wave {
            0% { transform: translate(0, 0); }
            100% { transform: translate(50%, 50%); }
        }

        .header h1 {
            font-size: 36px;
            font-weight: bold;
            margin-bottom: 10px;
            position: relative;
            z-index: 1;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        .header .subtitle {
            font-size: 18px;
            margin-bottom: 20px;
            position: relative;
            z-index: 1;
            opacity: 0.95;
        }

        .team {
            background: rgba(255,255,255,0.2);
            padding: 15px;
            border-radius: 10px;
            margin-top: 15px;
            position: relative;
            z-index: 1;
            backdrop-filter: blur(10px);
        }

        .team h3 {
            font-size: 16px;
            margin-bottom: 10px;
        }

        .team-member {
            font-size: 13px;
            margin: 5px 0;
            opacity: 0.95;
        }

        .content {
            background: white;
            padding: 40px;
        }

        .section {
            margin-bottom: 35px;
        }

        .section-title {
            background: linear-gradient(135deg, #0077BE, #00BCD4);
            color: white;
            padding: 15px 20px;
            border-radius: 10px;
            font-size: 22px;
            font-weight: bold;
            margin-bottom: 20px;
            display: flex;
            align-items: center;
            gap: 10px;
            box-shadow: 0 4px 15px rgba(0,119,190,0.3);
        }

        .icon {
            font-size: 28px;
        }

        .text-content {
            line-height: 1.8;
            color: #333;
            font-size: 15px;
            margin-bottom: 15px;
        }

        .highlight-box {
            background: linear-gradient(135deg, #E3F2FD, #B3E5FC);
            border-left: 5px solid #0077BE;
            padding: 20px;
            border-radius: 10px;
            margin: 20px 0;
        }

        .highlight-box strong {
            color: #0077BE;
            display: block;
            margin-bottom: 10px;
            font-size: 16px;
        }

        .grid-2 {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
            margin: 20px 0;
        }

        .card {
            background: #f8f9fa;
            border-radius: 12px;
            padding: 20px;
            border: 2px solid #e0e0e0;
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 25px rgba(0,0,0,0.15);
        }

        .card h4 {
            color: #0077BE;
            margin-bottom: 15px;
            font-size: 18px;
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .card ul {
            list-style: none;
            padding: 0;
        }

        .card li {
            padding: 8px 0;
            border-bottom: 1px solid #e0e0e0;
            font-size: 14px;
        }

        .card li:last-child {
            border-bottom: none;
        }

        .card li::before {
            content: "✓";
            color: #00BCD4;
            font-weight: bold;
            margin-right: 8px;
        }

        .method-box {
            background: linear-gradient(135deg, #FFF3E0, #FFE0B2);
            border-radius: 15px;
            padding: 25px;
            margin: 20px 0;
            border: 3px solid #FF9800;
        }

        .method-title {
            color: #E65100;
            font-size: 20px;
            font-weight: bold;
            margin-bottom: 15px;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .steps {
            background: white;
            border-radius: 10px;
            padding: 15px;
            margin: 15px 0;
        }

        .step {
            display: flex;
            align-items: start;
            margin: 12px 0;
            gap: 12px;
        }

        .step-number {
            background: linear-gradient(135deg, #0077BE, #00BCD4);
            color: white;
            width: 30px;
            height: 30px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
            flex-shrink: 0;
            box-shadow: 0 3px 10px rgba(0,119,190,0.4);
        }

        .step-text {
            flex: 1;
            padding-top: 4px;
            font-size: 14px;
            line-height: 1.6;
        }

        .result-positive {
            background: linear-gradient(135deg, #C8E6C9, #A5D6A7);
            border: 3px solid #4CAF50;
            border-radius: 12px;
            padding: 20px;
            margin: 15px 0;
            text-align: center;
        }

        .result-positive strong {
            color: #2E7D32;
            font-size: 18px;
            display: block;
            margin-bottom: 10px;
        }

        .result-text {
            color: #1B5E20;
            font-size: 15px;
            font-weight: 600;
        }

        .warning-box {
            background: linear-gradient(135deg, #FFEBEE, #FFCDD2);
            border-left: 5px solid #F44336;
            padding: 20px;
            border-radius: 10px;
            margin: 20px 0;
        }

        .warning-box li {
            margin: 10px 0;
            font-size: 14px;
            line-height: 1.6;
        }

        .references {
            background: #f8f9fa;
            padding: 20px;
            border-radius: 10px;
            border: 2px solid #dee2e6;
        }

        .references ol {
            padding-left: 20px;
        }

        .references li {
            margin: 12px 0;
            line-height: 1.7;
            font-size: 13px;
            color: #495057;
        }

        .footer {
            background: linear-gradient(135deg, #0077BE, #00BCD4);
            color: white;
            text-align: center;
            padding: 25px;
            font-size: 14px;
        }

        .footer strong {
            display: block;
            margin-bottom: 8px;
            font-size: 16px;
        }

        .molecule-bg {
            opacity: 0.05;
            position: absolute;
            font-size: 200px;
            right: -50px;
            top: 50%;
            transform: translateY(-50%);
        }

        @media print {
            body {
                background: white;
                padding: 0;
            }
            .infographic {
                box-shadow: none;
            }
        }
    </style>
</head>
<body>
    <div class="infographic">
        <!-- Header -->
        <div class="header">
            <h1>🧬 UJI FITOKIMIA KUALITATIF</h1>
            <div class="subtitle">SENYAWA STEROID DARI ORGANISME LAUT</div>
            <div class="team">
                <h3>Kelompok [Nomor] - Kelas [A/B]</h3>
                <div class="team-member">1. [Nama Lengkap] - [NPM]</div>
                <div class="team-member">2. [Nama Lengkap] - [NPM]</div>
                <div class="team-member">3. [Nama Lengkap] - [NPM]</div>
                <div class="team-member">4. [Nama Lengkap] - [NPM]</div>
            </div>
        </div>

        <!-- Content -->
        <div class="content">
            <!-- Pengertian -->
            <div class="section">
                <div class="section-title">
                    <span class="icon">🔬</span>
                    APA ITU STEROID?
                </div>
                <div class="text-content">
                    Steroid adalah senyawa organik lipid dengan struktur inti <strong>siklopentanoperhidrofenantren</strong> yang terdiri dari 4 cincin karbon (3 cincin sikloheksana dan 1 cincin siklopentana).
                </div>
                
                <div class="grid-2">
                    <div class="card">
                        <h4>📋 KARAKTERISTIK</h4>
                        <ul>
                            <li>Senyawa lipofilik (larut lemak)</li>
                            <li>Memiliki gugus hidroksil (-OH)</li>
                            <li>Struktur multi-cincin kaku</li>
                            <li>Berat molekul tinggi</li>
                        </ul>
                    </div>
                    <div class="card">
                        <h4>💊 MANFAAT BIOAKTIF</h4>
                        <ul>
                            <li>Anti-inflamasi</li>
                            <li>Antibakteri</li>
                            <li>Antioksidan</li>
                            <li>Antikanker</li>
                        </ul>
                    </div>
                </div>
            </div>

            <!-- Organisme Laut -->
            <div class="section">
                <div class="section-title">
                    <span class="icon">🌊</span>
                    ORGANISME LAUT PENGHASIL STEROID
                </div>
                
                <div class="grid-2">
                    <div class="card">
                        <h4>🌿 MAKROALGA</h4>
                        <ul>
                            <li>Sargassum sp.</li>
                            <li>Turbinaria sp.</li>
                            <li>Padina sp.</li>
                            <li>Ulva sp.</li>
                        </ul>
                    </div>
                    <div class="card">
                        <h4>🦠 MIKROALGA</h4>
                        <ul>
                            <li>Dunaliella salina</li>
                            <li>Chlorella vulgaris</li>
                            <li>Nannochloropsis sp.</li>
                            <li>Spirulina platensis</li>
                        </ul>
                    </div>
                </div>

                <div class="highlight-box">
                    <strong>🐚 INVERTEBRATA LAUT:</strong>
                    Spons (Haliclona sp., Petrosia sp.) • Karang Lunak (Sinularia sp.) • Teripang (Holothuria sp.) • Bintang Laut (Asteroidea)
                </div>
            </div>

            <!-- Metode 1 -->
            <div class="section">
                <div class="section-title">
                    <span class="icon">🧪</span>
                    METODE UJI 1: LIEBERMANN-BURCHARD
                </div>

                <div class="method-box">
                    <div class="method-title">⚗️ REAGEN</div>
                    <div class="text-content">
                        • Asam asetat anhidrat (CH₃CO)₂O<br>
                        • Asam sulfat pekat (H₂SO₄)
                    </div>

                    <div class="method-title">📝 PROSEDUR</div>
                    <div class="steps">
                        <div class="step">
                            <div class="step-number">1</div>
                            <div class="step-text">Masukkan ekstrak sampel ke dalam tabung reaksi</div>
                        </div>
                        <div class="step">
                            <div class="step-number">2</div>
                            <div class="step-text">Tambahkan 2 mL asam asetat anhidrat, kocok hingga homogen</div>
                        </div>
                        <div class="step">
                            <div class="step-number">3</div>
                            <div class="step-text">Tambahkan 1-2 tetes H₂SO₄ pekat melalui dinding tabung (hati-hati!)</div>
                        </div>
                        <div class="step">
                            <div class="step-number">4</div>
                            <div class="step-text">Amati perubahan warna yang terjadi</div>
                        </div>
                    </div>

                    <div class="method-title">⚛️ REAKSI KIMIA</div>
                    <div class="text-content">
                        Oksidasi gugus hidroksil (-OH) pada struktur steroid membentuk senyawa terkonjugasi berwarna
                    </div>

                    <div class="result-positive">
                        <strong>✅ HASIL POSITIF</strong>
                        <div class="result-text">Terbentuk warna HIJAU atau BIRU KEHIJAUAN<br>
                        Intensitas warna menunjukkan konsentrasi steroid</div>
                    </div>
                </div>
            </div>

            <!-- Metode 2 -->
            <div class="section">
                <div class="section-title">
                    <span class="icon">🧪</span>
                    METODE UJI 2: SALKOWSKI
                </div>

                <div class="method-box">
                    <div class="method-title">⚗️ REAGEN</div>
                    <div class="text-content">
                        • Kloroform (CHCl₃)<br>
                        • Asam sulfat pekat (H₂SO₄)
                    </div>

                    <div class="method-title">📝 PROSEDUR</div>
                    <div class="steps">
                        <div class="step">
                            <div class="step-number">1</div>
                            <div class="step-text">Masukkan ekstrak sampel ke dalam tabung reaksi</div>
                        </div>
                        <div class="step">
                            <div class="step-number">2</div>
                            <div class="step-text">Tambahkan 2 mL kloroform, kocok perlahan</div>
                        </div>
                        <div class="step">
                            <div class="step-number">3</div>
                            <div class="step-text">Tambahkan H₂SO₄ pekat hati-hati melalui dinding tabung (membentuk 2 lapisan)</div>
                        </div>
                        <div class="step">
                            <div class="step-number">4</div>
                            <div class="step-text">Diamkan dan amati batas antar lapisan (interfase)</div>
                        </div>
                    </div>

                    <div class="method-title">⚛️ REAKSI KIMIA</div>
                    <div class="text-content">
                        Dehidrasi dan oksidasi molekul steroid dalam kondisi asam kuat menghasilkan senyawa berwarna
                    </div>

                    <div class="result-positive">
                        <strong>✅ HASIL POSITIF</strong>
                        <div class="result-text">Terbentuk CINCIN MERAH atau COKLAT KEMERAHAN<br>
                        pada batas kedua lapisan (interfase)<br>
                        Lapisan atas (H₂SO₄): kuning keemasan<br>
                        Lapisan bawah (kloroform): merah/coklat</div>
                    </div>
                </div>
            </div>

            <!-- Warning -->
            <div class="section">
                <div class="section-title">
                    <span class="icon">⚠️</span>
                    HAL YANG PERLU DIPERHATIKAN
                </div>

                <div class="warning-box">
                    <ul>
                        <li>🔴 H₂SO₄ pekat bersifat korosif - gunakan dengan hati-hati!</li>
                        <li>🔴 Kerjakan di ruang berventilasi baik (asap berbahaya)</li>
                        <li>🔴 Gunakan APD lengkap (jas lab, sarung tangan, kacamata)</li>
                        <li>🔴 Reaksi menghasilkan panas - hindari wadah tertutup</li>
                        <li>✅ Uji positif harus dikonfirmasi dengan metode lain</li>
                        <li>✅ Ekstraksi sampel gunakan pelarut organik</li>
                    </ul>
                </div>
            </div>

            <!-- Referensi -->
            <div class="section">
                <div class="section-title">
                    <span class="icon">📚</span>
                    REFERENSI
                </div>

                <div class="references">
                    <ol>
                        <li>Harborne, J.B. (1987). <em>Metode Fitokimia: Penuntun Cara Modern Menganalisis Tumbuhan</em>. Terbitan Kedua. Bandung: Penerbit ITB.</li>
                        <li>Zhao, C., Yang, C., Liu, B., Lin, L., Sarker, S.D., Nahar, L., Yu, H., Cao, H., & Xiao, J. (2018). Bioactive compounds from marine macroalgae and their hypoglycemic benefits. <em>Trends in Food Science & Technology</em>, 72, 1-12.</li>
                        <li>Ergene, A., Guler, P., Tan, S., Mirici, S., Hamzaoglu, E., & Duran, A. (2006). Antibacterial and antifungal activity of Heracleum sphondylium. <em>African Journal of Biotechnology</em>, 5(11), 1087-1089.</li>
                    </ol>
                </div>
            </div>
        </div>

        <!-- Footer -->
        <div class="footer">
            <strong>Infografis Tugas KOBA - Kimia Organik Bahan Alam</strong>
            <div>Instagram: @[username] | #FitokimiaLaut #SteroidAlami #KOBA</div>
            <div style="margin-top: 10px; font-size: 12px;">
                Tag: @_gerardoh_ @adrians_maulana @margat___ @sfraurelia
            </div>
        </div>
    </div>
</body>
</html>
