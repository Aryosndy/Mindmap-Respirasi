<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Flashcard – Senyawa Non-Polar</title>
<link href="https://fonts.googleapis.com/css2?family=Syne:wght@400;700;800&family=DM+Sans:ital,wght@0,300;0,400;0,500;1,300&display=swap" rel="stylesheet">
<style>
  :root {
    --bg: #0a0f1e;
    --surface: #111827;
    --card-front: #0d1f3c;
    --card-back: #0f2d1f;
    --accent: #38f5c0;
    --accent2: #5b8cff;
    --accent3: #f5a623;
    --text: #e8f0fe;
    --muted: #7a8db0;
    --border: rgba(56,245,192,0.18);
  }

  * { box-sizing: border-box; margin: 0; padding: 0; }

  body {
    background: var(--bg);
    color: var(--text);
    font-family: 'DM Sans', sans-serif;
    min-height: 100vh;
    overflow-x: hidden;
  }

  /* Animated background */
  body::before {
    content: '';
    position: fixed;
    inset: 0;
    background:
      radial-gradient(ellipse 60% 40% at 20% 10%, rgba(56,245,192,0.07) 0%, transparent 60%),
      radial-gradient(ellipse 50% 50% at 80% 80%, rgba(91,140,255,0.08) 0%, transparent 60%);
    pointer-events: none;
    z-index: 0;
  }

  header {
    position: relative;
    z-index: 10;
    text-align: center;
    padding: 2.5rem 1rem 1rem;
  }

  .badge {
    display: inline-block;
    font-size: 0.65rem;
    font-weight: 700;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    color: var(--accent);
    border: 1px solid var(--accent);
    border-radius: 999px;
    padding: 0.3em 1.1em;
    margin-bottom: 1rem;
  }

  h1 {
    font-family: 'Syne', sans-serif;
    font-size: clamp(1.6rem, 5vw, 2.6rem);
    font-weight: 800;
    letter-spacing: -0.02em;
    line-height: 1.1;
    background: linear-gradient(135deg, var(--accent), var(--accent2));
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
  }

  .subtitle {
    color: var(--muted);
    font-size: 0.9rem;
    margin-top: 0.5rem;
  }

  /* Progress */
  .progress-wrap {
    position: relative;
    z-index: 10;
    max-width: 600px;
    margin: 1.5rem auto 0;
    padding: 0 1.5rem;
  }

  .progress-info {
    display: flex;
    justify-content: space-between;
    font-size: 0.78rem;
    color: var(--muted);
    margin-bottom: 0.4rem;
  }

  .progress-bar {
    height: 4px;
    background: rgba(255,255,255,0.08);
    border-radius: 999px;
    overflow: hidden;
  }

  .progress-fill {
    height: 100%;
    background: linear-gradient(90deg, var(--accent), var(--accent2));
    border-radius: 999px;
    transition: width 0.4s ease;
  }

  /* Card scene */
  .scene {
    position: relative;
    z-index: 10;
    width: 100%;
    max-width: 600px;
    margin: 2rem auto;
    padding: 0 1.5rem;
    perspective: 1200px;
    cursor: pointer;
  }

  .card-wrapper {
    position: relative;
    width: 100%;
    height: 320px;
    transform-style: preserve-3d;
    transition: transform 0.65s cubic-bezier(0.4, 0, 0.2, 1);
  }

  .card-wrapper.flipped {
    transform: rotateY(180deg);
  }

  .card-face {
    position: absolute;
    inset: 0;
    backface-visibility: hidden;
    -webkit-backface-visibility: hidden;
    border-radius: 20px;
    padding: 2rem 2.2rem;
    display: flex;
    flex-direction: column;
    justify-content: center;
    border: 1px solid var(--border);
    box-shadow: 0 8px 40px rgba(0,0,0,0.5);
    overflow: hidden;
  }

  .card-face::before {
    content: '';
    position: absolute;
    inset: 0;
    border-radius: 20px;
    background: radial-gradient(circle at 80% 20%, rgba(56,245,192,0.06), transparent 60%);
    pointer-events: none;
  }

  .card-front {
    background: var(--card-front);
  }

  .card-back {
    background: var(--card-back);
    transform: rotateY(180deg);
  }

  .card-category {
    font-size: 0.65rem;
    font-weight: 700;
    letter-spacing: 0.18em;
    text-transform: uppercase;
    color: var(--accent);
    margin-bottom: 1rem;
  }

  .card-question {
    font-family: 'Syne', sans-serif;
    font-size: clamp(1.1rem, 3vw, 1.5rem);
    font-weight: 700;
    line-height: 1.3;
    color: var(--text);
  }

  .card-hint {
    position: absolute;
    bottom: 1.2rem;
    right: 1.5rem;
    font-size: 0.7rem;
    color: var(--muted);
    display: flex;
    align-items: center;
    gap: 0.35rem;
  }

  .flip-icon {
    width: 14px;
    height: 14px;
    opacity: 0.5;
  }

  .card-answer {
    font-size: 0.9rem;
    line-height: 1.6;
    color: var(--text);
  }

  .card-answer ul {
    padding-left: 1.2rem;
    margin-top: 0.4rem;
  }

  .card-answer li {
    margin-bottom: 0.3rem;
  }

  .card-answer .tag {
    display: inline-block;
    background: rgba(56,245,192,0.12);
    color: var(--accent);
    border-radius: 6px;
    padding: 0.1em 0.6em;
    font-size: 0.78rem;
    font-weight: 500;
    margin: 0.15rem 0.1rem;
  }

  .card-answer .highlight {
    color: var(--accent);
    font-weight: 600;
  }

  .card-answer table {
    width: 100%;
    border-collapse: collapse;
    font-size: 0.78rem;
    margin-top: 0.5rem;
  }

  .card-answer table th {
    background: rgba(56,245,192,0.12);
    color: var(--accent);
    padding: 0.4rem 0.6rem;
    text-align: left;
    font-weight: 700;
  }

  .card-answer table td {
    padding: 0.35rem 0.6rem;
    border-bottom: 1px solid rgba(255,255,255,0.05);
  }

  .card-answer table tr:last-child td {
    border-bottom: none;
  }

  /* Controls */
  .controls {
    position: relative;
    z-index: 10;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 1rem;
    padding: 0 1.5rem 1.5rem;
    max-width: 600px;
    margin: 0 auto;
  }

  .btn {
    background: rgba(255,255,255,0.05);
    border: 1px solid rgba(255,255,255,0.1);
    color: var(--text);
    border-radius: 12px;
    padding: 0.75rem 1.8rem;
    font-family: 'DM Sans', sans-serif;
    font-size: 0.85rem;
    font-weight: 500;
    cursor: pointer;
    transition: all 0.2s;
    display: flex;
    align-items: center;
    gap: 0.5rem;
  }

  .btn:hover {
    background: rgba(255,255,255,0.1);
    border-color: rgba(255,255,255,0.2);
    transform: translateY(-1px);
  }

  .btn:active { transform: translateY(0); }

  .btn-primary {
    background: var(--accent);
    color: #0a0f1e;
    border-color: var(--accent);
    font-weight: 700;
  }

  .btn-primary:hover {
    background: #5fffce;
    border-color: #5fffce;
    transform: translateY(-1px);
  }

  /* Thumbnail nav */
  .nav-dots {
    position: relative;
    z-index: 10;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 0.4rem;
    padding: 0 1.5rem 2rem;
    max-width: 600px;
    margin: 0 auto;
  }

  .dot {
    width: 28px;
    height: 8px;
    border-radius: 4px;
    background: rgba(255,255,255,0.1);
    cursor: pointer;
    transition: all 0.2s;
  }

  .dot.active {
    background: var(--accent);
    width: 36px;
  }

  .dot.visited {
    background: rgba(56,245,192,0.35);
  }

  /* Category pills */
  .category-nav {
    position: relative;
    z-index: 10;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 0.5rem;
    padding: 0 1.5rem 1.5rem;
    max-width: 700px;
    margin: 0 auto;
  }

  .cat-pill {
    font-size: 0.7rem;
    font-weight: 600;
    letter-spacing: 0.08em;
    padding: 0.35em 1em;
    border-radius: 999px;
    border: 1px solid rgba(255,255,255,0.12);
    background: rgba(255,255,255,0.04);
    color: var(--muted);
    cursor: pointer;
    transition: all 0.2s;
  }

  .cat-pill.active, .cat-pill:hover {
    background: rgba(56,245,192,0.12);
    border-color: var(--accent);
    color: var(--accent);
  }

  /* Streak */
  .streak-row {
    position: relative;
    z-index: 10;
    display: flex;
    justify-content: center;
    gap: 2rem;
    padding: 0 1.5rem 1.5rem;
  }

  .stat-box {
    text-align: center;
  }

  .stat-num {
    font-family: 'Syne', sans-serif;
    font-size: 1.3rem;
    font-weight: 800;
    color: var(--accent);
  }

  .stat-label {
    font-size: 0.65rem;
    color: var(--muted);
    letter-spacing: 0.1em;
    text-transform: uppercase;
  }

  /* Animations */
  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(16px); }
    to { opacity: 1; transform: translateY(0); }
  }

  .scene { animation: fadeUp 0.5s ease both; }
</style>
</head>
<body>

<header>
  <div class="badge">Teknologi Bahan Alam</div>
  <h1>Senyawa Non-Polar</h1>
  <p class="subtitle">Klik kartu untuk melihat jawaban &nbsp;·&nbsp; Navigasi dengan tombol di bawah</p>
</header>

<div class="streak-row">
  <div class="stat-box"><div class="stat-num" id="totalCards">15</div><div class="stat-label">Total Kartu</div></div>
  <div class="stat-box"><div class="stat-num" id="visitedCount">0</div><div class="stat-label">Dipelajari</div></div>
  <div class="stat-box"><div class="stat-num" id="currentNum">1</div><div class="stat-label">Sekarang</div></div>
</div>

<div class="progress-wrap">
  <div class="progress-info">
    <span id="progressLabel">Kartu 1 dari 15</span>
    <span id="progressPct">0%</span>
  </div>
  <div class="progress-bar"><div class="progress-fill" id="progressFill" style="width:0%"></div></div>
</div>

<div class="category-nav" id="catNav"></div>

<div class="scene" id="scene" onclick="flipCard()">
  <div class="card-wrapper" id="cardWrapper">
    <div class="card-face card-front" id="cardFront">
      <div class="card-category" id="cardCat"></div>
      <div class="card-question" id="cardQ"></div>
      <div class="card-hint">
        <svg class="flip-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M1 4v6h6M23 20v-6h-6"/><path d="M20.49 9A9 9 0 0 0 5.64 5.64L1 10m22 4-4.64 4.36A9 9 0 0 1 3.51 15"/></svg>
        Klik untuk jawaban
      </div>
    </div>
    <div class="card-face card-back" id="cardBack">
      <div class="card-category" id="cardCatBack"></div>
      <div class="card-answer" id="cardA"></div>
    </div>
  </div>
</div>

<div class="controls">
  <button class="btn" onclick="prevCard()">← Sebelumnya</button>
  <button class="btn btn-primary" onclick="nextCard()">Selanjutnya →</button>
</div>

<div class="nav-dots" id="navDots"></div>

<script>
const cards = [
  {
    cat: "Definisi",
    q: "Apa definisi senyawa non-polar?",
    a: `Senyawa non-polar adalah senyawa dengan:<br>
      <span class="tag">Distribusi elektron merata</span>
      <span class="tag">Bentuk molekul simetris</span>
      <span class="tag">Momen dipol = 0</span>
      <span class="tag">Tidak larut dalam air</span><br><br>
      Karena distribusi elektron merata, tidak ada sisi positif/negatif dalam molekul.`
  },
  {
    cat: "Ciri-Ciri",
    q: "Sebutkan ciri-ciri utama senyawa non-polar!",
    a: `<ul>
      <li>Distribusi elektron <span class="highlight">merata</span></li>
      <li>Momen dipol <span class="highlight">μ = 0 Debye</span></li>
      <li>Geometri molekul <span class="highlight">simetris</span></li>
      <li>Tidak ada muatan parsial δ⁺ / δ⁻</li>
      <li>Tidak larut dalam air, larut dalam pelarut organik</li>
      <li>Titik didih & titik leleh <span class="highlight">relatif rendah</span></li>
      <li>Gaya antarmolekul: <span class="highlight">dispersi London</span> (lemah)</li>
      <li>Perbedaan keelektronegatifan <span class="highlight">≤ 0,4</span></li>
    </ul>`
  },
  {
    cat: "Struktur",
    q: "Bagaimana ciri struktur senyawa non-polar?",
    a: `<ul>
      <li><span class="highlight">Ikatan kovalen non-polar</span> — atom berikatan dengan atom yang sama atau keelektronegatifan hampir sama</li>
      <li><span class="highlight">Bentuk molekul simetris</span> — vektor dipol saling meniadakan</li>
      <li><span class="highlight">Gaya tarik elektron seimbang</span> — tidak ada kutub δ⁺/δ⁻</li>
    </ul>`
  },
  {
    cat: "Bentuk Molekul",
    q: "Apa saja bentuk molekul yang membuat senyawa bersifat non-polar?",
    a: `<ul>
      <li><span class="highlight">Linear</span> — CO₂ (O=C=O)</li>
      <li><span class="highlight">Tetrahedral simetris</span> — CH₄</li>
      <li><span class="highlight">Trigonal planar simetris</span> — BF₃</li>
      <li><span class="highlight">Diatomik homonuklir</span> — H₂, N₂, Cl₂</li>
      <li><span class="highlight">Oktahedral</span> — SF₆</li>
    </ul>
    <br>Kunci: semua vektor dipol saling <span class="highlight">meniadakan (resultan = 0)</span>`
  },
  {
    cat: "Sifat Fisik",
    q: "Apa sifat fisik senyawa non-polar?",
    a: `<ul>
      <li>Titik didih <span class="highlight">relatif rendah</span></li>
      <li><span class="highlight">Tidak larut</span> dalam air (pelarut polar)</li>
      <li><span class="highlight">Larut</span> dalam pelarut non-polar (heksana, eter)</li>
      <li>Tidak menghantarkan listrik</li>
    </ul>
    <br><em>Prinsip: <span class="highlight">"like dissolves like"</span> — non-polar larut dalam non-polar</em>`
  },
  {
    cat: "Gaya Antarmolekul",
    q: "Apa gaya antarmolekul pada senyawa non-polar?",
    a: `Gaya antarmolekul pada senyawa non-polar adalah <span class="highlight">Gaya London (Gaya Dispersi)</span>.<br><br>
      <ul>
        <li>Timbul akibat <span class="highlight">dipol sesaat</span> (fluktuasi elektron)</li>
        <li>Tergolong <span class="highlight">lemah</span> dibanding dipol-dipol atau ikatan hidrogen</li>
        <li>Kekuatannya meningkat seiring <span class="highlight">massa molekul relatif (Mr)</span> yang lebih besar</li>
      </ul>`
  },
  {
    cat: "Kegunaan",
    q: "Apa saja kegunaan senyawa non-polar dalam kehidupan?",
    a: `<ul>
      <li>🔥 <span class="highlight">Bahan bakar</span> — hidrokarbon (bensin, LPG)</li>
      <li>🕯️ <span class="highlight">Pembuatan lilin & plastik</span></li>
      <li>🧪 <span class="highlight">Pelarut organik</span> — heksana, kloroform</li>
      <li>🌊 Berperan dalam <span class="highlight">pencemaran minyak di laut</span> (tidak bercampur air)</li>
      <li>💊 Pelarut dalam industri farmasi</li>
    </ul>`
  },
  {
    cat: "Contoh Senyawa",
    q: "Sebutkan contoh-contoh senyawa non-polar beserta nama kimianya!",
    a: `<ul>
      <li><span class="highlight">H₂</span> — Hidrogen</li>
      <li><span class="highlight">O₂</span> — Oksigen</li>
      <li><span class="highlight">N₂</span> — Nitrogen</li>
      <li><span class="highlight">Cl₂</span> — Klorin</li>
      <li><span class="highlight">CH₄</span> — Metana</li>
      <li><span class="highlight">CO₂</span> — Karbon dioksida</li>
      <li><span class="highlight">CCl₄</span> — Karbon tetraklorida</li>
      <li><span class="highlight">C₆H₆</span> — Benzena</li>
    </ul>`
  },
  {
    cat: "Analisis Molekul",
    q: "Mengapa CH₄ bersifat non-polar? Jelaskan!",
    a: `<span class="highlight">CH₄ (Metana) → Non-polar</span><br><br>
      <ul>
        <li>Bentuk molekul: <span class="highlight">tetrahedral simetris</span></li>
        <li>4 ikatan C–H memiliki dipol, namun karena simetris, vektor dipol <span class="highlight">saling meniadakan</span></li>
        <li>Resultan momen dipol = <span class="highlight">0 Debye</span></li>
        <li>Perbedaan keelektronegatifan C & H ≈ 0,4 (kecil)</li>
      </ul>`
  },
  {
    cat: "Analisis Molekul",
    q: "Mengapa CO₂ bersifat non-polar padahal memiliki ikatan polar?",
    a: `<span class="highlight">CO₂ (Karbon Dioksida) → Non-polar</span><br><br>
      <ul>
        <li>Setiap ikatan C=O bersifat <span class="highlight">polar</span> (karena perbedaan keelektronegatifan)</li>
        <li>Bentuk molekul: <span class="highlight">linear simetris</span> (O=C=O)</li>
        <li>Dua vektor dipol berlawanan arah dan sama besar → <span class="highlight">saling menghapus</span></li>
        <li>Resultan momen dipol = <span class="highlight">0</span></li>
      </ul>
      <em>Kunci: polar bond ≠ polar molecule jika bentuknya simetris!</em>`
  },
  {
    cat: "Analisis Molekul",
    q: "Mengapa O₂ dan N₂ bersifat non-polar?",
    a: `<span class="highlight">O₂ & N₂ → Non-polar</span><br><br>
      <ul>
        <li>Merupakan molekul <span class="highlight">diatomik homonuklir</span> (atom sejenis)</li>
        <li>Tidak ada perbedaan keelektronegatifan antara dua atom</li>
        <li>Elektron terbagi <span class="highlight">merata sempurna</span></li>
        <li>Momen dipol = <span class="highlight">0 Debye</span></li>
      </ul>`
  },
  {
    cat: "Perbedaan",
    q: "Apa perbedaan senyawa polar vs non-polar dari segi distribusi elektron dan momen dipol?",
    a: `<table>
      <tr><th>Aspek</th><th>Polar</th><th>Non-Polar</th></tr>
      <tr><td>Distribusi e⁻</td><td>Tidak merata</td><td>Merata</td></tr>
      <tr><td>Momen dipol</td><td>μ > 0</td><td>μ = 0</td></tr>
    </table>`
  },
  {
    cat: "Perbedaan",
    q: "Bagaimana perbedaan polar vs non-polar dari segi geometri, kelarutan, dan titik didih?",
    a: `<table>
      <tr><th>Aspek</th><th>Polar</th><th>Non-Polar</th></tr>
      <tr><td>Geometri</td><td>Asimetris</td><td>Simetris</td></tr>
      <tr><td>Kelarutan</td><td>Larut di air</td><td>Larut di organik</td></tr>
      <tr><td>Gaya antarmol.</td><td>Dipol-dipol / H</td><td>Dispersi London</td></tr>
      <tr><td>Titik didih</td><td>Lebih tinggi</td><td>Lebih rendah</td></tr>
    </table>`
  },
  {
    cat: "Perbedaan",
    q: "Berikan contoh senyawa polar dan non-polar serta perbedaan cara mengenalinya!",
    a: `<table>
      <tr><th></th><th>Polar</th><th>Non-Polar</th></tr>
      <tr><td>Contoh</td><td>H₂O, HCl, NH₃</td><td>CH₄, CO₂, O₂</td></tr>
    </table><br>
    <span class="highlight">Cara mengenali:</span><br>
    <ul>
      <li>Polar: pasangan elektron bebas tidak simetris → μ ≠ 0</li>
      <li>Non-polar: semua dipol ikatan meniadakan satu sama lain → μ = 0</li>
    </ul>`
  },
  {
    cat: "Ringkasan",
    q: "Bagaimana cara cepat menentukan apakah suatu senyawa bersifat non-polar?",
    a: `<span class="highlight">Langkah Analisis Non-Polar:</span><br><br>
      <ol style="padding-left:1.2rem;line-height:1.9">
        <li>Lihat atom — <strong>atom sejenis</strong>? → Non-polar (H₂, N₂)</li>
        <li>Hitung perbedaan keelektronegatifan — <strong>≤ 0,4</strong>? → Non-polar</li>
        <li>Tentukan geometri molekul — <strong>simetris</strong>? → Non-polar</li>
        <li>Cek resultan vektor dipol — <strong>= 0</strong>? → Non-polar</li>
      </ol>`
  }
];

let current = 0;
let flipped = false;
let visited = new Set();
const categories = [...new Set(cards.map(c => c.cat))];

function render() {
  const card = cards[current];
  document.getElementById('cardCat').textContent = card.cat;
  document.getElementById('cardCatBack').textContent = card.cat;
  document.getElementById('cardQ').textContent = card.q;
  document.getElementById('cardA').innerHTML = card.a;

  document.getElementById('progressLabel').textContent = `Kartu ${current+1} dari ${cards.length}`;
  document.getElementById('progressPct').textContent = Math.round((visited.size/cards.length)*100) + '%';
  document.getElementById('progressFill').style.width = (visited.size/cards.length*100) + '%';
  document.getElementById('currentNum').textContent = current + 1;
  document.getElementById('visitedCount').textContent = visited.size;

  document.querySelectorAll('.dot').forEach((d,i) => {
    d.className = 'dot' + (i===current ? ' active' : '') + (visited.has(i) && i!==current ? ' visited' : '');
  });
}

function flipCard() {
  flipped = !flipped;
  document.getElementById('cardWrapper').classList.toggle('flipped', flipped);
  if (flipped) visited.add(current);
  render();
}

function goTo(idx) {
  flipped = false;
  document.getElementById('cardWrapper').classList.remove('flipped');
  current = idx;
  // re-trigger animation
  const scene = document.getElementById('scene');
  scene.style.animation = 'none';
  scene.offsetHeight;
  scene.style.animation = '';
  render();
}

function nextCard() {
  goTo((current + 1) % cards.length);
}

function prevCard() {
  goTo((current - 1 + cards.length) % cards.length);
}

// Build dots
const dotsEl = document.getElementById('navDots');
cards.forEach((_, i) => {
  const d = document.createElement('div');
  d.className = 'dot';
  d.onclick = () => goTo(i);
  dotsEl.appendChild(d);
});

// Build category nav
const catNav = document.getElementById('catNav');
const allPill = document.createElement('div');
allPill.className = 'cat-pill active';
allPill.textContent = 'Semua';
allPill.onclick = () => {
  document.querySelectorAll('.cat-pill').forEach(p => p.classList.remove('active'));
  allPill.classList.add('active');
  goTo(0);
};
catNav.appendChild(allPill);

categories.forEach(cat => {
  const pill = document.createElement('div');
  pill.className = 'cat-pill';
  pill.textContent = cat;
  pill.onclick = () => {
    document.querySelectorAll('.cat-pill').forEach(p => p.classList.remove('active'));
    pill.classList.add('active');
    const idx = cards.findIndex(c => c.cat === cat);
    if (idx >= 0) goTo(idx);
  };
  catNav.appendChild(pill);
});

// Keyboard navigation
document.addEventListener('keydown', e => {
  if (e.key === 'ArrowRight') nextCard();
  else if (e.key === 'ArrowLeft') prevCard();
  else if (e.key === ' ') { e.preventDefault(); flipCard(); }
});

document.getElementById('totalCards').textContent = cards.length;
render();
</script>
</body>
</html>
