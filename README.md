<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover">
<meta name="theme-color" content="#0a0e13">
<meta name="mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
<meta name="format-detection" content="telephone=no">
<meta name="description" content="Golla Sai Teja Viswanath — Electrical & Electronics Engineer specializing in VLSI Design, RTL, and Embedded Systems.">
<title>Golla Sai Teja Viswanath — Electrical &amp; Electronics Engineer</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@400;500;600;700&family=IBM+Plex+Mono:wght@400;500;600&family=Inter:wght@400;500;600&display=swap" rel="stylesheet">
<style>
  :root{
    --bg:#0a0e13;
    --panel:#10161d;
    --panel-2:#141b23;
    --line:#22303c;
    --line-soft:#1a232c;
    --text:#e7edf2;
    --text-dim:#8fa1ac;
    --text-faint:#5b6b76;
    --amber:#ffb020;
    --amber-dim:#a5741c;
    --cyan:#5fd9d0;
    --violet:#9d8cff;
    --violet-dim:#6b5fc4;
    --radius:2px;
    --mono:'IBM Plex Mono', monospace;
    --display:'Space Grotesk', sans-serif;
    --body:'Inter', sans-serif;
  }
  *{box-sizing:border-box; margin:0; padding:0;}
  html{scroll-behavior:smooth; -webkit-text-size-adjust:100%; text-size-adjust:100%;}
  html, body{max-width:100%; overflow-x:hidden;}
  body{
    background:var(--bg);
    color:var(--text);
    font-family:var(--body);
    line-height:1.6;
    background-image:
      linear-gradient(var(--line-soft) 1px, transparent 1px),
      linear-gradient(90deg, var(--line-soft) 1px, transparent 1px),
      radial-gradient(circle, rgba(230,180,90,0.35) 1px, transparent 1.4px);
    background-size: 48px 48px, 48px 48px, 48px 48px;
    background-position: -1px -1px, -1px -1px, -1px -1px;
    position:relative;
    overflow-x:hidden;
  }
  body::before{
    content:'';
    position:fixed; inset:0; z-index:0; pointer-events:none;
    background:
      radial-gradient(680px 420px at 82% -6%, rgba(255,176,32,0.16), transparent 60%),
      radial-gradient(640px 460px at -8% 22%, rgba(157,140,255,0.14), transparent 60%),
      radial-gradient(600px 420px at 96% 55%, rgba(95,217,208,0.10), transparent 60%);
  }
  body::after{
    content:'';
    position:fixed; inset:0; z-index:0; pointer-events:none; opacity:.05; mix-blend-mode:overlay;
    background-image:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='120' height='120'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='2' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)'/%3E%3C/svg%3E");
  }
  .wrap, .topbar, header.hero{position:relative; z-index:1;}
  @media (prefers-reduced-motion: reduce){
    html{scroll-behavior:auto;}
    *{animation-duration:0.01ms !important; animation-iteration-count:1 !important; transition-duration:0.01ms !important;}
  }
  a{color:inherit;}
  ::selection{background:var(--amber); color:#12100a;}

  .wrap{max-width:980px; margin:0 auto; padding:0 28px; padding-left:max(28px, env(safe-area-inset-left)); padding-right:max(28px, env(safe-area-inset-right));}

  /* ---------- Nav ---------- */
  .topbar{
    position:sticky; top:0; z-index:50;
    background:rgba(10,14,19,0.88);
    backdrop-filter:blur(6px);
    border-bottom:1px solid var(--line);
    padding-top:env(safe-area-inset-top);
  }
  .topbar-inner{
    display:flex; align-items:center; justify-content:space-between;
    padding:14px 28px; max-width:980px; margin:0 auto;
    padding-left:max(28px, env(safe-area-inset-left)); padding-right:max(28px, env(safe-area-inset-right));
    font-family:var(--mono); font-size:12px; letter-spacing:.04em;
  }
  .brand{color:var(--amber); font-weight:600; text-shadow:0 0 14px rgba(255,176,32,0.35);}
  .brand span{color:var(--text-faint);}
  .navlinks{display:flex; gap:22px;}
  .navlinks a{color:var(--text-dim); text-decoration:none; text-transform:uppercase; font-size:11px; letter-spacing:.08em; transition:color .15s;}
  .navlinks a:hover{color:var(--amber);}
  .navlinks a:focus-visible, a:focus-visible{outline:1px solid var(--amber); outline-offset:3px;}

  /* ---------- Hero ---------- */
  .hero{position:relative; padding:88px 0 64px; border-bottom:1px solid var(--line); overflow:hidden;}
  .scope{position:absolute; right:-10px; top:0; width:440px; max-width:58vw; opacity:.6; pointer-events:none;}
  .eyebrow{
    font-family:var(--mono); font-size:12px; color:var(--amber);
    letter-spacing:.14em; text-transform:uppercase; margin-bottom:18px;
    display:flex; align-items:center; gap:10px;
  }
  .eyebrow::before{content:''; width:8px; height:8px; background:var(--amber); border-radius:50%; box-shadow:0 0 8px var(--amber); animation:blink 2.4s ease-in-out infinite;}
  @keyframes blink{0%,100%{opacity:1;} 50%{opacity:.25;}}
  h1{
    font-family:var(--display); font-weight:700;
    font-size:clamp(34px, 6vw, 60px); line-height:1.04;
    letter-spacing:-0.01em; max-width:14ch;
    background:linear-gradient(100deg, var(--text) 40%, var(--amber) 85%, var(--cyan) 110%);
    -webkit-background-clip:text; background-clip:text; -webkit-text-fill-color:transparent;
  }
  .role{
    font-family:var(--mono); color:var(--cyan); font-size:16px; margin-top:16px;
    max-width:44ch;
  }
  .lede{color:var(--text-dim); max-width:56ch; margin-top:18px; font-size:15.5px;}
  .contact-row{
    display:flex; flex-wrap:wrap; gap:12px; margin-top:32px;
  }
  .contact-row a{
    display:flex; align-items:center; gap:8px;
    font-family:var(--mono); font-size:12.5px; color:var(--text);
    border:1px solid var(--line); padding:9px 14px; border-radius:var(--radius);
    text-decoration:none; transition:border-color .15s, color .15s;
  }
  .contact-row a:hover{border-color:var(--amber); color:var(--amber);}
  .contact-row svg{width:14px; height:14px; stroke:currentColor; fill:none; stroke-width:1.6;}

  /* ---------- Section shell ---------- */
  section{padding:56px 0; border-bottom:1px solid var(--line); position:relative; scroll-margin-top:64px;}
  .sec-head{display:flex; align-items:center; gap:14px; margin-bottom:32px;}
  .sec-num{font-family:var(--mono); color:var(--amber-dim); font-size:12px;}
  .sec-icon{width:20px; height:20px; flex-shrink:0;}
  .sec-icon svg{width:100%; height:100%; stroke:var(--accent, var(--amber)); fill:none; stroke-width:1.6; filter:drop-shadow(0 0 6px rgba(255,176,32,0.35));}
  .sec-title{font-family:var(--display); font-size:24px; font-weight:600; text-transform:uppercase; letter-spacing:.03em;}
  .sec-rule{flex:1; height:1px; background:linear-gradient(90deg, var(--line), transparent);}
  #experience .sec-icon svg{stroke:var(--amber); filter:drop-shadow(0 0 6px rgba(255,176,32,0.35));}
  #education .sec-icon svg{stroke:var(--cyan); filter:drop-shadow(0 0 6px rgba(95,217,208,0.35));}
  #skills .sec-icon svg{stroke:var(--violet); filter:drop-shadow(0 0 6px rgba(157,140,255,0.35));}
  #projects .sec-icon svg{stroke:var(--amber); filter:drop-shadow(0 0 6px rgba(255,176,32,0.35));}
  #certs .sec-icon svg{stroke:var(--cyan); filter:drop-shadow(0 0 6px rgba(95,217,208,0.35));}
  #contact .sec-icon svg{stroke:var(--violet); filter:drop-shadow(0 0 6px rgba(157,140,255,0.35));}
  #profile .sec-icon svg{stroke:var(--amber); filter:drop-shadow(0 0 6px rgba(255,176,32,0.35));}

  /* ---------- Profile ---------- */
  .profile-grid{display:grid; grid-template-columns:1.4fr 1fr; gap:40px;}
  .profile-grid p{color:var(--text-dim); font-size:15px;}
  .field-list{font-family:var(--mono); font-size:12.5px; display:flex; flex-direction:column; gap:10px;}
  .field-list .row{display:flex; justify-content:space-between; border-bottom:1px dashed var(--line-soft); padding-bottom:8px;}
  .field-list .k{color:var(--text-faint);}
  .field-list .v{color:var(--text); text-align:right;}
  .floorplan-bg{position:absolute; right:-20px; top:10px; width:460px; max-width:55vw; opacity:.09; pointer-events:none; z-index:0;}
  #profile .profile-grid{position:relative; z-index:1;}

  /* ---------- Timeline (trace) ---------- */
  .trace{position:relative; padding-left:34px;}
  .trace::before{
    content:''; position:absolute; left:6px; top:6px; bottom:6px; width:2px;
    background:linear-gradient(var(--amber-dim), var(--line) 90%);
  }
  .node{position:relative; margin-bottom:40px;}
  .node:last-child{margin-bottom:0;}
  .node::before{
    content:''; position:absolute; left:-35px; top:5px; width:13px; height:13px;
    background:var(--bg); border:2px solid var(--amber);
    clip-path:polygon(35% 0, 100% 0, 100% 100%, 0 100%, 0 35%);
    box-shadow:0 0 10px rgba(255,176,32,0.55);
  }
  .node-head{display:flex; flex-wrap:wrap; justify-content:space-between; align-items:baseline; gap:8px 16px;}
  .node-role{font-family:var(--display); font-weight:600; font-size:17px;}
  .node-date{font-family:var(--mono); font-size:11.5px; color:var(--amber); white-space:nowrap;}
  .node-org{font-family:var(--mono); font-size:12.5px; color:var(--cyan); margin-top:3px;}
  .node ul{margin-top:12px; padding-left:18px; color:var(--text-dim); font-size:14px;}
  .node li{margin-bottom:6px;}
  .node li::marker{color:var(--amber-dim);}

  /* ---------- Education ---------- */
  .edu-grid{display:grid; grid-template-columns:1fr 1fr; gap:20px;}
  .card{
    background:linear-gradient(160deg, var(--panel) 0%, var(--panel-2) 100%);
    border:1px solid var(--line); padding:22px; border-radius:6px;
    position:relative; overflow:hidden; transition:border-color .2s, transform .2s, box-shadow .2s;
  }
  .card::before{content:''; position:absolute; top:0; left:0; right:0; height:2px; background:linear-gradient(90deg, var(--amber), var(--cyan));}
  .card:hover{border-color:var(--amber-dim); transform:translateY(-3px); box-shadow:0 12px 28px -14px rgba(255,176,32,0.35);}
  .card .school{font-family:var(--display); font-weight:600; font-size:16px;}
  .card .deg{color:var(--text-dim); font-size:13.5px; margin-top:6px;}
  .card .meta{display:flex; justify-content:space-between; align-items:center; margin-top:16px; font-family:var(--mono); font-size:11.5px; color:var(--text-faint);}
  .card .score{color:var(--amber); font-weight:600; text-shadow:0 0 10px rgba(255,176,32,0.4);}

  /* ---------- Skills (datasheet table) ---------- */
  .spec-table{width:100%; border-collapse:collapse; font-size:13.5px;}
  .spec-table tr{border-bottom:1px solid var(--line-soft);}
  .spec-table tr:last-child{border-bottom:none;}
  .spec-table td{padding:14px 0; vertical-align:top;}
  .spec-table td.label{
    font-family:var(--mono); color:var(--text-faint); font-size:11px;
    text-transform:uppercase; letter-spacing:.06em; width:210px; padding-right:20px;
  }
  .chip-row{display:flex; flex-wrap:wrap; gap:8px;}
  .chip{
    font-family:var(--mono); font-size:12px; color:var(--text);
    border:1px solid var(--line); padding:5px 10px; border-radius:var(--radius);
    background:var(--panel-2); position:relative; padding-left:18px; transition:border-color .15s, color .15s;
  }
  .chip::before{content:''; position:absolute; left:8px; top:50%; transform:translateY(-50%); width:5px; height:5px; border-radius:50%; background:var(--dot, var(--amber));}
  .chip:hover{border-color:var(--dot, var(--amber)); color:var(--text);}
  .spec-table tr:nth-child(1) .chip{--dot:var(--amber);}
  .spec-table tr:nth-child(2) .chip{--dot:var(--cyan);}
  .spec-table tr:nth-child(3) .chip{--dot:var(--violet);}
  .spec-table tr:nth-child(4) .chip{--dot:var(--amber);}
  .spec-table tr:nth-child(5) .chip{--dot:var(--cyan);}
  .spec-table tr:nth-child(6) .chip{--dot:var(--violet);}
  .spec-table tr:nth-child(7) .chip{--dot:var(--amber);}
  .spec-table tr:nth-child(8) .chip{--dot:var(--cyan);}

  /* ---------- Projects ---------- */
  .proj-grid{display:grid; grid-template-columns:1fr 1fr; gap:18px;}
  .proj-card{
    background:linear-gradient(160deg, var(--panel) 0%, var(--panel-2) 100%);
    border:1px solid var(--line); padding:20px; border-radius:6px;
    transition:border-color .15s, transform .15s, box-shadow .2s; position:relative; overflow:hidden;
  }
  .proj-card::after{content:''; position:absolute; inset:0; border-radius:6px; padding:1px; pointer-events:none; opacity:0; transition:opacity .2s;
    background:linear-gradient(135deg, var(--violet), transparent 40%, var(--amber));
    -webkit-mask:linear-gradient(#fff 0 0) content-box, linear-gradient(#fff 0 0);
    -webkit-mask-composite:xor; mask-composite:exclude;
  }
  .proj-card:hover{border-color:transparent; transform:translateY(-3px); box-shadow:0 14px 30px -16px rgba(157,140,255,0.4);}
  .proj-card:hover::after{opacity:1;}
  .proj-tag{font-family:var(--mono); font-size:10.5px; color:var(--cyan); text-transform:uppercase; letter-spacing:.06em;}
  .proj-title{font-family:var(--display); font-weight:600; font-size:16px; margin-top:8px;}
  .proj-desc{color:var(--text-dim); font-size:13.5px; margin-top:10px;}

  /* ---------- Certs / extra ---------- */
  .two-col{display:grid; grid-template-columns:1fr 1fr; gap:40px;}
  .list-plain{list-style:none;}
  .list-plain li{
    display:flex; gap:12px; padding:12px 0; border-bottom:1px solid var(--line-soft); font-size:13.5px; color:var(--text-dim);
  }
  .list-plain li:last-child{border-bottom:none;}
  .list-plain .tick{color:var(--amber); font-family:var(--mono); flex-shrink:0;}
  .sub{font-family:var(--display); font-size:14px; font-weight:600; color:var(--text); text-transform:uppercase; letter-spacing:.04em; margin-bottom:14px;}

  /* ---------- Footer ---------- */
  footer{padding:56px 0 80px; padding-bottom:max(80px, calc(40px + env(safe-area-inset-bottom)));}
  .foot-inner{display:flex; flex-wrap:wrap; justify-content:space-between; align-items:flex-end; gap:24px;}
  .foot-title{font-family:var(--display); font-size:26px; font-weight:700;}
  footer .contact-row{margin-top:0;}
  .foot-note{font-family:var(--mono); font-size:11px; color:var(--text-faint); margin-top:40px;}

  /* ---------- Scroll reveal ---------- */
  .reveal{opacity:0; transform:translateY(18px); transition:opacity .6s ease, transform .6s ease;}
  .reveal.in{opacity:1; transform:translateY(0);}
  .reveal-stagger.in .stagger-item{opacity:1; transform:translateY(0);}
  .stagger-item{opacity:0; transform:translateY(14px); transition:opacity .5s ease, transform .5s ease;}
  .stagger-item:nth-child(1){transition-delay:.02s;}
  .stagger-item:nth-child(2){transition-delay:.08s;}
  .stagger-item:nth-child(3){transition-delay:.14s;}
  .stagger-item:nth-child(4){transition-delay:.20s;}
  .stagger-item:nth-child(5){transition-delay:.26s;}
  .stagger-item:nth-child(6){transition-delay:.32s;}

  .navlinks a.active{color:var(--amber);}

  /* ---------- Hamburger / mobile menu ---------- */
  .burger{display:none; flex-direction:column; gap:4px; background:none; border:none; cursor:pointer; padding:6px;}
  .burger span{width:20px; height:2px; background:var(--text); transition:transform .2s, opacity .2s;}
  .mobile-menu{
    display:none; position:fixed; inset:0; z-index:60; background:rgba(10,14,19,0.98);
    flex-direction:column; align-items:center; justify-content:center; gap:26px;
  }
  .mobile-menu.open{display:flex;}
  .mobile-menu a{
    font-family:var(--mono); text-transform:uppercase; letter-spacing:.1em; font-size:15px; color:var(--text);
    text-decoration:none;
  }
  .mobile-menu a:hover{color:var(--amber);}
  .mobile-close{position:absolute; top:20px; right:24px; background:none; border:none; color:var(--text); font-size:22px; cursor:pointer;}

  /* ---------- Stats ---------- */
  .stats-grid{display:grid; grid-template-columns:repeat(4,1fr); gap:1px; background:var(--line); border:1px solid var(--line); border-radius:6px; overflow:hidden;}
  .stat{background:linear-gradient(160deg, var(--panel) 0%, var(--panel-2) 100%); padding:26px 20px; text-align:center; transition:background .2s;}
  .stat:hover{background:var(--panel-2);}
  .stat-num{font-family:var(--display); font-weight:700; font-size:clamp(26px,4vw,38px); color:var(--amber); text-shadow:0 0 18px rgba(255,176,32,0.35);}
  .stat-label{font-family:var(--mono); font-size:10.5px; color:var(--text-faint); text-transform:uppercase; letter-spacing:.06em; margin-top:8px;}

  /* ---------- Contact form ---------- */
  .form-wrap{display:grid; grid-template-columns:1fr 1fr; gap:40px; align-items:start;}
  .form-note{color:var(--text-dim); font-size:14px;}
  .form-note .tag{display:inline-block; font-family:var(--mono); font-size:10.5px; color:var(--cyan); border:1px solid var(--line); padding:3px 8px; border-radius:var(--radius); margin-top:14px;}
  form.contact-form{display:flex; flex-direction:column; gap:14px;}
  .form-field{display:flex; flex-direction:column; gap:6px;}
  .form-field label{font-family:var(--mono); font-size:11px; color:var(--text-faint); text-transform:uppercase; letter-spacing:.06em;}
  .form-field input, .form-field textarea{
    background:var(--panel-2); border:1px solid var(--line); color:var(--text);
    padding:11px 13px; font-family:var(--body); font-size:14px; border-radius:var(--radius);
    transition:border-color .15s;
  }
  .form-field input:focus, .form-field textarea:focus{outline:none; border-color:var(--amber);}
  .form-field textarea{resize:vertical; min-height:100px;}
  .submit-btn{
    font-family:var(--mono); font-size:12.5px; text-transform:uppercase; letter-spacing:.08em;
    background:linear-gradient(100deg, var(--amber), #ffcf70); color:#12100a; border:none; padding:13px 20px; border-radius:var(--radius);
    cursor:pointer; font-weight:600; transition:opacity .15s, box-shadow .2s; align-self:flex-start;
    box-shadow:0 8px 22px -10px rgba(255,176,32,0.55);
  }
  .submit-btn:hover{opacity:.9; box-shadow:0 10px 26px -8px rgba(255,176,32,0.7);}
  .form-status{font-family:var(--mono); font-size:12px; color:var(--cyan); min-height:16px;}

  @media (max-width:760px){
    .navlinks{display:none;}
    .burger{display:flex;}
    .profile-grid, .edu-grid, .two-col, .proj-grid, .form-wrap{grid-template-columns:1fr;}
    .scope{display:none;}
    .spec-table td.label{width:auto; display:block; padding-bottom:6px;}
    .spec-table tr{display:flex; flex-direction:column; padding:12px 0;}
    .stats-grid{grid-template-columns:repeat(2,1fr);}
    .foot-inner{align-items:flex-start;}
  }

  @media (max-width:480px){
    .wrap{padding-left:max(18px, env(safe-area-inset-left)); padding-right:max(18px, env(safe-area-inset-right));}
    .topbar-inner{padding:12px 18px; padding-left:max(18px, env(safe-area-inset-left)); padding-right:max(18px, env(safe-area-inset-right));}
    .hero{padding:56px 0 44px;}
    .eyebrow{font-size:11px; margin-bottom:14px;}
    h1{font-size:clamp(28px, 9vw, 40px); max-width:none;}
    .role{font-size:14px;}
    .lede{font-size:14.5px;}
    .contact-row a{font-size:12px; padding:9px 12px; word-break:break-word;}
    .contact-row svg{width:13px; height:13px; flex-shrink:0;}
    section{padding:40px 0;}
    .sec-title{font-size:19px;}
    .sec-num{font-size:11px;}
    .stats-grid{grid-template-columns:repeat(2,1fr);}
    .stat{padding:18px 12px;}
    .stat-num{font-size:26px;}
    .floorplan-bg{display:none;}
    .node::before{left:-32px;}
    .trace{padding-left:30px;}
    .node-role{font-size:15.5px;}
    .foot-title{font-size:21px;}
    .burger{padding:10px;}
    .burger span{width:22px;}
    .mobile-menu a{font-size:16px; padding:6px 0;}
    .mobile-close{top:calc(20px + env(safe-area-inset-top)); right:20px; font-size:26px; padding:8px;}
    table.spec-table{font-size:13px;}
    .chip{font-size:11.5px;}
    .proj-title{font-size:15px;}
    .form-field input, .form-field textarea{font-size:16px;} /* prevents iOS auto-zoom on focus */
  }

  @media (hover:none){
    .contact-row a, .navlinks a, .submit-btn, .proj-card, .mobile-menu a{transition:none;}
  }
</style>
</head>
<body>

<div class="topbar">
  <div class="topbar-inner">
    <div class="brand">GSTV<span>—2026A</span></div>
    <nav class="navlinks">
      <a href="#experience">Experience</a>
      <a href="#education">Education</a>
      <a href="#skills">Skills</a>
      <a href="#projects">Projects</a>
      <a href="#certs">Certifications</a>
      <a href="#contact">Contact</a>
    </nav>
    <button class="burger" id="burgerBtn" aria-label="Open menu" aria-expanded="false">
      <span></span><span></span><span></span>
    </button>
  </div>
</div>

<div class="mobile-menu" id="mobileMenu">
  <button class="mobile-close" id="mobileClose" aria-label="Close menu">&times;</button>
  <a href="#experience">Experience</a>
  <a href="#education">Education</a>
  <a href="#skills">Skills</a>
  <a href="#projects">Projects</a>
  <a href="#certs">Certifications</a>
  <a href="#contact">Contact</a>
</div>

<header class="hero wrap">
  <svg class="scope" viewBox="0 0 480 340" xmlns="http://www.w3.org/2000/svg">
    <g opacity="0.9">
    <rect x="206.0" y="72" width="4" height="18" fill="#e6b450"/>
    <circle cx="208.0" cy="66" r="2" fill="#e6b450" opacity="0.85"/>
    <line x1="208.0" y1="66" x2="208.0" y2="32" stroke="#e6b450" stroke-width="1" opacity="0.25"/>
    <rect x="232.0" y="72" width="4" height="18" fill="#e6b450"/>
    <circle cx="234.0" cy="66" r="2" fill="#e6b450" opacity="0.85"/>
    <line x1="234.0" y1="66" x2="234.0" y2="32" stroke="#e6b450" stroke-width="1" opacity="0.25"/>
    <rect x="258.0" y="72" width="4" height="18" fill="#e6b450"/>
    <circle cx="260.0" cy="66" r="2" fill="#e6b450" opacity="0.85"/>
    <line x1="260.0" y1="66" x2="260.0" y2="32" stroke="#e6b450" stroke-width="1" opacity="0.25"/>
    <rect x="284.0" y="72" width="4" height="18" fill="#e6b450"/>
    <circle cx="286.0" cy="66" r="2" fill="#e6b450" opacity="0.85"/>
    <line x1="286.0" y1="66" x2="286.0" y2="32" stroke="#e6b450" stroke-width="1" opacity="0.25"/>
    <rect x="310.0" y="72" width="4" height="18" fill="#e6b450"/>
    <circle cx="312.0" cy="66" r="2" fill="#e6b450" opacity="0.85"/>
    <line x1="312.0" y1="66" x2="312.0" y2="32" stroke="#e6b450" stroke-width="1" opacity="0.25"/>
    <rect x="206.0" y="230" width="4" height="18" fill="#e6b450"/>
    <circle cx="208.0" cy="254" r="2" fill="#e6b450" opacity="0.85"/>
    <line x1="208.0" y1="254" x2="208.0" y2="288" stroke="#e6b450" stroke-width="1" opacity="0.25"/>
    <rect x="232.0" y="230" width="4" height="18" fill="#e6b450"/>
    <circle cx="234.0" cy="254" r="2" fill="#e6b450" opacity="0.85"/>
    <line x1="234.0" y1="254" x2="234.0" y2="288" stroke="#e6b450" stroke-width="1" opacity="0.25"/>
    <rect x="258.0" y="230" width="4" height="18" fill="#e6b450"/>
    <circle cx="260.0" cy="254" r="2" fill="#e6b450" opacity="0.85"/>
    <line x1="260.0" y1="254" x2="260.0" y2="288" stroke="#e6b450" stroke-width="1" opacity="0.25"/>
    <rect x="284.0" y="230" width="4" height="18" fill="#e6b450"/>
    <circle cx="286.0" cy="254" r="2" fill="#e6b450" opacity="0.85"/>
    <line x1="286.0" y1="254" x2="286.0" y2="288" stroke="#e6b450" stroke-width="1" opacity="0.25"/>
    <rect x="310.0" y="230" width="4" height="18" fill="#e6b450"/>
    <circle cx="312.0" cy="254" r="2" fill="#e6b450" opacity="0.85"/>
    <line x1="312.0" y1="254" x2="312.0" y2="288" stroke="#e6b450" stroke-width="1" opacity="0.25"/>
    <rect x="172" y="106.0" width="18" height="4" fill="#e6b450"/>
    <circle cx="166" cy="108.0" r="2" fill="#e6b450" opacity="0.85"/>
    <line x1="166" y1="108.0" x2="132" y2="108.0" stroke="#e6b450" stroke-width="1" opacity="0.25"/>
    <rect x="172" y="132.0" width="18" height="4" fill="#e6b450"/>
    <circle cx="166" cy="134.0" r="2" fill="#e6b450" opacity="0.85"/>
    <line x1="166" y1="134.0" x2="132" y2="134.0" stroke="#e6b450" stroke-width="1" opacity="0.25"/>
    <rect x="172" y="158.0" width="18" height="4" fill="#e6b450"/>
    <circle cx="166" cy="160.0" r="2" fill="#e6b450" opacity="0.85"/>
    <line x1="166" y1="160.0" x2="132" y2="160.0" stroke="#e6b450" stroke-width="1" opacity="0.25"/>
    <rect x="172" y="184.0" width="18" height="4" fill="#e6b450"/>
    <circle cx="166" cy="186.0" r="2" fill="#e6b450" opacity="0.85"/>
    <line x1="166" y1="186.0" x2="132" y2="186.0" stroke="#e6b450" stroke-width="1" opacity="0.25"/>
    <rect x="172" y="210.0" width="18" height="4" fill="#e6b450"/>
    <circle cx="166" cy="212.0" r="2" fill="#e6b450" opacity="0.85"/>
    <line x1="166" y1="212.0" x2="132" y2="212.0" stroke="#e6b450" stroke-width="1" opacity="0.25"/>
    <rect x="330" y="106.0" width="18" height="4" fill="#e6b450"/>
    <circle cx="354" cy="108.0" r="2" fill="#e6b450" opacity="0.85"/>
    <line x1="354" y1="108.0" x2="388" y2="108.0" stroke="#e6b450" stroke-width="1" opacity="0.25"/>
    <rect x="330" y="132.0" width="18" height="4" fill="#e6b450"/>
    <circle cx="354" cy="134.0" r="2" fill="#e6b450" opacity="0.85"/>
    <line x1="354" y1="134.0" x2="388" y2="134.0" stroke="#e6b450" stroke-width="1" opacity="0.25"/>
    <rect x="330" y="158.0" width="18" height="4" fill="#e6b450"/>
    <circle cx="354" cy="160.0" r="2" fill="#e6b450" opacity="0.85"/>
    <line x1="354" y1="160.0" x2="388" y2="160.0" stroke="#e6b450" stroke-width="1" opacity="0.25"/>
    <rect x="330" y="184.0" width="18" height="4" fill="#e6b450"/>
    <circle cx="354" cy="186.0" r="2" fill="#e6b450" opacity="0.85"/>
    <line x1="354" y1="186.0" x2="388" y2="186.0" stroke="#e6b450" stroke-width="1" opacity="0.25"/>
    <rect x="330" y="210.0" width="18" height="4" fill="#e6b450"/>
    <circle cx="354" cy="212.0" r="2" fill="#e6b450" opacity="0.85"/>
    <line x1="354" y1="212.0" x2="388" y2="212.0" stroke="#e6b450" stroke-width="1" opacity="0.25"/>
    <rect x="190" y="90" width="140" height="140" rx="6" fill="#12181f" stroke="#e6b450" stroke-width="2">
      <animate attributeName="stroke-dasharray" from="0,600" to="600,0" dur="1.8s" fill="freeze"/>
    </rect>
    <circle cx="204" cy="104" r="3.5" fill="#e6b450"/>
    <text x="260.0" y="156.0" text-anchor="middle" font-family="IBM Plex Mono, monospace" font-size="20" fill="#e6b450" font-weight="600">GSTV</text>
    <text x="260.0" y="176.0" text-anchor="middle" font-family="IBM Plex Mono, monospace" font-size="10" fill="#5fd9d0" letter-spacing="2">REV.2026A</text>
    </g>
    <g opacity="0.85">
      <polyline points="20,300 20,280 60,280 60,300 100,300 100,280 140,280 140,300 180,300 180,280 220,280 220,300"
        fill="none" stroke="#5fd9d0" stroke-width="2" stroke-linejoin="round">
        <animate attributeName="stroke-dasharray" from="0,400" to="400,0" dur="2.2s" fill="freeze"/>
      </polyline>
      <text x="20" y="318" font-family="IBM Plex Mono, monospace" font-size="10" fill="#5fd9d0" letter-spacing="1">CLK</text>
    </g>
  </svg>
  <div class="eyebrow">Bengaluru, India // RTL to rollout</div>
  <h1>Golla Sai Teja Viswanath</h1>
  <div class="role">Electrical &amp; Electronics Engineer — VLSI Design · Embedded Systems · Electrical Testing</div>
  <p class="lede">
    I move between hardware and software: diagnosing 765&nbsp;kV switchyard equipment on one project,
    processing LiDAR point clouds in ROS on another, and now training deep in RTL design and functional
    verification. Three years in the field taught me how real systems actually fail; I'm now channeling
    that instinct into chip-level design. Comfortable with a multimeter, a MATLAB script, or a Verilog
    testbench — and quick to pick up whatever the problem needs next.
  </p>
  <div class="contact-row">
    <a href="tel:+919346437956">
      <svg viewBox="0 0 24 24"><path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72c.127.96.361 1.903.7 2.81a2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45c.907.339 1.85.573 2.81.7A2 2 0 0 1 22 16.92z"/></svg>
      +91 93464 37956
    </a>
    <a href="mailto:golla.vissu03@gmail.com">
      <svg viewBox="0 0 24 24"><path d="M4 4h16v16H4z"/><path d="M22 6l-10 7L2 6"/></svg>
      golla.vissu03@gmail.com
    </a>
    <a href="https://www.linkedin.com/in/golla-sai-teja-viswanath" target="_blank" rel="noopener">
      <svg viewBox="0 0 24 24"><path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-4 0v7h-4v-7a6 6 0 0 1 6-6z"/><rect x="2" y="9" width="4" height="12"/><circle cx="4" cy="4" r="2"/></svg>
      LinkedIn
    </a>
    <a href="https://github.com/Viswanath03-dev" target="_blank" rel="noopener">
      <svg viewBox="0 0 24 24"><path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"/></svg>
      GitHub
    </a>
    <a href="https://viswanath-golla.netlify.app" target="_blank" rel="noopener">
      <svg viewBox="0 0 24 24"><circle cx="12" cy="12" r="10"/><path d="M2 12h20M12 2a15.3 15.3 0 0 1 4 10 15.3 15.3 0 0 1-4 10 15.3 15.3 0 0 1-4-10 15.3 15.3 0 0 1 4-10z"/></svg>
      Portfolio
    </a>
  </div>
</header>

<section class="wrap reveal">
  <div class="stats-grid">
    <div class="stat"><div class="stat-num" data-count="765">0</div><div class="stat-label">kV substations tested</div></div>
    <div class="stat"><div class="stat-num" data-count="6">0</div><div class="stat-label">Engineering projects</div></div>
    <div class="stat"><div class="stat-num" data-count="4">0</div><div class="stat-label">Companies &amp; teams</div></div>
    <div class="stat"><div class="stat-num" data-count="3">0</div><div class="stat-label">Certifications earned</div></div>
  </div>
</section>

<section class="wrap reveal" id="profile">
  <div class="sec-head"><span class="sec-num">PIN 01</span><span class="sec-icon"><svg viewBox="0 0 24 24"><circle cx="12" cy="8" r="4"/><path d="M4 21c0-4 4-7 8-7s8 3 8 7"/></svg></span><span class="sec-title">Profile</span><span class="sec-rule"></span></div>
  <svg class="floorplan-bg" viewBox="0 0 460 260" xmlns="http://www.w3.org/2000/svg">
    <rect x="4" y="4" width="452" height="252" fill="none" stroke="#e6b450" stroke-width="1.5"/>
    <rect x="24" y="24" width="190" height="100" fill="none" stroke="#5fd9d0" stroke-width="1"/>
    <text x="34" y="44" font-family="IBM Plex Mono, monospace" font-size="11" fill="#5fd9d0" letter-spacing="1">CORE / ALU</text>
    <rect x="246" y="24" width="190" height="100" fill="none" stroke="#9d8cff" stroke-width="1"/>
    <text x="256" y="44" font-family="IBM Plex Mono, monospace" font-size="11" fill="#9d8cff" letter-spacing="1">MEM CTRL</text>
    <rect x="24" y="150" width="190" height="86" fill="none" stroke="#e6b450" stroke-width="1"/>
    <text x="34" y="170" font-family="IBM Plex Mono, monospace" font-size="11" fill="#e6b450" letter-spacing="1">I/O PADS</text>
    <rect x="246" y="150" width="190" height="86" fill="none" stroke="#5fd9d0" stroke-width="1"/>
    <text x="256" y="170" font-family="IBM Plex Mono, monospace" font-size="11" fill="#5fd9d0" letter-spacing="1">TEST / DFT</text>
    <line x1="214" y1="74" x2="246" y2="74" stroke="#e6b450" stroke-width="1"/>
    <line x1="119" y1="124" x2="119" y2="150" stroke="#e6b450" stroke-width="1"/>
    <line x1="341" y1="124" x2="341" y2="150" stroke="#e6b450" stroke-width="1"/>
    <line x1="214" y1="193" x2="246" y2="193" stroke="#e6b450" stroke-width="1"/>
  </svg>
  <div class="profile-grid">
    <p>
      Electrical and Electronics Engineer with hands-on experience across electrical testing, embedded
      systems, robotics, and software-driven diagnostics. Comfortable working in Python, SQL, ROS,
      MATLAB/Simulink, and with LiDAR data pipelines, backed by strong analytical and troubleshooting
      instincts built on the field. Currently deepening expertise in VLSI design and verification, with a
      long-standing interest in electronics, automation, and embedded software.
    </p>
    <div class="field-list">
      <div class="row"><span class="k">LOCATION</span><span class="v">Bengaluru, India</span></div>
      <div class="row"><span class="k">EDUCATION</span><span class="v">B.Tech (Honors), EEE — CGPA 8.72</span></div>
      <div class="row"><span class="k">CURRENT</span><span class="v">VLSI Design &amp; Verification Trainee</span></div>
      <div class="row"><span class="k">CORE STACK</span><span class="v">Python · Verilog · MATLAB</span></div>
      <div class="row"><span class="k">DOMAIN</span><span class="v">VLSI / Embedded / EHV Testing</span></div>
    </div>
  </div>
</section>

<section class="wrap reveal" id="experience">
  <div class="sec-head"><span class="sec-num">PIN 02</span><span class="sec-icon"><svg viewBox="0 0 24 24"><rect x="2" y="7" width="20" height="13" rx="2"/><path d="M8 7V5a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v2"/></svg></span><span class="sec-title">Experience</span><span class="sec-rule"></span></div>
  <div class="trace">

    <div class="node">
      <div class="node-head">
        <div><div class="node-role">Advanced VLSI Design &amp; Verification Trainee</div><div class="node-org">Maven Silicon — Bengaluru, India</div></div>
        <div class="node-date">APR 2026 — PRESENT</div>
      </div>
      <ul>
        <li>Designed RTL modules using Verilog, including counters, RAM, FSMs, UART, SPI, ALU, multiplexers, and frequency dividers.</li>
        <li>Developed self-checking Verilog testbenches and performed functional simulation using Xilinx ISim and Intel Quartus Prime.</li>
        <li>Synthesized RTL designs using Xilinx XST and Intel Quartus Prime.</li>
        <li>Applied digital design concepts including finite state machines (FSMs), blocking/non-blocking assignments, timing analysis, and RTL coding guidelines.</li>
      </ul>
    </div>

    <div class="node">
      <div class="node-head">
        <div><div class="node-role">Customer Support Engineer — Fault Diagnosis &amp; Troubleshooting</div><div class="node-org">SCOPE T&amp;M Pvt. Ltd. — Pune, India</div></div>
        <div class="node-date">MAY 2025 — APR 2026</div>
      </div>
      <ul>
        <li>Performed fault diagnosis, calibration, servicing, and troubleshooting of electrical testing instruments used in switchyards and EHV power systems.</li>
        <li>Diagnosed hardware and embedded electronic systems at the component level (ICs and microcontrollers) and documented findings in detailed technical reports.</li>
        <li>Executed testing and maintenance of high-voltage equipment — transformers, circuit breakers, lightning arresters — in substations up to 765&nbsp;kV.</li>
        <li>Delivered technical seminars to government and private sector clients to improve system reliability.</li>
      </ul>
    </div>

    <div class="node">
      <div class="node-head">
        <div><div class="node-role">Electrical Testing Engineer — R&amp;D Center</div><div class="node-org">A-THON Allterrain Pvt. Ltd. — Bengaluru, India</div></div>
        <div class="node-date">DEC 2024 — APR 2025</div>
      </div>
      <ul>
        <li>Conducted data-driven testing and performance analysis of vehicle wiring harnesses, sensors, and engine components under all-terrain conditions.</li>
        <li>Developed and maintained FMEA and Poka-Yoke reports, service manuals, and validation reports for engineering teams.</li>
        <li>Optimized testing workflows and installed/maintained solar photovoltaic systems, ensuring electrical safety and performance.</li>
      </ul>
    </div>

    <div class="node">
      <div class="node-head">
        <div><div class="node-role">Electrical / Instrumentation Intern</div><div class="node-org">Godavari Gas Power Plant (236 MW) — Jegurupadu, India</div></div>
        <div class="node-date">SEP 2021 — MAR 2022</div>
      </div>
      <ul>
        <li>Assisted in maintenance and monitoring of electrical and instrumentation equipment in large-scale power generation systems.</li>
      </ul>
    </div>

  </div>
</section>

<section class="wrap reveal" id="education">
  <div class="sec-head"><span class="sec-num">PIN 03</span><span class="sec-icon"><svg viewBox="0 0 24 24"><path d="M2 9l10-5 10 5-10 5-10-5z"/><path d="M6 11v5c0 1 3 3 6 3s6-2 6-3v-5"/></svg></span><span class="sec-title">Education</span><span class="sec-rule"></span></div>
  <div class="edu-grid reveal-stagger">
    <div class="card stagger-item">
      <div class="school">Sagi Rama Krishnam Raju Engineering College</div>
      <div class="deg">B.Tech (Honors) in Electrical and Electronics Engineering</div>
      <div class="meta"><span>2022 — 2025</span><span class="score">CGPA 8.72</span></div>
    </div>
    <div class="card stagger-item">
      <div class="school">Andhra Polytechnic, Kakinada</div>
      <div class="deg">Diploma in Electrical and Electronics Engineering</div>
      <div class="meta"><span>2019 — 2022</span><span class="score">86.52%</span></div>
    </div>
  </div>
</section>

<section class="wrap reveal" id="skills">
  <div class="sec-head"><span class="sec-num">PIN 04</span><span class="sec-icon"><svg viewBox="0 0 24 24"><rect x="6" y="6" width="12" height="12" rx="1"/><path d="M9 2v3M15 2v3M9 19v3M15 19v3M2 9h3M2 15h3M19 9h3M19 15h3"/></svg></span><span class="sec-title">Skills</span><span class="sec-rule"></span></div>
  <table class="spec-table">
    <tr>
      <td class="label">Programming</td>
      <td><div class="chip-row"><span class="chip">Python</span><span class="chip">C</span><span class="chip">SQL</span><span class="chip">Core Java (basics)</span></div></td>
    </tr>
    <tr>
      <td class="label">HDL</td>
      <td><div class="chip-row"><span class="chip">Verilog</span></div></td>
    </tr>
    <tr>
      <td class="label">VLSI / Digital Design</td>
      <td><div class="chip-row"><span class="chip">RTL Design</span><span class="chip">Synthesis</span><span class="chip">Digital Logic Design</span></div></td>
    </tr>
    <tr>
      <td class="label">EDA / Simulation</td>
      <td><div class="chip-row"><span class="chip">Intel Quartus Prime</span><span class="chip">Xilinx ISim</span><span class="chip">Xilinx XST</span><span class="chip">MATLAB</span><span class="chip">Simulink</span><span class="chip">Multisim</span></div></td>
    </tr>
    <tr>
      <td class="label">Design Tools</td>
      <td><div class="chip-row"><span class="chip">AutoCAD</span><span class="chip">CATIA</span><span class="chip">Creo</span><span class="chip">Figma</span></div></td>
    </tr>
    <tr>
      <td class="label">Domains</td>
      <td><div class="chip-row"><span class="chip">VLSI Design</span><span class="chip">Digital Electronics</span><span class="chip">Analog Electronics</span><span class="chip">Power Electronics</span><span class="chip">Embedded Systems</span><span class="chip">Electrical Testing</span><span class="chip">IoT</span><span class="chip">Robotics (basics)</span></div></td>
    </tr>
    <tr>
      <td class="label">Additional</td>
      <td><div class="chip-row"><span class="chip">Linux</span><span class="chip">ROS (basics)</span><span class="chip">LiDAR Processing</span><span class="chip">Data Structures</span></div></td>
    </tr>
    <tr>
      <td class="label">Soft Skills</td>
      <td><div class="chip-row"><span class="chip">Team Collaboration</span><span class="chip">Communication</span><span class="chip">Problem Solving</span><span class="chip">Adaptability</span><span class="chip">Continuous Learning</span></div></td>
    </tr>
  </table>
</section>

<section class="wrap reveal" id="projects">
  <div class="sec-head"><span class="sec-num">PIN 05</span><span class="sec-icon"><svg viewBox="0 0 24 24"><path d="M12 2 2 7l10 5 10-5-10-5z"/><path d="M2 17l10 5 10-5"/><path d="M2 12l10 5 10-5"/></svg></span><span class="sec-title">Projects</span><span class="sec-rule"></span></div>
  <div class="proj-grid reveal-stagger">
    <div class="proj-card stagger-item">
      <div class="proj-tag">Verilog HDL — In Progress</div>
      <div class="proj-title">APB Interfaced SPI Master IP Core</div>
      <p class="proj-desc">Designing an APB-interfaced SPI Master IP Core based on the AMBA APB protocol, with configurable SPI modes (CPOL/CPHA), baud-rate generation, and TX/RX logic. Verified with self-checking testbenches.</p>
    </div>
    <div class="proj-card stagger-item">
      <div class="proj-tag">Verilog HDL — Xilinx ISim &amp; Quartus Prime</div>
      <div class="proj-title">RTL Design Projects</div>
      <p class="proj-desc">Designed and verified RTL modules including a 4:1 multiplexer, 8-bit ALU, frequency divider, UART, SPI, sequence detector, RAM, up/down counter, and FSMs — synthesized with industry-standard coding guidelines.</p>
    </div>
    <div class="proj-card stagger-item">
      <div class="proj-tag">MATLAB / Simulink</div>
      <div class="proj-title">Fuel Cell with DC–DC Boost Converter</div>
      <p class="proj-desc">Designed and simulated a fuel cell integrated with a DC–DC boost converter to improve voltage regulation and conversion efficiency.</p>
    </div>
    <div class="proj-card stagger-item">
      <div class="proj-tag">Boson Motors — ROS &amp; RViz</div>
      <div class="proj-title">Vehicle Localization &amp; Prediction</div>
      <p class="proj-desc">Implemented vehicle localization by processing 3D LiDAR point cloud data using ROS and RViz for autonomous navigation and environmental perception.</p>
    </div>
    <div class="proj-card stagger-item">
      <div class="proj-tag">Final Year Project</div>
      <div class="proj-title">Enhancing Electrical Component Performance</div>
      <p class="proj-desc">Performed testing and reliability analysis of electrical wiring harnesses and related components to improve system performance and durability.</p>
    </div>
  </div>
  <div class="contact-row" style="margin-top:24px;">
    <a href="https://github.com/Viswanath03-dev" target="_blank" rel="noopener">
      <svg viewBox="0 0 24 24"><path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"/></svg>
      View full code on GitHub
    </a>
  </div>
</section>

<section class="wrap reveal" id="certs">
  <div class="sec-head"><span class="sec-num">PIN 06</span><span class="sec-icon"><svg viewBox="0 0 24 24"><circle cx="12" cy="8" r="6"/><path d="M8.5 13 7 22l5-3 5 3-1.5-9"/></svg></span><span class="sec-title">Certifications &amp; Beyond</span><span class="sec-rule"></span></div>
  <div class="two-col">
    <div>
      <div class="sub">Certifications</div>
      <ul class="list-plain">
        <li><span class="tick">›</span>Advanced VLSI Design and Verification — Maven Silicon (Ongoing)</li>
        <li><span class="tick">›</span>Digital Protection of Power Systems — NPTEL, IIT Roorkee (2025)</li>
        <li><span class="tick">›</span>Sensor Technologies: Physics, Fabrication &amp; Circuits — NPTEL, IISER (2024)</li>
        <li><span class="tick">›</span>Solar PV Installer – Electrical (SGJ/Q012) — NSDC, Bhimavaram (Jul–Sep 2023)</li>
      </ul>
      <div class="sub" style="margin-top:32px;">Workshops &amp; Expos</div>
      <ul class="list-plain">
        <li><span class="tick">›</span>IMTEX 2025 &amp; 2026 Expo — representing A-THON Allterrain and SCOPE T&amp;M</li>
        <li><span class="tick">›</span>UI/UX Design Workshop — SRKR</li>
        <li><span class="tick">›</span>Electric Vehicle Workshop — JNTUK</li>
      </ul>
    </div>
    <div>
      <div class="sub">Extra-Curricular</div>
      <ul class="list-plain">
        <li><span class="tick">›</span>NSS Joint Secretary, SRKR — represented the college at the JNTUK Republic Day Parade; completed a 7-day NSS Special Camp in West Godavari.</li>
        <li><span class="tick">›</span>Basketball player — represented the Andhra Pradesh Special Police (APSP) team, Kakinada.</li>
      </ul>
    </div>
  </div>
</section>

<section class="wrap reveal" id="contact">
  <div class="sec-head"><span class="sec-num">PIN 07</span><span class="sec-icon"><svg viewBox="0 0 24 24"><path d="M22 2 11 13"/><path d="M22 2 15 22l-4-9-9-4 20-7z"/></svg></span><span class="sec-title">Get in touch</span><span class="sec-rule"></span></div>
  <div class="form-wrap">
    <div class="form-note">
      <p>Hiring for VLSI, embedded systems, or electrical engineering roles? Send a message below
      and it'll open directly in your email app, addressed to me — nothing gets stored or sent
      through a third party.</p>
      <span class="tag">RESPONSE TIME ~24H</span>
      <div class="contact-row" style="margin-top:24px;">
        <a href="mailto:golla.vissu03@gmail.com">Email</a>
        <a href="tel:+919346437956">Call</a>
        <a href="https://www.linkedin.com/in/golla-sai-teja-viswanath" target="_blank" rel="noopener">LinkedIn</a>
        <a href="https://github.com/Viswanath03-dev" target="_blank" rel="noopener">GitHub</a>
        <a href="https://viswanath-golla.netlify.app" target="_blank" rel="noopener">Portfolio</a>
      </div>
    </div>
    <form class="contact-form" id="contactForm">
      <div class="form-field">
        <label for="cf-name">Name</label>
        <input id="cf-name" name="name" type="text" required>
      </div>
      <div class="form-field">
        <label for="cf-email">Your email</label>
        <input id="cf-email" name="email" type="email" required>
      </div>
      <div class="form-field">
        <label for="cf-message">Message</label>
        <textarea id="cf-message" name="message" required></textarea>
      </div>
      <button type="submit" class="submit-btn">Send message</button>
      <div class="form-status" id="formStatus"></div>
    </form>
  </div>
</section>

<footer class="wrap">
  <div class="foot-inner">
    <div>
      <div class="eyebrow">Let's connect</div>
      <div class="foot-title">Open to VLSI, embedded &amp;<br>electrical engineering roles.</div>
    </div>
  </div>
  <div class="foot-note">© 2026 GOLLA SAI TEJA VISWANATH — BENGALURU, INDIA — OPEN TO OPPORTUNITIES</div>
</footer>

<script>
(function(){
  // ---- Mobile menu ----
  var burger = document.getElementById('burgerBtn');
  var menu = document.getElementById('mobileMenu');
  var closeBtn = document.getElementById('mobileClose');
  function openMenu(){ menu.classList.add('open'); burger.setAttribute('aria-expanded','true'); }
  function closeMenu(){ menu.classList.remove('open'); burger.setAttribute('aria-expanded','false'); }
  if(burger){ burger.addEventListener('click', openMenu); }
  if(closeBtn){ closeBtn.addEventListener('click', closeMenu); }
  menu.querySelectorAll('a').forEach(function(a){ a.addEventListener('click', closeMenu); });

  // ---- Scroll reveal ----
  var reduceMotion = window.matchMedia('(prefers-reduced-motion: reduce)').matches;
  var revealTargets = document.querySelectorAll('.reveal, .reveal-stagger');
  if(reduceMotion){
    revealTargets.forEach(function(el){ el.classList.add('in'); });
  } else if('IntersectionObserver' in window){
    var io = new IntersectionObserver(function(entries){
      entries.forEach(function(entry){
        if(entry.isIntersecting){
          entry.target.classList.add('in');
          io.unobserve(entry.target);
        }
      });
    }, {threshold:0.12, rootMargin:'0px 0px -60px 0px'});
    revealTargets.forEach(function(el){ io.observe(el); });
  } else {
    revealTargets.forEach(function(el){ el.classList.add('in'); });
  }

  // ---- Animated stat counters ----
  var stats = document.querySelectorAll('.stat-num');
  function animateCount(el){
    var target = parseInt(el.getAttribute('data-count'), 10) || 0;
    if(reduceMotion){ el.textContent = target; return; }
    var duration = 1100, start = null;
    function step(ts){
      if(start === null) start = ts;
      var progress = Math.min((ts - start) / duration, 1);
      var eased = 1 - Math.pow(1 - progress, 3);
      el.textContent = Math.round(eased * target);
      if(progress < 1){ requestAnimationFrame(step); }
    }
    requestAnimationFrame(step);
  }
  if('IntersectionObserver' in window){
    var statIo = new IntersectionObserver(function(entries){
      entries.forEach(function(entry){
        if(entry.isIntersecting){
          animateCount(entry.target);
          statIo.unobserve(entry.target);
        }
      });
    }, {threshold:0.5});
    stats.forEach(function(el){ statIo.observe(el); });
  } else {
    stats.forEach(animateCount);
  }

  // ---- Active nav link on scroll ----
  var navLinks = document.querySelectorAll('.navlinks a');
  var sections = Array.prototype.map.call(navLinks, function(a){
    return document.querySelector(a.getAttribute('href'));
  }).filter(Boolean);
  function onScroll(){
    var pos = window.scrollY + 140;
    var current = null;
    sections.forEach(function(sec){
      if(sec.offsetTop <= pos){ current = sec; }
    });
    navLinks.forEach(function(a){
      var target = document.querySelector(a.getAttribute('href'));
      a.classList.toggle('active', target === current);
    });
  }
  window.addEventListener('scroll', onScroll, {passive:true});
  onScroll();

  // ---- Contact form (mailto handoff, no backend) ----
  var form = document.getElementById('contactForm');
  var status = document.getElementById('formStatus');
  if(form){
    form.addEventListener('submit', function(e){
      e.preventDefault();
      var name = form.name.value.trim();
      var email = form.email.value.trim();
      var message = form.message.value.trim();
      if(!name || !email || !message){
        status.textContent = 'Please fill in every field.';
        return;
      }
      var subject = encodeURIComponent('Portfolio inquiry from ' + name);
      var body = encodeURIComponent(message + '\n\n— ' + name + ' (' + email + ')');
      window.location.href = 'mailto:golla.vissu03@gmail.com?subject=' + subject + '&body=' + body;
      status.textContent = 'Opening your email app…';
    });
  }
})();
</script>
</body>
</html>
