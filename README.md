<!doctype html>
<html lang="bn">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>MD NAYAN — Portfolio</title>
  <meta name="description" content="MD NAYAN — Portfolio, CV and social links. YouTube & Facebook promotion, freelancing contact." />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap" rel="stylesheet">
  <style>
    :root{ --bg:#0f1724; --card:#0b1220; --muted:#94a3b8; --accent:#06b6d4; --glass: rgba(255,255,255,0.04); --max-w:1100px; color-scheme: dark; font-family: 'Inter', system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial; }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{ margin:0; background:linear-gradient(180deg,#071022 0%, #071a2b 60%); color:#e6eef6; -webkit-font-smoothing:antialiased; -moz-osx-font-smoothing:grayscale; padding:40px 18px; display:flex; justify-content:center; align-items:flex-start; font-size:16px; }
    .wrap{width:100%; max-width:var(--max-w)}
    header{display:flex; justify-content:space-between; align-items:center; margin-bottom:28px}
    .brand{display:flex; gap:14px; align-items:center}
    .avatar{width:84px;height:84px;border-radius:14px;overflow:hidden;background:linear-gradient(135deg,var(--accent),#7c3aed);display:flex;align-items:center;justify-content:center;font-weight:800;color:#021021;border:2px solid rgba(255,255,255,0.06)}
    .avatar img{width:100%;height:100%;object-fit:cover;display:block}
    h1{margin:0;font-size:22px}
    .lead{color:var(--muted);font-weight:500}
    main{display:grid;grid-template-columns:1fr 360px;gap:28px}
    @media (max-width:900px){main{grid-template-columns:1fr} .side{order:2}}
    .card{background:linear-gradient(180deg,var(--card), rgba(11,17,32,0.7)); border-radius:14px; padding:22px; box-shadow:0 6px 20px rgba(2,6,23,0.6);} 
    .hero{display:flex; gap:18px; align-items:flex-start}
    .hero .intro{flex:1}
    .name{font-size:28px;margin:0 0 6px}
    .tag{display:inline-block;padding:6px 10px;border-radius:999px;background:var(--glass);color:var(--muted);font-weight:600;margin-bottom:10px}
    p{line-height:1.6;color:#dbe9f5}
    .actions{display:flex;gap:10px;margin-top:14px}
    .btn{display:inline-flex;gap:10px;align-items:center;padding:10px 14px;border-radius:10px;border:1px solid rgba(255,255,255,0.06);background:transparent;text-decoration:none;color:inherit;font-weight:600}
    .btn.primary{background:linear-gradient(90deg,var(--accent),#7c3aed);color:#021021}
    .skills{display:flex;flex-wrap:wrap;gap:8px;margin-top:12px}
    .skill{background:rgba(255,255,255,0.03);padding:8px 10px;border-radius:8px;font-weight:600;color:var(--muted)}
    .projects{display:grid;grid-template-columns:repeat(2,1fr);gap:12px;margin-top:12px}
    @media (max-width:700px){.projects{grid-template-columns:1fr}}
    .project{padding:12px;border-radius:10px;background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));border:1px solid rgba(255,255,255,0.03)}
    .project h4{margin:0 0 6px}
    .project p{margin:0;color:var(--muted);font-size:14px}
    .side{position:sticky; top:28px}
    .meta-row{display:flex;align-items:center;justify-content:space-between;margin-bottom:8px}
    .contact-list{display:flex;flex-direction:column;gap:8px;margin-top:10px}
    .social{display:flex;gap:8px}
    .social a{display:inline-flex;align-items:center;gap:8px;padding:8px;border-radius:10px;border:1px solid rgba(255,255,255,0.03);text-decoration:none;color:inherit}
    footer{margin-top:26px;text-align:center;color:var(--muted);font-size:14px}
    .card{transform:translateY(6px);opacity:0;animation:pop .6s ease forwards}
    .card:nth-child(1){animation-delay:.05s}
    @keyframes pop{to{transform:none;opacity:1}}
    .muted{color:var(--muted)}
    .divider{height:1px;background:rgba(255,255,255,0.03);margin:14px 0;border-radius:2px}
    a:focus, button:focus{outline:2px dashed rgba(6,182,212,0.25);outline-offset:3px}
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <div class="brand">
        <div class="avatar">
          <img src="image (1) (2).png" alt="MD NAYAN">
        </div>
        <div>
          <h1>MD NAYAN</h1>
          <div class="lead">Portfolio • YouTube & Facebook promotion • Freelance CV</div>
        </div>
      </div>
      <nav class="muted">
        <a class="btn" href="#about">About</a>
        <a class="btn" href="#projects">Work</a>
        <a class="btn" href="#contact">Contact</a>
      </nav>
    </header>

    <main>
      <section>
        <article class="card">
          <div class="hero">
            <div class="intro">
              <span class="tag">Freelancer • Content Creator</span>
              <h2 class="name">Assalamualaikum — আমি MD NAYAN</h2>
              <p>আমি একজন passionate creator ও freelancer। এখানে আমার কাজ, YouTube/Facebook লিংক এবং আমার CV/সেবা সম্বন্ধে সবকিছু পাবেন। নিচে আমার যোগাযোগের বিস্তারিত, কাজের উদাহরণ এবং ডাউনলোডযোগ্য CV দেওয়া আছে।</p>
              <div class="actions">
                <a class="btn primary" href="#contact">Hire / Contact</a>
                <a class="btn" href="#projects">আমার কাজ দেখুন</a>
                <a class="btn" href="My Personal Cv.pdf" target="_blank">Download CV</a>
              </div>
              <div class="skills" aria-hidden>
                <span class="skill">YouTube Promotion</span>
                <span class="skill">Social Media</span>
                <span class="skill">Frontend (HTML/CSS)</span>
                <span class="skill">Freelance CV</span>
                <span class="skill">Video Editing</span>
              </div>
            </div>
            <aside style="width:240px; text-align:center">
              <img src="image (1) (2).png" alt="MD NAYAN" style="width:100%;border-radius:12px;border:1px solid rgba(255,255,255,0.04);">
              <div style="margin-top:12px;color:var(--muted);font-size:14px">Available for freelance & collaborations</div>
              <div style="margin-top:12px;display:flex;gap:8px;justify-content:center">
                <a class="btn" href="tel:01819706098">Call</a>
                <a class="btn" href="mailto:nayon3707@gmail.com">Email</a>
              </div>
            </aside>
          </div>
          <div class="divider"></div>
          <section id="about">
            <h3>About — সংক্ষেপে</h3>
            <p>আমি MD NAYAN — YouTube ও Facebook-এ content তৈরি করি এবং freelancing করি। আমার লক্ষ্য হচ্ছে মানসম্মত ছবি/ভিডিও ও শিক্ষা ভিত্তিক কনটেন্ট তৈরি করে দর্শকদের কাছে মূল্যবোধ পৌঁছে দেওয়া।</p>
            <p style="margin-top:8px" class="muted">Short contact: nayon3707@gmail.com · 01819706098</p>
          </section>
          <section id="projects" style="margin-top:16px">
            <h3>Work / Projects</h3>
            <div class="projects">
              <div class="project"><h4>YouTube Channel Promo</h4><p>Channel growth strategy, video optimization, thumbnails & short promotion campaigns.</p></div>
              <div class="project"><h4>Facebook Page Campaign</h4><p>Page setup, content calendar, engagement optimization and simple ads setup guidance.</p></div>
              <div class="project"><h4>Freelance CV & Proposals</h4><p>Professional CV design, cover letters, and gig proposals tailored for clients.</p></div>
              <div class="project"><h4>Small Website</h4><p>Single-page portfolio sites (like this) — fast, responsive, and SEO friendly.</p></div>
            </div>
          </section>
        </article>
      </section>
      <aside class="side">
        <div class="card">
          <div class="meta-row"><strong>Quick Info</strong><span class="muted">Available</span></div>
          <div class="divider"></div>
          <div><strong>Email</strong><div class="muted">nayon3707@gmail.com</div></div>
          <div style="margin-top:10px"><strong>Phone</strong><div class="muted">01819706098</div></div>
          <div style="margin-top:10px"><strong>Location</strong><div class="muted">Chandgaon, Chattogram, Bangladesh</div></div>
          <div class="divider"></div>
          <div><strong>Connect</strong><div class="contact-list">
            <a class="social" href="https://www.youtube.com/@top-team-tv/shorts" target="_blank">YouTube</a>
            <a class="social" href="https://www.facebook.com/shojibmahmud09" target="_blank">Facebook (personal)</a>
            <a class="social" href="https://www.facebook.com/shojibMahmub" target="_blank">Facebook Page</a>
          </div></div>
          <div class="divider"></div>
          <div><strong>Resume</strong><div style="display:flex;gap:8px;margin-top:8px"><a class="btn" href="My Personal Cv.pdf" target="_blank">View / Download CV</a><a class="btn" href="mailto:nayon3707@gmail.com">Email me</a></div></div>
        </div>
        <div style="height:18px"></div>
        <div class="card"><strong id="contact">Contact & Hire</strong><p class="muted" style="margin-top:8px">সরাসরি ইমেইল করে বা নিচের ফর্ম ব্যবহার করে যোগাযোগ করুন —</p>
          <form action="mailto:nayon3707@gmail.com" method="post" enctype="text/plain" style="margin-top:12px;display:flex;flex-direction:column;gap:10px">
            <input name="Name" placeholder="Your name" style="padding:10px;border-radius:8px;border:1px solid rgba(255,255,255,0.04);background:transparent;color:inherit">
            <input name="Email" placeholder="Email" style="padding:10px;border-radius:8px;border:1px solid rgba(255,255,255,0.04);background:transparent;color:inherit">
            <textarea name="Message" placeholder="Brief message" rows="4" style="padding:10px;border-radius:8px;border:1px solid rgba(255,255,255,0.04);background:transparent;color:inherit"></textarea>
            <div style="display:flex;gap:8px"><button type="submit" class="btn primary">Send</button><a class="btn" href="tel:01819706098">Call</a></div>
          </form>
        </div>
      </aside>
    </main>
  </div>
</body>
</html>
