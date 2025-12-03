<!doctype html>
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
        <a href="#home">Home</a>
        <a href="#fees">Fees</a>
        <a href="#student-details">Student Details</a>
      </nav>
    </div>
  </header>
  <main class="container">
    <!-- Hero, About, Courses, Gallery, Admission, Fees, Contact, Student Login, Student Details sections go here -->
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
</body>
</html>
