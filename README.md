# Digital-World
Modern Digital Marketing Agency for Your Business
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Digital World — Modern Digital Marketing Agency</title>
  <meta name="description" content="Digital World — Social Media | Ads | Content. Modern & minimal digital marketing for businesses across niches." />
  <style>
    :root{
      --bg:#ffffff; --muted:#6b7280; --accent:#0f172a; --accent-2:#0ea5a4; --card:#f8fafc; --radius:12px;
      --max:1100px; --gap:24px; font-family:Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    *{box-sizing:border-box}
    html,body{height:100%;margin:0;background:var(--bg);color:var(--accent);-webkit-font-smoothing:antialiased}
    a{color:inherit;text-decoration:none}
    .container{max-width:var(--max);margin:0 auto;padding:40px 20px}

    /* header */
    header{display:flex;align-items:center;justify-content:space-between;gap:16px}
    .brand{display:flex;align-items:center;gap:14px}
    .logo-square{width:56px;height:56px;border-radius:10px;background:#111827;color:white;display:flex;align-items:center;justify-content:center;font-weight:700;font-size:20px}
    .brand h1{margin:0;font-size:18px;letter-spacing:0.4px}
    .brand p{margin:0;color:var(--muted);font-size:13px}
    nav{display:flex;gap:18px;align-items:center}
    nav a{font-size:14px;color:var(--muted)}
    .cta{background:var(--accent);color:white;padding:10px 14px;border-radius:10px;font-weight:600}

    /* hero */
    .hero{display:grid;grid-template-columns:1fr 360px;gap:40px;align-items:center;margin-top:44px}
    .hero h2{font-size:30px;margin:0 0 12px}
    .hero p{margin:0;color:var(--muted);line-height:1.6}
    .hero .actions{margin-top:20px;display:flex;gap:12px}
    .btn{background:var(--accent-2);color:white;padding:12px 16px;border-radius:10px;font-weight:600}
    .secondary{border:1px solid #e6eef0;padding:10px 14px;border-radius:10px;color:var(--accent)}

    /* card */
    .card{background:var(--card);padding:18px;border-radius:14px;box-shadow:0 6px 20px rgba(10,10,12,0.04)}

    /* services */
    .services{display:grid;grid-template-columns:repeat(3,1fr);gap:18px;margin-top:40px}
    .service h3{margin:0 0 8px;font-size:16px}
    .service p{margin:0;color:var(--muted);font-size:14px;line-height:1.5}

    /* portfolio */
    .portfolio{margin-top:44px}
    .gallery{display:grid;grid-template-columns:repeat(3,1fr);gap:14px}
    .gallery img{width:100%;height:160px;object-fit:cover;border-radius:10px}

    /* packages */
    .packages{display:grid;grid-template-columns:repeat(3,1fr);gap:18px;margin-top:34px}
    .pkg{padding:18px;border-radius:12px;border:1px solid #eef2f5;background:white}
    .pkg h4{margin:0 0 6px}
    .price{font-weight:700;margin:10px 0;font-size:20px}
    .pkg ul{padding-left:18px;color:var(--muted);margin:0}

    /* contact */
    .contact{display:grid;grid-template-columns:1fr 340px;gap:20px;margin-top:40px}
    form{display:flex;flex-direction:column;gap:12px}
    input,textarea{padding:12px;border-radius:8px;border:1px solid #e6eef0;font-size:14px}
    .footer{margin-top:40px;padding-top:22px;border-top:1px solid #f1f5f9;color:var(--muted);display:flex;justify-content:space-between;align-items:center}

    /* responsive */
    @media (max-width:900px){.hero{grid-template-columns:1fr;}.services{grid-template-columns:1fr 1fr}.packages{grid-template-columns:1fr 1fr}.gallery{grid-template-columns:1fr 1fr}.contact{grid-template-columns:1fr}.logo-square{width:48px;height:48px}}
    @media (max-width:520px){.services{grid-template-columns:1fr}.packages{grid-template-columns:1fr}.gallery{grid-template-columns:1fr}.brand h1{font-size:16px}.hero h2{font-size:22px}}

    /* small utilities */
    .muted{color:var(--muted)}
    .center{text-align:center}

    /* logo variants */
    .logo-dw{display:flex;gap:10px;align-items:center}
    .logo-dw svg{width:56px;height:56px}

    /* highlight small */
    .pill{display:inline-block;padding:6px 10px;border-radius:999px;background:#eefaf9;color:var(--accent-2);font-weight:600;font-size:13px}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">
        <!-- Logo Variant: Lettermark D (Concept B) -->
        <div class="logo-dw">
          <svg viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
            <rect width="100" height="100" rx="16" fill="#0f172a"></rect>
            <text x="50%" y="56%" text-anchor="middle" font-family="Arial, Helvetica, sans-serif" font-size="54" fill="#fff" font-weight="700">D</text>
          </svg>
          <!-- Geometric icon concept (Concept C) -->
          <svg viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
            <defs>
              <linearGradient id="g1" x1="0" x2="1">
                <stop offset="0" stop-color="#0ea5a4" />
                <stop offset="1" stop-color="#06b6d4" />
              </linearGradient>
            </defs>
            <circle cx="50" cy="50" r="44" fill="url(#g1)" />
            <path d="M34 36 L66 36 L50 64 Z" fill="#fff" opacity="0.95" />
          </svg>
        </div>
        <div>
          <h1>Digital World</h1>
          <p class="muted">Social Media • Ads • Content — Modern & Minimal</p>
        </div>
      </div>

      <nav>
        <a href="#services">Services</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#packages">Packages</a>
        <a href="#contact">Contact</a>
        <a class="cta" href="#contact">Get Started</a>
      </nav>
    </header>

    <main>
      <section class="hero">
        <div>
          <h2>Modern digital marketing for businesses that want clean, measurable growth.</h2>
          <p class="muted">We help local and online brands grow with a simple, results-driven approach — social media management, Meta ads, and content that converts. Minimal design, maximum impact.</p>

          <div class="actions">
            <a class="btn" href="#contact">Request a Free Audit</a>
            <a class="secondary" href="#portfolio">See Work</a>
          </div>

          <div style="margin-top:24px;display:flex;gap:12px;align-items:center">
            <div class="card" style="display:inline-block;padding:12px 16px;border-radius:10px">
              <div style="font-size:13px;color:var(--muted);">Starter package</div>
              <div style="font-weight:700;font-size:18px">₹3,500 / month</div>
            </div>
            <div class="pill">Mixed Niches</div>
          </div>
        </div>

        <aside>
          <div class="card">
            <h3 style="margin:0 0 8px">How we help</h3>
            <p class="muted" style="margin:0 0 12px">Short-term wins + long-term growth. Clear strategy, consistent content, and smart ads.</p>
            <ul style="margin:0;padding-left:18px;color:var(--muted)">
              <li>Content calendars & creative</li>
              <li>Meta (Facebook & Instagram) ads</li>
              <li>Engagement & community building</li>
            </ul>
            <div style="margin-top:12px;text-align:right">
              <a class="btn" href="#contact">Book a Call</a>
            </div>
          </div>
        </aside>
      </section>

      <section id="services" class="services">
        <div class="service card">
          <h3>Social Media Management</h3>
          <p class="muted">Content creation, captions, stories, reels, scheduling and community engagement — built around your brand voice.</p>
        </div>
        <div class="service card">
          <h3>Meta Ads (FB & IG)</h3>
          <p class="muted">Targeted campaigns, A/B tests, and conversion tracking to get real leads and sales for your budget.</p>
        </div>
        <div class="service card">
          <h3>Content & Copy</h3>
          <p class="muted">Short-form content, blog posts, ad copy and captions optimized for engagement and conversions.</p>
        </div>
      </section>

      <section id="portfolio" class="portfolio">
        <h3 style="margin:0 0 14px">Selected Work</h3>
        <div class="gallery">
          <img src="https://images.unsplash.com/photo-1515378791036-0648a3ef77b2?q=80&w=800&auto=format&fit=crop&ixlib=rb-4.0.3&s=placeholder" alt="Sample social post design 1">
          <img src="https://images.unsplash.com/photo-1498050108023-c5249f4df085?q=80&w=800&auto=format&fit=crop&ixlib=rb-4.0.3&s=placeholder" alt="Sample ad creative 2">
          <img src="https://images.unsplash.com/photo-1515378791036-0648a3ef77b2?q=80&w=800&auto=format&fit=crop&ixlib=rb-4.0.3&s=placeholder" alt="Sample reel thumbnail">
        </div>

        <p class="muted" style="margin-top:12px">(Replace these images with your real samples — I can insert your files into the portfolio PDF on request.)</p>
      </section>

      <section id="packages" class="packages">
        <div class="pkg">
          <h4>Basic</h4>
          <div class="price">₹3,500 / month</div>
          <ul>
            <li>8 posts / month</li>
            <li>Caption writing & hashtags</li>
            <li>Page optimization</li>
          </ul>
        </div>
        <div class="pkg">
          <h4>Standard</h4>
          <div class="price">₹7,500 / month</div>
          <ul>
            <li>12 posts + 4 reels</li>
            <li>Engagement (30min/day)</li>
            <li>Monthly report</li>
          </ul>
        </div>
        <div class="pkg">
          <h4>Premium</h4>
          <div class="price">₹15,000 / month</div>
          <ul>
            <li>15 posts + 6 reels</li>
            <li>Ads management included</li>
            <li>Strategy calls & detailed reporting</li>
          </ul>
        </div>
      </section>

      <section id="contact" class="contact">
        <div>
          <h3>Let's work together</h3>
          <p class="muted">Send a quick message — we usually reply within 12 hours.</p>

          <form onsubmit="event.preventDefault(); alert('This demo form is not linked. Copy the code or connect it to your email provider.');">
            <input type="text" name="name" placeholder="Your name" required />
            <input type="email" name="email" placeholder="Email address" required />
            <input type="text" name="business" placeholder="Business / Instagram handle" />
            <textarea name="message" rows="4" placeholder="Tell us about your goals"></textarea>
            <div style="display:flex;gap:10px">
              <button class="btn" type="submit">Send message</button>
              <a class="secondary" href="mailto:hello@digitalworld.example">hello@digitalworld.example</a>
            </div>
          </form>
        </div>

        <aside class="card">
          <h4 style="margin:0 0 10px">Contact & Links</h4>
          <p class="muted" style="margin:0 0 8px">hello@digitalworld.example</p>
          <p class="muted" style="margin:0 0 8px">+91 98765 43210</p>
          <p class="muted" style="margin:0 0 8px"><a href="#">@digitalworld.agency</a></p>

          <div style="margin-top:14px">
            <div style="font-size:13px;color:var(--muted);margin-bottom:6px">Quick audit</div>
            <div style="background:#ffffff;padding:10px;border-radius:8px;border:1px dashed #eef2f5;color:var(--muted);font-size:14px">Get a free 3-post sample + a short growth plan</div>
          </div>
        </aside>
      </section>

    </main>

    <div class="footer">
      <div class="muted">© Digital World — Modern & Minimal · All rights reserved</div>
      <div class="muted">Designed for mixed niches · India</div>
    </div>
  </div>

  <!-- Helpful notes for editing:
       - Replace sample gallery images with your real images (use local files or a CDN)
       - Update contact email and phone in the contact aside
       - Integrate form with your email service or Zapier for leads
       - To change colors, edit CSS variables near the top
  -->
</body>
</html>
