<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Both Sides — See Every Story Whole</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,700;1,400&family=DM+Sans:wght@300;400;500&family=DM+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
  :root {
    --bg: #0a0a0a;
    --bg2: #111111;
    --bg3: #181818;
    --border: rgba(255,255,255,0.08);
    --border2: rgba(255,255,255,0.14);
    --text: #f0ede8;
    --text2: #8a8680;
    --text3: #4a4845;
    --accent-a: #4a7fa5;
    --accent-a-bg: rgba(74,127,165,0.12);
    --accent-a-border: rgba(74,127,165,0.3);
    --accent-b: #b85c38;
    --accent-b-bg: rgba(184,92,56,0.12);
    --accent-b-border: rgba(184,92,56,0.3);
    --neutral: #8a8680;
    --red: #c0392b;
    --serif: 'Playfair Display', Georgia, serif;
    --sans: 'DM Sans', sans-serif;
    --mono: 'DM Mono', monospace;
  }

  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  html { scroll-behavior: smooth; }

  body {
    background: var(--bg);
    color: var(--text);
    font-family: var(--sans);
    font-weight: 300;
    line-height: 1.6;
    min-height: 100vh;
    overflow-x: hidden;
  }

  /* NOISE TEXTURE OVERLAY */
  body::before {
    content: '';
    position: fixed;
    inset: 0;
    background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noise'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noise)' opacity='0.03'/%3E%3C/svg%3E");
    pointer-events: none;
    z-index: 0;
    opacity: 0.4;
  }

  /* NAV */
  nav {
    position: sticky;
    top: 0;
    z-index: 100;
    background: rgba(10,10,10,0.92);
    backdrop-filter: blur(12px);
    border-bottom: 1px solid var(--border);
    padding: 0 2rem;
    height: 56px;
    display: flex;
    align-items: center;
    justify-content: space-between;
  }

  .nav-logo {
    display: flex;
    align-items: center;
    gap: 10px;
    text-decoration: none;
  }

  .logo-mark {
    display: flex;
    gap: 3px;
    align-items: center;
  }

  .logo-bar {
    width: 3px;
    height: 18px;
    border-radius: 2px;
  }

  .logo-bar-a { background: var(--accent-a); }
  .logo-bar-sep { width: 1px; height: 10px; background: var(--border2); }
  .logo-bar-b { background: var(--accent-b); }

  .logo-text {
    font-family: var(--serif);
    font-size: 17px;
    color: var(--text);
    letter-spacing: 0.01em;
  }

  .nav-tag {
    font-family: var(--mono);
    font-size: 11px;
    color: var(--text3);
    letter-spacing: 0.08em;
  }

  /* HERO */
  .hero {
    position: relative;
    padding: 6rem 2rem 4rem;
    max-width: 900px;
    margin: 0 auto;
    text-align: center;
    z-index: 1;
  }

  .hero-eyebrow {
    font-family: var(--mono);
    font-size: 11px;
    letter-spacing: 0.14em;
    color: var(--text3);
    text-transform: uppercase;
    margin-bottom: 1.5rem;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 10px;
  }

  .eyebrow-line {
    width: 32px;
    height: 1px;
    background: var(--border2);
  }

  .hero h1 {
    font-family: var(--serif);
    font-size: clamp(42px, 7vw, 82px);
    font-weight: 400;
    line-height: 1.08;
    color: var(--text);
    margin-bottom: 1.5rem;
    letter-spacing: -0.02em;
  }

  .hero h1 em {
    font-style: italic;
    color: var(--text2);
  }

  .hero-sub {
    font-size: 16px;
    color: var(--text2);
    max-width: 520px;
    margin: 0 auto 3rem;
    line-height: 1.7;
  }

  /* SEARCH */
  .search-wrap {
    max-width: 680px;
    margin: 0 auto 2rem;
    position: relative;
    z-index: 1;
  }

  .search-box {
    width: 100%;
    background: var(--bg2);
    border: 1px solid var(--border2);
    border-radius: 4px;
    padding: 16px 140px 16px 20px;
    font-family: var(--sans);
    font-size: 15px;
    font-weight: 300;
    color: var(--text);
    outline: none;
    transition: border-color 0.2s;
  }

  .search-box::placeholder { color: var(--text3); }
  .search-box:focus { border-color: rgba(255,255,255,0.25); }

  .search-btn {
    position: absolute;
    right: 6px;
    top: 50%;
    transform: translateY(-50%);
    background: var(--text);
    color: var(--bg);
    border: none;
    border-radius: 3px;
    padding: 9px 20px;
    font-family: var(--sans);
    font-size: 13px;
    font-weight: 500;
    cursor: pointer;
    transition: opacity 0.15s, transform 0.1s;
    white-space: nowrap;
  }

  .search-btn:hover { opacity: 0.85; }
  .search-btn:active { transform: translateY(-50%) scale(0.97); }

  /* API KEY SETUP */
  .api-setup {
    max-width: 680px;
    margin: 0 auto 1.5rem;
    background: var(--bg2);
    border: 1px solid var(--border2);
    border-radius: 4px;
    padding: 14px 18px;
    display: flex;
    align-items: center;
    gap: 12px;
    flex-wrap: wrap;
  }

  .api-label {
    font-family: var(--mono);
    font-size: 11px;
    color: var(--text3);
    letter-spacing: 0.06em;
    white-space: nowrap;
  }

  .api-input {
    flex: 1;
    min-width: 200px;
    background: transparent;
    border: none;
    border-bottom: 1px solid var(--border2);
    padding: 4px 0;
    font-family: var(--mono);
    font-size: 12px;
    color: var(--text);
    outline: none;
  }

  .api-input::placeholder { color: var(--text3); }

  .api-save {
    background: transparent;
    border: 1px solid var(--border2);
    border-radius: 3px;
    padding: 5px 14px;
    font-family: var(--mono);
    font-size: 11px;
    color: var(--text2);
    cursor: pointer;
    transition: all 0.15s;
  }

  .api-save:hover { border-color: var(--border2); color: var(--text); background: var(--bg3); }

  .api-status {
    font-family: var(--mono);
    font-size: 11px;
    color: #4a9460;
    display: none;
  }

  /* TOPIC CHIPS */
  .topics {
    max-width: 680px;
    margin: 0 auto 5rem;
    display: flex;
    gap: 8px;
    flex-wrap: wrap;
    justify-content: center;
    z-index: 1;
    position: relative;
  }

  .t-chip {
    font-family: var(--mono);
    font-size: 11px;
    letter-spacing: 0.04em;
    padding: 5px 14px;
    border-radius: 2px;
    border: 1px solid var(--border);
    color: var(--text3);
    cursor: pointer;
    transition: all 0.15s;
    background: transparent;
  }

  .t-chip:hover { border-color: var(--border2); color: var(--text2); background: var(--bg2); }
  .t-chip.active { border-color: rgba(255,255,255,0.2); color: var(--text); background: var(--bg2); }

  /* DIVIDER */
  .section-divider {
    border: none;
    border-top: 1px solid var(--border);
    margin: 0;
  }

  /* OUTPUT SECTION */
  #output {
    max-width: 960px;
    margin: 0 auto;
    padding: 0 2rem 6rem;
    position: relative;
    z-index: 1;
  }

  /* LOADING */
  .loading-state {
    text-align: center;
    padding: 6rem 2rem;
  }

  .loading-ticker {
    font-family: var(--mono);
    font-size: 12px;
    color: var(--text3);
    letter-spacing: 0.08em;
    animation: fadetext 2s ease infinite;
  }

  @keyframes fadetext {
    0%, 100% { opacity: 0.3; }
    50% { opacity: 1; }
  }

  /* RESULT LAYOUT */
  .result-header {
    padding: 3rem 0 2rem;
    border-bottom: 1px solid var(--border);
    margin-bottom: 2rem;
  }

  .result-meta {
    display: flex;
    align-items: center;
    gap: 16px;
    margin-bottom: 1rem;
  }

  .live-pill {
    display: inline-flex;
    align-items: center;
    gap: 6px;
    font-family: var(--mono);
    font-size: 10px;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    color: var(--red);
    border: 1px solid rgba(192,57,43,0.3);
    border-radius: 2px;
    padding: 3px 10px;
  }

  .live-dot {
    width: 5px;
    height: 5px;
    border-radius: 50%;
    background: var(--red);
    animation: pulse 1.4s ease infinite;
  }

  @keyframes pulse { 0%,100%{opacity:1} 50%{opacity:0.2} }

  .result-date {
    font-family: var(--mono);
    font-size: 11px;
    color: var(--text3);
  }

  .result-title {
    font-family: var(--serif);
    font-size: clamp(26px, 4vw, 44px);
    font-weight: 400;
    line-height: 1.15;
    letter-spacing: -0.01em;
    color: var(--text);
    margin-bottom: 0.5rem;
  }

  .result-dispute {
    font-size: 14px;
    color: var(--text2);
    max-width: 640px;
  }

  /* SPLIT GRID */
  .split-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 1px;
    background: var(--border);
    border: 1px solid var(--border);
    border-radius: 4px;
    overflow: hidden;
    margin-bottom: 1px;
  }

  .side-panel {
    background: var(--bg);
    padding: 2rem;
  }

  .side-panel:first-child {
    border-right: 1px solid var(--border);
  }

  .side-header {
    display: flex;
    align-items: flex-start;
    justify-content: space-between;
    margin-bottom: 1.5rem;
  }

  .side-label {
    font-family: var(--mono);
    font-size: 11px;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    padding: 4px 12px;
    border-radius: 2px;
  }

  .label-a { background: var(--accent-a-bg); color: var(--accent-a); border: 1px solid var(--accent-a-border); }
  .label-b { background: var(--accent-b-bg); color: var(--accent-b); border: 1px solid var(--accent-b-border); }

  .side-stance {
    font-family: var(--serif);
    font-size: 18px;
    font-weight: 400;
    color: var(--text);
    line-height: 1.35;
    margin-bottom: 1rem;
  }

  .side-narrative {
    font-size: 14px;
    color: var(--text2);
    line-height: 1.75;
    margin-bottom: 1.5rem;
  }

  .actions-label {
    font-family: var(--mono);
    font-size: 10px;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    color: var(--text3);
    margin-bottom: 8px;
  }

  .action-item {
    font-size: 13px;
    color: var(--text2);
    padding: 7px 0;
    border-top: 1px solid var(--border);
    display: flex;
    gap: 8px;
    align-items: flex-start;
  }

  .action-item::before {
    content: '—';
    color: var(--text3);
    font-size: 12px;
    flex-shrink: 0;
    margin-top: 1px;
  }

  .side-sources {
    margin-top: 1.5rem;
    padding-top: 1rem;
    border-top: 1px solid var(--border);
  }

  .sources-label {
    font-family: var(--mono);
    font-size: 10px;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    color: var(--text3);
    margin-bottom: 6px;
  }

  .source-link {
    display: block;
    font-family: var(--mono);
    font-size: 11px;
    color: var(--text3);
    text-decoration: none;
    padding: 3px 0;
    transition: color 0.15s;
  }

  .source-link:hover { color: var(--text2); }

  /* NEUTRAL SECTION */
  .neutral-section {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    gap: 1px;
    background: var(--border);
    border: 1px solid var(--border);
    border-radius: 4px;
    overflow: hidden;
    margin-bottom: 1px;
  }

  .neutral-block {
    background: var(--bg2);
    padding: 1.5rem;
  }

  .neutral-label {
    font-family: var(--mono);
    font-size: 10px;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    color: var(--text3);
    margin-bottom: 10px;
  }

  .neutral-text {
    font-size: 13px;
    color: var(--text2);
    line-height: 1.7;
  }

  /* CLAIMS SECTION */
  .claims-section {
    border: 1px solid var(--border);
    border-radius: 4px;
    overflow: hidden;
    margin-bottom: 1px;
  }

  .claims-header {
    padding: 14px 1.5rem;
    background: var(--bg2);
    border-bottom: 1px solid var(--border);
    font-family: var(--mono);
    font-size: 10px;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    color: var(--text3);
  }

  .claim-row {
    display: flex;
    gap: 16px;
    padding: 14px 1.5rem;
    border-bottom: 1px solid var(--border);
    align-items: flex-start;
    background: var(--bg);
  }

  .claim-row:last-child { border-bottom: none; }

  .claim-tag {
    font-family: var(--mono);
    font-size: 10px;
    letter-spacing: 0.06em;
    padding: 3px 10px;
    border-radius: 2px;
    white-space: nowrap;
    flex-shrink: 0;
    margin-top: 2px;
  }

  .tag-a { background: var(--accent-a-bg); color: var(--accent-a); }
  .tag-b { background: var(--accent-b-bg); color: var(--accent-b); }

  .claim-text {
    font-size: 14px;
    color: var(--text);
    line-height: 1.55;
  }

  /* BOOKS */
  .books-section {
    margin-top: 3rem;
    padding-top: 2rem;
    border-top: 1px solid var(--border);
  }

  .books-header {
    display: flex;
    align-items: baseline;
    gap: 16px;
    margin-bottom: 1.5rem;
  }

  .books-title {
    font-family: var(--serif);
    font-size: 22px;
    font-weight: 400;
    color: var(--text);
  }

  .books-sub {
    font-family: var(--mono);
    font-size: 11px;
    color: var(--text3);
  }

  .books-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 1px;
    background: var(--border);
    border: 1px solid var(--border);
    border-radius: 4px;
    overflow: hidden;
  }

  .book-card {
    background: var(--bg);
    padding: 1.5rem;
    transition: background 0.15s;
  }

  .book-card:hover { background: var(--bg2); }

  .book-num {
    font-family: var(--mono);
    font-size: 11px;
    color: var(--text3);
    margin-bottom: 12px;
  }

  .book-title {
    font-family: var(--serif);
    font-size: 16px;
    font-weight: 400;
    color: var(--text);
    line-height: 1.35;
    margin-bottom: 6px;
  }

  .book-author {
    font-family: var(--mono);
    font-size: 11px;
    color: var(--text3);
    margin-bottom: 10px;
  }

  .book-why {
    font-size: 12px;
    color: var(--text2);
    line-height: 1.55;
  }

  /* FOOTER */
  footer {
    border-top: 1px solid var(--border);
    padding: 2rem;
    text-align: center;
    position: relative;
    z-index: 1;
  }

  .footer-text {
    font-family: var(--mono);
    font-size: 11px;
    color: var(--text3);
    letter-spacing: 0.06em;
  }

  /* RESPONSIVE */
  @media (max-width: 700px) {
    .split-grid { grid-template-columns: 1fr; }
    .neutral-section { grid-template-columns: 1fr; }
    .books-grid { grid-template-columns: 1fr; }
    .hero { padding: 4rem 1.5rem 2rem; }
    #output { padding: 0 1.5rem 4rem; }
    .side-panel:first-child { border-right: none; border-bottom: 1px solid var(--border); }
  }

  /* ENTRY ANIMATIONS */
  .fade-in {
    opacity: 0;
    transform: translateY(16px);
    animation: fadeUp 0.5s ease forwards;
  }

  @keyframes fadeUp {
    to { opacity: 1; transform: translateY(0); }
  }

  .fade-in:nth-child(2) { animation-delay: 0.08s; }
  .fade-in:nth-child(3) { animation-delay: 0.16s; }
  .fade-in:nth-child(4) { animation-delay: 0.24s; }
  .fade-in:nth-child(5) { animation-delay: 0.32s; }
</style>
</head>
<body>

<nav>
  <a class="nav-logo" href="#">
    <div class="logo-mark">
      <div class="logo-bar logo-bar-a"></div>
      <div class="logo-bar-sep"></div>
      <div class="logo-bar logo-bar-b"></div>
    </div>
    <span class="logo-text">Both Sides</span>
  </a>
  <span class="nav-tag">every story, whole</span>
</nav>

<div class="hero">
  <div class="hero-eyebrow">
    <span class="eyebrow-line"></span>
    independent · unfiltered · unbiased
    <span class="eyebrow-line"></span>
  </div>
  <h1>The news you watch<br>has <em>two sides.</em></h1>
  <p class="hero-sub">Most media shows you one. We show you both — side by side, without telling you what to think. Form your own opinion.</p>
</div>

<div style="position:relative;z-index:1;padding:0 2rem;">

  <div class="api-setup" id="apiSetup">
    <span class="api-label">API KEY</span>
    <input class="api-input" type="password" id="apiKeyInput" placeholder="sk-ant-..." />
    <button class="api-save" onclick="saveKey()">Save</button>
    <span class="api-status" id="apiStatus">Key saved</span>
    <span style="font-size:11px;color:var(--text3);margin-left:auto;">
      Get yours free at
      <a href="https://console.anthropic.com" target="_blank" style="color:var(--text2);text-decoration:none;">console.anthropic.com</a>
    </span>
  </div>

  <div class="search-wrap">
    <input class="search-box" id="searchInput" type="text" placeholder="Search any conflict, event, or topic in the news..." />
    <button class="search-btn" onclick="search()">Analyze ↗</button>
  </div>

  <div class="topics">
    <button class="t-chip" onclick="quick('Russia Ukraine war 2025')">Russia–Ukraine</button>
    <button class="t-chip" onclick="quick('Iran US nuclear deal tensions 2025')">Iran–US</button>
    <button class="t-chip" onclick="quick('Israel Palestine Gaza 2025')">Israel–Palestine</button>
    <button class="t-chip" onclick="quick('China Taiwan military tensions 2025')">China–Taiwan</button>
    <button class="t-chip" onclick="quick('India Pakistan Kashmir 2025')">India–Pakistan</button>
    <button class="t-chip" onclick="quick('US China trade war tariffs 2025')">US–China trade</button>
    <button class="t-chip" onclick="quick('global AI regulation policy 2025')">AI regulation</button>
    <button class="t-chip" onclick="quick('Sudan civil war humanitarian crisis')">Sudan</button>
  </div>
</div>

<hr class="section-divider">

<div id="output"></div>

<footer>
  <p class="footer-text">Both Sides — Read the world without the bias &nbsp;·&nbsp; Powered by Anthropic Claude + Live Web Search</p>
</footer>

<script>
  let apiKey = localStorage.getItem('bs_apikey') || '';

  if (apiKey) {
    document.getElementById('apiKeyInput').value = apiKey;
    document.getElementById('apiStatus').style.display = 'inline';
  }

  function saveKey() {
    const v = document.getElementById('apiKeyInput').value.trim();
    if (!v) return;
    apiKey = v;
    localStorage.setItem('bs_apikey', v);
    const s = document.getElementById('apiStatus');
    s.style.display = 'inline';
    s.textContent = 'Key saved ✓';
    setTimeout(() => { s.textContent = 'Key saved'; }, 2000);
  }

  function quick(t) {
    document.getElementById('searchInput').value = t;
    document.querySelectorAll('.t-chip').forEach(c => c.classList.remove('active'));
    event.target.classList.add('active');
    search();
  }

  document.getElementById('searchInput').addEventListener('keydown', e => {
    if (e.key === 'Enter') search();
  });

  async function search() {
    const topic = document.getElementById('searchInput').value.trim();
    if (!topic) return;

    if (!apiKey) {
      document.getElementById('output').innerHTML = `
        <div style="text-align:center;padding:4rem 2rem;">
          <p style="font-family:var(--mono);font-size:13px;color:var(--text3);">Enter your Anthropic API key above to get started.</p>
        </div>`;
      return;
    }

    document.getElementById('output').innerHTML = `
      <div class="loading-state">
        <div class="loading-ticker" id="tickerText">Searching live news sources...</div>
      </div>`;

    const messages = [
      "Searching live news sources...",
      "Reading global media outlets...",
      "Extracting both perspectives...",
      "Stripping bias from the narrative...",
      "Building your unbiased report..."
    ];
    let mi = 0;
    const ticker = setInterval(() => {
      mi = (mi + 1) % messages.length;
      const el = document.getElementById('tickerText');
      if (el) el.textContent = messages[mi];
    }, 1800);

    const prompt = `You are a neutral, unbiased journalist and analyst. The user wants both sides of: "${topic}"

Search the web for the most recent and reliable information. Then return ONLY valid JSON — no markdown fences, no backticks, no explanation before or after:

{
  "topic": "clean readable topic name",
  "lastUpdated": "most recent date of news you found (e.g. April 2025)",
  "sideA": {
    "label": "Country or Group A name",
    "stance": "their core position in 10 words or less",
    "narrative": "3 sentences: what Side A claims, their official statements, their media narrative. Specific and factual.",
    "keyActions": ["recent concrete action or statement", "another recent action"],
    "sources": [
      {"name": "e.g. RT, TASS, Xinhua, Al Jazeera", "url": "https://actual-url.com"}
    ]
  },
  "sideB": {
    "label": "Country or Group B name",
    "stance": "their core position in 10 words or less",
    "narrative": "3 sentences: what Side B claims, their official statements, their media narrative. Specific and factual.",
    "keyActions": ["recent concrete action or statement", "another recent action"],
    "sources": [
      {"name": "e.g. BBC, Reuters, AP, NYT", "url": "https://actual-url.com"}
    ]
  },
  "neutral": {
    "background": "2 sentences of verified neutral historical context explaining WHY this conflict exists.",
    "whatBothAgreeOn": "The one verified fact both sides accept as true.",
    "coreDifference": "The single point they fundamentally disagree on."
  },
  "keyClaims": [
    {"side": "exact sideA label", "claim": "specific claim they are making right now"},
    {"side": "exact sideB label", "claim": "specific claim they are making right now"},
    {"side": "exact sideA label", "claim": "another specific claim"},
    {"side": "exact sideB label", "claim": "another specific claim"}
  ],
  "books": [
    {"title": "Real book title", "author": "Real author name", "why": "One sentence: why this book helps understand this conflict."},
    {"title": "Real book title", "author": "Real author name", "why": "One sentence: why this book helps."},
    {"title": "Real book title", "author": "Real author name", "why": "One sentence: why this book helps."}
  ]
}`;

    try {
      const res = await fetch("https://api.anthropic.com/v1/messages", {
        method: "POST",
        headers: {
          "Content-Type": "application/json",
          "x-api-key": apiKey,
          "anthropic-version": "2023-06-01",
          "anthropic-dangerous-direct-browser-access": "true"
        },
        body: JSON.stringify({
          model: "claude-sonnet-4-20250514",
          max_tokens: 2000,
          tools: [{ "type": "web_search_20250305", "name": "web_search" }],
          messages: [{ role: "user", content: prompt }]
        })
      });

      clearInterval(ticker);
      const data = await res.json();

      if (data.error) {
        showError(data.error.message || 'API error. Check your key.');
        return;
      }

      const text = (data.content || []).filter(i => i.type === 'text').map(i => i.text).join('').trim();
      const clean = text.replace(/```json|```/g, '').trim();
      const d = JSON.parse(clean);
      render(d);

    } catch(e) {
      clearInterval(ticker);
      showError('Could not parse response. Try a different topic.');
    }
  }

  function showError(msg) {
    document.getElementById('output').innerHTML = `
      <div style="text-align:center;padding:4rem 2rem;">
        <p style="font-family:var(--mono);font-size:13px;color:var(--text3);">${msg}</p>
      </div>`;
  }

  function render(d) {
    const sideALabel = d.sideA.label;
    const sideBLabel = d.sideB.label;

    const actionsA = (d.sideA.keyActions || []).map(a =>
      `<div class="action-item">${a}</div>`).join('');

    const actionsB = (d.sideB.keyActions || []).map(a =>
      `<div class="action-item">${a}</div>`).join('');

    const sourcesA = (d.sideA.sources || []).map(s =>
      `<a class="source-link" href="${s.url}" target="_blank">↗ ${s.name}</a>`).join('');

    const sourcesB = (d.sideB.sources || []).map(s =>
      `<a class="source-link" href="${s.url}" target="_blank">↗ ${s.name}</a>`).join('');

    const claims = (d.keyClaims || []).map(c => {
      const isA = c.side === sideALabel;
      return `<div class="claim-row">
        <span class="claim-tag ${isA ? 'tag-a' : 'tag-b'}">${c.side}</span>
        <span class="claim-text">${c.claim}</span>
      </div>`;
    }).join('');

    const books = (d.books || []).map((b, i) => `
      <div class="book-card fade-in">
        <div class="book-num">0${i + 1}</div>
        <div class="book-title">${b.title}</div>
        <div class="book-author">${b.author}</div>
        <div class="book-why">${b.why}</div>
      </div>`).join('');

    document.getElementById('output').innerHTML = `
      <div class="result-header fade-in">
        <div class="result-meta">
          <span class="live-pill"><span class="live-dot"></span>live</span>
          <span class="result-date">${d.lastUpdated || 'Recent'}</span>
        </div>
        <h2 class="result-title">${d.topic}</h2>
        <p class="result-dispute">${d.neutral?.coreDifference || ''}</p>
      </div>

      <div class="split-grid fade-in">
        <div class="side-panel">
          <div class="side-header">
            <span class="side-label label-a">${sideALabel}</span>
          </div>
          <div class="side-stance">${d.sideA.stance}</div>
          <div class="side-narrative">${d.sideA.narrative}</div>
          ${actionsA ? `<div class="actions-label">recent actions</div>${actionsA}` : ''}
          ${sourcesA ? `<div class="side-sources"><div class="sources-label">sources</div>${sourcesA}</div>` : ''}
        </div>
        <div class="side-panel">
          <div class="side-header">
            <span class="side-label label-b">${sideBLabel}</span>
          </div>
          <div class="side-stance">${d.sideB.stance}</div>
          <div class="side-narrative">${d.sideB.narrative}</div>
          ${actionsB ? `<div class="actions-label">recent actions</div>${actionsB}` : ''}
          ${sourcesB ? `<div class="side-sources"><div class="sources-label">sources</div>${sourcesB}</div>` : ''}
        </div>
      </div>

      <div class="neutral-section fade-in">
        <div class="neutral-block">
          <div class="neutral-label">background</div>
          <div class="neutral-text">${d.neutral?.background || ''}</div>
        </div>
        <div class="neutral-block">
          <div class="neutral-label">what both sides agree on</div>
          <div class="neutral-text">${d.neutral?.whatBothAgreeOn || ''}</div>
        </div>
        <div class="neutral-block">
          <div class="neutral-label">core disagreement</div>
          <div class="neutral-text">${d.neutral?.coreDifference || ''}</div>
        </div>
      </div>

      ${claims ? `
      <div class="claims-section fade-in">
        <div class="claims-header">key claims being made right now</div>
        ${claims}
      </div>` : ''}

      ${books ? `
      <div class="books-section fade-in">
        <div class="books-header">
          <span class="books-title">Go deeper</span>
          <span class="books-sub">books to understand the full picture</span>
        </div>
        <div class="books-grid">${books}</div>
      </div>` : ''}
    `;
  }
</script>
</body>
</html>
