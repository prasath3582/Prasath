<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="prasath" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Your Name – Resume</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:opsz,wght@12..96,500;12..96,700&family=Source+Serif+4:ital,wght@0,400;0,600;1,400&display=swap" rel="stylesheet">
<style>
:root{
  --bg:#EEF1F4; --surface:#FFFFFF; --ink:#16233B; --muted:#56637A; --line:#CFD7E2; --accent:#2A55E5;
  --display:"Bricolage Grotesque","Helvetica Neue",Arial,sans-serif;
  --body:"Source Serif 4",Georgia,"Times New Roman",serif;
  color-scheme:light and dark;
  box-sizing:border-box;
  padding-top:env(safe-area-inset-top,0px);
  padding-bottom:env(safe-area-inset-bottom,0px);
}
@media (prefers-color-scheme:dark){
  :root:not([data-theme="light"]){--bg:#0F1624;--surface:#18223A;--ink:#E8EDF6;--muted:#9AA7BE;--line:#2B3857;--accent:#7C9BFF;color-scheme:dark}
}
:root[data-theme="dark"]{--bg:#0F1624;--surface:#18223A;--ink:#E8EDF6;--muted:#9AA7BE;--line:#2B3857;--accent:#7C9BFF;color-scheme:dark}
html{scroll-padding-top:env(safe-area-inset-top,0px)}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--ink);font:18px/1.6 var(--body)}
a{color:var(--accent);text-underline-offset:3px}
a:focus-visible{outline:2px solid var(--accent);outline-offset:3px}
.wrap{max-width:1040px;margin:0 auto;padding:56px 24px;display:grid;grid-template-columns:280px 1fr;gap:56px}
aside{position:sticky;top:32px;align-self:start}
h1{font:700 clamp(2.4rem,5vw,3.2rem)/1.02 var(--display);letter-spacing:-.02em;margin:0 0 12px}
.role{font:500 1.15rem/1.3 var(--display);color:var(--accent);margin:0 0 24px}
.contact{list-style:none;padding:0;margin:0;color:var(--muted);font-size:.95rem}
.contact li{padding:8px 0;border-top:1px solid var(--line)}
.contact li:last-child{border-bottom:1px solid var(--line)}
h2{font:700 1.5rem/1.2 var(--display);margin:0 0 20px;letter-spacing:-.01em}
section{margin-bottom:48px}
.lead{font-size:1.25rem;line-height:1.55;margin:0 0 48px;max-width:34em}
.job{display:grid;grid-template-columns:130px 1fr;gap:8px 24px;padding:20px 0;border-top:1px solid var(--line)}
.when{color:var(--muted);font-size:.9rem;padding-top:.3em}
.job h3{font:600 1.1rem/1.3 var(--display);margin:0}
.job .org{color:var(--muted);margin:0 0 8px;font-style:italic}
.job ul{margin:0;padding-left:1.1em;max-width:36em}
.job li{margin-bottom:6px}
.skills{display:flex;flex-wrap:wrap;gap:8px;padding:0;margin:0;list-style:none}
.skills li{background:var(--surface);border:1px solid var(--line);border-radius:6px;padding:4px 12px;font:500 .9rem var(--display)}
.proj{padding:16px 0;border-top:1px solid var(--line)}
.proj h3{font:600 1.1rem var(--display);margin:0 0 4px}
.proj p{margin:0;max-width:36em}
@media (max-width:760px){
  .wrap{grid-template-columns:1fr;gap:32px;padding:32px 20px}
  aside{position:static}
  .job{grid-template-columns:1fr}
}
@media print{
  body{background:#fff;color:#000;font-size:11pt}
  .wrap{padding:0;display:block}
  a{color:#000}
}
</style>
</head>
<body>
<div class="wrap">
  <aside>
    <h1>Your Name</h1>
    <p class="role">Software Engineer</p>
    <ul class="contact">
      <li>Chennai, Tamil Nadu</li>
      <li><a href="mailto:you@example.com">you@example.com</a></li>
      <li><a href="https://linkedin.com/in/yourname">linkedin.com/in/yourname</a></li>
      <li><a href="https://github.com/yourname">github.com/yourname</a></li>
    </ul>
  </aside>

  <main>
    <p class="lead">I build reliable web products, from data models to the last pixel. Add two sentences here about what you do best and the kind of work you want next.</p>

    <section>
      <h2>Experience</h2>
      <article class="job">
        <div class="when">2023 – Present</div>
        <div>
          <h3>Senior Software Engineer</h3>
          <p class="org">Company Name</p>
          <ul>
            <li>Led a redesign of the checkout flow, lifting conversion by 12%.</li>
            <li>Cut API response time from 800 ms to 220 ms by reworking caching.</li>
            <li>Mentored four engineers and ran the weekly code review.</li>
          </ul>
        </div>
      </article>
      <article class="job">
        <div class="when">2020 – 2023</div>
        <div>
          <h3>Software Engineer</h3>
          <p class="org">Previous Company</p>
          <ul>
            <li>Built a reporting dashboard used by 300+ internal staff.</li>
            <li>Moved a legacy monolith's billing module to a standalone service.</li>
          </ul>
        </div>
      </article>
    </section>

    <section>
      <h2>Selected projects</h2>
      <div class="proj"><h3><a href="#">Project One</a></h3><p>One line on what it does, who uses it, and the result.</p></div>
      <div class="proj"><h3><a href="#">Project Two</a></h3><p>One line on what it does, who uses it, and the result.</p></div>
    </section>

    <section>
      <h2>Skills</h2>
      <ul class="skills">
        <li>JavaScript</li><li>TypeScript</li><li>React</li><li>Node.js</li><li>Python</li><li>PostgreSQL</li><li>AWS</li><li>System design</li>
      </ul>
    </section>

    <section>
      <h2>Education</h2>
      <article class="job">
        <div class="when">2016 – 2020</div>
        <div>
          <h3>B.E. Computer Science</h3>
          <p class="org">University Name</p>
        </div>
      </article>
    </section>
  </main>
</div>
</body>
</html>
