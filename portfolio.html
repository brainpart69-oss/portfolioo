<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>The Upside Down Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Benguiat:wght@400;700&family=Libre+Baskerville:ital,wght@0,400;0,700;1,400&family=VT323&display=swap" rel="stylesheet"/>
  <style>
    :root {
      --red:        #c0392b;
      --red-glow:   #e74c3c;
      --dim-red:    #7b1a13;
      --cream:      #f5ead6;
      --parchment:  #e8d5b0;
      --dark:       #0a0704;
      --dark2:      #130e08;
      --mid:        #1e1408;
      --brown:      #3b2710;
      --gold:       #c9a84c;
      --gold-light: #f0d080;
      --teal:       #1a8c7a;
      --teal-glow:  #2ecfb5;
      --grey:       #4a3f30;
      --font-title: 'VT323', monospace;
      --font-body:  'Libre Baskerville', serif;
    }

    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    html { scroll-behavior: smooth; }

    body {
      background-color: var(--dark);
      color: var(--cream);
      font-family: var(--font-body);
      min-height: 100vh;
      overflow-x: hidden;
      position: relative;
    }

    /* ── NOISE OVERLAY ── */
    body::before {
      content: '';
      position: fixed; inset: 0;
      background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 200 200' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.85' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='1'/%3E%3C/svg%3E");
      opacity: 0.04;
      pointer-events: none;
      z-index: 1000;
    }

    /* ── FLICKERING LIGHT PARTICLES ── */
    .particles {
      position: fixed; inset: 0;
      pointer-events: none;
      z-index: 2;
      overflow: hidden;
    }
    .particle {
      position: absolute;
      width: 3px; height: 3px;
      border-radius: 50%;
      animation: drift linear infinite;
    }
    @keyframes drift {
      0%   { transform: translateY(100vh) translateX(0);   opacity: 0; }
      10%  { opacity: 1; }
      90%  { opacity: 0.6; }
      100% { transform: translateY(-10vh) translateX(40px); opacity: 0; }
    }

    /* ── NAVBAR ── */
    nav {
      position: sticky; top: 0;
      z-index: 500;
      background: linear-gradient(to bottom, #0e0905, #130e08ee);
      border-bottom: 2px solid var(--red);
      padding: 0 2rem;
      display: flex;
      align-items: center;
      justify-content: space-between;
      height: 64px;
      box-shadow: 0 0 30px #c0392b55, 0 4px 20px #00000099;
      backdrop-filter: blur(6px);
    }

    .nav-logo {
      font-family: var(--font-title);
      font-size: 2.2rem;
      color: var(--red-glow);
      text-shadow: 0 0 12px var(--red), 0 0 30px var(--red), 0 0 60px #c0392b88;
      letter-spacing: 4px;
      animation: flicker 6s infinite;
    }

    @keyframes flicker {
      0%,19%,21%,23%,25%,54%,56%,100% { opacity: 1; text-shadow: 0 0 12px var(--red), 0 0 30px var(--red), 0 0 60px #c0392b88; }
      20%,24%,55% { opacity: 0.5; text-shadow: none; }
    }

    .nav-links {
      display: flex;
      gap: 2rem;
      list-style: none;
    }

    .nav-links a {
      font-family: var(--font-title);
      font-size: 1.3rem;
      color: var(--parchment);
      text-decoration: none;
      letter-spacing: 2px;
      transition: color 0.2s, text-shadow 0.2s;
      position: relative;
    }

    .nav-links a::after {
      content: '';
      position: absolute;
      bottom: -4px; left: 0;
      width: 0; height: 1px;
      background: var(--red-glow);
      box-shadow: 0 0 8px var(--red);
      transition: width 0.3s;
    }

    .nav-links a:hover { color: var(--red-glow); text-shadow: 0 0 10px var(--red); }
    .nav-links a:hover::after { width: 100%; }

    /* ── LAYOUT ── */
    .layout {
      display: grid;
      grid-template-columns: 260px 1fr;
      min-height: calc(100vh - 64px);
    }

    /* ── SIDEBAR ── */
    aside {
      background: linear-gradient(to bottom, #0e0904, #130e08);
      border-right: 1px solid #3b2710;
      padding: 2rem 0;
      position: sticky;
      top: 64px;
      height: calc(100vh - 64px);
      overflow-y: auto;
    }

    .sidebar-title {
      font-family: var(--font-title);
      font-size: 1rem;
      color: var(--gold);
      letter-spacing: 4px;
      text-transform: uppercase;
      padding: 0 1.5rem 1rem;
      border-bottom: 1px solid #3b2710;
      margin-bottom: 1rem;
      text-shadow: 0 0 8px var(--gold);
    }

    .sidebar-item {
      display: block;
      padding: 0.85rem 1.5rem;
      color: var(--parchment);
      text-decoration: none;
      font-family: var(--font-title);
      font-size: 1.1rem;
      letter-spacing: 1.5px;
      border-left: 3px solid transparent;
      transition: all 0.25s;
      position: relative;
    }

    .sidebar-item::before {
      content: '▸';
      margin-right: 0.6rem;
      color: var(--red);
      opacity: 0;
      transition: opacity 0.2s, transform 0.2s;
      transform: translateX(-4px);
      display: inline-block;
    }

    .sidebar-item:hover {
      color: var(--cream);
      background: #1e140888;
      border-left-color: var(--red);
      text-shadow: 0 0 8px var(--red-glow);
      padding-left: 2rem;
    }

    .sidebar-item:hover::before { opacity: 1; transform: translateX(0); }

    .sidebar-num {
      font-size: 0.75rem;
      color: var(--dim-red);
      display: block;
      letter-spacing: 1px;
    }

    /* ── MAIN ── */
    main {
      padding: 3rem 3rem 4rem;
      position: relative;
    }

    /* ── HERO / ABOUT ME ── */
    .hero {
      display: grid;
      grid-template-columns: 1fr 240px;
      gap: 2.5rem;
      margin-bottom: 4rem;
      padding: 2.5rem;
      background: #0e0904cc;
      border: 1px solid #3b2710;
      border-top: 3px solid var(--red);
      position: relative;
      overflow: hidden;
    }

    .hero::before {
      content: '';
      position: absolute;
      top: -60px; right: -60px;
      width: 250px; height: 250px;
      background: radial-gradient(circle, #c0392b22 0%, transparent 70%);
      pointer-events: none;
    }

    .hero-badge {
      font-family: var(--font-title);
      font-size: 0.85rem;
      letter-spacing: 5px;
      color: var(--red-glow);
      text-transform: uppercase;
      margin-bottom: 0.6rem;
      animation: flicker 8s 2s infinite;
    }

    .hero-name {
      font-family: var(--font-title);
      font-size: 3.8rem;
      line-height: 1;
      color: var(--cream);
      letter-spacing: 2px;
      margin-bottom: 0.4rem;
      text-shadow: 2px 2px 0 var(--brown);
    }

    .hero-subtitle {
      font-family: var(--font-title);
      font-size: 1.3rem;
      color: var(--gold);
      letter-spacing: 3px;
      margin-bottom: 1.5rem;
      text-shadow: 0 0 10px var(--gold);
    }

    .hero-text {
      font-size: 0.92rem;
      line-height: 1.85;
      color: #c8b89a;
      max-width: 560px;
    }

    .hero-text em { color: var(--teal-glow); font-style: normal; }

    .hero-tags {
      display: flex;
      flex-wrap: wrap;
      gap: 0.5rem;
      margin-top: 1.4rem;
    }

    .tag {
      font-family: var(--font-title);
      font-size: 0.9rem;
      letter-spacing: 2px;
      padding: 0.3rem 0.8rem;
      border: 1px solid var(--teal);
      color: var(--teal-glow);
      background: #1a8c7a18;
    }
    @keyframes pulse {
      0%,100% { text-shadow: 0 0 20px var(--red); }
      50%      { text-shadow: 0 0 40px var(--red), 0 0 80px #c0392b66; }
    }

    /* ── SECTION TITLE ── */
    .section-head {
      display: flex;
      align-items: center;
      gap: 1rem;
      margin-bottom: 2rem;
    }

    .section-head h2 {
      font-family: var(--font-title);
      font-size: 2rem;
      letter-spacing: 4px;
      color: var(--cream);
      text-transform: uppercase;
    }

    .section-line {
      flex: 1;
      height: 1px;
      background: linear-gradient(to right, var(--red), transparent);
      box-shadow: 0 0 6px var(--red);
    }

    /* ── ASSIGNMENT GRID ── */
    .grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 1.5rem;
    }

    /* ── CARD (checkbox hack for open/close) ── */
    .card-toggle { display: none; }

    .card {
      background: #0e0904;
      border: 1px solid #3b2710;
      border-top: 3px solid var(--red);
      position: relative;
      overflow: hidden;
      cursor: pointer;
      transition: transform 0.25s, box-shadow 0.25s;
    }

    .card:hover {
      transform: translateY(-4px);
      box-shadow: 0 0 30px #c0392b44, 0 12px 40px #00000088;
    }

    .card::before {
      content: '';
      position: absolute;
      inset: 0;
      background: linear-gradient(135deg, #c0392b08, transparent 60%);
      pointer-events: none;
    }

    .card-label {
      display: block;
      cursor: pointer;
    }

    .card-front {
      padding: 1.6rem;
    }

    .card-num {
      font-family: var(--font-title);
      font-size: 0.8rem;
      letter-spacing: 4px;
      color: var(--dim-red);
      display: block;
      margin-bottom: 0.4rem;
    }

    .card-icon {
      font-size: 2.2rem;
      margin-bottom: 0.8rem;
      display: block;
      filter: drop-shadow(0 0 8px var(--red));
    }

    .card-title {
      font-family: var(--font-title);
      font-size: 1.35rem;
      letter-spacing: 1.5px;
      color: var(--cream);
      margin-bottom: 0.5rem;
    }

    .card-desc {
      font-size: 0.82rem;
      color: #9a8870;
      line-height: 1.6;
    }

    .card-footer {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 0.7rem 1.6rem;
      border-top: 1px solid #3b2710;
      background: #0a0703;
    }

    .card-status {
      font-family: var(--font-title);
      font-size: 0.8rem;
      letter-spacing: 2px;
      color: var(--teal-glow);
    }

    .card-arrow {
      font-size: 1rem;
      color: var(--red);
      transition: transform 0.3s;
      display: inline-block;
    }

    /* ── EXPANDED PANEL (CSS only, no JS) ── */
    .card-toggle:checked + .card .card-arrow { transform: rotate(90deg); }

    .card-body {
      max-height: 0;
      overflow: hidden;
      transition: max-height 0.5s cubic-bezier(0.4,0,0.2,1);
    }

    .card-toggle:checked + .card .card-body { max-height: 600px; }

    .card-body-inner {
      padding: 1.4rem 1.6rem;
      border-top: 1px dashed #3b2710;
      background: #0a0604;
    }

    .card-body-inner h4 {
      font-family: var(--font-title);
      font-size: 1rem;
      letter-spacing: 3px;
      color: var(--gold);
      margin-bottom: 0.8rem;
      text-shadow: 0 0 8px var(--gold);
    }

    .card-body-inner p {
      font-size: 0.85rem;
      line-height: 1.75;
      color: #b0a090;
      margin-bottom: 0.8rem;
    }

    .card-body-inner ul {
      list-style: none;
      display: flex;
      flex-wrap: wrap;
      gap: 0.4rem;
    }

    .card-body-inner ul li {
      font-family: var(--font-title);
      font-size: 0.8rem;
      letter-spacing: 1.5px;
      padding: 0.25rem 0.6rem;
      border: 1px solid var(--teal);
      color: var(--teal-glow);
      background: #1a8c7a14;
    }

    .card-body-inner .grade {
      margin-top: 0.8rem;
      font-family: var(--font-title);
      font-size: 1rem;
      letter-spacing: 2px;
      color: var(--gold-light);
    }

    /* ── SCROLLBAR ── */
    ::-webkit-scrollbar { width: 6px; }
    ::-webkit-scrollbar-track { background: var(--dark2); }
    ::-webkit-scrollbar-thumb { background: var(--dim-red); border-radius: 3px; }

    /* ── FOOTER ── */
    footer {
      text-align: center;
      padding: 2rem;
      font-family: var(--font-title);
      font-size: 0.9rem;
      letter-spacing: 3px;
      color: #4a3f30;
      border-top: 1px solid #1e1408;
    }

    footer span { color: var(--red); animation: flicker 4s infinite; }

    /* ── VINE DECORATIONS ── */
    .vine-left {
      position: fixed;
      left: 0; top: 64px;
      width: 4px;
      height: 100%;
      background: linear-gradient(to bottom, transparent, var(--red), transparent, var(--teal), transparent);
      opacity: 0.3;
      pointer-events: none;
    }

    /* ── UPSIDE DOWN DIVIDER ── */
    .divider {
      text-align: center;
      margin: 3rem 0;
      font-family: var(--font-title);
      font-size: 1.2rem;
      letter-spacing: 8px;
      color: #3b2710;
      position: relative;
    }

    .divider::before, .divider::after {
      content: '';
      position: absolute;
      top: 50%; width: 25%;
      height: 1px;
      background: linear-gradient(to right, transparent, #3b2710);
    }
    .divider::before { left: 0; background: linear-gradient(to right, transparent, #3b2710); }
    .divider::after  { right: 0; background: linear-gradient(to left, transparent, #3b2710); }
    
  </style>
</head>
<body>

  <!-- PARTICLES -->
  <div class="particles" aria-hidden="true">
    <div class="particle" style="left:5%;  animation-duration:12s; animation-delay:0s;   background:#c0392b; box-shadow:0 0 4px #c0392b;"></div>
    <div class="particle" style="left:15%; animation-duration:18s; animation-delay:3s;   background:#1a8c7a; box-shadow:0 0 4px #1a8c7a;"></div>
    <div class="particle" style="left:30%; animation-duration:14s; animation-delay:6s;   background:#c0392b; box-shadow:0 0 4px #c0392b;"></div>
    <div class="particle" style="left:50%; animation-duration:20s; animation-delay:1s;   background:#c9a84c; box-shadow:0 0 4px #c9a84c;"></div>
    <div class="particle" style="left:65%; animation-duration:16s; animation-delay:9s;   background:#1a8c7a; box-shadow:0 0 4px #1a8c7a;"></div>
    <div class="particle" style="left:80%; animation-duration:13s; animation-delay:4s;   background:#c0392b; box-shadow:0 0 4px #c0392b;"></div>
    <div class="particle" style="left:92%; animation-duration:22s; animation-delay:7s;   background:#c9a84c; box-shadow:0 0 4px #c9a84c;"></div>
  </div>

  <div class="vine-left"></div>

  <!-- NAVBAR -->
  <nav>
    <div class="nav-logo">Utsav Chaturvedi</div>
    <ul class="nav-links">
      <li><a href="#about">ABOUT</a></li>
      <li><a href="#assignments">ASSIGNMENTS</a></li>
      <li><a href="workshop.html">WORKSHOP</a></li>
    </ul>
  </nav>

  <div class="layout">

    <!-- SIDEBAR -->
    <aside>
      <div class="sidebar-title">Assignments</div>
      <a class="sidebar-item" href="#a1"><span class="sidebar-num">01 ──</span> Typography</a>
      <a class="sidebar-item" href="#a2"><span class="sidebar-num">02 ──</span> Elements Of Design</a>
      <a class="sidebar-item" href="#a3"><span class="sidebar-num">03 ──</span> Empathy In Design</a>
      <a class="sidebar-item" href="#a4"><span class="sidebar-num">04 ──</span> Visualization and Storytelling</a>
      <a class="sidebar-item" href="#a5"><span class="sidebar-num">05 ──</span> Sketching</a>
      <a class="sidebar-item" href="#a6"><span class="sidebar-num">06 ──</span> History Of Art And Evolution In Design</a>
    </aside>

    <!-- MAIN -->
    <main>

      <!-- ABOUT ME -->
      <section id="about">
        <div class="hero">
          <div class="hero-content">
            <div class="hero-badge">About Me</div>
            <div class="hero-name">Utsav Chaturvedi</div>
            <div class="Pro-image"><img src="ChatGPT Image Mar 3, 2026, 12_40_38 PM.png" width="200" height="200" align="right" style="margin-bottom: 100px;"></div>
            <div class="hero-subtitle">★ UX Designing · DIT University ★</div>
            <p class="hero-text">
              Welcome to my <em>portfolio</em>. Bachelor's Of Design. UX 2025-2029 
       A collection of six assignments that explore the boundaries of design, technology, and storytelling — all through the lens of a world turned upside down.
            </p>
            <div class="hero-tags">
              <span class="tag">Figma</span>
              <span class="tag">Blender</span>
              <span class="tag">Photoshop</span>
              <span class="tag">Illustrator</span>
              <span class="tag">UX Research</span>
             
            </div>
          </div>
        </div>
      </section>

      <!-- ASSIGNMENTS -->
      <section id="assignments">
        <div class="section-head">
          <h2>Case Files</h2>
          <div class="section-line"></div>
        </div>

        <div class="grid">

          <!-- CARD 1 -->
          <div id="a1">
            <input type="checkbox" id="c1" class="card-toggle"/>
            <div class="card">
              <label class="card-label" for="c1">
                <div class="card-front">
                  <span class="card-num">ASSIGNMENT 01</span>
                  <span class="card-icon"><a href="TYPO.html">🔬</a></span>
                  <div class="card-title">Typography</div>
                  <div class="card-desc">Assignment which taught the importance of fonts and text.</div>
                </div>
                <div class="card-footer">
                  <span class="card-status">COMPLETE</span>
                  <span class="card-arrow">▶</span>
                </div>
                <div class="card-body">
                  <div class="card-body-inner">
                    <h4>// OVERVIEW</h4>
                    <p>The art of arranging type to make text readable, clear, and visually appealing. It shapes how users perceive and interact with written content.</p>
                    <ul>
                      <li>TEXT</li><li>FONT</li><li>READABILITY</li><li>FONT-DESIGN</li>
                    </ul>
                    <div class="grade">GRADE: A</div>
                  </div>
                </div>
              </label>
            </div>
          </div>

          <!-- CARD 2 -->
          <div id="a2">
            <input type="checkbox" id="c2" class="card-toggle"/>
            <div class="card">
              <label class="card-label" for="c2">
                <div class="card-front">
                  <span class="card-num">ASSIGNMENT 02</span>
                  <span class="card-icon"><a href="EOD.html">🧠</a></span>
                  <div class="card-title">Elements Of Design</div>
                  <div class="card-desc">The Assignment which helped learn how design would look good with its principles.</div>
                </div>
                <div class="card-footer">
                  <span class="card-status">COMPLETE</span>
                  <span class="card-arrow">▶</span>
                </div>
                <div class="card-body">
                  <div class="card-body-inner">
                    <h4>// OVERVIEW</h4>
                    <p>Basic building blocks like line, shape, color, texture, and space used to create visual compositions. They form the foundation of all visual communication.</p>
                    <ul>
                      <li>ELEMENTS</li><li>PRINCIPLES</li><li>UX LAWS</li><li>COLOR PSYCHOLOGY</li>
                    </ul>
                    <div class="grade">GRADE: c+</div>
                  </div>
                </div>
              </label>
            </div>
          </div>

          <!-- CARD 3 -->
          <div id="a3">
            <input type="checkbox" id="c3" class="card-toggle"/>
            <div class="card">
              <label class="card-label" for="c3">
                <div class="card-front">
                  <span class="card-num">ASSIGNMENT 03</span>
                  <span class="card-icon"><a href="EID.html">🌿</a></span>
                  <div class="card-title">Empathy In Design</div>
                  <div class="card-desc">Taught the basics of research and user-centered design.</div>
                </div>
                <div class="card-footer">
                  <span class="card-status">COMPLETE</span>
                  <span class="card-arrow">▶</span>
                </div>
                <div class="card-body">
                  <div class="card-body-inner">
                    <h4>// OVERVIEW</h4>
                    <p>Understanding users’ emotions, needs, and experiences to create meaningful solutions. It ensures designs are human-centered and genuinely useful.</p>
                    <ul>
                      <li>EMPATHY</li><li>SYMPATHY</li><li>QUALITATIVE</li><li>QUANTITATIVE</li>
                    </ul>
                    <div class="grade">GRADE: A-</div>
                  </div>
                </div>
              </label>
            </div>
          </div>

          <!-- CARD 4 -->
          <div id="a4">
            <input type="checkbox" id="c4" class="card-toggle"/>
            <div class="card">
              <label class="card-label" for="c4">
                <div class="card-front">
                  <span class="card-num">ASSIGNMENT 04</span>
                  <span class="card-icon"><a href="VAS.html">🌀</a></span>
                  <div class="card-title">Visualization And Storytelling</div>
                  <div class="card-desc">Assignment which made us think and visualize data in creative ways.</div>
                </div>
                <div class="card-footer">
                  <span class="card-status">COMPLETE</span>
                  <span class="card-arrow">▶</span>
                </div>
                <div class="card-body">
                  <div class="card-body-inner">
                    <h4>// OVERVIEW</h4>
                    <p>Presenting ideas or data visually in a way that communicates a clear narrative. It helps users quickly understand complex information.</p>
                    <ul>
                      <li>STORY</li><li>VISUAL</li><li>REPRESENTATION</li><li>COMPLEXITY</li>
                    </ul>
                    <div class="grade">GRADE: B+</div>
                  </div>
                </div>
              </label>
            </div>
          </div>

          <!-- CARD 5 -->
          <div id="a5">
            <input type="checkbox" id="c5" class="card-toggle"/>
            <div class="card">
              <label class="card-label" for="c5">
                <div class="card-front">
                  <span class="card-num">ASSIGNMENT 05</span>
                  <span class="card-icon"><a href="SKETCH.html">⚡</a></span>
                  <div class="card-title">Sketching</div>
                  <div class="card-desc">The basics of desigining which help improve visualizing things and emotions.</div>
                </div>
                <div class="card-footer">
                  <span class="card-status">COMPLETE</span>
                  <span class="card-arrow">▶</span>
                </div>
                <div class="card-body">
                  <div class="card-body-inner">
                    <h4>// OVERVIEW</h4>
                    <p>SiA quick, rough way to visualize ideas and concepts on paper or digitally. It’s essential for exploring and refining design solutions early.</p>
                    <ul>
                      <li>SKETCHES</li><li>CONCEPTS</li><li>DRAWINGS</li><li>SHADING</li>
                    </ul>
                    <div class="grade">GRADE: A</div>
                  </div>
                </div>
              </label>
            </div>
          </div>

          <!-- CARD 6 -->
          <div id="a6">
            <input type="checkbox" id="c6" class="card-toggle"/>
            <div class="card">
              <label class="card-label" for="c6">
                <div class="card-front">
                  <span class="card-num">ASSIGNMENT 06</span>
                  <span class="card-icon"><a href="HOAAEID.html">🚪</a></span>
                  <div class="card-title">History Of Art And Evolution Of Design</div>
                  <div class="card-desc">Taught us about the history of art and how it has evolved into modern design practices.</div>
                </div>
                <div class="card-footer">
                  <span class="card-status">COMPLETE</span>
                  <span class="card-arrow">▶</span>
                </div>
                <div class="card-body">
                  <div class="card-body-inner">
                    <h4>// OVERVIEW</h4>
                    <p>Study of how art and design styles have changed over time. It helps designers draw inspiration and understand cultural and visual trends.</p>
                    <ul>
                      <li>HISTORY</li><li>EVOLUTION</li><li>DESIGN</li><li>ART</li>
                    </ul>
                    <div class="grade">GRADE: b+</div>
                  </div>
                </div>
              </label>
            </div>
          </div>

        </div>
      </section>

      <div class="divider">✦ THE UPSIDE DOWN ✦</div>

    </main>
  </div>

  <footer id="contact">
    DIT University, Dehradun &nbsp;·&nbsp; <span>portfolio 2026</span> &nbsp;·&nbsp; Jaychaturvedi681@gmail.com
  </footer>

</body>
</html>
