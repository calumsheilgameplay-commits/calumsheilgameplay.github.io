<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Redlands Redback Muay Thai | Kids Muay Thai in Cleveland / Ormiston</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="description" content="Kids Muay Thai in Cleveland / Ormiston. Ages 5–11. Safe, fun, confidence-building training from Coach Calum. First class is FREE!">

  <style>
    :root {
      --red: #b91c1c;
      --red-dark: #7f1d1d;
      --orange: #f97316;
      --bg-dark: #020617;
      --bg-light: #f9fafb;
      --text-main: #111827;
      --muted: #6b7280;
    }

    * {
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      margin: 0;
      font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
      line-height: 1.6;
      color: #e5e7eb;
      background:
        radial-gradient(circle at 0% 0%, rgba(255,255,255,0.04) 0%, transparent 60%),
        repeating-linear-gradient(
          45deg,
          rgba(255,255,255,0.015) 0px,
          rgba(255,255,255,0.015) 2px,
          transparent 2px,
          transparent 6px
        ),
        #020617;
    }

    a {
      color: inherit;
      text-decoration: none;
    }

    .page {
      max-width: 1040px;
      margin: 0 auto;
      padding: 0 1.5rem 2.5rem;
    }

    /* INTAKE BANNER */
    .intake-banner {
      position: sticky;
      top: 0;
      z-index: 100;
      background: linear-gradient(135deg, var(--red) 0%, var(--orange) 100%);
      color: white;
      text-align: center;
      padding: 0.55rem 1rem;
      font-size: 0.9rem;
      font-weight: 700;
      text-transform: uppercase;
      letter-spacing: 0.06em;
      box-shadow: 0 4px 16px rgba(0, 0, 0, 0.4);
      animation: slideDown 0.45s ease-out both;
    }

    /* HEADER */
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1rem 0 0.5rem;
    }

    .logo-wrap {
      display: flex;
      align-items: center;
      gap: 0.75rem;
    }

    .logo-icon {
      width: 40px;
      height: 40px;
      border-radius: 50%;
      border: 2px solid var(--red);
      display: flex;
      align-items: center;
      justify-content: center;
      font-weight: 800;
      color: var(--red);
      background: rgba(15, 23, 42, 0.9);
    }

    .logo-text {
      font-size: 1.25rem;
      font-weight: 800;
      letter-spacing: 0.05em;
      text-transform: uppercase;
    }

    .logo-sub {
      font-size: 0.75rem;
      color: #9ca3af;
      text-transform: uppercase;
      letter-spacing: 0.14em;
    }

    .header-contact {
      text-align: right;
      font-size: 0.8rem;
      color: #9ca3af;
    }

    .header-contact strong {
      display: block;
      color: #e5e7eb;
      font-size: 0.9rem;
    }

    @media (max-width: 720px) {
      header {
        flex-direction: column;
        align-items: flex-start;
        gap: 0.5rem;
      }

      .header-contact {
        text-align: left;
      }
    }

    /* HERO */
    .hero {
      display: grid;
      grid-template-columns: minmax(0, 1.6fr) minmax(0, 1.05fr);
      gap: 2rem;
      padding: 2.25rem 0 2.75rem;
      align-items: center;
    }

    @media (max-width: 900px) {
      .hero {
        grid-template-columns: 1fr;
        padding-top: 1.5rem;
      }
    }

    .pill {
      display: inline-flex;
      align-items: center;
      gap: 0.4rem;
      background: rgba(248, 113, 113, 0.16);
      color: #fecaca;
      border-radius: 999px;
      padding: 0.3rem 0.8rem;
      font-size: 0.8rem;
      border: 1px solid rgba(248, 113, 113, 0.4);
      animation: fadeInDown 0.7s ease-out both;
    }

    .pill-dot {
      width: 7px;
      height: 7px;
      border-radius: 999px;
      background: #22c55e;
      box-shadow: 0 0 0 3px rgba(34, 197, 94, 0.3);
    }

    .hero h1 {
      font-size: clamp(2.1rem, 3vw + 1rem, 2.7rem);
      margin: 0.7rem 0 0.6rem;
      line-height: 1.15;
    }

    .hero-highlight {
      color: var(--red);
    }

    .hero-sub {
      color: #d1d5db;
      font-size: 0.98rem;
      max-width: 520px;
    }

    .hero-meta {
      font-size: 0.85rem;
      color: #9ca3af;
      margin-top: 0.6rem;
    }

    .hero-actions {
      display: flex;
      flex-wrap: wrap;
      gap: 0.9rem;
      align-items: center;
      margin-top: 1.2rem;
    }

    .hero-note {
      font-size: 0.8rem;
      color: #9ca3af;
      margin-top: 0.7rem;
    }

    /* BUTTONS */
    .btn-primary {
      background: linear-gradient(135deg, var(--red) 0%, var(--orange) 100%);
      color: white;
      padding: 0.85rem 1.7rem;
      border-radius: 999px;
      border: none;
      font-weight: 700;
      font-size: 0.95rem;
      letter-spacing: 0.04em;
      text-transform: uppercase;
      box-shadow: 0 12px 30px rgba(248, 113, 113, 0.55);
      cursor: pointer;
      display: inline-flex;
      align-items: center;
      gap: 0.4rem;
      transform: translateY(0);
      transition: transform 0.12s ease, box-shadow 0.12s ease, filter 0.12s ease;
      animation: pulseGlow 2.1s ease-in-out infinite;
    }

    .btn-primary span {
      font-size: 1.1rem;
    }

    .btn-primary:hover {
      transform: translateY(-1px);
      box-shadow: 0 18px 42px rgba(248, 113, 113, 0.85);
      filter: brightness(1.05);
    }

    .btn-ghost {
      padding: 0.75rem 1.4rem;
      border-radius: 999px;
      border: 1px solid rgba(148, 163, 184, 0.9);
      font-size: 0.9rem;
      color: #e5e7eb;
      cursor: pointer;
      background: rgba(15, 23, 42, 0.7);
      display: inline-flex;
      align-items: center;
      gap: 0.35rem;
      backdrop-filter: blur(4px);
      transition: background 0.15s ease, border-color 0.15s ease, transform 0.1s ease;
    }

    .btn-ghost:hover {
      background: rgba(15, 23, 42, 0.95);
      border-color: rgba(248, 250, 252, 0.9);
      transform: translateY(-1px);
    }

    /* HERO CARD */
    .hero-card {
      background: radial-gradient(circle at top, #111827 0, #020617 75%);
      border-radius: 1.25rem;
      padding: 1.4rem 1.4rem 1.2rem;
      border: 1px solid rgba(148, 163, 184, 0.45);
      box-shadow: 0 16px 40px rgba(15, 23, 42, 0.9);
      position: relative;
      overflow: hidden;
      animation: floatIn 0.8s ease-out 0.1s both;
    }

    .hero-card::before {
      content: "";
      position: absolute;
      inset: -40%;
      background:
        radial-gradient(circle at 0% 0%, rgba(248, 113, 113, 0.35), transparent 55%),
        radial-gradient(circle at 100% 0%, rgba(56, 189, 248, 0.3), transparent 55%);
      opacity: 0.25;
      pointer-events: none;
    }

    .hero-card-inner {
      position: relative;
      z-index: 1;
    }

    .badge {
      display: inline-block;
      padding: 0.1rem 0.6rem;
      border-radius: 999px;
      border: 1px solid rgba(148, 163, 184, 0.7);
      font-size: 0.7rem;
      letter-spacing: 0.12em;
      text-transform: uppercase;
      color: #e5e7eb;
      margin-bottom: 0.45rem;
    }

    .hero-card h3 {
      margin: 0 0 0.4rem;
      font-size: 1.05rem;
    }

    .hero-card p {
      font-size: 0.9rem;
      color: #e5e7eb;
    }

    .hero-card ul {
      list-style: none;
      padding: 0;
      margin: 0.6rem 0 0;
    }

    .hero-card li {
      font-size: 0.83rem;
      color: #e5e7eb;
      margin-bottom: 0.25rem;
      display: flex;
      gap: 0.35rem;
      align-items: baseline;
    }

    .hero-card li span {
      color: #22c55e;
      font-size: 0.9rem;
    }

    /* MAIN WRAPPER */
    .main {
      background: #f9fafb;
      color: var(--text-main);
      border-radius: 1.5rem 1.5rem 0 0;
      margin-top: 1rem;
      padding: 2rem 1.5rem 2.6rem;
      box-shadow: 0 -4px 25px rgba(15, 23, 42, 0.9);
    }

    @media (max-width: 720px) {
      .main {
        padding: 1.6rem 1.2rem 2.3rem;
      }
    }

    h2 {
      font-size: 1.45rem;
      margin-bottom: 0.4rem;
    }

    .section-lead {
      font-size: 0.95rem;
      color: var(--muted);
      margin-top: 0;
      margin-bottom: 1rem;
    }

    .section {
      margin-bottom: 2.1rem;
    }

    .section-split {
      display: grid;
      grid-template-columns: minmax(0, 1.2fr) minmax(0, 1fr);
      gap: 1.5rem;
    }

    @media (max-width: 900px) {
      .section-split {
        grid-template-columns: 1fr;
      }
    }

    .card {
      background: white;
      border-radius: 1rem;
      border: 1px solid #e5e7eb;
      padding: 1.15rem 1.25rem;
      position: relative;
      overflow: hidden;
      transition: transform 0.15s ease, box-shadow 0.15s ease, border-color 0.15s ease;
    }

    .card:hover {
      transform: translateY(-2px);
      box-shadow: 0 18px 40px rgba(15, 23, 42, 0.09);
      border-color: rgba(248, 113, 113, 0.5);
    }

    .card-tag {
      position: absolute;
      top: 0.9rem;
      right: 1rem;
      font-size: 0.7rem;
      text-transform: uppercase;
      letter-spacing: 0.16em;
      color: #9ca3af;
    }

    ul.checklist {
      list-style: none;
      padding: 0;
      margin: 0.45rem 0 0;
    }

    ul.checklist li {
      padding-left: 1.3rem;
      position: relative;
      margin-bottom: 0.35rem;
      font-size: 0.9rem;
      color: #374151;
    }

    ul.checklist li::before {
      content: "✓";
      position: absolute;
      left: 0;
      top: 0;
      color: #16a34a;
      font-weight: 700;
      font-size: 0.9rem;
    }

    .muted {
      font-size: 0.85rem;
      color: var(--muted);
    }

    /* FORM */
    form {
      display: grid;
      gap: 0.75rem;
    }

    label {
      font-size: 0.85rem;
      color: #374151;
      display: block;
      margin-bottom: 0.1rem;
    }

    input, select, textarea {
      width: 100%;
      padding: 0.6rem 0.65rem;
      border-radius: 0.55rem;
      border: 1px solid #d1d5db;
      font-family: inherit;
      font-size: 0.9rem;
      background: white;
      color: #111827;
    }

    textarea {
      min-height: 70px;
      resize: vertical;
    }

    /* ANIMATIONS */
    @keyframes fadeInDown {
      from { opacity: 0; transform: translateY(-8px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @keyframes floatIn {
      from { opacity: 0; transform: translateY(14px) scale(0.98); }
      to { opacity: 1; transform: translateY(0) scale(1); }
    }

    @keyframes pulseGlow {
      0%, 100% { box-shadow: 0 12px 30px rgba(248, 113, 113, 0.4); }
      50% { box-shadow: 0 16px 45px rgba(248, 113, 113, 0.85); }
    }

    @keyframes slideDown {
      from { transform: translateY(-100%); }
      to { transform: translateY(0); }
    }

    /* FOOTER */
    footer {
      margin-top: 1.2rem;
      font-size: 0.8rem;
      color: #9ca3af;
      text-align: center;
    }
  </style>
</head>

<body>
  <!-- NEXT INTAKE STRIP -->
  <div class="intake-banner">
    ⚡ NEXT INTAKE STARTS FEB 5 – LIMITED SPOTS FOR AGES 5–11 ⚡
  </div>

  <div class="page">
    <!-- HEADER -->
    <header>
      <div class="logo-wrap">
        <div class="logo-icon">R</div>
        <div>
          <div class="logo-text">Redlands Redback Muay Thai</div>
          <div class="logo-sub">Kids Muay Thai • Cleveland / Ormiston</div>
        </div>
      </div>
      <div class="header-contact">
        <strong>0403 435 444</strong>
        RBMT@gmail.com
      </div>
    </header>

    <!-- HERO -->
    <section class="hero">
      <div>
        <div class="pill">
          <span class="pill-dot"></span>
          Kids Muay Thai • First class free
        </div>
        <h1>
          Confidence-building <span class="hero-highlight">Muay Thai for Kids</span> in the Redlands
        </h1>
        <p class="hero-sub">
          Ages 5–11. Safe, structured Muay Thai classes that build confidence, focus and discipline –
          taught by an experienced local coach with real fight experience in Queensland and Thailand.
        </p>
        <div class="hero-meta">
          Wednesdays after school • Cleveland Scout Group Hall, 26 Bainbridge St, Ormiston QLD 4160
        </div>
        <div class="hero-actions">
          <a href="#trial">
            <button class="btn-primary">
              <span>✔</span> Book Free Trial
            </button>
          </a>
          <a href="#classes">
            <button class="btn-ghost">
              View class times & pricing →
            </button>
          </a>
        </div>
        <p class="hero-note">
          Small groups • Beginner-friendly • No contracts or joining fees.
        </p>
      </div>

      <aside class="hero-card">
        <div class="hero-card-inner">
          <div class="badge">Your coach</div>
          <h3>Coach Calum</h3>
          <p>
            4 years kids training & coaching experience. Multiple fights across QLD and Thailand.
            Trained under Ironfist Gym and Sinbi Muay Thai.
          </p>
          <ul>
            <li><span>●</span> Patient, kid-focused coaching style</li>
            <li><span>●</span> Real Muay Thai fundamentals taught safely</li>
            <li><span>●</span> Focus on respect, confidence and self-control</li>
          </ul>
        </div>
      </aside>
    </section>

    <!-- MAIN CONTENT -->
    <div class="main">
      <!-- CLASSES -->
      <section class="section" id="classes">
        <h2>Class times (Wednesdays)</h2>
        <p class="section-lead">
          Two age groups so kids train with others at a similar stage.
        </p>

        <div class="section-split">
          <div class="card">
            <div class="card-tag">Ages 5–8</div>
            <h3>Class 1 – Foundations & Fun</h3>
            <p><strong>3:45pm – 4:25pm</strong></p>
            <ul class="checklist">
              <li>Basic stance, balance and movement</li>
              <li>Simple punches, kicks and knees on pads</li>
              <li>Games and drills to build coordination and confidence</li>
            </ul>
            <p class="muted">
              Ideal for younger kids who need a positive outlet after school and a gentle introduction to martial arts.
            </p>
          </div>

          <div class="card">
            <div class="card-tag">Ages 9–11</div>
            <h3>Class 2 – Skills & Confidence</h3>
            <p><strong>4:30pm – 5:15pm</strong></p>
            <ul class="checklist">
              <li>More advanced combinations and padwork</li>
              <li>Footwork, defence and controlled partner drills</li>
              <li>Focus on effort, discipline and mindset</li>
            </ul>
            <p class="muted">
              Perfect for kids who want to be challenged, grow resilience and learn real Muay Thai technique in a safe environment.
            </p>
          </div>
        </div>
      </section>

      <!-- PRICING & LOCATION -->
      <section class="section">
        <div class="section-split">
          <div>
            <h2>Pricing</h2>
            <p class="section-lead">
              Simple, family-friendly pricing while the club grows.
            </p>
            <div class="card">
              <h3>$20 per class</h3>
              <p><strong>First class is FREE</strong> for every new student.</p>
              <ul class="checklist">
                <li>No joining fee</li>
                <li>No contracts or term lock-ins</li>
                <li>Pay per class at the hall</li>
              </ul>
              <p class="muted">
                As numbers grow, we’ll add optional grading events and extra training opportunities for kids who want to take things further.
              </p>
            </div>
          </div>

          <div>
            <h2>Location</h2>
            <p class="section-lead">
              Easy after-school drop-off in the Redlands.
            </p>
            <div class="card">
              <h3>Cleveland Scout Group Hall</h3>
              <p>
                26 Bainbridge St<br>
                Ormiston QLD 4160
              </p>
              <ul class="checklist">
                <li>Plenty of street parking nearby</li>
                <li>Parents welcome to quietly watch from the side</li>
                <li>Look for the Redback Muay Thai sign on training days</li>
              </ul>
              <p>
                <a href="https://maps.app.goo.gl/7q6hQZJaXG3CeL6q7" target="_blank" style="color: var(--red-dark); font-weight: 600;">
                  Open in Google Maps →
                </a>
              </p>
            </div>
          </div>
        </div>
      </section>

      <!-- TRIAL FORM -->
      <section class="section" id="trial">
        <h2>Book a free trial class</h2>
        <p class="section-lead">
          Pop in your details and Coach Calum will get back to you to confirm a Wednesday that works for your child.
        </p>

        <div class="section-split">
          <div class="card">
            <form action="mailto:RBMT@gmail.com?subject=New%20Trial%20Enquiry%20-%20Redlands%20Redback%20Muay%20Thai" method="post" enctype="text/plain">
              <div>
                <label>Parent / guardian name</label>
                <input type="text" name="Parent Name" required>
              </div>
              <div>
                <label>Child's name & age</label>
                <input type="text" name="Child Name & Age" required>
              </div>
              <div>
                <label>Preferred class</label>
                <select name="Preferred Class" required>
                  <option value="5-8">Ages 5–8 (3:45pm – 4:25pm)</option>
                  <option value="9-11">Ages 9–11 (4:30pm – 5:15pm)</option>
                  <option value="either">Either is fine</option>
                </select>
              </div>
              <div>
                <label>Best contact (mobile or email)</label>
                <input type="text" name="Contact" required>
              </div>
              <div>
                <label>Anything we should know? (optional)</label>
                <textarea name="Notes" placeholder="E.g. confidence level, previous experience, goals, injuries..."></textarea>
              </div>
              <div>
                <button class="btn-primary" type="submit">
                  <span>✔</span> Send Trial Request
                </button>
              </div>
            </form>
          </div>

          <div class="card">
            <div class="card-tag">Quick contact</div>
            <h3>Prefer to message directly?</h3>
            <p>
              You can also text or WhatsApp:
            </p>
            <p style="font-size: 1rem; font-weight: 700; color: var(--red-dark);">
              0403 435 444
            </p>
            <p class="muted">
              Send your name, your child’s name and age, and which class you’re interested in,
              and we’ll lock in a time for your free trial.
            </p>
            <p class="muted">
              Email works too: <strong>RBMT@gmail.com</strong>
            </p>
          </div>
        </div>
      </section>

      <footer>
        © 2025 Redlands Redback Muay Thai • Kids Muay Thai in Cleveland / Ormiston
      </footer>
    </div>
  </div>
</body>
</html>
