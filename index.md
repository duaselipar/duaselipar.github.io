---
layout: homepage
title: DuaSelipar Dev Hub
---

<style>
.hero-nocard {
  text-align: center;
  padding: 4rem 0 2.2rem 0;
}
.hero-nocard .hero-ico {
  width: 64px; height: 64px;
  background: var(--icon-bg);
  color: var(--accent);
  display: flex; align-items: center; justify-content: center;
  border-radius: 50%;
  font-size: 2.4rem;
  margin: 0 auto 1.5rem auto;
}
.hero-nocard h1 {
  font-size: 2.7rem;
  font-weight: 800;
  margin-bottom: 0.7rem;
  letter-spacing: -1.2px;
}
.hero-nocard p {
  font-size: 1.16rem;
  color: #535669;
  font-weight: 500;
  margin-bottom: 2rem;
}
.hero-nocard .hero-btns {
  display: flex; gap: 1rem; justify-content: center; flex-wrap: wrap;
}
.hero-nocard .hero-btn {
  background: var(--accent);
  color: #18181b;
  border-radius: 999px;
  padding: 0.93rem 2.1rem;
  font-size: 1.07rem;
  font-weight: 600;
  text-decoration: none;
  border: none;
  transition: background .18s, color .18s;
  cursor: pointer;
  box-shadow: 0 2px 12px #1bd2a36c;
}
.hero-nocard .hero-btn:hover {
  background: #14b8a6;
  color: #fff;
}
.section-nocard {
  margin-top: 3.5rem;
  margin-bottom: 3.5rem;
  background: var(--section);
  border-radius: 18px;
  padding: 2rem 1.4rem 1.6rem 1.4rem;
  box-shadow: 0 1.5px 10px 0 #0001;
  border: 1px solid var(--border);
}
.section-nocard h2 {
  font-size: 1.25rem;
  font-weight: 700;
  margin-bottom: 1.1rem;
  color: var(--text);
  display: flex; align-items: center; gap: .5em;
  letter-spacing: -.2px;
}
.list-nocard {
  display: flex;
  flex-direction: column;
  gap: 0.7rem;
  margin: 0; padding: 0;
}
.list-nocard li {
  list-style: none;
  display: flex;
  align-items: flex-start;
  gap: 1.1rem;
  padding: 1.12rem 0 1.12rem 0;
  border-bottom: 1.3px solid var(--border);
  background: none;
  transition: background .13s;
}
.list-nocard li:last-child { border-bottom: none; }
.list-nocard li .icon {
  width: 38px; height: 38px;
  background: var(--icon-bg);
  color: var(--accent);
  display: flex; align-items: center; justify-content: center;
  border-radius: 50%;
  font-size: 1.3rem;
  margin-top: 0.07rem;
  flex-shrink: 0;
}
.list-nocard li .desc-group {
  flex: 1;
  min-width: 0;
}
.list-nocard li .label {
  font-size: 1.09rem;
  font-weight: 600;
  margin-bottom: .12rem;
  color: var(--text);
  line-height: 1.3;
  text-decoration: none;
  transition: color .16s;
}
.list-nocard li .label[aria-disabled="true"] {
  color: #c3c6d0;
  cursor: not-allowed;
}
.list-nocard li .desc {
  color: #5d6484;
  font-size: .98rem;
  margin-top: 0.07rem;
  line-height: 1.4;
}
.list-nocard li.disabled .label,
.list-nocard li.disabled .desc { color: #c3c6d0;}
.list-nocard li.disabled .icon { filter: grayscale(0.9) opacity(.4);}
.list-nocard li a.label {
  text-decoration: none;
  color: inherit;
}
.list-nocard li:hover:not(.disabled) { background: #eafff7; }
.footer-nocard {
  text-align: center;
  color: #a2adc7;
  font-size: .99rem;
  margin: 3.5rem 0 1.6rem 0;
  padding-top: 1.1rem;
  border-top: 1.2px solid var(--border);
}
.footer-nocard a { color: var(--accent); text-decoration: underline dotted;}
.footer-nocard a:hover { color: #18e8c6; }
@media (max-width: 600px) {
  .hero-nocard h1 { font-size: 1.45rem;}
  .section-nocard { margin-top:2rem;margin-bottom:2rem; padding:1.1rem .4rem;}
  .list-nocard li { padding: 0.78rem 0; gap:0.65rem;}
}
</style>

<div class="hero-nocard">
  <div class="hero-ico">
    <svg width="30" height="30" fill="none" stroke="currentColor" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round" viewBox="0 0 24 24"><circle cx="12" cy="12" r="10" opacity="0.16"/><path d="M8 16l4-8 4 8"/><path d="M9.5 13h5"/></svg>
  </div>
  <h1>DuaSelipar Dev Hub</h1>
  <p>
    Developer tools and guides for Eudemons Online private server.<br>
    Simple, fast, and built for the EO scripting community.
  </p>
  <div class="hero-btns">
    <a href="#tools" class="hero-btn">EO Tools</a>
    <a href="#guides" class="hero-btn">Guides</a>
    <a href="https://www.facebook.com/profile.php?id=61554036273018" target="_blank" class="hero-btn">Facebook</a>
    <a href="https://github.com/duaselipar/duaselipar.github.io" target="_blank" class="hero-btn">GitHub</a>
  </div>
</div>

<section class="section-nocard" id="guides">
  <h2>
    <svg width="21" height="21" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><rect x="4" y="5" width="16" height="14" rx="2"/><path d="M16 3v4"/></svg>
    Guides & References
  </h2>
  <ul class="list-nocard">
    <li>
      <div class="icon">⚙️</div>
      <div class="desc-group">
        <a class="label" href="/eudemons-cq_action-guide/">CQ_Action Type Explained</a>
        <div class="desc">Understand action chains, triggers, and scripting for EO servers.</div>
      </div>
    </li>
    <li class="disabled">
      <div class="icon">🗺️</div>
      <div class="desc-group">
        <span class="label" aria-disabled="true">CQ_Map Guide</span>
        <div class="desc">Map structure, attributes, and customizing EO worlds. <em>Coming soon</em></div>
      </div>
    </li>
  </ul>
</section>

<section class="section-nocard" id="tools">
  <h2>
    <svg width="21" height="21" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><rect x="6" y="4" width="16" height="16" rx="4"/><path d="M12 9v6"/><path d="M9 12h6"/></svg>
    EO Tools
  </h2>
  <ul class="list-nocard">
    <li>
      <div class="icon">🎨</div>
      <div class="desc-group">
        <a class="label" href="/eoscripts/color-generator.html">Color Code Generator</a>
        <div class="desc">Visual color generator for item codes and NPCs.</div>
      </div>
    </li>
    <li>
      <div class="icon">🃏</div>
      <div class="desc-group">
        <a class="label" href="/eoscripts/cq_card-generator.html">CQ Card Generator</a>
        <div class="desc">Generate, preview, and export card scripts for EO servers.</div>
      </div>
    </li>
    <li>
      <div class="icon">📝</div>
      <div class="desc-group">
        <a class="label" href="/eoscripts/register-generator.html">Register Generator</a>
        <div class="desc">Create custom registration links and hashes for your players.</div>
      </div>
    </li>
    <li>
      <div class="icon">🧠</div>
      <div class="desc-group">
        <a class="label" href="/eoscripts/cq_action-tracker.html">CQ Action Tracker</a>
        <div class="desc">Trace and debug action chain calls live.</div>
      </div>
    </li>
    <li>
      <div class="icon">📬</div>
      <div class="desc-group">
        <a class="label" href="https://github.com/duaselipar/Mail-Sender" target="_blank">Mail Sender</a>
        <div class="desc">Automate in-game mail and rewards for events.</div>
      </div>
    </li>
    <li>
      <div class="icon">🔧</div>
      <div class="desc-group">
        <a class="label" href="https://github.com/duaselipar/AutoPatchServerGUIEO" target="_blank">Auto Patch Server</a>
        <div class="desc">Modern patch delivery system for EO clients.</div>
      </div>
    </li>
    <li>
      <div class="icon">📦</div>
      <div class="desc-group">
        <a class="label" href="https://github.com/duaselipar/Eudemon-Patch-Maker" target="_blank">Patch Maker</a>
        <div class="desc">One-click patch package builder and updater.</div>
      </div>
    </li>
    <li>
  <div class="icon">🗑️</div>
  <div class="desc-group">
    <a class="label" href="/eoscripts/reset-database.html" target="_blank">Reset Database</a>
    <div class="desc">Wipe & reset EO account, character, and related tables (old & new database).</div>
  </div>
</li>

<li>
<div class="icon">📝</div>
<div class="desc-group">
  <a class="label" href="https://github.com/duaselipar/ActivityEditorEO" target="_blank">Activity Editor EO</a>
  <div class="desc">
    Editor for <b>playexplain.ini</b>, <b>activitycalendarnew.ini</b> &amp; trigger scripts.<br>
  </div>
</div>
</li>

<li>
  <div class="icon">🛒</div>
  <div class="desc-group">
    <a class="label" href="https://github.com/duaselipar/Event-Shop-Editor-EO" target="_blank">Event Shop Editor EO</a>
    <div class="desc">
      Editor for <b>event shop</b> configuration &amp; items.<br>
    </div>
  </div>
</li>

<li>
  <div class="icon">🗃️</div>
  <div class="desc-group">
    <a class="label" href="https://github.com/duaselipar/FDBEditorEO" target="_blank">FDB Editor EO</a>
    <div class="desc">
      All-in-one FDB file editor. Supports full editing, CSV import/export, copy-paste, and more.<br>
    </div>
  </div>
</li>

<li>
  <div class="icon">🗄️</div>
  <div class="desc-group">
    <a class="label" href="https://github.com/duaselipar/FDB-Merge-Replace" target="_blank">FDB Merge & Replace</a>
    <div class="desc">
      Merge or replace .fdb database files for EO. Supports field mapping, duplicate checking, and instant preview.<br>
    </div>
  </div>
</li>


  </ul>
</section>

<div class="footer-nocard">
  © 2025 DuaSelipar Dev Hub.
  Powered by <a href="https://github.com/duaselipar/duaselipar.github.io" target="_blank">GitHub Pages</a>
</div>
