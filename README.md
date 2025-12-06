# Musab-portfolio-
My personal portfolio website 
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Musab Khuhro — MSB DevMark | Portfolio</title>
  <meta name="description" content="Portfolio of Musab Khuhro — Digital Marketer, SEO & Content Specialist, Canva Designer." />
  <style>
    :root{--bg:#0f1724;--card:#0b1220;--muted:#94a3b8;--accent:#06b6d4;--glass:rgba(255,255,255,0.03)}
    *{box-sizing:border-box;margin:0;padding:0}
    body{font-family:Inter,ui-sans-serif,system-ui,Segoe UI,Roboto,'Helvetica Neue',Arial;background:linear-gradient(180deg,#071027 0%, #071a2a 100%);color:#e6eef6;line-height:1.5}
    .container{max-width:1100px;margin:40px auto;padding:24px}
    header{display:flex;align-items:center;justify-content:space-between;gap:16px}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{width:56px;height:56px;border-radius:12px;background:linear-gradient(135deg,var(--accent),#7c3aed);display:grid;place-items:center;font-weight:700}
    nav ul{display:flex;gap:12px;list-style:none}
    nav a{color:var(--muted);text-decoration:none;padding:8px 12px;border-radius:8px}
    nav a.active,nav a:hover{color:#fff;background:var(--glass)}
    .hero{display:grid;grid-template-columns:1fr 380px;gap:32px;margin-top:36px}
    .card{background:linear-gradient(180deg,rgba(255,255,255,0.02),transparent);border-radius:14px;padding:22px}
    h1{font-size:28px;margin-bottom:6px}
    p.lead{color:var(--muted)}
    .cta{margin-top:16px;display:flex;gap:10px}
    .btn{background:var(--accent);color:#022; padding:10px 14px;border-radius:10px;text-decoration:none;font-weight:600}
    .btn.secondary{background:transparent;border:1px solid rgba(255,255,255,0.06);color:var(--muted)}
    .profile{padding:18px;border-radius:12px;background:linear-gradient(180deg,rgba(255,255,255,0.02),transparent)}
    .avatar{width:100%;border-radius:10px;overflow:hidden;height:220px;background:linear-gradient(135deg,#0ea5a0,#7c3aed);display:flex;align-items:center;justify-content:center;font-size:36px}
    .skills{display:flex;flex-direction:column;gap:10px;margin-top:12px}
    .skill{display:flex;justify-content:space-between;gap:10px}
    .bar{flex:1;height:10px;background:rgba(255,255,255,0.06);border-radius:999px;overflow:hidden;margin-left:12px}
    .bar > i{display:block;height:100%;background:linear-gradient(90deg,var(--accent),#7c3aed)}
    section{margin-top:26px}
    .projects{display:grid;grid-template-columns:repeat(3,1fr);gap:14px}
    .project{padding:14px;border-radius:10px;background:linear-gradient(180deg,rgba(255,255,255,0.01),transparent)}
    .project h4{margin-bottom:8px}
    .project p{color:var(--muted);font-size:14px}
    footer{margin-top:40px;color:var(--muted);text-align:center;padding:18px}
    @media (max-width:900px){.hero{grid-template-columns:1fr}.projects{grid-template-columns:repeat(2,1fr)}nav ul{display:none}}
    @media (max-width:560px){.projects{grid-template-columns:1fr}}
    .contact-form{display:flex;flex-direction:column;gap:10px}
    input,textarea{background:transparent;border:1px solid rgba(255,255,255,0.06);color:inherit;padding:10px;border-radius:8px}
    .tags{display:flex;gap:8px;flex-wrap:wrap}
    .tag{padding:6px 8px;border-radius:999px;background:rgba(255,255,255,0.03);font-size:13px;color:var(--muted)}
    .projects .project .meta{display:flex;gap:8px;flex-wrap:wrap;margin-top:10px}
    .small{font-size:13px;color:var(--muted)}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">
        <div class="logo">MSB</div>
        <div>
          <div style="font-weight:700">Musab Khuhro</div>
          <div class="small">Founder — MSB DevMark · Digital Marketer · SEO Specialist</div>
        </div>
      </div>
      <nav>
        <ul>
          <li><a href="#about" class="active">About</a></li>
          <li><a href="#skills">Skills</a></li>
          <li><a href="#projects">Projects</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </header>

    <main>
      <div class="hero">
        <div class="card">
          <h1>Hi — I’m Musab. I make businesses rank & sell.</h1>
          <p class="lead">I build growth-focused content, SEO strategies, UGC & Meta ads, and visual assets with Canva. I help startups and local businesses increase leads and revenue.</p>
          <div class="cta">
            <a class="btn" href="mailto:musab@example.com?subject=Work%20inquiry">Hire me</a>
            <a class="btn secondary" href="#projects">See projects</a>
          </div>

          <section id="about">
            <h3 style="margin-top:18px">About me</h3>
            <p class="small" style="margin-top:8px">I’m a student and digital marketer — SEO, content writing, guest posting, Canva design, UGC ads, and Google Analytics. I love turning ideas into measurable growth. I manage MSB DevMark where I help clients get real results: higher traffic, better conversions, and clear marketing ROI.</p>
          </section>

          <section id="skills">
            <h3 style="margin-top:18px">What I do</h3>
            <div class="skills">
              <div class="skill"><strong>SEO & Local SEO</strong><div class="bar" title="90%"><i style="width:90%"></i></div></div>
              <div class="skill"><strong>Content Writing & Copy</strong><div class="bar" title="88%"><i style="width:88%"></i></div></div>
              <div class="skill"><strong>Meta Ads & UGC</strong><div class="bar" title="80%"><i style="width:80%"></i></div></div>
              <div class="skill"><strong>Canva & Visuals</strong><div class="bar" title="87%"><i style="width:87%"></i></div></div>
              <div class="skill"><strong>Google Analytics</strong><div class="bar" title="75%"><i style="width:75%"></i></div></div>
            </div>
          </section>

        </div>

        <aside class="profile card">
          <div class="avatar">MSB</div>
          <h3 style="margin-top:12px">Fast facts</h3>
          <div class="small" style="margin-top:6px">Location: Pakistan · Languages: English, Urdu, Sindhi · Availability: Freelance & projects</div>

          <div style="margin-top:12px">
            <div class="tags">
              <div class="tag">SEO</div>
              <div class="tag">Content</div>
              <div class="tag">Canva</div>
              <div class="tag">UGC</div>
              <div class="tag">Meta Ads</div>
            </div>
          </div>

          <div style="margin-top:14px">
            <a class="btn" href="mailto:musab@example.com">Contact</a>
          </div>
        </aside>
      </div>

      <section id="projects">
        <h3 style="margin-top:8px">Selected projects</h3>
        <div class="projects">
          <article class="project card">
            <h4>Local SEO — Cafe Chain (Client)</h4>
            <p>Full local SEO audit, GMB optimization, keyword targeting & citation clean-up. Result: 3x increase in organic bookings in 3 months.</p>
            <div class="meta small">Skills: Local SEO · Google My Business · Content · Reporting</div>
          </article>

          <article class="project card">
            <h4>UGC & Meta Ad Campaign — E‑commerce</h4>
            <p>Scripted & produced UGC-style short ads, ran A/B tests on Meta. Result: 1.8x ROAS improvement and lower CPA.</p>
            <div class="meta small">Skills: UGC · Meta Ads · Copywriting · Analytics</div>
          </article>

          <article class="project card">
            <h4>Content + Guest Posting — SaaS Startup</h4>
            <p>Content calendar, long-form SEO articles and outreach for guest posts. Result: authoritative backlinks and +40% organic sessions in 4 months.</p>
            <div class="meta small">Skills: Content Strategy · Outreach · SEO</div>
          </article>
        </div>
      </section>

      <section id="contact">
        <h3 style="margin-top:24px">Work with me</h3>
        <div style="display:grid;grid-template-columns:1fr 1fr;gap:14px;margin-top:12px">
          <div class="card">
            <p class="small">Want actionable growth, not vague promises. Tell me the goal, your budget range, and your current conversion metric (if any). I’ll reply with a practical plan.</p>
            <ul style="margin-top:12px;color:var(--muted);font-size:14px">
              <li>Hourly consulting, fixed-price packages, or long-term retainers</li>
              <li>Quick audit (48–72 hours) available for paid requests</li>
            </ul>
            <div style="margin-top:12px">
              <a class="btn" href="mailto:musab@example.com?subject=Project%20Inquiry">Email me</a>
            </div>
          </div>

          <div class="card">
            <form class="contact-form" onsubmit="submitContact(event)">
              <input id="name" placeholder="Your name" required />
              <input id="email" type="email" placeholder="Your email" required />
              <input id="subject" placeholder="Subject" />
              <textarea id="message" rows="4" placeholder="Message (goal, budget, current conversion)"></textarea>
              <div style="display:flex;gap:8px;align-items:center;justify-content:flex-end">
                <button class="btn" type="submit">Send</button>
              </div>
            </form>
            <div id="contactResult" class="small" style="margin-top:8px"></div>
          </div>
        </div>
      </section>

    </main>

    <footer>
      <div class="small">© <strong>Musab Khuhro</strong> — MSB DevMark · Built with focus on results</div>
    </footer>
  </div>

  <script>
    // Simple contact handler (client-side only)
    function submitContact(e){
      e.preventDefault();
      const name=document.getElementById('name').value.trim();
      const email=document.getElementById('email').value.trim();
      const subject=document.getElementById('subject').value.trim();
      const message=document.getElementById('message').value.trim();
      const out=document.getElementById('contactResult');
      if(!name||!email){out.textContent='Name and email are required.';return}
      out.textContent='Thanks — this form is demo-only. Click the email button to message directly.';
      // For real form, connect to backend or use a form service like Formspree
    }

    // Smooth nav scrolling
    document.querySelectorAll('nav a').forEach(a=>{
      a.addEventListener('click',e=>{
        e.preventDefault();
        document.querySelectorAll('nav a').forEach(x=>x.classList.remove('active'));
        a.classList.add('active');
        const id=a.getAttribute('href');
        document.querySelector(id).scrollIntoView({behavior:'smooth',block:'start'});
      })
    })
  </script>
</body>
</html>
