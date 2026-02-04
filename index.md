---
layout: default
title: RCUAS Workshop Archive
---

<style>
  /* ===== Home Hero ===== */
  .home-hero{
    position: relative;
    border-radius: 20px;
    overflow: hidden;
    margin: 12px 0 18px 0;
    min-height: 320px;
    background-image: url("{{ '/assets/branding/unnamed.jpg' | relative_url }}");
    background-size: cover;
    background-position: center;
  }
  .home-hero::before{
    content:"";
    position:absolute;
    inset:0;
    background:
      radial-gradient(900px 360px at 20% 20%, rgba(0,0,0,.65), rgba(0,0,0,.15)),
      linear-gradient(90deg, rgba(0,0,0,.78), rgba(0,0,0,.25));
  }
  .home-inner{
    position:relative;
    padding: 22px 20px 20px 20px;
    color:#fff;
  }
  .home-logos{
    display:flex;
    gap:14px;
    align-items:center;
    flex-wrap:wrap;
    margin-bottom: 12px;
  }
  .home-logos img{
    height: 46px;
    width:auto;
    background: rgba(255,255,255,.9);
    padding: 6px 10px;
    border-radius: 12px;
  }
  .home-title{
    margin: 0;
    font-size: 34px;
    font-weight: 950;
    letter-spacing: .2px;
    line-height: 1.12;
    max-width: 980px;
  }
  .home-sub{
    margin: 12px 0 0 0;
    font-size: 16px;
    color: rgba(255,255,255,.92);
    max-width: 920px;
    line-height: 1.55;
    font-weight: 650;
  }
  .home-actions{
    display:flex;
    gap:10px;
    flex-wrap:wrap;
    margin-top: 16px;
  }
  .home-btn{
    display:inline-block;
    padding: 10px 14px;
    border-radius: 12px;
    font-weight: 950;
    text-decoration:none;
    border:1px solid rgba(255,255,255,.25);
    background: rgba(255,255,255,.14);
    color:#fff;
    backdrop-filter: blur(6px);
    transition: transform .08s ease, box-shadow .12s ease, background .12s ease;
  }
  .home-btn:hover{ transform: translateY(-1px); background: rgba(255,255,255,.20); box-shadow: 0 10px 26px rgba(0,0,0,.18); }
  .home-btn.primary{
    background: rgba(255,255,255,.92);
    color:#0f172a;
    border-color: rgba(255,255,255,.65);
  }

  /* ===== Key cards ===== */
  .cards{
    display:grid;
    grid-template-columns: repeat(3, minmax(220px, 1fr));
    gap:12px;
    margin: 14px 0 24px 0;
  }
  .card{
    border:1px solid #eee;
    border-radius: 16px;
    padding: 14px 14px;
    background:#fff;
    box-shadow: 0 8px 22px rgba(0,0,0,.04);
  }
  .card .k{
    color:#64748b;
    font-weight:950;
    font-size:12px;
    letter-spacing:.25px;
    text-transform: uppercase;
  }
  .card .v{
    margin-top:8px;
    font-weight:950;
    color:#0f172a;
    font-size:16px;
    line-height:1.35;
  }
  .card .p{
    margin-top:8px;
    color:#475569;
    line-height:1.55;
    font-weight:650;
  }

  /* ===== Section ===== */
  .section{
    margin: 16px 0 10px 0;
    padding: 10px 12px;
    border-radius: 14px;
    background:#0f172a;
    color:#fff;
    font-weight: 950;
    letter-spacing:.2px;
  }
  .list{
    margin: 10px 0 24px 0;
    padding: 0;
    list-style: none;
  }
  .list li{
    padding: 12px 0;
    border-bottom: 1px solid #eee;
  }
  .list li:last-child{ border-bottom:none; }
  .list a{
    font-weight: 950;
    text-decoration:none;
    border-bottom: 1px solid #cbd5e1;
    color:#0f172a;
  }
  .muted{ color:#64748b; font-weight:700; }

  @media (max-width: 900px){
    .cards{ grid-template-columns: 1fr; }
    .home-hero{ min-height: 300px; }
    .home-title{ font-size: 28px; }
  }
</style>

<div class="home-hero">
  <div class="home-inner">
    <div class="home-logos">
      <img src="{{ '/assets/branding/1.png' | relative_url }}" alt="RCUAS">
      <img src="{{ '/assets/branding/2.png' | relative_url }}" alt="AAE">
    </div>

    <h1 class="home-title">Workshop for RCUAS</h1>

    <p class="home-sub">
      RCUAS leads the way in advancing unmanned autonomous systems, committed to transforming challenges into solutions for a sustainable and prosperous future.
    </p>

    <div class="home-actions">
      <a class="home-btn primary" href="{{ '/editions/2026.html' | relative_url }}">View Workshop 2026</a>
      <a class="home-btn" href="{{ '/editions/' | relative_url }}">All Editions</a>
      <a class="home-btn" href="https://www.polyu.edu.hk/rcuas/">About RCUAS</a>
    </div>
  </div>
</div>

<div class="cards">
  <div class="card">
    <div class="k">Mission</div>
    <div class="v">Research → Impact</div>
    <div class="p">Bridging academic breakthroughs and industry needs to deliver reliable autonomous systems.</div>
  </div>
  <div class="card">
    <div class="k">Focus</div>
    <div class="v">UAS · Robotics · Sensing</div>
    <div class="p">From perception &amp; SLAM to planning, safety assurance, and real-world deployment.</div>
  </div>
  <div class="card">
    <div class="k">Workshop</div>
    <div class="v">Talks · Showcase · Materials</div>
    <div class="p">A yearly hub for invited speakers, partners, videos, slides, and project highlights.</div>
  </div>
</div>

<div class="section">Latest</div>
<ul class="list">
  <li>
    <a href="{{ '/editions/2026.html' | relative_url }}">Workshop 2026</a>
    <div class="muted">Agenda, invited speakers/guests, and materials archive.</div>
  </li>
</ul>

<div class="section">Editions</div>
<ul class="list">
  <li><a href="{{ '/editions/2026.html' | relative_url }}">2026</a> <span class="muted">— The 2nd Research Workshop</span></li>
  <!-- 你后面有 2025/2024，就继续加在这里 -->
</ul>

<div class="section">Contact</div>
<p class="muted">
  For enquiries and collaborations, please contact the organizing team via your official channels.
</p>
