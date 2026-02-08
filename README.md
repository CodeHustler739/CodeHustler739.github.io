<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Project: New Education — Rebuild Learning & Work for 8 Billion People</title>
  <meta name="description" content="We’re building the world’s first AI-native education & work system — a global platform that replaces obsolete schools, creates new careers, and unlocks human potential. Founder: [Your Name] • Cofounder: [Dog Name]. Join the Founders’ List." />
  <link rel="canonical" href="https://YOURDOMAIN/" />
  <!-- Open Graph -->
  <meta property="og:title" content="Project: New Education — Rebuild Learning & Work for 8 Billion People" />
  <meta property="og:description" content="A global movement to replace outdated schooling and create an economy that rewards skills and creativity. Join early — Founders receive lifetime access & equity invites." />
  <meta property="og:image" content="https://YOURDOMAIN/path-to-hero-image.jpg" />
  <meta name="twitter:card" content="summary_large_image" />

  <!-- Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">

  <style>
    :root{
      --bg:#07060a;
      --card-bg: rgba(255,255,255,0.04);
      --accent1: #7a5cff;
      --accent2: #8f6bff;
      --glass: rgba(255,255,255,0.06);
      --muted: #bfc3d6;
      --max-width: 1100px;
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,"Helvetica Neue",Arial;
      color:#e9eaf0;
      background:linear-gradient(180deg,#05040a 0%,#0f0d14 100%);
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      line-height:1.45;
    }
    a{color:inherit;text-decoration:none}
    .container{max-width:var(--max-width);margin:0 auto;padding:32px;}
    header.site-header{padding:22px 0;display:flex;align-items:center;justify-content:space-between;}
    .logo{font-weight:800;letter-spacing:1px}
    nav a{margin-left:20px;color:var(--muted);font-weight:600;font-size:14px}
    .topbar{background:linear-gradient(90deg, rgba(122,92,255,0.12), rgba(143,107,255,0.06));padding:8px 16px;border-radius:999px;color:#dcd6ff;font-size:13px;display:inline-block}

    /* HERO */
    .hero{
      display:flex;
      gap:40px;
      align-items:center;
      padding:48px 0 80px;
    }
    .hero-left{flex:1;min-width:320px}
    .eyebrow{font-size:13px;color:var(--muted);text-transform:uppercase;letter-spacing:1px;margin-bottom:10px}
    h1{font-size:46px;line-height:1.02;margin:0 0 18px;font-weight:800; color: #fff;}
    p.lead{color: #d1cfe0;font-size:18px;margin:0 0 20px;max-width:60ch}
    .cta-row{display:flex;gap:12px;margin-top:22px}
    .btn{
      padding:12px 18px;border-radius:12px;border:0;cursor:pointer;font-weight:700;
      box-shadow:0 6px 24px rgba(77,52,199,0.18), inset 0 -1px rgba(255,255,255,0.03);
    }
    .btn-primary{background:linear-gradient(90deg,var(--accent1),var(--accent2));color:white}
    .btn-ghost{background:transparent;border:1px solid rgba(255,255,255,0.08);color:var(--muted)}

    .microtrust{margin-top:14px;color:var(--muted);font-size:13px}

    /* hero mockup */
    .hero-right{flex:1;display:flex;justify-content:center;align-items:center;min-height:360px}
    .mockup{
      width:360px;height:700px;border-radius:28px;position:relative;
      background:linear-gradient(180deg, rgba(255,255,255,0.06) 0%, rgba(0,0,0,0.08) 100%);
      box-shadow: 0 30px 80px rgba(10,6,20,0.7), 0 6px 18px rgba(120,90,255,0.08);
      overflow:hidden;border:1px solid rgba(255,255,255,0.03);
      display:flex;flex-direction:column;align-items:center;padding:30px;
    }
    .mockup .phone-screen{width:100%;height:100%;background:
      radial-gradient(circle at 10% 15%, rgba(255,255,255,0.04), transparent 10%),
      linear-gradient(180deg,#2e2450 0%, #6f57d9 100%);border-radius:20px;display:flex;flex-direction:column;gap:12px;padding:18px;color:white;font-weight:600}
    .floating-card{position:absolute;left:-30px;top:160px;background:linear-gradient(90deg, rgba(255,255,255,0.03), rgba(255,255,255,0.02));backdrop-filter:blur(6px);padding:14px;border-radius:14px;border:1px solid rgba(255,255,255,0.04);box-shadow:0 10px 30px rgba(0,0,0,0.4)}
    .floating-card.right{right:-36px;left:auto;top:140px}

    /* sections */
    section.block{padding:64px 0;border-top:1px solid rgba(255,255,255,0.02)}
    .two-col{display:grid;grid-template-columns:1fr 420px;gap:36px;align-items:start}
    .card{background:var(--card-bg);padding:20px;border-radius:14px;border:1px solid rgba(255,255,255,0.03)}
    .muted{color:var(--muted)}

    /* features grid */
    .grid-3{display:grid;grid-template-columns:repeat(3,1fr);gap:18px}
    .pill{display:inline-block;padding:8px 12px;border-radius:999px;background:rgba(255,255,255,0.03);font-weight:700;color:#efeefe;font-size:13px}

    /* roadmap */
    .roadmap-item{margin-bottom:18px}
    .offers{display:flex;gap:18px;flex-wrap:wrap}
    .offer{flex:1;min-width:240px;padding:20px;border-radius:12px;background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));border:1px solid rgba(255,255,255,0.03)}

    footer{padding:40px 0;text-align:center;color:var(--muted);font-size:14px}
    .small{font-size:13px;color:var(--muted)}

    /* modal */
    .modal-backdrop{position:fixed;inset:0;background:rgba(0,0,0,0.6);display:none;align-items:center;justify-content:center;z-index:80}
    .modal{background:linear-gradient(180deg,#0f0d14,#141019);padding:22px;border-radius:14px;max-width:680px;width:100%;color:#fff;border:1px solid rgba(255,255,255,0.03)}
    .form-row{display:flex;gap:8px}
    .form-field{display:block;width:100%;padding:10px;border-radius:8px;border:1px solid rgba(255,255,255,0.06);background:transparent;color:#fff;margin-bottom:10px}
    .close-x{background:transparent;border:0;color:var(--muted);cursor:pointer;font-weight:700}

    @media (max-width:900px){
      .hero{flex-direction:column-reverse;gap:30px}
      .two-col{grid-template-columns:1fr; }
      h1{font-size:34px}
      .mockup{transform:scale(0.95)}
      .grid-3{grid-template-columns:1fr}
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- Header / Topbar -->
    <header class="site-header">
      <div style="display:flex;align-items:center;gap:18px">
        <div class="logo">Project: New Education</div>
        <div class="topbar">Founders seats open — Join the private workshop</div>
      </div>
      <nav aria-label="Main navigation">
        <a href="#vision">Vision</a>
        <a href="#roadmap">Roadmap</a>
        <a href="#platform">Platform</a>
        <a href="#join">Join</a>
        <a href="#press">Press</a>
        <a href="#speaker">Speaker</a>
      </nav>
    </header>

    <!-- HERO -->
    <main class="hero" role="main" aria-labelledby="hero-heading">
      <div class="hero-left">
        <div class="eyebrow">NeoAI</div>
        <h1 id="hero-heading">Replace Schools. Rebuild Work. Reimagine Humanity.</h1>
        <p class="lead">We’re creating the world’s first AI-native learning and life system — a private, practical, ethical platform that teaches the skills economies actually need, issues employer-trusted credentials, and builds new career architectures for every person on Earth. Founder: <strong>[Your Name]</strong> • Cofounder & mascot: <strong>[Dog Name]</strong>.</p>

        <div class="cta-row">
          <button class="btn btn-primary" onclick="openForm('founder')">Join Founders’ List — Limited Early Seats</button>
          <button class="btn btn-ghost" onclick="openModal('video')">Watch the 3-minute Vision (Video)</button>
        </div>
        <div class="microtrust">Live beta • Founders seats open • Early access = lifetime perks + equity invites</div>
      </div>

      <div class="hero-right" aria-hidden="false">
        <div class="mockup" role="img" aria-label="Hero mockup showing mobile AI product">
          <div class="phone-screen">
            <div style="display:flex;justify-content:space-between;align-items:center">
              <div style="font-weight:800">Use AI To Meet<br>All Your Needs</div>
              <div style="font-size:13px;background:rgba(255,255,255,0.06);padding:6px 10px;border-radius:10px">Beta</div>
            </div>
            <div style="flex:1;display:flex;flex-direction:column;justify-content:center;gap:8px;">
              <div style="background:rgba(0,0,0,0.12);padding:10px;border-radius:10px">Purchases • Delivery • Events</div>
              <div style="background:rgba(0,0,0,0.08);padding:10px;border-radius:10px">Tickets • Projects • Mentors</div>
            </div>
            <div style="display:flex;justify-content:space-between;align-items:center;width:100%">
              <div style="font-size:13px;color:rgba(255,255,255,0.8)">How can I help you?</div>
              <div style="background:rgba(255,255,255,0.06);padding:8px 12px;border-radius:999px">Say hi →</div>
            </div>
          </div>

          <div class="floating-card" style="width:220px">
            <div style="font-weight:700;margin-bottom:6px">Complete your Profile</div>
            <div class="muted" style="font-size:13px">Create a profile in your style</div>
          </div>

          <div class="floating-card right" style="width:200px">
            <div style="font-weight:700;margin-bottom:6px">Monthly • $20 / month</div>
            <div class="muted" style="font-size:13px">Yearly $200 / year • Lifetime $480</div>
          </div>
        </div>
      </div>
    </main>

    <!-- Founder strip -->
    <section class="block">
      <div class="container two-col" id="vision">
        <div>
          <h2>From $0 to system-level change — this is the plan.</h2>
          <p class="muted">I’m <strong>[Your Name]</strong>. I build systems that teach people to create value, not pass exams. I believe the future should be learned, not leased. My dog <strong>[Dog Name]</strong> documents the ride.</p>
          <p style="margin-top:16px"><button class="btn btn-primary" onclick="openForm('call')">Book a short call — Founder invites limited</button></p>
        </div>
        <div class="card">
          <img src="/assets/founder.jpg" alt="[Your Name], founder of Project: New Education" style="width:100%;border-radius:8px;margin-bottom:10px;object-fit:cover;height:220px" />
          <div style="font-weight:700">Founder strip</div>
          <div class="muted" style="margin-top:6px">Short founder intro + photo caption</div>
        </div>
      </div>
    </section>

    <!-- Manifesto -->
    <section class="block">
      <div class="container">
        <h2>A Manifesto for Human Potential</h2>
        <p>Schools were built for the industrial era — to produce workers who fit jobs that no longer exist. The future belongs to people who can learn, adapt, and create. We will not wait for institutions to change. We will build the system around humans: personalized, auditable, portable, and infinitely improvable. Our platform rewards real-world contribution, lifts up communities that were left behind, and designs jobs that respect creativity, dignity and purpose. This is not incremental reform — this is a civilizational upgrade.</p>
        <p style="font-weight:700;margin-top:8px">If you believe humans are more than a resume, join us.</p>
      </div>
    </section>

    <!-- Problem -->
    <section class="block">
      <div class="container">
        <h3>What’s broken (and why it costs us everything)</h3>
        <ul>
          <li><strong>Degrees over skills:</strong> Most hiring still rewards diplomas, not ability — millions of capable people are excluded purely because of credential gatekeeping.</li>
          <li><strong>One-size schooling:</strong> Curricula are slow, standardized, and fail to teach creative problem solving or emergent AI skills.</li>
          <li><strong>Job fragility:</strong> Automation and platform economies are erasing old jobs faster than we create new ones — leaving entire communities unemployed or underemployed.</li>
        </ul>
        <p class="muted" style="margin-top:8px">The real cost: wasted talent, rising inequality, and trillions in unrealized productivity. That’s the world we refuse to accept.</p>
      </div>
    </section>

    <!-- Solution -->
    <section class="block" id="platform">
      <div class="container">
        <h3>The New Education System — Built for the 21st Century</h3>
        <p>Three core pillars power our system.</p>

        <div style="display:flex;gap:18px;flex-wrap:wrap;margin-top:18px">
          <div class="card" style="flex:1;min-width:260px">
            <div style="font-weight:800">Pillar A — Adaptive Learning OS</div>
            <ul style="margin-top:8px">
              <li>Personalized AI coaches that map your skills, create daily learning paths, and show employers what you can actually do.</li>
              <li>Outcome: People learn faster, retain more, and can prove impact.</li>
            </ul>
          </div>

          <div class="card" style="flex:1;min-width:260px">
            <div style="font-weight:800">Pillar B — Credentials as Action</div>
            <ul style="margin-top:8px">
              <li>Micro-certifications tied to real projects and employer assessments — portable, verifiable, and stackable into careers.</li>
              <li>Outcome: Hiring matches skills, not paper.</li>
            </ul>
          </div>

          <div class="card" style="flex:1;min-width:260px">
            <div style="font-weight:800">Pillar C — New Job Architectures</div>
            <ul style="margin-top:8px">
              <li>Work marketplaces, project cooperatives, and local innovation studios that turn learning into paying work, apprenticeships, and startups.</li>
              <li>Outcome: Jobs that reward creativity and entrepreneurship — not rote tasks.</li>
            </ul>
          </div>
        </div>

        <p style="margin-top:16px">Sign up, get an AI coach, complete hands-on missions, earn a credential and get matched to paid projects or employers — all within weeks.</p>
      </div>
    </section>

    <!-- Platform snapshot -->
    <section class="block">
      <div class="container">
        <h3>Platform at a glance</h3>
        <div class="grid-3" style="margin-top:18px">
          <div class="card">
            <div class="pill">AI Mentor</div>
            <p class="muted" style="margin-top:10px">24/7 coaching, tailored practice, instant feedback.</p>
          </div>
          <div class="card">
            <div class="pill">Real Projects</div>
            <p class="muted" style="margin-top:10px">Learn by shipping — portfolio shows your value.</p>
          </div>
          <div class="card">
            <div class="pill">Employer Hub</div>
            <p class="muted" style="margin-top:10px">Companies hire from our vetted talent pool.</p>
          </div>
          <div class="card">
            <div class="pill">Offline Mode</div>
            <p class="muted" style="margin-top:10px">Low-bandwidth, offline lessons for global reach.</p>
          </div>
          <div class="card">
            <div class="pill">Local Hubs</div>
            <p class="muted" style="margin-top:10px">Community partners run real-world labs and micro-schools.</p>
          </div>
          <div class="card">
            <div class="pill">Creator Marketplace</div>
            <p class="muted" style="margin-top:10px">Educators and creators earn revenue and equity.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Roadmap -->
    <section class="block" id="roadmap">
      <div class="container">
        <h3>Roadmap — how we scale to billions</h3>
        <div style="margin-top:18px">
          <div class="roadmap-item card">
            <strong>First 0–6 months (launch):</strong>
            <ul class="muted">
              <li>MVP: AI tutor + 3 micro-courses.</li>
              <li>Pilot: 10 community partners (schools/NGOs/corporates).</li>
              <li>Founders cohort: 1,000 learners, early credentials.</li>
            </ul>
          </div>

          <div class="roadmap-item card" style="margin-top:12px">
            <strong>Months 6–18 (scale):</strong>
            <ul class="muted">
              <li>Localized rollouts in 10 languages.</li>
              <li>Partnership with telcos for offline access.</li>
              <li>Employer accreditation pilots.</li>
            </ul>
          </div>

          <div class="roadmap-item card" style="margin-top:12px">
            <strong>Years 2–5 (mass adoption):</strong>
            <ul class="muted">
              <li>Certified credentials recognized by global employers.</li>
              <li>Integrated job platform + regional hubs.</li>
              <li>Global movement + ambassador network in 200 countries.</li>
            </ul>
          </div>

          <div class="roadmap-item card" style="margin-top:12px">
            <strong>Long term (10 years):</strong>
            <p class="muted">New learning & work architecture embedded in national systems. Continuous lifelong learning for everyone.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- How to Join -->
    <section class="block" id="join">
      <div class="container">
        <h3>Pick your way in — be an architect of the future</h3>
        <div class="offers" style="margin-top:18px">
          <div class="offer">
            <h4>Founders Pass <span class="small muted">(limited / equity invites)</span></h4>
            <p>Lifetime seat, early discounts, governance votes, founder badge.</p>
            <p style="font-weight:800">$297 early</p>
            <p><button class="btn btn-primary" onclick="openForm('founder')">Join Founders’ List — $297</button></p>
          </div>

          <div class="offer">
            <h4>Learner <span class="small muted">(early cohort)</span></h4>
            <p>12-week bootcamps, AI mentor, guaranteed employer pipeline.</p>
            <p class="muted">Reserve spot — pay what you can / sliding scale</p>
            <p><button class="btn btn-ghost" onclick="openForm('learner')">Reserve spot</button></p>
          </div>

          <div class="offer">
            <h4>Ambassador</h4>
            <p>Localize courses, host cohorts, earn rewards + revenue share.</p>
            <p><button class="btn btn-ghost" onclick="openForm('ambassador')">Apply to be an Ambassador (no cost)</button></p>
          </div>

          <div class="offer">
            <h4>Partner</h4>
            <p>Pilot your institution, co-brand programs, hire trained talent.</p>
            <p><button class="btn btn-ghost" onclick="openForm('partner')">Request a pilot</button></p>
          </div>
        </div>

        <p class="muted" style="margin-top:12px">(Each CTA opens modal / form — collect name, email, role, country, and short motivation.)</p>
      </div>
    </section>

    <!-- Pricing -->
    <section class="block">
      <div class="container">
        <h3>Pricing & Early-Adopter offers</h3>
        <div style="display:flex;gap:18px;flex-wrap:wrap;margin-top:18px">
          <div class="card" style="min-width:260px">
            <h4>Founder Plan</h4>
            <p class="muted">One-time pre-sale — $297 (early) — lifetime access to core platform + equity lottery + Founders workshop</p>
          </div>
          <div class="card" style="min-width:260px">
            <h4>Learner Plan</h4>
            <p class="muted">Free Tier — basic AI mentor + free micro-lessons</p>
            <p class="muted">Growth Monthly — $19/mo — full course access, community, certificates</p>
            <p class="muted">Pro Cohort — $497 (one-time) — mentor + employer-placement track</p>
          </div>
          <div class="card" style="min-width:260px">
            <h4>Ambassador / Partner</h4>
            <p class="muted">Free to apply; revenue-share arrangements by contract.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Dog + brand -->
    <section class="block">
      <div class="container two-col">
        <div>
          <h3>Meet our co-founder: [Dog Name]</h3>
          <p class="muted">[Dog Name] is our mascot, moral compass, and creative director. Expect candid videos, “learning with pups” micro-lessons, and gentle reminders that humanity must build a future that’s kinder and more joyful.</p>
          <p><a href="https://instagram.com" class="btn btn-ghost">Follow [Dog Name] on Instagram</a></p>
        </div>
        <div class="card">
          <img src="/assets/dog.jpg" alt="[Dog Name], project co-founder and mascot" style="width:100%;height:220px;object-fit:cover;border-radius:8px" />
          <div style="margin-top:12px;font-weight:700">Dog + Creative Brand Block</div>
        </div>
      </div>
    </section>

    <!-- Speaker -->
    <section class="block" id="speaker">
      <div class="container">
        <h3>Book [Your Name] — Visionary Speaker on Education, AI & the Future of Work</h3>
        <p class="muted">[Your Name] is the founder of Project: New Education — an ecosystem that rethinks learning and work for the age of AI. Combining startup grit with social mission, [Your Name] delivers electrifying keynotes about systems change, skill economies, and what real human flourishing looks like.</p>
        <ul style="margin-top:10px" class="muted">
          <li>“The Last Degree: Why Credentials Must Die”</li>
          <li>“AI Tutors, Human Futures: Personalizing Education at Planet Scale”</li>
          <li>“Rebuild Work: From Jobs to Projects, From Bosses to Communities”</li>
        </ul>
        <p style="margin-top:12px"><button class="btn btn-primary" onclick="openForm('speaker')">Request Speaking Fee & Dates</button></p>
      </div>
    </section>

    <!-- Press kit -->
    <section class="block" id="press">
      <div class="container">
        <h3>Press Kit</h3>
        <p class="muted">Project: New Education builds an AI-centric platform of personalized tutors, real project credentials, and employer pipelines. Founded by [Your Name], its mission is to make learning practical and careers equitable for everyone.</p>
        <div style="display:flex;gap:12px;flex-wrap:wrap;margin-top:12px">
          <a class="btn btn-ghost" href="/assets/press-one-sheet.pdf" download>Download Press One-Sheet (PDF)</a>
          <a class="btn btn-ghost" href="/assets/press-assets.zip" download>Download Press Assets</a>
        </div>
        <div class="muted" style="margin-top:10px">Press contact: <a href="mailto:hello@YOURDOMAIN">hello@YOURDOMAIN</a></div>
      </div>
    </section>

    <!-- Testimonials -->
    <section class="block">
      <div class="container">
        <h3>Testimonials</h3>
        <div style="display:flex;gap:12px;flex-wrap:wrap;margin-top:12px">
          <div class="card" style="min-width:260px">
            <blockquote>"I taught my son in 30 days; he’s more confident and got a paid gig." — Maria, Parent</blockquote>
          </div>
          <div class="card" style="min-width:260px">
            <blockquote>"We hired three apprentices from the platform last month — faster and cheaper than ads." — Tomas, HR lead</blockquote>
          </div>
        </div>
        <p style="margin-top:12px"><button class="btn btn-ghost" onclick="openForm('testimonial')">Share your story — get a free month</button></p>
      </div>
    </section>

    <!-- FAQ -->
    <section class="block">
      <div class="container">
        <h3>FAQ</h3>
        <div style="margin-top:12px">
          <p><strong>Is this a school?</strong><br>Not like the old ones. It’s a living system — an AI mentor + project marketplace + credential network that equips people for work that pays.</p>

          <p><strong>How much does it cost?</strong><br>There is a free tier for everyone. Founders and pro cohorts unlock advanced mentoring and placement services.</p>

          <p><strong>Will this replace teachers?</strong><br>No. Teachers and mentors are critical. We amplify and fund teachers, create better tools, and enable them to scale impact.</p>

          <p><strong>Are the credentials real?</strong><br>Yes — they are verified with project evidence and employer acceptance. We build credibility through outcomes.</p>

          <p><strong>How can I help?</strong><br>Join the founders list, apply to be an ambassador, or partner with us to run a pilot.</p>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer>
      <div class="container">
        <div style="margin-bottom:10px">© <span id="year"></span> Project: New Education. All rights reserved. <a href="/privacy">Privacy</a> • <a href="/terms">Terms</a> • <a href="/press">Press</a> • <a href="mailto:hello@YOURDOMAIN">Contact</a></div>
        <div class="small">We are an educational platform. Outcomes depend on user effort and external partners. We do not guarantee job placement; our mission is to create pathways and partnerships that increase opportunities.</div>
      </div>
    </footer>
  </div>

  <!-- Modal / Forms -->
  <div id="modalBackdrop" class="modal-backdrop" role="dialog" aria-modal="true" aria-hidden="true">
    <div class="modal" role="document" aria-labelledby="modalTitle">
      <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:8px">
        <div id="modalTitle" style="font-weight:800">Apply</div>
        <button class="close-x" onclick="closeModal()">✕</button>
      </div>

      <form id="mainForm" onsubmit="handleSubmit(event)">
        <input type="hidden" name="role" id="formRole" value="founder" />
        <input class="form-field" name="name" placeholder="Full name" required />
        <input class="form-field" name="email" placeholder="Email address" type="email" required />
        <div style="display:flex;gap:8px">
          <input class="form-field" name="country" placeholder="Country" required />
          <input class="form-field" name="price" placeholder="If paying: price / plan" />
        </div>
        <textarea class="form-field" name="motivation" rows="4" placeholder="Short motivation: why do you want to join? (max 200 chars)"></textarea>
        <div style="display:flex;gap:10px;align-items:center;justify-content:space-between;margin-top:6px">
          <div class="muted" style="font-size:13px">We keep your data private. By submitting you agree to our <a href="/terms">terms</a>.</div>
          <div style="display:flex;gap:8px">
            <button type="button" class="btn btn-ghost" onclick="closeModal()">Cancel</button>
            <button type="submit" class="btn btn-primary">Submit</button>
          </div>
        </div>
      </form>
    </div>
  </div>

  <!-- Video modal -->
  <div id="videoBackdrop" class="modal-backdrop" aria-hidden="true" style="display:none;z-index:85">
    <div class="modal" style="max-width:980px;padding:0;overflow:hidden">
      <div style="display:flex;justify-content:space-between;align-items:center;padding:12px 18px">
        <div style="font-weight:800">The 3-minute Vision</div>
        <button class="close-x" onclick="closeVideo()">✕</button>
      </div>
      <div style="background:#000;">
        <!-- Replace the iframe src with your hosted video -->
        <iframe width="100%" height="520" src="https://www.youtube.com/embed/dQw4w9WgXcQ" title="Vision video" frameborder="0" allowfullscreen></iframe>
      </div>
    </div>
  </div>

  <!-- Thank you overlay (simple) -->
  <div id="thanksBackdrop" class="modal-backdrop" style="display:none;">
    <div class="modal">
      <div style="font-weight:800">Welcome to the Founders’ Circle</div>
      <p class="muted" style="margin-top:8px">Thank you — check your inbox for access details. Expect an invite to the private Discord and the Founders’ workshop. Meanwhile, join our quick survey to help shape the curriculum.</p>
      <div style="display:flex;gap:10px;margin-top:12px">
        <a class="btn btn-primary" href="/survey">Fill the 90-second survey</a>
        <button class="btn btn-ghost" onclick="closeThanks()">Close</button>
      </div>
    </div>
  </div>

  <script>
    // small helpers
    document.getElementById('year').innerText = new Date().getFullYear();

    function openForm(role){
      // set role and open modal
      document.getElementById('formRole').value = role || 'founder';
      document.getElementById('modalBackdrop').style.display = 'flex';
      document.getElementById('modalBackdrop').setAttribute('aria-hidden','false');
    }
    function closeModal(){
      document.getElementById('modalBackdrop').style.display = 'none';
      document.getElementById('modalBackdrop').setAttribute('aria-hidden','true');
    }

    function openModal(id){
      if(id === 'video'){
        document.getElementById('videoBackdrop').style.display = 'flex';
        document.getElementById('videoBackdrop').setAttribute('aria-hidden','false');
      }
    }
    function closeVideo(){
      document.getElementById('videoBackdrop').style.display = 'none';
      document.getElementById('videoBackdrop').setAttribute('aria-hidden','true');
    }

    function handleSubmit(e){
      e.preventDefault();
      const form = e.target;
      const data = new FormData(form);
      const obj = {};
      data.forEach((v,k)=>obj[k]=v);
      // TODO: Replace this with actual API call (fetch to your server or 3rd party forms)
      console.log('FORM SUBMIT', obj);

      // show thank you overlay
      document.getElementById('modalBackdrop').style.display = 'none';
      document.getElementById('thanksBackdrop').style.display = 'flex';
      document.getElementById('thanksBackdrop').setAttribute('aria-hidden','false');

      // optional: send mailto fallback (uncomment to enable mailto)
      // window.location.href = `mailto:hello@YOURDOMAIN?subject=New%20Application%20(${encodeURIComponent(obj.role)})&body=${encodeURIComponent(JSON.stringify(obj, null, 2))}`;
    }

    function closeThanks(){
      document.getElementById('thanksBackdrop').style.display = 'none';
      document.getElementById('thanksBackdrop').setAttribute('aria-hidden','true');
    }

    // keyboard accessible close
    window.addEventListener('keydown', (e)=>{
      if(e.key === 'Escape'){
        closeModal();
        closeVideo();
        closeThanks();
      }
    });
  </script>
</body>
</html>
