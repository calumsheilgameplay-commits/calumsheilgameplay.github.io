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
      --bg-dark: #020617;
      --bg-light: #f9fafb;
      --text-main: #111827;
      --muted: #6b7280;
    }

    /* GLOBAL RESET */
    * { box-sizing: border-box; }

    html { scroll-behavior: smooth; }

    body {
      margin: 0;
      font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
      line-height: 1.6;
      background: #020617;
      color: #e5e7eb;

      /* ⭐ SOFT TEXTURED BACKGROUND PATTERN */
      background-image:
        radial-gradient(circle at 0% 0%, rgba(255,255,255,0.04) 0%, transparent 70%),
        repeating-linear-gradient(
          45deg,
          rgba(255,255,255,0.015) 0px,
          rgba(255,255,255,0.015) 2px,
          transparent 2px,
          transparent 6px
        );
      background-size: cover;
    }

    a { color: inherit; text-decoration: none; }

    .page { max-width: 1040px; margin: 0 auto; padding: 1.5rem 1.5rem 2.5rem; }

    /* ⭐ NEXT INTAKE BANNER */
    .intake-banner {
      background: linear-gradient(135deg, var(--red) 0%, #f97316 100%);
      text-align: center;
      padding: 0.55rem 1rem;
      color: white;
      font-weight: 700;
      font-size: 0.9rem;
      text-transform: uppercase;
      letter-spacing: 0.04em;
      border-bottom: 2px solid rgba(255,255,255,0.2);
      box-shadow: 0 4px 12px rgba(0,0,0,0.25);
      position: sticky;
      top: 0;
      z-index: 99;
      animation: slideDown 0.5s ease-out forwards;
    }

    /* HEADER */
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding-top: 0.8rem;
      padding-bottom: 0.6rem;
    }

    .logo-wrap { display: flex; align-items: center; gap: 0.75rem; }

    .logo-icon {
      width: 40px; height: 40px;
      border-radius: 50%;
      border: 2px solid var(--red);
      display: flex; align-items: center; justify-content: center;
      font-size: 1.2rem; font-weight: 700;
      color: var(--red);
    }

    .logo-text { font-size: 1.25rem; font-weight: 800; text-transform: uppercase; }
    .logo-sub { font-size: 0.75rem; color: #9ca3af; text-transform: uppercase; }

    .header-contact { text-align: right; font-size: 0.8rem; color: #9ca3af; }
    .header-contact strong { color: #fff; font-size: 0.9rem; }

    @media (max-width: 720px) {
      header { flex-direction: column; align-items: flex-start; gap: 0.5rem; }
      .header-contact { text-align: left; }
    }

    /* HERO SECTION */
    .hero {
      display: grid;
      grid-template-columns: minmax(0, 1.6fr) minmax(0, 1fr);
      gap: 2rem;
      padding: 2.5rem 0 3rem;
      align-items: center;
    }

    @media (max-width: 900px) {
      .hero { grid-template-columns: 1fr; }
    }

    .pill {
      background: rgba(248,113,113,0.12);
      padding: 0.35rem 0.8rem;
      border-radius: 999px;
      color: #fecaca;
      font-size: 0.8rem;
      border: 1px solid rgba(248,113,113,0.35);
    }

    .hero h1 { font-size: 2.4rem; margin: 0.5rem 0; }
    .hero-highlight { color: var(--red); }
    .hero-sub { color: #d1d5db; max-width: 520px; }

    /* BUTTONS */
    .btn-primary {
      background: linear-gradient(135deg, var(--red) 0%, #f97316 100%);
      padding: 0.85rem 1.7rem;
      border-radius: 999px;
      border: none;
      color: white;
      font-size: 0.95rem;
      font-weight: 700;
      text-transform: uppercase;
      box-shadow: 0 12px 30px rgba(248, 113, 113, 0.5);
      cursor: pointer;
      animation: pulseGlow 2.2s infinite ease-in-out;
    }

    /* HERO RIGHT CARD */
    .hero-card {
      background: rgba(15, 23, 42, 0.6);
      padding: 1.3rem;
      border-radius: 1.2rem;
      border: 1px solid rgba(255,255,255,0.08);
      backdrop-filter: blur(4px);
      animation: fadeUp 0.7s ease-out forwards;
    }

    /* MAIN BODY WRAPPER */
    .main {
      background: #f9fafb;
      color: #111;
      padding: 2rem 1.5rem;
      border-radius: 1.5rem 1.5rem 0 0;
      margin-top: 1.4rem;
    }

    .section { margin-bottom: 2rem; }
    h2 { font-size: 1.45rem; }

    .card {
      background: white;
      padding: 1.2rem;
      border-radius: 1rem;
      border: 1px solid #e5e7eb;
    }

    /* FORM */
    form { display: grid; gap: 0.75rem; }
    input, select, textarea {
      padding: 0.65rem;
      border: 1px solid #d1d5db;
      border-radius: 0.55rem;
      background: white;
    }

    /* ANIMATIONS */
    @keyframes pulseGlow {
      0%, 100% { box-shadow: 0 12px 30px rgba(248,113,113,0.4); }
      50% { box-shadow: 0 14px 45px rgba(248,113,113,0.8); }
    }

    @keyframes fadeUp {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @keyframes slideDown {
      from { transform: translateY(-100%); }
      to { transform: translateY(0); }
    }

  </style>
</head>

<body>

<!-- ⭐ NEXT INTAKE STRIP -->
<div class="intake-banner">
  ⚡ NEXT INTAKE STARTS FEB 5 — LIMITED SPOTS FOR AGES 5–11 ⚡
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
      <strong>0403 435 444</strong><br>
      RBMT@gmail.com
    </div>
  </header>

  <!-- HERO -->
  <section class="hero">
    <div>
      <div class="pill">First Class FREE • Wednesdays After School</div>
      <h1>Confidence-Building <span class="hero-highlight">Kids Muay Thai</span></h1>
      <p class="hero-sub">
        Ages 5–11. Safe Muay Thai fundamentals taught by Coach Calum — 4 years kids coaching experience, multiple fights across QLD & Thailand.
      </p>

      <a href="#trial"><button class="btn-primary">✔ Book Free Trial</button></a>
    </div>

    <div class="hero-card">
      <h3>Meet Coach Calum</h3>
      <p>
        • 4 years coaching kids<br>
        •
