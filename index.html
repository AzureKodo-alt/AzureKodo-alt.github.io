<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>AzureKodo — Cybersecurity Portfolio</title>
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@300;400;500;600;700&family=Space+Mono:wght@400;700&display=swap" rel="stylesheet" />
  <style>
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    :root {
      --bg:     #080b10;
      --bg2:    #0d1117;
      --border: rgba(255,255,255,0.07);
      --accent: #3b82f6;
      --accent2:#60a5fa;
      --green:  #22c55e;
      --text:   #e2e8f0;
      --muted:  #64748b;
      --mono:   'Space Mono', monospace;
      --sans:   'Space Grotesk', sans-serif;
    }

    html { scroll-behavior: smooth; }

    body {
      background: var(--bg);
      color: var(--text);
      font-family: var(--sans);
      line-height: 1.6;
      overflow-x: hidden;
    }

    /* ── NOISE ── */
    body::before {
      content: '';
      position: fixed;
      inset: 0;
      background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='0.03'/%3E%3C/svg%3E");
      pointer-events: none;
      z-index: 0;
      opacity: 0.4;
    }

    /* ── GRID BG ── */
    body::after {
      content: '';
      position: fixed;
      inset: 0;
      background-image:
        linear-gradient(rgba(59,130,246,0.03) 1px, transparent 1px),
        linear-gradient(90deg, rgba(59,130,246,0.03) 1px, transparent 1px);
      background-size: 48px 48px;
      pointer-events: none;
      z-index: 0;
    }

    /* ── KEYFRAMES ── */
    @keyframes fadeUp {
      from { opacity: 0; transform: translateY(24px); }
      to   { opacity: 1; transform: translateY(0); }
    }
    @keyframes fadeIn {
      from { opacity: 0; }
      to   { opacity: 1; }
    }
    @keyframes slideRight {
      from { opacity: 0; transform: translateX(-20px); }
      to   { opacity: 1; transform: translateX(0); }
    }
    @keyframes pulse-dot {
      0%,100% { opacity: 1; box-shadow: 0 0 0 0 rgba(34,197,94,0.4); }
      50%     { opacity: 0.7; box-shadow: 0 0 0 6px rgba(34,197,94,0); }
    }
    @keyframes scanline {
      0%   { top: -2px; }
      100% { top: 100%; }
    }
    @keyframes typewriter {
      from { width: 0; }
      to   { width: 100%; }
    }
    @keyframes blink {
      0%,100% { border-color: var(--accent); }
      50%     { border-color: transparent; }
    }
    @keyframes glow {
      0%,100% { text-shadow: 0 0 20px rgba(59,130,246,0.3); }
      50%     { text-shadow: 0 0 40px rgba(59,130,246,0.6), 0 0 80px rgba(59,130,246,0.2); }
    }
    @keyframes borderPulse {
      0%,100% { border-color: rgba(255,255,255,0.07); }
      50%     { border-color: rgba(59,130,246,0.25); }
    }

    /* ── SCROLL REVEAL ── */
    .reveal {
      opacity: 0;
      transform: translateY(30px);
      transition: opacity 0.7s ease, transform 0.7s ease;
    }
    .reveal.visible {
      opacity: 1;
      transform: translateY(0);
    }
    .reveal-delay-1 { transition-delay: 0.1s; }
    .reveal-delay-2 { transition-delay: 0.2s; }
    .reveal-delay-3 { transition-delay: 0.3s; }
    .reveal-delay-4 { transition-delay: 0.4s; }

    /* ── NAV ── */
    nav {
      position: fixed;
      top: 0; left: 0; right: 0;
      z-index: 100;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 40px;
      border-bottom: 1px solid var(--border);
      background: rgba(8,11,16,0.85);
      backdrop-filter: blur(16px);
      animation: fadeIn 0.8s ease forwards;
    }

    .nav-logo {
      font-family: var(--mono);
      font-size: 14px;
      color: var(--accent2);
      letter-spacing: 2px;
      text-decoration: none;
      transition: color 0.2s;
    }
    .nav-logo:hover { color: #fff; }

    .nav-links { display: flex; gap: 32px; }
    .nav-links a {
      font-size: 13px;
      color: var(--muted);
      text-decoration: none;
      letter-spacing: 1px;
      text-transform: uppercase;
      transition: color 0.2s;
      position: relative;
    }
    .nav-links a::after {
      content: '';
      position: absolute;
      bottom: -4px; left: 0;
      width: 0; height: 1px;
      background: var(--accent);
      transition: width 0.3s ease;
    }
    .nav-links a:hover { color: var(--text); }
    .nav-links a:hover::after { width: 100%; }

    /* ── SCANLINE ── */
    .scanline {
      position: fixed;
      left: 0; right: 0;
      height: 2px;
      background: linear-gradient(90deg, transparent, rgba(59,130,246,0.3), transparent);
      animation: scanline 8s linear infinite;
      pointer-events: none;
      z-index: 99;
    }

    /* ── HERO ── */
    .hero {
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      padding: 120px 40px 80px;
      max-width: 1100px;
      margin: 0 auto;
      position: relative;
      z-index: 1;
    }

    .hero-eyebrow {
      font-family: var(--mono);
      font-size: 12px;
      color: var(--accent);
      letter-spacing: 3px;
      text-transform: uppercase;
      margin-bottom: 24px;
      display: flex;
      align-items: center;
      gap: 12px;
      animation: slideRight 0.8s ease 0.2s both;
    }

    .hero-eyebrow::before {
      content: '';
      display: block;
      width: 32px; height: 1px;
      background: var(--accent);
    }

    .hero h1 {
      font-size: clamp(48px, 8vw, 96px);
      font-weight: 700;
      line-height: 0.95;
      letter-spacing: -2px;
      margin-bottom: 32px;
      animation: fadeUp 0.9s ease 0.3s both;
    }

    .hero h1 .name { color: var(--text); }
    .hero h1 .handle {
      color: var(--accent);
      display: block;
      animation: glow 4s ease-in-out infinite;
    }

    .hero-desc {
      max-width: 560px;
      font-size: 17px;
      color: var(--muted);
      line-height: 1.75;
      margin-bottom: 48px;
      animation: fadeUp 0.9s ease 0.5s both;
    }
    .hero-desc strong { color: var(--text); font-weight: 500; }

    .hero-tags {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      margin-bottom: 48px;
      animation: fadeUp 0.9s ease 0.6s both;
    }

    .tag {
      font-family: var(--mono);
      font-size: 11px;
      padding: 6px 14px;
      border: 1px solid var(--border);
      border-radius: 3px;
      color: var(--muted);
      letter-spacing: 1px;
      text-transform: uppercase;
      transition: all 0.2s;
    }
    .tag:hover { border-color: rgba(59,130,246,0.3); color: var(--accent2); }

    .tag.active {
      border-color: rgba(59,130,246,0.4);
      color: var(--accent2);
      background: rgba(59,130,246,0.06);
    }

    .hero-cta {
      display: flex;
      gap: 16px;
      flex-wrap: wrap;
      animation: fadeUp 0.9s ease 0.7s both;
    }

    .btn {
      font-family: var(--mono);
      font-size: 12px;
      letter-spacing: 2px;
      text-transform: uppercase;
      padding: 14px 28px;
      border-radius: 4px;
      text-decoration: none;
      transition: all 0.25s;
      display: inline-block;
      position: relative;
      overflow: hidden;
    }
    .btn::before {
      content: '';
      position: absolute;
      inset: 0;
      background: rgba(255,255,255,0.05);
      opacity: 0;
      transition: opacity 0.2s;
    }
    .btn:hover::before { opacity: 1; }

    .btn-primary {
      background: var(--accent);
      color: #fff;
      border: 1px solid var(--accent);
      box-shadow: 0 0 20px rgba(59,130,246,0.2);
    }
    .btn-primary:hover {
      background: var(--accent2);
      box-shadow: 0 0 30px rgba(59,130,246,0.4);
      transform: translateY(-1px);
    }

    .btn-ghost {
      background: transparent;
      color: var(--muted);
      border: 1px solid var(--border);
    }
    .btn-ghost:hover {
      color: var(--text);
      border-color: rgba(255,255,255,0.2);
      transform: translateY(-1px);
    }

    /* ── SECTIONS ── */
    section {
      padding: 100px 40px;
      max-width: 1100px;
      margin: 0 auto;
      position: relative;
      z-index: 1;
    }

    .section-label {
      font-family: var(--mono);
      font-size: 11px;
      letter-spacing: 4px;
      text-transform: uppercase;
      color: var(--accent);
      margin-bottom: 16px;
    }

    .section-title {
      font-size: clamp(28px, 4vw, 42px);
      font-weight: 700;
      letter-spacing: -1px;
      margin-bottom: 48px;
      color: var(--text);
    }

    /* ── ORIGIN ── */
    .origin { border-top: 1px solid var(--border); }

    .origin-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 60px;
      align-items: start;
    }

    .origin-text p {
      color: var(--muted);
      font-size: 16px;
      line-height: 1.8;
      margin-bottom: 20px;
    }
    .origin-text p strong { color: var(--text); font-weight: 500; }

    .origin-quote {
      border-left: 2px solid var(--accent);
      padding: 20px 24px;
      background: rgba(59,130,246,0.04);
      border-radius: 0 4px 4px 0;
      margin-top: 32px;
      animation: borderPulse 4s ease-in-out infinite;
    }
    .origin-quote p {
      font-size: 15px;
      color: var(--text);
      font-style: italic;
      margin: 0;
    }

    .stat-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 16px;
    }

    .stat-card {
      border: 1px solid var(--border);
      border-radius: 6px;
      padding: 24px;
      background: var(--bg2);
      transition: all 0.3s ease;
      cursor: default;
    }
    .stat-card:hover {
      border-color: rgba(59,130,246,0.3);
      transform: translateY(-3px);
      box-shadow: 0 8px 24px rgba(0,0,0,0.3);
    }

    .stat-number {
      font-family: var(--mono);
      font-size: 32px;
      font-weight: 700;
      color: var(--accent);
      display: block;
      margin-bottom: 6px;
    }

    .stat-label {
      font-size: 12px;
      color: var(--muted);
      text-transform: uppercase;
      letter-spacing: 1px;
    }

    /* ── PROJECTS ── */
    .projects { border-top: 1px solid var(--border); }

    .project-card {
      border: 1px solid var(--border);
      border-radius: 8px;
      padding: 32px;
      background: var(--bg2);
      margin-bottom: 20px;
      transition: all 0.3s ease;
      position: relative;
      overflow: hidden;
    }
    .project-card::before {
      content: '';
      position: absolute;
      top: 0; left: 0;
      width: 3px; height: 100%;
      background: linear-gradient(to bottom, var(--accent), var(--accent2));
      opacity: 0;
      transition: opacity 0.3s;
    }
    .project-card:hover {
      border-color: rgba(59,130,246,0.3);
      transform: translateY(-3px);
      box-shadow: 0 12px 32px rgba(0,0,0,0.4);
    }
    .project-card:hover::before { opacity: 1; }

    .project-header {
      display: flex;
      justify-content: space-between;
      align-items: flex-start;
      margin-bottom: 12px;
      flex-wrap: wrap;
      gap: 12px;
    }

    .project-name {
      font-size: 18px;
      font-weight: 600;
      color: var(--text);
    }

    .project-badge {
      font-family: var(--mono);
      font-size: 10px;
      padding: 4px 10px;
      border-radius: 3px;
      letter-spacing: 1px;
      text-transform: uppercase;
    }

    .badge-live {
      background: rgba(34,197,94,0.1);
      border: 1px solid rgba(34,197,94,0.3);
      color: var(--green);
      animation: borderPulse 3s ease-in-out infinite;
    }

    .project-desc {
      color: var(--muted);
      font-size: 14px;
      line-height: 1.7;
      margin-bottom: 20px;
    }

    .project-stack {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
    }

    .stack-tag {
      font-family: var(--mono);
      font-size: 10px;
      padding: 4px 10px;
      background: rgba(255,255,255,0.04);
      border: 1px solid var(--border);
      border-radius: 3px;
      color: var(--muted);
      letter-spacing: 1px;
      transition: all 0.2s;
    }
    .stack-tag:hover {
      border-color: rgba(59,130,246,0.3);
      color: var(--accent2);
    }

    /* ── REPORTS ── */
    .reports { border-top: 1px solid var(--border); }

    .report-card {
      display: flex;
      gap: 24px;
      padding: 24px;
      border: 1px solid var(--border);
      border-radius: 8px;
      background: var(--bg2);
      align-items: flex-start;
      transition: all 0.3s ease;
    }
    .report-card:hover {
      border-color: rgba(59,130,246,0.2);
      transform: translateY(-2px);
      box-shadow: 0 8px 24px rgba(0,0,0,0.3);
    }

    .report-id {
      font-family: var(--mono);
      font-size: 11px;
      color: var(--accent);
      letter-spacing: 1px;
      white-space: nowrap;
      padding-top: 2px;
      min-width: 100px;
    }

    .report-info h4 {
      font-size: 15px;
      font-weight: 500;
      color: var(--text);
      margin-bottom: 6px;
    }

    .report-info p {
      font-size: 13px;
      color: var(--muted);
      line-height: 1.6;
    }

    .report-severity {
      font-family: var(--mono);
      font-size: 10px;
      padding: 3px 8px;
      border-radius: 3px;
      margin-left: auto;
      white-space: nowrap;
      align-self: flex-start;
    }

    .sev-high {
      background: rgba(239,68,68,0.1);
      border: 1px solid rgba(239,68,68,0.3);
      color: #f87171;
      animation: borderPulse 3s ease-in-out infinite;
    }

    /* ── SKILLS ── */
    .skills { border-top: 1px solid var(--border); }

    .skills-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 20px;
    }

    .skill-group {
      border: 1px solid var(--border);
      border-radius: 6px;
      padding: 24px;
      background: var(--bg2);
      transition: all 0.3s ease;
    }
    .skill-group:hover {
      border-color: rgba(59,130,246,0.2);
      transform: translateY(-3px);
      box-shadow: 0 8px 24px rgba(0,0,0,0.3);
    }

    .skill-group-title {
      font-family: var(--mono);
      font-size: 11px;
      color: var(--accent);
      letter-spacing: 2px;
      text-transform: uppercase;
      margin-bottom: 16px;
    }

    .skill-item {
      font-size: 13px;
      color: var(--muted);
      padding: 8px 0;
      border-bottom: 1px solid var(--border);
      display: flex;
      align-items: center;
      gap: 8px;
      transition: color 0.2s, padding-left 0.2s;
    }
    .skill-item:last-child { border-bottom: none; }
    .skill-item::before { content: '›'; color: var(--accent); font-size: 16px; }
    .skill-item:hover { color: var(--text); padding-left: 6px; }

    /* ── MISSION ── */
    .mission {
      border-top: 1px solid var(--border);
      text-align: center;
    }

    .mission-statement {
      font-size: clamp(20px, 3vw, 32px);
      font-weight: 600;
      color: var(--text);
      max-width: 700px;
      margin: 0 auto 24px;
      line-height: 1.4;
      letter-spacing: -0.5px;
      animation: glow 5s ease-in-out infinite;
    }

    .mission-sub {
      color: var(--muted);
      font-size: 15px;
      max-width: 500px;
      margin: 0 auto 48px;
    }

    /* ── FOOTER ── */
    footer {
      border-top: 1px solid var(--border);
      padding: 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      max-width: 1100px;
      margin: 0 auto;
      flex-wrap: wrap;
      gap: 20px;
      position: relative;
      z-index: 1;
    }

    .footer-left {
      font-family: var(--mono);
      font-size: 12px;
      color: var(--muted);
      display: flex;
      align-items: center;
      gap: 8px;
    }

    .footer-links { display: flex; gap: 24px; }
    .footer-links a {
      font-size: 13px;
      color: var(--muted);
      text-decoration: none;
      transition: color 0.2s;
    }
    .footer-links a:hover { color: var(--text); }

    .online-dot {
      display: inline-block;
      width: 8px; height: 8px;
      background: var(--green);
      border-radius: 50%;
      animation: pulse-dot 2s infinite;
    }

    /* ── RESPONSIVE ── */
    @media (max-width: 768px) {
      nav { padding: 16px 20px; }
      .nav-links { display: none; }
      .hero { padding: 100px 20px 60px; }
      section { padding: 60px 20px; }
      .origin-grid { grid-template-columns: 1fr; gap: 40px; }
      .skills-grid { grid-template-columns: 1fr; }
      .stat-grid { grid-template-columns: 1fr 1fr; }
      footer { padding: 30px 20px; }
      .report-card { flex-direction: column; gap: 12px; }
      .report-severity { margin-left: 0; }
    }
  </style>
</head>
<body>

  <div class="scanline"></div>

  <!-- NAV -->
  <nav>
    <a href="#" class="nav-logo">AzureKodo</a>
    <div class="nav-links">
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#reports">Intel</a>
      <a href="#skills">Skills</a>
    </div>
  </nav>

  <!-- HERO -->
  <div class="hero">
    <div class="hero-eyebrow">Cybersecurity Portfolio</div>
    <h1>
      <span class="name">AzureKodo</span>
      <span class="handle">Aspiring SOC Analyst<br/>& Aspiring Ethical Hacker</span>
    </h1>
    <p class="hero-desc">
      Self-taught cybersecurity practitioner from the <strong>Philippines</strong>.
      Building tools, analyzing threats, and documenting the journey of
      <strong>protecting people who can't protect themselves online.</strong>
    </p>
    <div class="hero-tags">
      <span class="tag active">SOC Analysis</span>
      <span class="tag active">Threat Intelligence</span>
      <span class="tag active">Ethical Hacking</span>
      <span class="tag">Phishing Analysis</span>
      <span class="tag">IOC Extraction</span>
      <span class="tag">Python Scripting</span>
    </div>
    <div class="hero-cta">
      <a href="#projects" class="btn btn-primary">View Projects</a>
      <a href="https://github.com/AzureKodo-alt" class="btn btn-ghost" target="_blank">GitHub →</a>
    </div>
  </div>

  <!-- ORIGIN -->
  <section class="origin" id="about">
    <div class="section-label reveal">Origin</div>
    <h2 class="section-title reveal reveal-delay-1">Why Cybersecurity</h2>
    <div class="origin-grid">
      <div class="origin-text reveal reveal-delay-2">
        <p>
          My entry into cybersecurity wasn't through a classroom — it was personal.
          <strong>My mother's Facebook account was compromised in a phishing attack.</strong>
          Instead of accepting the loss, I investigated, learned the recovery process,
          and successfully retrieved her account. That moment changed everything.
        </p>
        <p>
          Seeing how easily someone I love was targeted — not because she was careless,
          but because <strong>nobody taught her what to look for</strong> — made me realize
          how many ordinary Filipinos face the same vulnerability every day.
          Scams, phishing, account takeovers, deepfakes — these aren't just technical problems.
          They're human ones.
        </p>
        <p>
          Since then I've been self-studying — no formal degree, no expensive certifications,
          no shortcuts. Just consistent daily learning, real world practice, and a mission
          that keeps me going even on the hard days.
        </p>
        <div class="origin-quote">
          <p>"Protecting people who can't protect themselves online — that's not just a career goal. It's the reason I'm here."</p>
        </div>
      </div>
      <div class="stat-grid reveal reveal-delay-3">
        <div class="stat-card">
          <span class="stat-number">2+</span>
          <span class="stat-label">HTB Machines Pwned</span>
        </div>
        <div class="stat-card">
          <span class="stat-number">1</span>
          <span class="stat-label">Threat Intel Reports</span>
        </div>
        <div class="stat-card">
          <span class="stat-number">100%</span>
          <span class="stat-label">Self Taught</span>
        </div>
        <div class="stat-card">
          <span class="stat-number">PH</span>
          <span class="stat-label">Based in Philippines</span>
        </div>
      </div>
    </div>
  </section>

  <!-- PROJECTS -->
  <section class="projects" id="projects">
    <div class="section-label reveal">Projects</div>
    <h2 class="section-title reveal reveal-delay-1">Tools Built</h2>
    <div class="project-card reveal reveal-delay-2">
      <div class="project-header">
        <span class="project-name">Phishing Email Analyzer</span>
        <span class="project-badge badge-live">● Live</span>
      </div>
      <p class="project-desc">
        AI-powered phishing email analysis tool built for SOC workflows.
        Extracts IOCs — malicious domains, URLs, IP addresses — detects social engineering
        tactics, assigns severity ratings, flags escalation requirements, and generates
        structured SOC-style incident reports. Directly addresses the growing problem
        of AI-generated phishing overwhelming Tier 1 analyst queues.
      </p>
      <div class="project-stack">
        <span class="stack-tag">IOC Extraction</span>
        <span class="stack-tag">SOC Reporting</span>
        <span class="stack-tag">Phishing Analysis</span>
        <span class="stack-tag">Threat Intelligence</span>
        <span class="stack-tag">Social Engineering Detection</span>
      </div>
    </div>
  </section>

  <!-- THREAT INTEL -->
  <section class="reports" id="reports">
    <div class="section-label reveal">Threat Intelligence</div>
    <h2 class="section-title reveal reveal-delay-1">Real World Analysis</h2>
    <div class="report-card reveal reveal-delay-2">
      <span class="report-id">TIR-2026-001</span>
      <div class="report-info">
        <h4>Filipino Facebook Account Compromise — Online Gambling Scam Campaign</h4>
        <p>
          Analysis of a compromised Filipino Facebook account used to distribute
          phishing URLs disguised as online gambling promotions. Cross-vendor IOC
          correlation across ESET and Fortinet. Documented attack chain, social
          engineering tactics, and recommended response actions.
        </p>
      </div>
      <span class="report-severity sev-high">HIGH</span>
    </div>
  </section>

  <!-- SKILLS -->
  <section class="skills" id="skills">
    <div class="section-label reveal">Capabilities</div>
    <h2 class="section-title reveal reveal-delay-1">Skills & Tools</h2>
    <div class="skills-grid">
      <div class="skill-group reveal reveal-delay-1">
        <div class="skill-group-title">SOC & Defense</div>
        <div class="skill-item">Alert Triage & Analysis</div>
        <div class="skill-item">IOC Identification</div>
        <div class="skill-item">Incident Response</div>
        <div class="skill-item">Phishing Analysis</div>
        <div class="skill-item">Wireshark</div>
        <div class="skill-item">LetsDefend</div>
      </div>
      <div class="skill-group reveal reveal-delay-2">
        <div class="skill-group-title">Offensive Security</div>
        <div class="skill-item">Nmap Reconnaissance</div>
        <div class="skill-item">Metasploit Framework</div>
        <div class="skill-item">HackTheBox</div>
        <div class="skill-item">TryHackMe</div>
        <div class="skill-item">Kali Linux</div>
        <div class="skill-item">Parrot OS</div>
      </div>
      <div class="skill-group reveal reveal-delay-3">
        <div class="skill-group-title">Development</div>
        <div class="skill-item">Python (Learning)</div>
        <div class="skill-item">HTML & CSS</div>
        <div class="skill-item">JavaScript</div>
        <div class="skill-item">GitHub</div>
        <div class="skill-item">Linux CLI</div>
        <div class="skill-item">VS Code</div>
      </div>
    </div>
  </section>

  <!-- MISSION -->
  <section class="mission">
    <div class="section-label reveal">Mission</div>
    <p class="mission-statement reveal reveal-delay-1">
      "Cybersecurity awareness isn't optional in a country where millions are targeted daily."
    </p>
    <p class="mission-sub reveal reveal-delay-2">
      Building tools and spreading awareness to protect ordinary Filipinos
      from phishing, scams, account compromise, and digital exploitation.
    </p>
    <div class="reveal reveal-delay-3">
      <a href="https://github.com/AzureKodo-alt" class="btn btn-primary" target="_blank">
        View GitHub Portfolio
      </a>
    </div>
  </section>

  <!-- FOOTER -->
  <footer>
    <div class="footer-left">
      <span class="online-dot"></span>
      AzureKodo · Philippines · 2026
    </div>
    <div class="footer-links">
      <a href="https://github.com/AzureKodo-alt" target="_blank">GitHub</a>
      <a href="#projects">Projects</a>
      <a href="#reports">Intel Reports</a>
    </div>
  </footer>

  <script>
    // Scroll reveal
    const observer = new IntersectionObserver((entries) => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          entry.target.classList.add('visible');
        }
      });
    }, { threshold: 0.1 });

    document.querySelectorAll('.reveal').forEach(el => observer.observe(el));

    // Navbar active link highlight on scroll
    const sections = document.querySelectorAll('section[id]');
    const navLinks = document.querySelectorAll('.nav-links a');

    window.addEventListener('scroll', () => {
      let current = '';
      sections.forEach(section => {
        const sectionTop = section.offsetTop - 100;
        if (window.scrollY >= sectionTop) current = section.getAttribute('id');
      });
      navLinks.forEach(link => {
        link.style.color = link.getAttribute('href') === `#${current}`
          ? 'var(--accent2)'
          : '';
      });
    });
  </script>

</body>
</html>
