<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Pocket Publicist™ | Local Authority Engine</title>
  <style>
    :root{
      --primary:#0B1C3E;
      --accent:#2CA4DE;
      --success:#10b981;
      --text-main:#334155;
      --text-light:#64748b;
      --bg-light:#f8fafc;
      --white:#ffffff;
      --border-radius:8px;
      --font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Arial, sans-serif;
    }
    *{margin:0;padding:0;box-sizing:border-box;}
    body{font-family:var(--font-family);color:var(--text-main);line-height:1.6;background:var(--white);}
    h1,h2,h3{color:var(--primary);font-weight:700;line-height:1.2;}
    h1{font-size:2.5rem;margin-bottom:1rem;}
    h2{font-size:2rem;margin-bottom:1.5rem;}
    h3{font-size:1.25rem;margin-bottom:.5rem;}
    p{margin-bottom:1rem;font-size:1.1rem;}
    .highlight{color:var(--accent);}
    .container{max-width:900px;margin:0 auto;padding:0 20px;}
    section{padding:80px 0;}
    .btn{
      display:inline-block;background:var(--accent);color:#fff;
      padding:16px 32px;font-size:1.1rem;font-weight:600;
      text-decoration:none;border-radius:var(--border-radius);
      transition:transform .2s, background-color .2s;
      box-shadow:0 4px 6px rgba(44,164,222,.2);
    }
    .btn:hover{background:#2488b8;transform:translateY(-2px);}
    header{padding:15px 0;border-bottom:1px solid #e2e8f0;background:#fff;}
    .logo-container{display:flex;align-items:center;}
    /* If you add a logo later, uncomment the img tag in the HTML below */
    .logo-img{height:70px;width:auto;}
    .hero{text-align:center;padding:100px 0 80px;background:radial-gradient(circle at top,#f0f9ff,#fff);}
    .hero-sub{font-size:1.25rem;color:var(--text-light);margin-bottom:2rem;max-width:600px;margin-left:auto;margin-right:auto;}
    .problem-grid{display:grid;grid-template-columns:1fr;gap:2rem;margin-top:2rem;}
    .problem-item{padding-left:20px;border-left:4px solid #ef4444;}
    .punchline{margin-top:3rem;text-align:center;font-size:1.3rem;font-weight:700;color:var(--primary);}
    .solution-section{background:var(--bg-light);}
    .solution-list{list-style:none;margin-top:2rem;}
    .solution-list li{
      background:#fff;margin-bottom:1rem;padding:1.5rem;border-radius:var(--border-radius);
      display:flex;align-items:center;box-shadow:0 1px 3px rgba(0,0,0,.05);
    }
    .checkmark{color:var(--success);margin-right:15px;font-size:1.5rem;}
    .pricing-section{text-align:center;}
    .pricing-card{
      background:var(--primary);color:#fff;padding:3rem;border-radius:var(--border-radius);
      max-width:700px;margin:0 auto;overflow:hidden;
    }
    .pricing-card h2{color:#fff;}
    .price{font-size:3.5rem;font-weight:800;margin:1rem 0;color:var(--success);}
    .period{font-size:1.2rem;color:#94a3b8;font-weight:400;}
    .roi-logic{margin-top:2rem;padding-top:2rem;border-top:1px solid rgba(255,255,255,.1);text-align:left;}
    .roi-logic p{color:#cbd5e1;}
    footer{text-align:center;padding:40px 0;color:var(--text-light);font-size:.9rem;border-top:1px solid #e2e8f0;}
    @media (min-width:768px){
      h1{font-size:3.5rem;}
      .problem-grid{grid-template-columns:1fr 1fr;}
    }
  </style>
</head>
<body>

  <header>
    <div class="container logo-container">
      <!-- Add logo later like this (ONLY if the file exists in the repo): -->
      <!-- <img src="logo.jpg" alt="Pocket Publicist" class="logo-img"> -->
      <strong style="color:#0B1C3E;">Pocket Publicist™</strong>
    </div>
  </header>

  <section class="hero">
    <div class="container">
      <h1>Turn Your Google Profile Into a <br><span class="highlight">24/7 PI Case Intake Machine</span></h1>
      <p class="hero-sub">No ads. No lead vendors. No long-term contracts.</p>
      <a href="https://calendly.com/pocketpublicist-consult/20min" target="_blank" class="btn">Get Local Dominance</a>
    </div>
  </section>

  <section class="problem-section">
    <div class="container">
      <h2>The Invisible Problem Costing You Signed Cases</h2>
      <p>Prospective clients don’t call the “best” firm. They call the firm that looks dominant online. Most PI firms lose cases because:</p>

      <div class="problem-grid">
        <div class="problem-item">
          <h3>Visibility Slipping</h3>
          <p>Your Google Maps visibility is quietly fading while competitors climb.</p>
        </div>
        <div class="problem-item">
          <h3>Sporadic Reviews</h3>
          <p>Reviews arrive randomly instead of predictably, hurting your ranking.</p>
        </div>
        <div class="problem-item">
          <h3>Low Authority</h3>
          <p>Your online presence doesn’t signal the “Alpha” status clients trust.</p>
        </div>
        <div class="problem-item">
          <h3>Active Competitors</h3>
          <p>Competing firms look more active, credible, and established.</p>
        </div>
      </div>

      <p class="punchline">When that happens, Google and prospects choose someone else.</p>
    </div>
  </section>

  <section class="solution-section">
    <div class="container">
      <h2>The Solution: Local Authority Engine™</h2>
      <p>This isn’t marketing. It’s <strong>local dominance infrastructure</strong>. The Local Authority Engine™ turns your Google presence into a case-generating asset that compounds over time.</p>

      <ul class="solution-list">
        <li><span class="checkmark">✓</span> <strong>Google Maps Optimization:</strong> Strategic updates to increase local visibility.</li>
        <li><span class="checkmark">✓</span> <strong>Weekly Profile Activity:</strong> consistent signals of relevance sent directly to Google.</li>
        <li><span class="checkmark">✓</span> <strong>Automated Reviews:</strong> Systems for 5-star review acquisition and monitoring.</li>
        <li><span class="checkmark">✓</span> <strong>Authority Content:</strong> Building social proof that converts browsers to callers.</li>
        <li><span class="checkmark">✓</span> <strong>Performance Protection:</strong> Ongoing tracking, adjustments, and defense.</li>
      </ul>

      <p style="text-align:center;margin-top:2rem;font-weight:600;">No ads. No lead resellers. No chasing. Just controlled visibility and trust.</p>
    </div>
  </section>

  <section class="pricing-section" id="pricing">
    <div class="container">
      <div class="pricing-card">
        <h2>Investment & ROI Logic</h2>
        <div class="price">$997 <span class="period">/ month</span></div>
        <p>Month-to-month. No long-term handcuffs.</p>

        <div class="roi-logic">
          <h3>Simple Math:</h3>
          <p>One additional PI case every few months more than covers the cost. Everything after that is profit driven by authority you own, not rented traffic.</p>

          <div style="margin-top:2rem;text-align:center;">
            <a href="https://calendly.com/pocketpublicist-consult/20min" target="_blank" class="btn" style="background:var(--success);">Start Your Engine</a>
          </div>
        </div>

      </div>
    </div>
  </section>

  <footer>
    <div class="container">
      <p>&copy; 2024 Pocket Publicist™ AI Agency. All rights reserved.</p>
    </div>
  </footer>

</body>
</html>
