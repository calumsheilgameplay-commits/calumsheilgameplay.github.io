<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Kids Muay Thai in [[Your Suburb]] | [[Your Club Name]]</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="description" content="Kids Muay Thai classes in [[Your Suburb]] for ages 8 and up. Fun, safe, small-group training focused on confidence, discipline and fitness. First class is free.">
  <style>
    body {
      margin: 0;
      font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
      line-height: 1.6;
      color: #111827;
      background: #f9fafb;
    }
    a { color: inherit; text-decoration: none; }
    .page {
      max-width: 960px;
      margin: 0 auto;
      padding: 1.5rem;
    }
    header {
      padding: 1rem 0 0.5rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 1rem;
    }
    .logo-text {
      font-weight: 700;
      font-size: 1.1rem;
      letter-spacing: 0.03em;
      text-transform: uppercase;
    }
    .tagline {
      font-size: 0.85rem;
      color: #6b7280;
    }
    .hero {
      padding: 2rem 0 2.5rem;
      display: grid;
      grid-template-columns: minmax(0, 2fr) minmax(0, 1.5fr);
      gap: 2rem;
      align-items: center;
    }
    @media (max-width: 768px) {
      .hero { grid-template-columns: 1fr; }
    }
    .hero h1 {
      font-size: 2rem;
      margin-bottom: 0.75rem;
    }
    .hero h1 span.highlight {
      color: #ea580c;
    }
    .hero-sub {
      color: #4b5563;
      margin-bottom: 1rem;
    }
    .pill {
      display: inline-flex;
      align-items: center;
      gap: 0.5rem;
      font-size: 0.85rem;
      background: #fee2e2;
      color: #b91c1c;
      border-radius: 999px;
      padding: 0.35rem 0.8rem;
      margin-bottom: 0.75rem;
    }
    .hero-actions {
      display: flex;
      flex-wrap: wrap;
      gap: 0.75rem;
      margin-top: 1rem;
    }
    .btn-primary {
      background: #ea580c;
      color: white;
      border-radius: 999px;
      padding: 0.7rem 1.4rem;
      font-weight: 600;
      border: none;
      cursor: pointer;
      font-size: 0.95rem;
    }
    .btn-primary:hover { background: #c2410c; }
    .btn-outline {
      border-radius: 999px;
      padding: 0.7rem 1.4rem;
      border: 1px solid #d1d5db;
      background: white;
      font-size: 0.95rem;
      cursor: pointer;
    }
    .hero-note {
      font-size: 0.8rem;
      color: #6b7280;
      margin-top: 0.75rem;
    }
    .hero-img {
      background: #111827;
      border-radius: 1.25rem;
      padding: 1.25rem;
      color: #f9fafb;
      display: flex;
      flex-direction: column;
      gap: 0.75rem;
    }
    .hero-img-tag {
      font-size: 0.8rem;
      text-transform: uppercase;
      letter-spacing: 0.08em;
      color: #9ca3af;
    }
    .hero-img-main {
      font-size: 0.95rem;
      font-weight: 500;
    }
    .hero-img-list {
      font-size: 0.85rem;
      color: #e5e7eb;
    }
    .hero-img-list li { margin-bottom: 0.25rem; }

    section {
      margin-bottom: 2.5rem;
    }
    section h2 {
      font-size: 1.4rem;
      margin-bottom: 0.5rem;
    }
    section p.lead {
      color: #4b5563;
      margin-bottom: 1rem;
    }
    .grid-2 {
      display: grid;
      grid-template-columns: minmax(0, 1fr) minmax(0, 1fr);
      gap: 1.5rem;
    }
    @media (max-width: 768px) {
      .grid-2 { grid-template-columns: 1fr; }
    }
    ul.checklist {
      list-style: none;
      padding: 0;
      margin: 0.5rem 0 0;
    }
    ul.checklist li {
      padding-left: 1.3rem;
      position: relative;
      margin-bottom: 0.35rem;
      font-size: 0.95rem;
      color: #374151;
    }
    ul.checklist li::before {
      content: "✓";
      position: absolute;
      left: 0;
      top: 0;
      color: #16a34a;
      font-weight: 600;
    }
    .card {
      background: white;
      border-radius: 1rem;
      padding: 1rem 1.25rem;
      border: 1px solid #e5e7eb;
    }
    .badge {
      display: inline-block;
      padding: 0.1rem 0.5rem;
      font-size: 0.75rem;
      border-radius: 999px;
      background: #eff6ff;
      color: #1d4ed8;
      margin-bottom: 0.25rem;
    }
    .muted {
      color: #6b7280;
      font-size: 0.9rem;
    }
    .pricing-grid {
      display: grid;
      grid-template-columns: minmax(0, 1.25fr) minmax(0, 1fr);
      gap: 1.5rem;
    }
    @media (max-width: 768px) {
      .pricing-grid { grid-template-columns: 1fr; }
    }
    .price-amount {
      font-size: 1.8rem;
      font-weight: 700;
    }
    .price-amount span {
      font-size: 0.9rem;
      font-weight: 500;
      color: #6b7280;
    }
    .faq-item {
      margin-bottom: 1rem;
    }
    .faq-item h3 {
      font-size: 1rem;
      margin-bottom: 0.25rem;
    }
    form {
      display: grid;
      gap: 0.75rem;
      margin-top: 0.5rem;
    }
    label {
      font-size: 0.85rem;
      color: #374151;
    }
    input, textarea, select {
      width: 100%;
      padding: 0.55rem 0.6rem;
      border-radius: 0.5rem;
      border: 1px solid #d1d5db;
      font: inherit;
      box-sizing: border-box;
    }
    textarea { min-height: 80px; resize: vertical; }
    footer {
      padding: 1.5rem 0 0.5rem;
      font-size: 0.8rem;
      color: #9ca3af;
      text-align: center;
    }
  </style>
</head>
<body>
  <div class="page">
    <header>
      <div>
        <div class="logo-text">Best Start MMA</div>
        <div class="tagline">Kids Muay Thai • Cleveland</div>
      </div>
      <div class="tagline">Text / WhatsApp: [[000]</div>
    </header>

    <main>
      <!-- HERO -->
      <section class="hero" id="top">
        <div>
          <div class="pill">
            New in [[Your Suburb]] • First class free
          </div>
          <h1>
            Confidence-building <span class="highlight">Kids Muay Thai</span><br>
            in [[Your Suburb]]
          </h1>
          <p class="hero-sub">
            Small-group Muay Thai classes for kids and teens. Safe, fun and structured training
            that builds confidence, discipline and fitness — taught by a coach who’s trained and fought in Thailand.
          </p>
          <p class="muted">
            Ages <strong>8–10/11</strong> and <strong>11+</strong> • No experience needed • First class is free.
          </p>
          <div class="hero-actions">
            <a href="#trial-form"><button class="btn-primary">Book a Free Trial Class</button></a>
            <a href="#classes"><button class="btn-outline">View Class Times &amp; Pricing</button></a>
          </div>
          <p class="hero-note">
            We keep class sizes small so every student gets attention — spots are limited.
          </p>
        </div>

        <aside class="hero-img">
          <div class="hero-img-tag">Your coach</div>
          <div class="hero-img-main">
            Hi, I’m [[Your Name]], a Muay Thai coach who’s trained under Thai fighters overseas and competed locally.
          </div>
          <ul class="hero-img-list">
            <li>Authentic Muay Thai fundamentals taught in a kid-friendly way</li>
            <li>Focus on confidence, respect and self-control – not ego</li>
            <li>Perfect for beginners who’ve never tried martial arts before</li>
          </ul>
          <div class="muted">
            Photos on this page are from my own training and fights — no stock images.
          </div>
        </aside>
      </section>

      <!-- WHY MUAY THAI -->
      <section id="why">
        <h2>Why Muay Thai is great for kids</h2>
        <p class="lead">
          Muay Thai is one of the most effective striking arts in the world – but for kids, the real benefits
          are confidence, discipline and resilience.
        </p>

        <div class="grid-2">
          <div class="card">
            <h3>Builds real confidence (without arrogance)</h3>
            <ul class="checklist">
              <li>Kids learn to set goals, work hard and see progress</li>
              <li>Shy kids get more comfortable speaking up and joining in</li>
              <li>Clear expectations around respect, effort and attitude</li>
            </ul>
          </div>
          <div class="card">
            <h3>Improves focus, fitness and emotional control</h3>
            <ul class="checklist">
              <li>Great outlet for energy and stress after school</li>
              <li>Develops balance, coordination and core strength</li>
              <li>Teaches kids how to stay calm and controlled, even when challenged</li>
            </ul>
          </div>
        </div>
      </section>

      <!-- ABOUT COACH -->
      <section id="coach">
        <h2>About your coach</h2>
        <div class="grid-2">
          <div>
            <p class="lead">
              I’m [[Your Name]], and I’ve built this program to bring authentic Muay Thai to kids in [[Your Suburb]]
              in a way that’s safe, structured and age-appropriate.
            </p>
            <ul class="checklist">
              <li>Trained in Thailand under experienced Thai fighters</li>
              <li>Competed in Muay Thai / combat sports here in Australia</li>
              <li>Working with kids in small-group settings</li>
              <li>Blue card / WWCC held (available on request)</li>
            </ul>
            <p class="muted">
              My goal isn’t to turn every kid into a fighter – it’s to help them become more confident, respectful and resilient,
              using Muay Thai as the vehicle.
            </p>
          </div>
          <div class="card">
            <span class="badge">What parents can expect</span>
            <ul class="checklist">
              <li>Clear rules around respect, language and behaviour</li>
              <li>No bullying, bravado or “tough guy” culture</li>
              <li>Beginner-friendly classes – we meet kids where they’re at</li>
              <li>Open communication with parents about progress</li>
            </ul>
          </div>
        </div>
      </section>

      <!-- CLASSES & PRICING -->
      <section id="classes">
        <h2>Class times &amp; pricing</h2>
        <p class="lead">
          We run two back-to-back classes on [[Day, e.g. Wednesday]] afternoons at [[Hall Name / Location]].
        </p>

        <div class="pricing-grid">
          <div class="card">
            <h3>Class schedule</h3>
            <p><strong>[[Day Name]]</strong> – after school</p>
            <ul class="checklist">
              <li><strong>3:45pm – 4:30pm</strong> &nbsp;• Kids 8–10/11 (fundamentals &amp; confidence)</li>
              <li><strong>4:30pm – 5:15pm</strong> &nbsp;• Youth 11+ (technique, fitness &amp; mindset)</li>
            </ul>
            <p class="muted">
              Please arrive 5–10 minutes early so we can start on time.
            </p>
            <h3>What to wear / bring</h3>
            <ul class="checklist">
              <li>Comfortable sports clothes (T-shirt and shorts/leggings)</li>
              <li>Water bottle</li>
              <li>We provide beginner gloves and pads to start with</li>
            </ul>
          </div>

          <div class="card">
            <h3>Pricing</h3>
            <p class="muted">Simple, flexible and family-friendly.</p>
            <p class="price-amount">$20 <span>per class</span></p>
            <ul class="checklist">
              <li>First class is <strong>100% free</strong> (no obligation)</li>
              <li>Pay-as-you-go to start – no lock-in contracts</li>
              <li>Discounted second class in the same week (only $10)</li>
            </ul>
            <p class="muted">
              As the club grows we’ll introduce optional grading events and equipment packages for
              kids who want to commit longer-term.
            </p>
            <a href="#trial-form"><button class="btn-primary">Book a Free Trial</button></a>
          </div>
        </div>
      </section>

      <!-- LOCATION -->
      <section id="location">
        <h2>Location</h2>
        <div class="grid-2">
          <div>
            <p class="lead">
              Classes are held at [[Community Hall Name]], [[Street Address]], [[Suburb]].
            </p>
            <ul class="checklist">
              <li>Easy parking nearby for school pickup</li>
              <li>Clean, bright hall with wooden floors</li>
              <li>Parents are welcome to watch from the side of the room</li>
            </ul>
            <p class="muted">
              You’ll see our pull-up banner and A-frame sign out the front on training days.
            </p>
          </div>
          <div class="card">
            <span class="badge">Map</span>
            <p class="muted">
              Embed a Google Map here or link out:
            </p>
            <p>
              <a href="[[Google Maps Link]]" target="_blank" rel="noopener">
                View [[Community Hall Name]] on Google Maps →
              </a>
            </p>
          </div>
        </div>
      </section>

      <!-- FAQ -->
      <section id="faq">
        <h2>Frequently asked questions</h2>
        <div class="faq-item">
          <h3>My child has never done martial arts before – is that okay?</h3>
          <p>
            Absolutely. Most of our students start as complete beginners. We go over stance, basic movement and
            simple techniques in a very step-by-step way, and no one is thrown in the deep end.
          </p>
        </div>
        <div class="faq-item">
          <h3>Is Muay Thai safe for kids?</h3>
          <p>
            Yes – when it’s taught properly. For kids, we focus on pads, drills, technique and controlled partner
            work. There is no hard sparring, and safety, control and respect are non-negotiable.
          </p>
        </div>
        <div class="faq-item">
          <h3>Can parents watch?</h3>
          <p>
            Yes, parents are welcome to watch quietly from the side of the hall. Some kids are more focused when
            parents sit a bit further back – we’ll find what works best for your child.
          </p>
        </div>
        <div class="faq-item">
          <h3>What if my child is nervous or shy?</h3>
          <p>
            Totally normal. We keep groups small and ease kids in gently. Many of our favourite students were
            nervous on day one and are now some of the most confident in the room.
          </p>
        </div>
      </section>

      <!-- CONTACT / TRIAL FORM -->
      <section id="trial-form">
        <h2>Book a free trial class</h2>
        <p class="lead">
          Fill in your details below and we’ll get back to you with available trial dates and what to bring.
        </p>
        <div class="grid-2">
          <div>
            <!-- If you’re using a form tool (e.g. Tally, Google Forms), replace this whole form block with their embed -->
            <form action="[[Your Form Handler or Google Form URL]]" method="post">
              <div>
                <label for="parent-name">Parent / guardian name</label>
                <input id="parent-name" name="parent_name" type="text" required>
              </div>
              <div>
                <label for="child-name">Child's name &amp; age</label>
                <input id="child-name" name="child_name_age" type="text" required>
              </div>
              <div>
                <label for="class-preference">Preferred class</label>
                <select id="class-preference" name="class_preference" required>
                  <option value="">Select an option</option>
                  <option value="8-10">3:45pm – 4:30pm (Ages 8–10/11)</option>
                  <option value="11+">4:30pm – 5:15pm (Ages 11+)</option>
                  <option value="either">Either class is fine</option>
                </select>
              </div>
              <div>
                <label for="contact">Best contact (mobile or email)</label>
                <input id="contact" name="contact" type="text" required>
              </div>
              <div>
                <label for="notes">Anything we should know? (optional)</label>
                <textarea id="notes" name="notes" placeholder="E.g. experience level, injuries, confidence, goals..."></textarea>
              </div>
              <div>
                <button class="btn-primary" type="submit">Request Free Trial</button>
              </div>
            </form>
          </div>
          <div>
            <div class="card">
              <span class="badge">What happens next?</span>
              <ul class="checklist">
                <li>You’ll get a confirmation message from [[Your Name]]</li>
                <li>We’ll lock in a trial date that suits you</li>
                <li>On the day, arrive 10 minutes early so we can say hi and settle your child in</li>
              </ul>
              <p class="muted">
                Prefer to message directly? Text or WhatsApp <strong>[[Your Phone]]</strong> with your child’s name and age
                and we’ll sort it out from there.
              </p>
            </div>
          </div>
        </div>
      </section>
    </main>

    <footer>
      &copy; [[Year]] [[Your Club Name]] • Kids Muay Thai in [[Your Suburb]]
    </footer>
  </div>
</body>
</html>
# calumsheilgameplay.github.io
