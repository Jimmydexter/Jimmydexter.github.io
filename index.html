<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Smit Gharat — fabrikat0r</title>
<meta name="description" content="Smit Gharat (fabrikat0r) — Security Researcher & Bug Bounty Hunter. IDOR, auth bypass, SSRF, recon automation.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;500;700;800&family=Inter:wght@400;500;600&display=swap" rel="stylesheet">
<style>
  :root{
    --bg:#0b0e11;
    --surface:#12161c;
    --surface-2:#171c23;
    --line:#232a33;
    --text:#c9d1d9;
    --text-dim:#7d8894;
    --amber:#e8a33d;
    --amber-dim:#a97a30;
    --teal:#3fa796;
    --red:#d16a6a;
    --mono:'JetBrains Mono', ui-monospace, monospace;
    --sans:'Inter', system-ui, sans-serif;
  }
  *{box-sizing:border-box; margin:0; padding:0;}
  html{scroll-behavior:smooth;}
  body{
    background:var(--bg);
    color:var(--text);
    font-family:var(--sans);
    line-height:1.6;
    background-image:
      radial-gradient(circle at 15% 10%, rgba(232,163,61,0.05), transparent 40%),
      radial-gradient(circle at 85% 60%, rgba(63,167,150,0.05), transparent 45%);
  }
  @media (prefers-reduced-motion: reduce){
    *{animation-duration:0.01ms !important; animation-iteration-count:1 !important; transition-duration:0.01ms !important;}
  }
  a{color:inherit;}
  .wrap{max-width:840px; margin:0 auto; padding:0 24px;}

  /* ---------- NAV ---------- */
  header.nav{
    position:sticky; top:0; z-index:50;
    background:rgba(11,14,17,0.88);
    backdrop-filter:blur(8px);
    border-bottom:1px solid var(--line);
  }
  .nav-inner{
    max-width:840px; margin:0 auto; padding:14px 24px;
    display:flex; justify-content:space-between; align-items:center;
    font-family:var(--mono); font-size:13px;
  }
  .nav-inner .brand{color:var(--amber); font-weight:700; letter-spacing:0.02em;}
  .nav-inner .brand span{color:var(--text-dim);}
  .nav-links{display:flex; gap:20px;}
  .nav-links a{color:var(--text-dim); text-decoration:none; transition:color .15s;}
  .nav-links a:hover, .nav-links a:focus-visible{color:var(--amber);}

  /* ---------- HERO / TERMINAL ---------- */
  .hero{padding:64px 0 40px;}
  .term{
    background:var(--surface);
    border:1px solid var(--line);
    border-radius:8px;
    overflow:hidden;
    box-shadow:0 20px 60px -20px rgba(0,0,0,0.6);
  }
  .term-bar{
    display:flex; align-items:center; gap:8px;
    padding:10px 14px;
    background:var(--surface-2);
    border-bottom:1px solid var(--line);
  }
  .dot{width:10px; height:10px; border-radius:50%;}
  .dot.r{background:#d16a6a;} .dot.y{background:#e8c33d;} .dot.g{background:#5cb896;}
  .term-title{margin-left:8px; font-family:var(--mono); font-size:12px; color:var(--text-dim);}
  .term-body{padding:22px 20px; font-family:var(--mono); font-size:13.5px;}
  .term-body .req{color:var(--teal);}
  .term-body .req .path{color:#e8e3d9;}
  .term-body .comment{color:var(--text-dim);}
  .term-body .status-line{color:var(--amber); font-weight:700; margin-top:14px; display:block;}
  .hdr-row{display:flex; gap:8px; margin-top:2px;}
  .hdr-key{color:var(--text-dim); min-width:180px;}
  .hdr-val{color:var(--text);}
  .hdr-val.accent{color:var(--amber);}
  .cursor{display:inline-block; width:8px; height:15px; background:var(--amber); margin-left:2px; animation:blink 1s step-end infinite; vertical-align:text-bottom;}
  @keyframes blink{50%{opacity:0;}}

  .hero-tagline{margin-top:26px; font-size:15px; color:var(--text-dim); max-width:560px;}
  .hero-tagline b{color:var(--text); font-weight:600;}

  /* ---------- SECTION SCAFFOLD ---------- */
  section{padding:52px 0; border-top:1px solid var(--line);}
  .eyebrow{
    font-family:var(--mono); font-size:12px; color:var(--amber-dim);
    text-transform:uppercase; letter-spacing:0.12em; margin-bottom:10px;
  }
  h2{font-family:var(--mono); font-size:20px; color:var(--text); font-weight:700; margin-bottom:18px;}
  p{color:var(--text-dim); font-size:14.5px; max-width:620px;}

  /* ---------- ABOUT ---------- */
  .about-grid{display:grid; grid-template-columns:1fr 1fr; gap:28px; margin-top:20px;}
  @media (max-width:640px){.about-grid{grid-template-columns:1fr;}}
  .fact{border-left:2px solid var(--line); padding-left:14px;}
  .fact .k{font-family:var(--mono); font-size:11px; color:var(--text-dim); text-transform:uppercase; letter-spacing:0.08em;}
  .fact .v{font-size:14.5px; color:var(--text); margin-top:4px;}

  /* ---------- PLATFORMS ---------- */
  .plat-grid{display:grid; grid-template-columns:repeat(3, 1fr); gap:14px; margin-top:20px;}
  @media (max-width:700px){.plat-grid{grid-template-columns:1fr;}}
  .plat-card{
    background:var(--surface); border:1px solid var(--line); border-radius:8px;
    padding:18px; text-decoration:none; display:block; transition:border-color .15s, transform .15s;
  }
  .plat-card:hover, .plat-card:focus-visible{border-color:var(--amber-dim); transform:translateY(-2px);}
  .plat-card .p-name{font-family:var(--mono); font-weight:700; color:var(--text); font-size:14px;}
  .plat-card .p-handle{font-family:var(--mono); font-size:12px; color:var(--teal); margin-top:2px;}
  .plat-card .p-stat{font-family:var(--mono); font-size:11px; color:var(--text-dim); margin-top:10px; padding-top:10px; border-top:1px dashed var(--line);}

  /* ---------- FINDINGS / LOG ---------- */
  .log{margin-top:14px;}
  .log-entry{
    display:grid; grid-template-columns:96px 1fr; gap:16px;
    padding:16px 0; border-bottom:1px solid var(--line);
  }
  .log-entry:last-child{border-bottom:none;}
  .log-tag{
    font-family:var(--mono); font-size:11px; font-weight:700;
    color:var(--bg); background:var(--amber);
    border-radius:4px; padding:3px 6px; height:fit-content; text-align:center;
    letter-spacing:0.03em;
  }
  .log-tag.info{background:var(--teal);}
  .log-tag.crit{background:var(--red);}
  .log-title{font-size:14.5px; color:var(--text); font-weight:600; margin-bottom:4px;}
  .log-desc{font-size:13.5px; color:var(--text-dim);}

  /* ---------- TOOLS ---------- */
  .tool-list{margin-top:16px; display:flex; flex-direction:column; gap:0;}
  .tool-row{
    display:flex; justify-content:space-between; align-items:baseline;
    padding:12px 0; border-bottom:1px solid var(--line); gap:16px;
  }
  .tool-row:last-child{border-bottom:none;}
  .tool-name{font-family:var(--mono); font-size:14px; color:var(--amber); white-space:nowrap;}
  .tool-desc{font-size:13.5px; color:var(--text-dim); text-align:right;}

  /* ---------- WRITEUP ---------- */
  .writeup-card{
    background:var(--surface); border:1px solid var(--line); border-radius:8px;
    padding:20px; margin-top:16px; text-decoration:none; display:block;
    transition:border-color .15s;
  }
  .writeup-card:hover, .writeup-card:focus-visible{border-color:var(--teal);}
  .writeup-card .w-title{font-size:15px; color:var(--text); font-weight:600;}
  .writeup-card .w-meta{font-family:var(--mono); font-size:11.5px; color:var(--teal); margin-top:6px;}
  .writeup-card .w-desc{font-size:13.5px; color:var(--text-dim); margin-top:8px;}

  /* ---------- CONTACT / FOOTER ---------- */
  footer{padding:56px 0 60px;}
  .prompt{font-family:var(--mono); font-size:14px; color:var(--text-dim); margin-bottom:20px;}
  .prompt .sym{color:var(--teal);}
  .contact-links{display:flex; flex-wrap:wrap; gap:12px;}
  .contact-links a{
    font-family:var(--mono); font-size:13px;
    border:1px solid var(--line); border-radius:6px;
    padding:9px 14px; text-decoration:none; color:var(--text);
    transition:border-color .15s, color .15s;
  }
  .contact-links a:hover, .contact-links a:focus-visible{border-color:var(--amber); color:var(--amber);}
  .foot-note{margin-top:32px; font-family:var(--mono); font-size:11.5px; color:var(--text-dim);}

  ::selection{background:var(--amber-dim); color:#0b0e11;}
</style>
</head>
<body>

<header class="nav">
  <div class="nav-inner">
    <div class="brand">smit<span>@</span>fabrikat0r</div>
    <nav class="nav-links">
      <a href="#about">about</a>
      <a href="#platforms">platforms</a>
      <a href="#findings">findings</a>
      <a href="#tools">tools</a>
      <a href="#contact">contact</a>
    </nav>
  </div>
</header>

<main class="wrap">

  <section class="hero" id="top" style="border-top:none; padding-top:56px;">
    <div class="term">
      <div class="term-bar">
        <span class="dot r"></span><span class="dot y"></span><span class="dot g"></span>
        <span class="term-title">smit.local — burp / GET</span>
      </div>
      <div class="term-body">
        <span class="req">GET <span class="path">/smit</span> HTTP/1.1</span><br>
        <span class="comment">Host: fabrikat0r.dev</span><br>
        <span class="comment">User-Agent: recruiter/1.0</span>

        <span class="status-line">HTTP/1.1 200 OK</span>
        <div class="hdr-row"><span class="hdr-key">X-Name:</span><span class="hdr-val">Smit Gharat</span></div>
        <div class="hdr-row"><span class="hdr-key">X-Alias:</span><span class="hdr-val accent">fabrikat0r</span></div>
        <div class="hdr-row"><span class="hdr-key">X-Role:</span><span class="hdr-val">Security Researcher, Independent Bug Bounty Hunter</span></div>
        <div class="hdr-row"><span class="hdr-key">X-Background:</span><span class="hdr-val">Computer Science Engineer</span></div>
        <div class="hdr-row"><span class="hdr-key">X-Focus:</span><span class="hdr-val">IDOR · Auth Bypass · SSRF · Recon Automation</span></div>
        <div class="hdr-row"><span class="hdr-key">X-Status:</span><span class="hdr-val accent">Hunting<span class="cursor"></span></span></div>
      </div>
    </div>

    <p class="hero-tagline">
      I break authentication and authorization logic for a living, then write it up
      so someone else can fix it. <b>Independent researcher</b> across Intigriti, Bugcrowd
      and HackerOne — currently building AI-assisted recon tooling on top of manual
      triage, not instead of it.
    </p>
  </section>

  <section id="about">
    <div class="eyebrow">// 01 about</div>
    <h2>who's asking</h2>
    <p>
      I hunt vulnerabilities across web apps and APIs — auth flows, access control,
      request smuggling, and the messy business-logic edges automated scanners miss.
      Most of my work is manual triage backed by custom tooling I build myself, from
      recon pipelines to JS bundle analyzers.
    </p>
    <div class="about-grid">
      <div class="fact">
        <div class="k">Certification</div>
        <div class="v">Certified Ethical Hacker (CEH)</div>
      </div>
      <div class="fact">
        <div class="k">Education</div>
        <div class="v">B.E. Computer Science</div>
      </div>
      <div class="fact">
        <div class="k">Specialties</div>
        <div class="v">IDOR, XSS, SSRF, auth bypass, subdomain takeover, business logic abuse</div>
      </div>
      <div class="fact">
        <div class="k">Currently</div>
        <div class="v"> Triager at XXXXXXXXX & Building agent-driven recon pipelines & Client-side stuff (Playwright MCP + Burp MCP)</div>
      </div>
    </div>
  </section>

  <section id="platforms">
    <div class="eyebrow">// 02 platforms</div>
    <h2>where the reports live</h2>
    <div class="plat-grid">
      <a class="plat-card" href="https://app.intigriti.com/profile/smit" target="_blank" rel="noopener">
        <div class="p-name">Intigriti</div>
        <div class="p-handle">@smit</div>
        <div class="p-stat">Active researcher — profile ↗</div>
      </a>
      <a class="plat-card" href="https://bugcrowd.com/h/fabrikat0r" target="_blank" rel="noopener">
        <div class="p-name">Bugcrowd</div>
        <div class="p-handle">@fabrikat0r</div>
        <div class="p-stat">Active researcher — profile ↗</div>
      </a>
      <a class="plat-card" href="#contact">
        <div class="p-name">HackerOne</div>
        <div class="p-handle">on request</div>
        <div class="p-stat">Reach out for handle</div>
      </a>
    </div>
  </section>

  <section id="findings">
    <div class="eyebrow">// 03 findings</div>
    <h2>notable work</h2>
    <div class="log">
      <div class="log-entry">
        <span class="log-tag crit">AUTH</span>
        <div>
          <div class="log-title">Unauthenticated referral API exposing customer PII</div>
          <div class="log-desc">Identified an authentication bypass in a third-party referral integration on a major e-commerce platform, allowing unauthenticated retrieval of customer PII and tokens.</div>
        </div>
      </div>
      <div class="log-entry">
        <span class="log-tag">OAUTH</span>
        <div>
          <div class="log-title">PKCE downgrade on an authorization server</div>
          <div class="log-desc">Found a plain-method PKCE downgrade path on a production auth server; scoped and reported despite a BFF architecture limiting direct exploitation.</div>
        </div>
      </div>
      <div class="log-entry">
        <span class="log-tag info">STATE</span>
        <div>
          <div class="log-title">Client-side state corruption &amp; cross-account preference confusion</div>
          <div class="log-desc">Discovered logic flaws where client-side state machines could be manipulated to leak or overwrite another account's stored preferences.</div>
        </div>
      </div>
      <div class="log-entry">
        <span class="log-tag">RECON</span>
        <div>
          <div class="log-title">Large-scale subdomain takeover &amp; postMessage triage</div>
          <div class="log-desc">Built and ran a recon pipeline surfacing subdomain takeover candidates and origin-validation issues in postMessage handlers across a large attack surface.</div>
        </div>
      </div>
    </div>
  </section>

  <section id="writeups">
    <div class="eyebrow">// 04 writeups</div>
    <h2>from the notebook</h2>
    <a class="writeup-card" href="https://medium.com/@smitgharat0001/cloudflare-bypass-origin-server-deserves-some-love-too-e8bd2182cfea" target="_blank" rel="noopener">
      <div class="w-title">Cloudflare Bypass — Origin Server Deserves Some Love Too</div>
      <div class="w-meta">medium.com/@smitgharat0001 ↗</div>
      <div class="w-desc">On why WAF coverage means nothing if the origin server behind it is still reachable directly — and how to find it.</div>
    </a>
  </section>

  <section id="tools">
    <div class="eyebrow">// 05 tooling</div>
    <h2>things I've built</h2>
    <div class="tool-list">
      <div class="tool-row">
        <span class="tool-name">recon-pipeline</span>
        <span class="tool-desc">Agent-driven recon pipeline using Playwright MCP + Burp MCP, split into micro-skills</span>
      </div>
      <div class="tool-row">
        <span class="tool-name">wp_vuln_scanner</span>
        <span class="tool-desc">Bash-based WordPress plugin/theme vulnerability scanner with FFUF enumeration &amp; rate limiting</span>
      </div>
      <div class="tool-row">
        <span class="tool-name">quick-api.js</span>
        <span class="tool-desc">JS endpoint extractor — 54+ patterns for minified/bundled JS</span>
      </div>
      <div class="tool-row">
        <span class="tool-name">scrape-pipeline.js</span>
        <span class="tool-desc">Puppeteer + local LLM recon triage pipeline</span>
      </div>
    </div>
  </section>

  <footer id="contact">
    <div class="eyebrow">// 06 contact</div>
    <div class="prompt"><span class="sym">smit@fabrikat0r</span>:~$ curl -s reach_me</div>
    <div class="contact-links">
      <a href="https://x.com/Fabrikat0r" target="_blank" rel="noopener">X / Twitter ↗</a>
      <a href="https://www.linkedin.com/in/smitgharat/" target="_blank" rel="noopener">LinkedIn ↗</a>
      <a href="https://github.com/Jimmydexter" target="_blank" rel="noopener">GitHub ↗</a>
      <a href="https://app.intigriti.com/profile/smit" target="_blank" rel="noopener">Intigriti ↗</a>
      <a href="https://bugcrowd.com/h/fabrikat0r" target="_blank" rel="noopener">Bugcrowd ↗</a>
    </div>
    <div class="foot-note">// scope is always in writing. report responsibly.</div>
  </footer>

</main>

</body>
</html>
