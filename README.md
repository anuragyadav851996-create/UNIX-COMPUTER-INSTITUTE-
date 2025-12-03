!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>UNIX COMPUTER INSTITUTE - Baghmarawan</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700;900&display=swap" rel="stylesheet">
  <style>
    :root{
      --brand-1: #ff6b6b;
      --brand-2: #ffd166;
      --brand-3: #4ecdc4;
      --dark: #0b2545;
      --muted: #6b7280;
      --card-shadow: 0 8px 24px rgba(11,37,69,0.08);
      font-family: 'Roboto', system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
    }
    *{box-sizing:border-box}
    body{margin:0;background:linear-gradient(180deg,#fff 0%, #f7fbff 100%);color:var(--dark);}
    header{background:linear-gradient(90deg,var(--brand-1),var(--brand-2));color:white;padding:18px 24px;position:sticky;top:0;z-index:50}
    .container{max-width:1100px;margin:0 auto;padding:20px}
    .nav{display:flex;align-items:center;justify-content:space-between;gap:12px}
    .logo{display:flex;align-items:center;gap:12px;font-weight:900}
    .logo .mark{width:52px;height:52px;border-radius:10px;background:rgba(255,255,255,0.12);display:grid;place-items:center}
    nav a{color:rgba(255,255,255,0.95);text-decoration:none;margin-left:14px;font-weight:600}
    .hero{display:flex;gap:30px;align-items:center;padding:48px 0}
    .hero-left{flex:1}
    .hero h1{font-size:28px;margin:0 0 8px}
    .hero p{color:#06203a;margin:10px 0 18px;font-size:15px}
    .cta{display:flex;gap:12px}
    .btn{padding:12px 18px;border-radius:10px;border:none;font-weight:700;cursor:pointer}
    .btn-primary{background:var(--dark);color:white}
    .btn-outline{background:transparent;border:2px solid var(--dark);color:var(--dark)}
    .hero-right{flex:1;display:grid;grid-template-columns:repeat(2,1fr);gap:12px}
    .card{background:white;padding:14px;border-radius:12px;box-shadow:var(--card-shadow)}
    section{padding:36px 0}
    .courses-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(180px,1fr));gap:14px}
    .course{padding:18px;border-radius:12px;background:linear-gradient(180deg,rgba(78,205,196,0.12),rgba(255,255,255,0.6));}
    .course h4{margin:0 0 6px}
    .about-grid{display:grid;grid-template-columns:1fr 320px;gap:18px}
    .gallery-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(150px,1fr));gap:10px}
    .gallery-grid img{width:100%;height:140px;object-fit:cover;border-radius:8px}
    .form-row{display:flex;gap:10px;flex-wrap:wrap}
    input,textarea,select{width:100%;padding:10px;border-radius:8px;border:1px solid #e6eef6}
    label{font-weight:600;font-size:13px}
    table{width:100%;border-collapse:collapse;background:white;border-radius:8px;overflow:hidden}
    th,td{padding:12px;border-bottom:1px solid #eef6fb;text-align:left}
    th{background:linear-gradient(90deg,var(--brand-2),var(--brand-3));color:var(--dark)}
    footer{background:#031426;color:#cfeef2;padding:20px}
    .small{font-size:13px;color:var(--muted)}
    /* responsive */
    @media(max-width:880px){.hero{flex-direction:column}.about-grid{grid-template-columns:1fr}.hero-right{grid-template-columns:1fr 1fr}}
  </style>
</head>
<body>
  <header>
    <div class="container nav">
      <div class="logo">
        <div class="mark"><strong>U</strong></div>
        <div>
          <div style="font-size:18px;line-height:1">UNIX COMPUTER INSTITUTE</div>
          <div style="font-size:12px;opacity:0.95">Baghmarawan, Bahadurganj, Ghazipur</div>
        </div>
      </div>
      <nav>
        <a href="#about">About</a>
        <a href="#courses">Courses</a>
        <a href="#gallery">Gallery</a>
        <a href="#admission">Admission</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>

  <main class="container">
    <section class="hero">
      <div class="hero-left">
        <h1>UNIX COMPUTER INSTITUTE</h1>
        <p><strong>Location:</strong> Baghmarawan, Bahadurganj, Ghazipur • <strong>Contact:</strong> 9648391373 • ucibahadurganj9648@gmail.com</p>
        <p class="small">Aapke career ki shuruaat yahin se — practical training, experienced faculty aur affordable fees.</p>
        <div class="cta" style="margin-top:12px">
          <button class="btn btn-primary" onclick="document.getElementById('admission').scrollIntoView({behavior:'smooth'})">Apply Online</button>
          <button class="btn btn-outline" onclick="document.getElementById('contact').scrollIntoView({behavior:'smooth'})">Contact Us</button>
        </div>
      </div>
      <div class="hero-right">
        <div class="card">
          <h3 style="margin:0 0 6px">Popular Courses</h3>
          <div class="small">ADCA, DCA, Tally, BCA, MS Office</div>
          <hr style="margin:10px 0;border:none;border-top:1px solid #f1f7fb">
          <ul style="padding-left:18px;margin:0">
            <li>ADCA</li>
            <li>DCA</li>
            <li>Tally</li>
            <li>CCC</li>
            <li>Hardware & Software</li>
            <li>MS.Office, CorelDraw, Photoshop</li>
          </ul>
        </div>
        <div class="card" style="display:flex;flex-direction:column;justify-content:space-between">
          <div>
            <h3 style="margin:0 0 8px">Why choose us?</h3>
            <p class="small" style="margin:0">Experienced faculty • Practical labs • Affordable fees • Placement guidance</p>
          </div>
          <div style="margin-top:10px;text-align:right">
            <button class="btn btn-primary" onclick="openContact()">Get a Call</button>
          </div>
        </div>
      </div>
    </section>

    <section id="about">
      <div class="container">
        <h2>About Us (हमारे बारे में)</h2>
        <div class="about-grid">
          <div>
            <p>UNIX COMPUTER INSTITUTE, Baghmarawan - Bahadurganj, Ghazipur mein sthit ek pramukh computer training sansthan hai. Hum practical aur industry-aligned courses dete hain jaise ADCA, DCA, Tally, CCC, Hardware & Software, BCA aur creative courses jaise CorelDraw aur Photoshop. Humara uddeshya students ko employable skills dena hai taaki ve local aur national job markets mein compete kar saken.</p>
            <ul>
              <li>Experienced trainers</li>
              <li>Practical lab sessions</li>
              <li>Affordable fees & flexible timings</li>
              <li>Placement assistance</li>
            </ul>
            <p class="small"><strong>Contact:</strong> 9648391373 • ucibahadurganj9648@gmail.com</p>
          </div>
          <aside class="card">
            <h4>Location</h4>
            <p class="small">Baghmarawan, Bahadurganj, Ghazipur</p>
            <h4 style="margin-top:10px">Timing</h4>
            <p class="small">Mon - Sat: 9:30 AM - 6:00 PM</p>
            <h4 style="margin-top:10px">Languages</h4>
            <p class="small">Hindi / English</p>
          </aside>
        </div>
      </div>
    </section>

    <section id="courses">
      <div>
        <h2>Our Courses</h2>
        <div class="courses-grid">
          <div class="course"><h4>ADCA</h4><p class="small">Advanced Diploma in Computer Applications</p></div>
          <div class="course"><h4>DCA</h4><p class="small">Diploma in Computer Applications</p></div>
          <div class="course"><h4>TALLY</h4><p class="small">Tally ERP with GST</p></div>
          <div class="course"><h4>CCC</h4><p class="small">Basic Computer Certificate Course</p></div>
          <div class="course"><h4>HARDWARE</h4><p class="small">PC Assembling & Troubleshooting</p></div>
          <div class="course"><h4>SOFTWARE</h4><p class="small">Software Installation & Maintenance</p></div>
          <div class="course"><h4>MS. OFFICE</h4><p class="small">Word, Excel, PowerPoint</p></div>
          <div class="course"><h4>COREL DRAW</h4><p class="small">Graphic Designing - CorelDraw</p></div>
          <div class="course"><h4>PHOTO SHOP</h4><p class="small">Adobe Photoshop Basics</p></div>
          <div class="course"><h4>BCA</h4><p class="small">Bachelor of Computer Applications (coaching)</p></div>
        </div>
      </div>
    </section>

    <section id="gallery">
      <h2>Gallery</h2>
      <div class="gallery-grid">
        <img src="https://via.placeholder.com/600x400?text=Lab+1" alt="lab1">
        <img src="https://via.placeholder.com/600x400?text=Lab+2" alt="lab2">
        <img src="https://via.placeholder.com/600x400?text=Students" alt="students">
        <img src="https://via.placeholder.com/600x400?text=Certificate" alt="certificate">
      </div>
    </section>

    <section id="admission">
      <h2>Online Admission</h2>
      <div class="card">
        <form id="admissionForm" onsubmit="submitAdmission(event)">
          <div class="form-row">
            <div style="flex:1">
              <label for="name">Full name</label>
              <input id="name" required />
            </div>
            <div style="width:220px">
              <label for="phone">Phone</label>
              <input id="phone" required />
            </div>
          </div>
          <div style="margin-top:10px">
            <label for="courseSel">Select course</label>
            <select id="courseSel">
              <option>ADCA</option>
              <option>DCA</option>
              <option>TALLY</option>
              <option>CCC</option>
              <option>HARDWARE</option>
              <option>SOFTWARE</option>
              <option>MS.OFFICE</option>
              <option>COREL DRAW</option>
              <option>PHOTO SHOP</option>
              <option>BCA</option>
            </select>
          </div>
          <div style="margin-top:10px">
            <label for="msg">Address / Notes</label>
            <textarea id="msg" rows="3"></textarea>
          </div>
          <div style="margin-top:12px;text-align:right">
            <button class="btn btn-primary" type="submit">Submit Admission</button>
          </div>
        </form>
      </div>
    </section>

    <section id="fees">
      <h2>Fees Structure</h2>
      <div class="card">
        <table>
          <thead>
            <tr><th>Course</th><th>Duration</th><th>Fees (₹)</th></tr>
          </thead>
          <tbody>
            <tr><td>ADCA</td><td>6 months</td><td>8,000</td></tr>
            <tr><td>DCA</td><td>3 months</td><td>5,000</td></tr>
            <tr><td>TALLY</td><td>2 months</td><td>3,000</td></tr>
            <tr><td>CCC</td><td>1 month</td><td>1,500</td></tr>
            <tr><td>Hardware</td><td>2 months</td><td>4,000</td></tr>
            <tr><td>MS.Office</td><td>1 month</td><td>2,000</td></tr>
            <tr><td>CorelDraw</td><td>1 month</td><td>2,500</td></tr>
            <tr><td>Photoshop</td><td>1 month</td><td>2,500</td></tr>
            <tr><td>BCA (Coaching)</td><td>Year</td><td>18,000</td></tr>
          </tbody>
        </table>
      </div>
    </section>

    <section id="contact">
      <h2>Contact Us</h2>
      <div class="card">
        <div class="form-row">
          <div style="flex:1">
            <label for="cname">Name</label>
            <input id="cname">
          </div>
          <div style="width:220px">
            <label for="cphone">Phone</label>
            <input id="cphone">
          </div>
        </div>
        <div style="margin-top:10px">
          <label for="cmsg">Message</label>
          <textarea id="cmsg" rows="3"></textarea>
        </div>
        <div style="margin-top:10px;text-align:right">
          <button class="btn btn-primary" onclick="sendContact()">Send Message</button>
        </div>
      </div>
    </section>

    <section id="student-login">
      <h2>Student Login</h2>
      <div class="card" style="display:flex;gap:12px;align-items:center">
        <div style="flex:1">
          <p class="small">Students can login to access course materials. (Demo login below)</p>
        </div>
        <div>
          <button class="btn btn-outline" onclick="openLogin()">Open Login</button>
        </div>
      </div>
    </section>
  </main>

  <footer>
    <div class="container" style="display:flex;justify-content:space-between;align-items:center;gap:12px;flex-wrap:wrap">
      <div>
        <div style="font-weight:900">UNIX COMPUTER INSTITUTE</div>
        <div class="small">Baghmarawan, Bahadurganj, Ghazipur • 9648391373 • ucibahadurganj9648@gmail.com</div>
      </div>
      <div class="small">© UNIX COMPUTER INSTITUTE - All rights reserved</div>
    </div>
  </footer>

  <!-- Login Modal (simple) -->
  <div id="loginModal" style="display:none;position:fixed;inset:0;background:rgba(2,6,23,0.6);place-items:center;padding:20px">
    <div style="max-width:420px;margin:auto;background:white;padding:20px;border-radius:12px">
      <h3 style="margin-top:0">Student Login (Demo)</h3>
      <div style="margin-bottom:8px"><label>Username</label><input id="user" /></div>
      <div style="margin-bottom:8px"><label>Password</label><input id="pass" type="password" /></div>
      <div style="text-align:right"><button class="btn btn-primary" onclick="doLogin()">Login</button> <button class="btn btn-outline" onclick="closeLogin()">Close</button></div>
      <p class="small">Demo credentials: user: student pass: 1234</p>
    </div>
  </div>

  <script>
    function openContact(){ document.getElementById('contact').scrollIntoView({behavior:'smooth'}); }
    function submitAdmission(e){ e.preventDefault();
      const name=document.getElementById('name').value||'--';
      const phone=document.getElementById('phone').value||'--';
      const course=document.getElementById('courseSel').value;
      alert('Thank you '+name+"!\nWe've received your admission request for "+course+".\nWe will contact you at "+phone);
      document.getElementById('admissionForm').reset();
    }
    function sendContact(){ const n=document.getElementById('cname').value||'Friend'; const ph=document.getElementById('cphone').value||''; const m=document.getElementById('cmsg').value||''; if(!m){alert('Please write a message.');return;} alert('Thanks '+n+'. We will contact you soon.'); document.getElementById('cname').value='';document.getElementById('cphone').value='';document.getElementById('cmsg').value=''; }
    function openLogin(){ document.getElementById('loginModal').style.display='grid'; }
    function closeLogin(){ document.getElementById('loginModal').style.display='none'; }
    function doLogin(){ const u=document.getElementById('user').value; const p=document.getElementById('pass').value; if(u==='student' && p==='1234'){ alert('Login successful — welcome!'); closeLogin(); } else { alert('Invalid demo credentials. Use user: student and pass: 1234'); } }
  </script>
</body>
</html>
