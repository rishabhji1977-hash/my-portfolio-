# my-portfolio-<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Rishabh Mishra — Portfolio</title>
  <meta name="description" content="Portfolio of Rishabh Mishra" />
  <style>
    :root{--bg:#0f1724;--card:#0b1220;--accent:#06b6d4;--muted:#94a3b8;--white:#eef2ff}
    *{box-sizing:border-box}
    body{font-family:Inter,system-ui,-apple-system,"Segoe UI",Roboto,Helvetica,Arial;line-height:1.5;margin:0;background:linear-gradient(180deg,#071023 0%, #081226 60%);color:var(--white);}
    .container{max-width:1000px;margin:36px auto;padding:20px}
    header{display:flex;gap:20px;align-items:center}
    .avatar{width:150px;height:150px;border-radius:18px;overflow:hidden;flex:0 0 150px;border:4px solid rgba(255,255,255,0.06);background:linear-gradient(135deg,#0b1220,#0f1724)}
    .avatar img{width:100%;height:100%;object-fit:cover;display:block}
    h1{font-size:26px;margin:0 0 6px}
    .role{color:var(--accent);font-weight:600}
    .intro{color:var(--muted);margin-top:6px}
    nav{margin-left:auto}
    nav a{color:var(--muted);text-decoration:none;margin-left:14px;font-size:14px}
    nav a:hover{color:var(--white)}

    .grid{display:grid;grid-template-columns:1fr 320px;gap:20px;margin-top:28px}
    .card{background:rgba(255,255,255,0.02);padding:18px;border-radius:12px;box-shadow:0 6px 18px rgba(2,6,23,0.6)}
    .section-title{display:flex;align-items:center;gap:10px;margin-bottom:12px}
    .section-title h2{font-size:18px;margin:0}
    .muted{color:var(--muted);font-size:14px}

    ul.clean{list-style:none;padding:0;margin:0}
    ul.clean li{padding:8px 0;border-bottom:1px dashed rgba(255,255,255,0.03)}

    .skills{display:flex;gap:8px;flex-wrap:wrap}
    .chip{background:rgba(255,255,255,0.03);padding:6px 10px;border-radius:999px;font-size:13px}

    .education .school{display:flex;justify-content:space-between;align-items:center}
    .education .school .years{color:var(--muted);font-size:13px}

    .contact a.button{display:inline-block;padding:10px 14px;border-radius:8px;background:var(--accent);color:#042027;text-decoration:none;font-weight:600}

    footer{margin-top:26px;color:var(--muted);font-size:13px;text-align:center}

    /* Responsive */
    @media (max-width:880px){
      .grid{grid-template-columns:1fr;}
      .avatar{width:120px;height:120px;flex:0 0 120px}
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="avatar card">
        
        <img src="rishabh photo.jpg" alt="Rishabh Mishra">
      </div>

      <div>
        <h1>Rishabh Mishra <span class="role">— Student /Aspiring Web Developer</span></h1>
        <p class="intro muted">I am a BCA student studying computer applications. I love building simple, useful web projects and learning new technologies. I enjoy problem solving, algorithms and front-end design.</p>
        <p class="muted" style="margin-top:8px">Location: Bareilly, India • Email: <a href="rishabhji1977@gmail.com">rishabhji1977@gmail.com</a></p>
      </div>

      <nav>
        <a href="#about">About</a>
        <a href="#education">Education</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <main class="grid">
      <section class="card">
        <div id="about" class="section-title">
          <h2>About Me</h2>
        </div>
        <p class="muted">Hi — I'm Rishabh. I am currently pursuing a Bachelor of Computer Applications (BCA) at Mahatma Jyotiba Phule Rohilkhand University (MJPRU). I enjoy coding, studying data structures & algorithms, and building small web apps to learn new technologies.</p>

        <div style="margin-top:16px">
          <h3 style="margin:0 0 8px">Quick facts</h3>
          <ul class="clean">
            <li><strong>Study:</strong> BCA — MJPRU (Current)</li>
            <li><strong>Interests:</strong> Web development, DS & Algorithms, System design basics</li>
            <li><strong>Languages:</strong> English, Hindi</li>
          </ul>
        </div>

        <div style="margin-top:18px">
          <h3 style="margin:0 0 8px">Skills</h3>
          <div class="skills">
            <span class="chip">HTML</span>
            <span class="chip">CSS</span>
            <span class="chip">JavaScript</span>
            <span class="chip">React (learning)</span>
            <span class="chip">C / C++</span>
            <span class="chip">Git</span>
          </div>
        </div>

        <div id="projects" style="margin-top:18px">
          <h3 style="margin:0 0 8px">Selected Projects</h3>
          <ul class="clean">
            <li><strong>Personal Portfolio</strong> — Static responsive website (this page)</li>
            <li><strong>Quiz App</strong> — JavaScript-based MCQ quiz for practice</li>
            <li><strong>To-do App</strong> — LocalStorage CRUD demo</li>
          </ul>
        </div>

      </section>

      <aside class="card">
        <div id="education" class="section-title">
          <h2>Education</h2>
        </div>
        <div class="education">
          <div class="school">
            <div>
              <strong>Bachelor of Computer Applications (BCA)</strong>
              <div class="muted">M.J.P. Rohilkhand University — Current</div>
            </div>
            <div class="years">2024 — Present</div>
          </div>

          <div style="height:10px"></div>

          <div class="school">
            <div>
              <strong>10th,12th</strong>
              <div class="muted">Ben Hur Public School,Pilibhit, Uttar Pradesh</div>
            </div>
            <div class="years">2022,2024</div>
          </div>

          <div style="height:18px"></div>

          <div class="section-title"><h2>Contact</h2></div>
          <div class="contact">
            <p class="muted">Want to collaborate or have a question? Reach out!</p>
            <p style="margin-top:8px"><a class="button" href="rishabhji1977@gmail.com">Email me</a></p>
            <p style="margin-top:10px" class="muted">Or download my resume:</p>
            <p style="margin-top:8px"><a href="#" class="muted">Resume (PDF)</a></p>
          </div>

          <div style="height:18px"></div>

          <div class="section-title"><h2>Quick Links</h2></div>
          <ul class="clean">
            <li><a href="#projects" class="muted">Projects</a></li>
            <li><a href="https://github.com/rishabhji1977-hash" class="muted">GitHub</a></li>
           <li><a href="https://www.linkedin.com/in/rishabhmishra28/" class="muted">LinkedIn</a></li>
            <li><a href="https://www.instagram.com/its_mishra28/" class="muted">Instagram</a></li>
          </ul>

        </div>
      </aside>

    </main>

    <footer>
      <p>Made with ❤️ —Rishabh Mishra</p>
    </footer>
  </div>

  <!-- Optional small script to smooth-scroll to anchors -->
  <script>
    document.querySelectorAll('a[href^="#"]').forEach(a=>{
      a.addEventListener('click',e=>{
        const target=document.querySelector(a.getAttribute('href'));
        if(target){e.preventDefault();target.scrollIntoView({behavior:'smooth',block:'start'});}
      });
    });
  </script>
</body>
</html>
