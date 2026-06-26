
<style>
*{box-sizing:border-box;margin:0;padding:0}
.rm{max-width:860px;margin:0 auto;padding:1.5rem;font-family:-apple-system,BlinkMacSystemFont,'Segoe UI',sans-serif;color:#1a1a1a;background:#fff}

/* HERO */
.hero{position:relative;padding:3rem 2rem;border-radius:20px;border:1.5px solid #C9A84C;background:#fff;text-align:center;overflow:hidden;margin-bottom:1.5rem}
.hero-corner{position:absolute;width:80px;height:80px;border-color:#C9A84C;border-style:solid;opacity:0.5}
.hero-corner.tl{top:12px;left:12px;border-width:2px 0 0 2px;border-radius:8px 0 0 0}
.hero-corner.tr{top:12px;right:12px;border-width:2px 2px 0 0;border-radius:0 8px 0 0}
.hero-corner.bl{bottom:12px;left:12px;border-width:0 0 2px 2px;border-radius:0 0 0 8px}
.hero-corner.br{bottom:12px;right:12px;border-width:0 2px 2px 0;border-radius:0 0 8px 0}
.hero-eyebrow{font-size:10px;letter-spacing:4px;text-transform:uppercase;color:#C9A84C;font-weight:700;margin-bottom:1rem}
.hero-name{font-size:52px;font-weight:800;letter-spacing:-2px;line-height:1;margin-bottom:0.3rem}
.hero-name .gold{color:#C9A84C}
.hero-role{font-size:13px;letter-spacing:3px;text-transform:uppercase;color:#888;margin-bottom:0.3rem}
.hero-city{font-size:12px;color:#bbb;margin-bottom:1.4rem}
.hero-city b{color:#C9A84C}
.divider-gold{width:60px;height:2px;background:linear-gradient(90deg,transparent,#C9A84C,transparent);margin:0 auto 1.4rem}
.tagline{font-size:14px;color:#555;font-style:italic;margin-bottom:1.8rem;line-height:1.6}
.hero-btns{display:flex;flex-wrap:wrap;gap:8px;justify-content:center}
.hbtn{display:inline-flex;align-items:center;gap:6px;padding:8px 18px;border-radius:8px;font-size:11px;font-weight:700;letter-spacing:1.5px;text-transform:uppercase;cursor:pointer;transition:all .2s;border:1.5px solid #1a1a1a;background:#1a1a1a;color:#fff}
.hbtn:hover{background:#C9A84C;border-color:#C9A84C}
.hbtn.outline{background:transparent;color:#1a1a1a}
.hbtn.outline:hover{background:#1a1a1a;color:#fff}

/* SECTION */
.sec{margin-bottom:1.8rem}
.sec-head{display:flex;align-items:center;gap:12px;margin-bottom:1.2rem}
.sec-num{font-size:10px;font-weight:800;letter-spacing:3px;color:#C9A84C;background:rgba(201,168,76,0.1);border:1px solid rgba(201,168,76,0.3);padding:3px 10px;border-radius:20px}
.sec-line{flex:1;height:1px;background:linear-gradient(90deg,rgba(201,168,76,0.5),transparent)}
.sec-title{font-size:16px;font-weight:700;color:#1a1a1a;letter-spacing:-0.3px}

/* ABOUT */
.about-wrap{display:grid;grid-template-columns:1fr 1fr;gap:10px}
.acard{background:#fafaf8;border:1px solid rgba(201,168,76,0.2);border-radius:12px;padding:1rem 1.1rem;border-left:3px solid #C9A84C}
.acard-lbl{font-size:9px;text-transform:uppercase;letter-spacing:3px;color:#C9A84C;font-weight:800;margin-bottom:5px}
.acard-val{font-size:13px;color:#444;line-height:1.6}

/* SKILLS */
.skills-wrap{display:grid;grid-template-columns:1fr 1fr;gap:8px}
.sk{background:#fafaf8;border:1px solid rgba(201,168,76,0.15);border-radius:10px;padding:10px 14px}
.sk-top{display:flex;justify-content:space-between;align-items:center;margin-bottom:6px}
.sk-name{font-size:12px;font-weight:700;color:#222}
.sk-pct{font-size:11px;font-weight:800;color:#C9A84C}
.sk-track{height:3px;background:#e8e8e5;border-radius:3px;overflow:hidden}
.sk-fill{height:100%;background:linear-gradient(90deg,#C9A84C,#E8C56D);border-radius:3px}
.sk-tags{display:flex;flex-wrap:wrap;gap:6px;margin-top:10px}
.stag{font-size:10px;font-weight:700;letter-spacing:0.5px;padding:4px 10px;border-radius:6px;background:rgba(201,168,76,0.1);color:#8B6914;border:1px solid rgba(201,168,76,0.25)}

/* STATS */
.stats-row{display:grid;grid-template-columns:repeat(3,1fr);gap:10px}
.stc{text-align:center;background:#fafaf8;border:1px solid rgba(201,168,76,0.2);border-radius:12px;padding:1.2rem 0.5rem;position:relative;overflow:hidden}
.stc::before{content:'';position:absolute;top:0;left:0;right:0;height:3px;background:linear-gradient(90deg,transparent,#C9A84C,transparent)}
.stc-n{font-size:36px;font-weight:800;color:#C9A84C;line-height:1}
.stc-l{font-size:9px;text-transform:uppercase;letter-spacing:2px;color:#999;margin-top:4px}

/* PROJECTS */
.proj-list{display:flex;flex-direction:column;gap:10px}
.pcard{display:flex;gap:14px;background:#fafaf8;border:1px solid rgba(201,168,76,0.15);border-radius:14px;padding:1.1rem 1.2rem;cursor:pointer;transition:all .2s;position:relative;overflow:hidden}
.pcard::before{content:'';position:absolute;left:0;top:0;bottom:0;width:3px;background:#C9A84C;border-radius:3px 0 0 3px;opacity:0;transition:.2s}
.pcard:hover{border-color:#C9A84C;transform:translateX(4px)}
.pcard:hover::before{opacity:1}
.picon{width:42px;height:42px;border-radius:10px;background:#1a1a1a;display:flex;align-items:center;justify-content:center;flex-shrink:0;font-size:18px}
.pinfo{flex:1}
.pname{font-size:14px;font-weight:700;color:#1a1a1a;margin-bottom:3px;display:flex;align-items:center;gap:8px}
.pbadge{font-size:9px;font-weight:800;letter-spacing:1px;padding:2px 8px;border-radius:4px;background:#C9A84C;color:#fff;text-transform:uppercase}
.pdesc{font-size:12px;color:#666;line-height:1.5;margin-bottom:8px}
.ptags{display:flex;flex-wrap:wrap;gap:5px}
.ptag{font-size:10px;font-weight:600;padding:2px 8px;border-radius:4px;background:rgba(26,26,26,0.06);color:#555;border:1px solid rgba(26,26,26,0.1)}
.parr{color:#C9A84C;font-size:20px;align-self:center;font-weight:300}

/* GITHUB STATS — fake cards */
.gh-wrap{display:grid;grid-template-columns:1fr 1fr;gap:10px}
.gh-card{background:#fafaf8;border:1px solid rgba(201,168,76,0.2);border-radius:12px;padding:1.2rem;position:relative;overflow:hidden}
.gh-card::before{content:'';position:absolute;top:0;left:0;right:0;height:2px;background:linear-gradient(90deg,#C9A84C,#E8C56D)}
.gh-title{font-size:11px;font-weight:800;letter-spacing:2px;text-transform:uppercase;color:#C9A84C;margin-bottom:1rem}
.gh-row{display:flex;justify-content:space-between;align-items:center;margin-bottom:8px}
.gh-lbl{font-size:12px;color:#666;display:flex;align-items:center;gap:6px}
.gh-dot{width:8px;height:8px;border-radius:50%}
.gh-val{font-size:12px;font-weight:700;color:#1a1a1a}
.gh-stat-big{text-align:center;padding:0.5rem 0}
.gh-big-n{font-size:28px;font-weight:800;color:#C9A84C}
.gh-big-l{font-size:10px;text-transform:uppercase;letter-spacing:2px;color:#aaa;margin-top:2px}
.gh-mini-row{display:grid;grid-template-columns:1fr 1fr;gap:8px;margin-top:10px}
.gh-mini{text-align:center;background:rgba(201,168,76,0.07);border-radius:8px;padding:8px}
.gh-mini-n{font-size:16px;font-weight:800;color:#C9A84C}
.gh-mini-l{font-size:9px;text-transform:uppercase;letter-spacing:1px;color:#999;margin-top:2px}
.lang-bar-wrap{margin-top:8px}
.lang-bar{height:6px;border-radius:6px;display:flex;overflow:hidden;margin-bottom:6px}
.lb-html{background:#e34c26;flex:0.39}
.lb-ts{background:#3178c6;flex:0.35}
.lb-js{background:#f1e05a;flex:0.13}
.lb-css{background:#563d7c;flex:0.09}
.lb-other{background:#ddd;flex:0.04}

/* CONTACT */
.contact-wrap{display:flex;flex-wrap:wrap;gap:8px}
.cbtn{display:inline-flex;align-items:center;gap:7px;padding:10px 20px;border-radius:10px;font-size:12px;font-weight:700;letter-spacing:1px;text-transform:uppercase;border:1.5px solid #1a1a1a;color:#1a1a1a;background:transparent;cursor:pointer;transition:all .2s}
.cbtn:hover,.cbtn.gold{background:#1a1a1a;color:#fff}
.cbtn.gold{background:#C9A84C;border-color:#C9A84C}

/* FOOTER */
.rm-foot{text-align:center;padding:1.5rem 0 0;border-top:1px solid rgba(201,168,76,0.2);margin-top:2rem}
.rm-foot p{font-size:11px;color:#aaa}
.rm-foot b{color:#C9A84C}
.visitor-badge{display:inline-flex;align-items:center;gap:6px;background:#fafaf8;border:1px solid rgba(201,168,76,0.25);border-radius:6px;padding:4px 12px;font-size:11px;color:#888;margin-top:8px}
.visitor-num{font-weight:800;color:#C9A84C}
</style>

<div class="rm">

<!-- HERO -->
<div class="hero">
  <div class="hero-corner tl"></div>
  <div class="hero-corner tr"></div>
  <div class="hero-corner bl"></div>
  <div class="hero-corner br"></div>
  <div class="hero-eyebrow">✦ Portfolio · 2025 ✦</div>
  <div class="hero-name">Jasur<span class="gold">bek</span><br>Nematillayev</div>
  <div class="hero-role">Frontend Developer</div>
  <div class="hero-city">📍 <b>Tashkent</b>, Uzbekistan</div>
  <div class="divider-gold"></div>
  <div class="tagline">"Minimal aesthetics. Maximum precision. Zero compromise."</div>
  <div class="hero-btns">
    <span class="hbtn">⬡ GitHub</span>
    <span class="hbtn">✉ Email</span>
    <span class="hbtn">✈ Telegram</span>
    <span class="hbtn outline">💼 Portfolio</span>
  </div>
</div>

<!-- ABOUT -->
<div class="sec">
  <div class="sec-head">
    <span class="sec-num">01</span>
    <span class="sec-title">About Me</span>
    <div class="sec-line"></div>
  </div>
  <div class="about-wrap">
    <div class="acard">
      <div class="acard-lbl">Who I am</div>
      <div class="acard-val">Frontend developer passionate about building premium, performant web experiences with clean code and sharp design.</div>
    </div>
    <div class="acard">
      <div class="acard-lbl">Current Focus</div>
      <div class="acard-val">Building cinematic portfolio with Next.js 14, and AI-powered Telegram bot — mateAssistent.</div>
    </div>
    <div class="acard">
      <div class="acard-lbl">Location</div>
      <div class="acard-val">🇺🇿 Tashkent, Uzbekistan — open to remote worldwide.</div>
    </div>
    <div class="acard">
      <div class="acard-lbl">Philosophy</div>
      <div class="acard-val">Every pixel matters. Every line has a purpose. Build once, build right.</div>
    </div>
  </div>
</div>

<!-- SKILLS -->
<div class="sec">
  <div class="sec-head">
    <span class="sec-num">02</span>
    <span class="sec-title">Tech Arsenal</span>
    <div class="sec-line"></div>
  </div>
  <div class="skills-wrap">
    <div class="sk"><div class="sk-top"><span class="sk-name">HTML5</span><span class="sk-pct">95%</span></div><div class="sk-track"><div class="sk-fill" style="width:95%"></div></div></div>
    <div class="sk"><div class="sk-top"><span class="sk-name">CSS3 / Sass</span><span class="sk-pct">90%</span></div><div class="sk-track"><div class="sk-fill" style="width:90%"></div></div></div>
    <div class="sk"><div class="sk-top"><span class="sk-name">JavaScript</span><span class="sk-pct">85%</span></div><div class="sk-track"><div class="sk-fill" style="width:85%"></div></div></div>
    <div class="sk"><div class="sk-top"><span class="sk-name">React</span><span class="sk-pct">85%</span></div><div class="sk-track"><div class="sk-fill" style="width:85%"></div></div></div>
    <div class="sk"><div class="sk-top"><span class="sk-name">Tailwind CSS</span><span class="sk-pct">88%</span></div><div class="sk-track"><div class="sk-fill" style="width:88%"></div></div></div>
    <div class="sk"><div class="sk-top"><span class="sk-name">Next.js</span><span class="sk-pct">75%</span></div><div class="sk-track"><div class="sk-fill" style="width:75%"></div></div></div>
    <div class="sk"><div class="sk-top"><span class="sk-name">TypeScript</span><span class="sk-pct">72%</span></div><div class="sk-track"><div class="sk-fill" style="width:72%"></div></div></div>
    <div class="sk"><div class="sk-top"><span class="sk-name">Git</span><span class="sk-pct">82%</span></div><div class="sk-track"><div class="sk-fill" style="width:82%"></div></div></div>
  </div>
  <div class="sk-tags" style="margin-top:10px">
    <span class="stag">React</span><span class="stag">Next.js</span><span class="stag">TypeScript</span><span class="stag">Tailwind</span><span class="stag">Framer Motion</span><span class="stag">Sass</span><span class="stag">Bootstrap</span><span class="stag">Git</span><span class="stag">Lottie</span><span class="stag">GSAP</span>
  </div>
</div>

<!-- STATS -->
<div class="sec">
  <div class="sec-head">
    <span class="sec-num">03</span>
    <span class="sec-title">By the Numbers</span>
    <div class="sec-line"></div>
  </div>
  <div class="stats-row">
    <div class="stc"><div class="stc-n">2+</div><div class="stc-l">Years Coding</div></div>
    <div class="stc"><div class="stc-n">10+</div><div class="stc-l">Projects Built</div></div>
    <div class="stc"><div class="stc-n">8+</div><div class="stc-l">Technologies</div></div>
  </div>
</div>

<!-- PROJECTS -->
<div class="sec">
  <div class="sec-head">
    <span class="sec-num">04</span>
    <span class="sec-title">Featured Projects</span>
    <div class="sec-line"></div>
  </div>
  <div class="proj-list">
    <div class="pcard">
      <div class="picon">🤖</div>
      <div class="pinfo">
        <div class="pname">mateAssistent <span class="pbadge">Live</span></div>
        <div class="pdesc">AI-powered Telegram bot with 16-language support, TON/USDT crypto payments, Payme & Click integrations, RSS feeds and media downloading.</div>
        <div class="ptags"><span class="ptag">Python</span><span class="ptag">Telegram API</span><span class="ptag">AI</span><span class="ptag">Web3</span><span class="ptag">Payme</span><span class="ptag">Click</span></div>
      </div>
      <div class="parr">→</div>
    </div>
    <div class="pcard">
      <div class="picon">🎬</div>
      <div class="pinfo">
        <div class="pname">Cinematic Portfolio <span class="pbadge">WIP</span></div>
        <div class="pdesc">Premium interactive SPA with cinematic room scene, real human characters, gold & white palette. Next.js 14 + Framer Motion + Lottie.</div>
        <div class="ptags"><span class="ptag">Next.js 14</span><span class="ptag">TypeScript</span><span class="ptag">Framer Motion</span><span class="ptag">Tailwind</span><span class="ptag">GSAP</span></div>
      </div>
      <div class="parr">→</div>
    </div>
  </div>
</div>

<!-- GITHUB STATS (visual cards) -->
<div class="sec">
  <div class="sec-head">
    <span class="sec-num">05</span>
    <span class="sec-title">GitHub Activity</span>
    <div class="sec-line"></div>
  </div>
  <div class="gh-wrap">
    <div class="gh-card">
      <div class="gh-title">GitHub Stats</div>
      <div class="gh-stat-big">
        <div class="gh-big-n">Nematillayev379</div>
        <div class="gh-big-l">github.com</div>
      </div>
      <div class="gh-mini-row">
        <div class="gh-mini"><div class="gh-mini-n">⭐</div><div class="gh-mini-l">Stars</div></div>
        <div class="gh-mini"><div class="gh-mini-n">🍴</div><div class="gh-mini-l">Forks</div></div>
        <div class="gh-mini"><div class="gh-mini-n">📦</div><div class="gh-mini-l">Repos</div></div>
        <div class="gh-mini"><div class="gh-mini-n">🔥</div><div class="gh-mini-l">Streak</div></div>
      </div>
    </div>
    <div class="gh-card">
      <div class="gh-title">Most Used Languages</div>
      <div class="lang-bar-wrap">
        <div class="lang-bar">
          <div class="lb-html"></div>
          <div class="lb-ts"></div>
          <div class="lb-js"></div>
          <div class="lb-css"></div>
          <div class="lb-other"></div>
        </div>
      </div>
      <div class="gh-row"><span class="gh-lbl"><span class="gh-dot" style="background:#e34c26"></span>HTML</span><span class="gh-val">39.21%</span></div>
      <div class="gh-row"><span class="gh-lbl"><span class="gh-dot" style="background:#3178c6"></span>TypeScript</span><span class="gh-val">35.12%</span></div>
      <div class="gh-row"><span class="gh-lbl"><span class="gh-dot" style="background:#f1e05a"></span>JavaScript</span><span class="gh-val">13.24%</span></div>
      <div class="gh-row"><span class="gh-lbl"><span class="gh-dot" style="background:#563d7c"></span>CSS</span><span class="gh-val">9.43%</span></div>
      <div class="gh-row"><span class="gh-lbl"><span class="gh-dot" style="background:#ddd"></span>Other</span><span class="gh-val">3.00%</span></div>
    </div>
  </div>
</div>

<!-- CONTACT -->
<div class="sec">
  <div class="sec-head">
    <span class="sec-num">06</span>
    <span class="sec-title">Let's Connect</span>
    <div class="sec-line"></div>
  </div>
  <div class="contact-wrap">
    <span class="cbtn gold">💼 Portfolio</span>
    <span class="cbtn">✉ Email</span>
    <span class="cbtn">✈ Telegram</span>
    <span class="cbtn">👔 LinkedIn</span>
  </div>
</div>

<!-- FOOTER -->
<div class="rm-foot">
  <p>Crafted with <b>♦</b> precision · <b>Jasurbek Nematillayev</b> · Tashkent 🇺🇿</p>
  <div class="visitor-badge">👁 Profile views: <span class="visitor-num">—</span></div>
</div>

</div>
