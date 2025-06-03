---
layout: homepage
title: DuaSelipar Dev Hub
---

<style>
  .hero {
    background: linear-gradient(135deg, #43cea2, #185a9d);
    color: #fff;
    text-align: center;
    padding: 5rem 2rem;
    border-radius: 20px;
    margin-top: 1rem;
  }

  .hero h1 {
    font-size: 3rem;
    margin-bottom: 1rem;
  }

  .hero p {
    font-size: 1.25rem;
    margin-bottom: 2rem;
  }

  .hero a {
    background: rgba(255,255,255,0.15);
    padding: 0.75rem 1.5rem;
    color: #fff;
    font-weight: bold;
    text-decoration: none;
    border-radius: 10px;
    transition: background 0.3s ease;
    display: inline-block;
  }

  .hero a:hover {
    background: rgba(255,255,255,0.3);
  }

  .section {
    margin-top: 3rem;
    padding: 2rem;
    border-radius: 15px;
    background: #ffffffdd;
    backdrop-filter: blur(10px);
    box-shadow: 0 4px 24px rgba(0,0,0,0.08);
  }

  .section h2 {
    font-size: 1.8rem;
    margin-bottom: 1rem;
    border-left: 5px solid #43cea2;
    padding-left: 1rem;
  }

  .grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
    gap: 1.5rem;
  }

  .grid a {
    background: #f9f9f9;
    padding: 1rem;
    border-radius: 10px;
    text-decoration: none;
    color: #333;
    font-weight: bold;
    box-shadow: 0 2px 10px rgba(0,0,0,0.05);
    transition: transform 0.2s ease, box-shadow 0.2s ease;
  }

  .grid a:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 20px rgba(0,0,0,0.12);
  }

  .footer {
    text-align: center;
    margin: 4rem 0 2rem 0;
    font-size: 0.95rem;
    color: #888;
  }

  .footer a {
    color: #185a9d;
    text-decoration: none;
  }

  .footer a:hover {
    text-decoration: underline;
  }
</style>

<div class="hero" data-aos="zoom-in">
  <h1>🛠️ <span id="typed"></span></h1>
  <p>Tools, guides, and scripting utilities for EO Private Server developers.</p>
  <a href="https://www.facebook.com/profile.php?id=61554036273018" target="_blank">📘 Connect with DuaSelipar</a>
</div>

<div class="section" data-aos="fade-up" id="guides">
  <h2>📚 Guides & References</h2>
  <div class="grid">
    <a href="/eudemons-cq_action-guide/" data-aos="flip-left">⚙️ CQ_Action Type Explaination</a>
    <a href="#" data-aos="flip-left">📜 CQ_Map Explaination (Coming Soon)</a>
  </div>
</div>

<div class="section" data-aos="fade-up" id="tools">
  <h2>🧰 EO Tools</h2>
  <div class="grid">
    <a href="/eoscripts/color-generator.html" data-aos="zoom-in">🎨 Color Code Generator</a>
    <a href="/eoscripts/cq_card-generator.html" data-aos="zoom-in" data-aos-delay="100">🃏 CQ Card Generator</a>
    <a href="/eoscripts/register-generator.html" data-aos="zoom-in" data-aos-delay="200">📝 Register Generator</a>
     <a href="/eoscripts/cq_action-tracker.html" data-aos="zoom-in" data-aos-delay="300">🧠 CQ Action Tracker</a>
    <a href="https://github.com/duaselipar/Mail-Sender" target="_blank" data-aos="zoom-in" data-aos-delay="400">📬 Mail Sender</a>

  </div>
</div>



<div class="footer" id="footer" data-aos="fade-up">
  <p>© 2025 DuaSelipar Dev Hub. Powered by GitHub Pages. View on <a href="https://github.com/duaselipar/duaselipar.github.io" target="_blank">GitHub</a></p>
</div>

<script src="https://cdn.jsdelivr.net/npm/typed.js@2.0.12"></script>
<script>
  new Typed("#typed", {
    strings: ["DuaSelipar Dev Hub", "EO Scripting Tools", "Private Server Resources"],
    typeSpeed: 40,
    backSpeed: 25,
    loop: true
  });
</script>