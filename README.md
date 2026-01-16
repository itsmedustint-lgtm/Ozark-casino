<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Ozark Casino — Investor Overview</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <meta
    name="description"
    content="Ozark Casino — a disciplined, capped-risk sweepstakes casino with instant payouts, forensic risk control, and influencer-driven growth."
  />
  <style>
    :root {
      --bg: #050814;
      --bg-alt: #0b1022;
      --accent: #f5b544;
      --accent-soft: rgba(245, 181, 68, 0.12);
      --text: #f7f7fb;
      --muted: #a3a7c2;
      --border: #262a40;
      --danger: #ff5c7a;
      --success: #3fd6a5;
      --radius-lg: 18px;
      --radius-md: 12px;
      --radius-pill: 999px;
      --shadow-soft: 0 18px 45px rgba(0, 0, 0, 0.55);
      --shadow-subtle: 0 10px 30px rgba(0, 0, 0, 0.35);
      --font-sans: system-ui, -apple-system, BlinkMacSystemFont, "SF Pro Text",
        "Segoe UI", sans-serif;
      --max-width: 1040px;
    }

    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      padding: 0;
      font-family: var(--font-sans);
      background: radial-gradient(circle at top, #151a33 0, #050814 55%, #02030a 100%);
      color: var(--text);
      -webkit-font-smoothing: antialiased;
    }

    main {
      max-width: var(--max-width);
      margin: 0 auto;
      padding: 32px 18px 64px;
    }

    a {
      color: var(--accent);
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    .pill {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      padding: 4px 12px;
      border-radius: var(--radius-pill);
      border: 1px solid rgba(245, 181, 68, 0.4);
      background: linear-gradient(
        120deg,
        rgba(245, 181, 68, 0.18),
        rgba(245, 181, 68, 0.04)
      );
      color: var(--accent);
      font-size: 11px;
      letter-spacing: 0.08em;
      text-transform: uppercase;
    }

    .pill-dot {
      width: 7px;
      height: 7px;
      border-radius: 50%;
      background: var(--success);
      box-shadow: 0 0 10px rgba(63, 214, 165, 0.9);
    }

    .hero {
      display: grid;
      grid-template-columns: minmax(0, 3fr) minmax(0, 2.4fr);
      gap: 32px;
      align-items: center;
      margin-bottom: 40px;
    }

    .hero-left h1 {
      font-size: clamp(30px, 4vw, 40px);
      line-height: 1.1;
      margin: 14px 0 12px;
    }

    .hero-highlight {
      background: linear-gradient(120deg, #f5b544, #ffdf9a);
      -webkit-background-clip: text;
      background-clip: text;
      color: transparent;
    }

    .hero-subtitle {
      color: var(--muted);
      font-size: 14px;
      max-width: 520px;
      line-height: 1.5;
    }

    .hero-metrics {
      display: flex;
      flex-wrap: wrap;
      gap: 18px;
      margin: 22px 0 26px;
    }

    .metric {
      padding: 10px 14px;
      border-radius: var(--radius-md);
      border: 1px solid var(--border);
      background: radial-gradient(circle at top left, #1b2340 0, #070a16 55%);
      box-shadow: var(--shadow-subtle);
      min-width: 130px;
    }

    .metric-label {
      font-size: 11px;
      text-transform: uppercase;
      letter-spacing: 0.08em;
      color: var(--muted);
      margin-bottom: 4px;
    }

    .metric-value {
      font-size: 18px;
      font-weight: 600;
    }

    .metric-note {
      font-size: 11px;
      color: var(--muted);
      margin-top: 2px;
    }

    .hero-actions {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      align-items: center;
    }

    .btn-primary {
      border: none;
      border-radius: var(--radius-pill);
      padding: 10px 18px;
      font-size: 13px;
      font-weight: 600;
      letter-spacing: 0.04em;
      text-transform: uppercase;
      cursor: pointer;
      background: linear-gradient(135deg, #f5b544, #ffdf9a);
      color: #1b1304;
      box-shadow: 0 14px 30px rgba(245, 181, 68, 0.45);
    }

    .btn-primary:hover {
      filter: brightness(1.05);
    }

    .btn-ghost {
      border-radius: var(--radius-pill);
      padding: 9px 16px;
      font-size: 12px;
      border: 1px solid var(--border);
      background: rgba(8, 10, 24, 0.7);
      color: var(--muted);
      cursor: pointer;
    }

    .btn-ghost:hover {
      border-color: rgba(245, 181, 68, 0.6);
      color: var(--accent);
    }

    .hero-right {
      border-radius: var(--radius-lg);
      border: 1px solid var(--border);
      background: radial-gradient(circle at top, #20284a 0, #050814 60%);
      box-shadow: var(--shadow-soft);
      padding: 18px 18px 16px;
      position: relative;
      overflow: hidden;
    }

    .hero-right-header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-bottom: 10px;
      font-size: 11px;
      color: var(--muted);
    }

    .hero-right-title {
      font-size: 12px;
      text-transform: uppercase;
      letter-spacing: 0.12em;
      color: var(--accent);
    }

    .hero-right-tag {
      padding: 3px 8px;
      border-radius: var(--radius-pill);
      background: rgba(3, 255, 171, 0.08);
      color: var(--success);
      font-size: 10px;
      text-transform: uppercase;
      letter-spacing: 0.08em;
    }

    .hero-chart {
      border-radius: 14px;
      border: 1px solid rgba(255, 255, 255, 0.04);
      background: linear-gradient(145deg, rgba(10, 16, 40, 0.9), rgba(5, 8, 20, 0.95));
      padding: 14px 14px 10px;
      position: relative;
      overflow: hidden;
    }

    .hero-chart-grid {
      position: absolute;
      inset: 0;
      background-image: linear-gradient(
          to right,
          rgba(255, 255, 255, 0.04) 1px,
          transparent 1px
        ),
        linear-gradient(
          to bottom,
          rgba(255, 255, 255, 0.04) 1px,
          transparent 1px
        );
      background-size: 40px 40px;
      opacity: 0.6;
      pointer-events: none;
    }

    .hero-chart-content {
      position: relative;
      z-index: 1;
    }

    .hero-chart-row {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-bottom: 8px;
      font-size: 11px;
      color: var(--muted);
    }

    .hero-chart-row strong {
      color: var(--text);
      font-size: 12px;
    }

    .hero-chart-bars {
      display: flex;
      gap: 6px;
      margin-top: 10px;
      margin-bottom: 6px;
    }

    .hero-chart-bar {
      flex: 1;
      height: 46px;
      border-radius: 999px;
      background: linear-gradient(to top, rgba(245, 181, 68, 0.1), transparent);
      border: 1px solid rgba(245, 181, 68, 0.3);
      position: relative;
      overflow: hidden;
    }

    .hero-chart-bar-fill {
      position: absolute;
      bottom: 0;
      left: 0;
      right: 0;
      border-radius: inherit;
      background: linear-gradient(to top, #f5b544, #ffdf9a);
    }

    .hero-chart-bar-fill.low {
      height: 35%;
    }

    .hero-chart-bar-fill.mid {
      height: 55%;
    }

    .hero-chart-bar-fill.high {
      height: 80%;
    }

    .hero-chart-labels {
      display: flex;
      justify-content: space-between;
      font-size: 10px;
      color: var(--muted);
    }

    .hero-footnote {
      margin-top: 10px;
      font-size: 10px;
      color: var(--muted);
    }

    .section {
      margin-bottom: 40px;
      border-radius: var(--radius-lg);
      border: 1px solid var(--border);
      background: radial-gradient(circle at top left, #151a33 0, #050814 60%);
      box-shadow: var(--shadow-soft);
      padding: 20px 18px 18px;
    }

    .section-header {
      display: flex;
      justify-content: space-between;
      align-items: baseline;
      margin-bottom: 14px;
      gap: 12px;
    }

    .section-title {
      font-size: 16px;
      font-weight: 600;
    }

    .section-kicker {
      font-size: 11px;
      text-transform: uppercase;
      letter-spacing: 0.12em;
      color: var(--muted);
    }

    .section-body {
      font-size: 13px;
      color: var(--muted);
      line-height: 1.6;
    }

    .section-grid {
      display: grid;
      grid-template-columns: repeat(3, minmax(0, 1fr));
      gap: 14px;
      margin-top: 14px;
    }

    .card {
      border-radius: var(--radius-md);
      border: 1px solid var(--border);
      background: rgba(5, 8, 20, 0.9);
      padding: 12px 12px 10px;
      font-size: 12px;
      color: var(--muted);
    }

    .card-title {
      font-size: 12px;
      font-weight: 600;
      margin-bottom: 4px;
      color: var(--text);
    }

    .badge {
      display: inline-flex;
      align-items: center;
      gap: 6px;
      padding: 3px 8px;
      border-radius: var(--radius-pill);
      font-size: 10px;
      text-transform: uppercase;
      letter-spacing: 0.08em;
      border: 1px solid rgba(245, 181, 68, 0.4);
      color: var(--accent);
      background: rgba(245, 181, 68, 0.06);
    }

    .badge-danger {
      border-color: rgba(255, 92, 122, 0.6);
      color: var(--danger);
      background: rgba(255, 92, 122, 0.08);
    }

    .badge-soft {
      border-color: rgba(163, 167, 194, 0.5);
      color: var(--muted);
      background: rgba(163, 167, 194, 0.08);
    }

    .list {
      margin: 10px 0 0;
      padding-left: 16px;
      font-size: 12px;
      color: var(--muted);
    }

    .list li {
      margin-bottom: 4px;
    }

    .two-col {
      display: grid;
      grid-template-columns: minmax(0, 1.4fr) minmax(0, 1fr);
      gap: 18px;
      margin-top: 10px;
    }

    .table {
      width: 100%;
      border-collapse: collapse;
      font-size: 11px;
      margin-top: 8px;
    }

    .table th,
    .table td {
      padding: 6px 6px;
      border-bottom: 1px solid rgba(38, 42, 64, 0.9);
      text-align: left;
    }

    .table th {
      font-weight: 500;
      color: var(--muted);
      text-transform: uppercase;
      letter-spacing: 0.08em;
      font-size: 10px;
    }

    .table tr:last-child td {
      border-bottom: none;
    }

    .table-highlight {
      color: var(--accent);
      font-weight: 600;
    }

    .tagline {
      margin-top: 4px;
      font-size: 11px;
      color: var(--muted);
    }

    .footnote {
      font-size: 11px;
      color: var(--muted);
      text-align: center;
      margin-top: 24px;
    }

    .divider {
      height: 1px;
      border: none;
      margin: 18px 0 10px;
      background: linear-gradient(
        to right,
        transparent,
        rgba(255, 255, 255, 0.12),
        transparent
      );
    }

    @media (max-width: 800px) {
      main {
        padding: 20px 14px 40px;
      }

      .hero {
        grid-template-columns: minmax(0, 1fr);
      }

      .hero-right {
        order: -1;
      }

      .section-grid {
        grid-template-columns: minmax(0, 1fr);
      }

      .two-col {
        grid-template-columns: minmax(0, 1fr);
      }
    }
  </style>
</head>
<body>
  <main>
    <!-- HERO -->
    <section class="hero">
      <div class="hero-left">
        <div class="pill">
          <span class="pill-dot"></span>
          <span>Founder-led, capped-risk sweepstakes casino</span>
        </div>
        <h1>
          Ozark Casino:
          <span class="hero-highlight">disciplined upside</span> with a hard ceiling on risk.
        </h1>
        <p class="hero-subtitle">
          Ozark Casino is a sweepstakes-based, U.S.-compliant casino experience built for
          instant payouts, forensic risk control, and compounding, influencer-driven growth.
          The goal: institutional discipline with indie-founder speed.
        </p>

        <div class="hero-metrics">
          <div class="metric">
            <div class="metric-label">Initial investor pool</div>
            <div class="metric-value">$25k – $75k</div>
            <div class="metric-note">Structured as capped exposure, not open-ended burn.</div>
          </div>
          <div class="metric">
            <div class="metric-label">Risk ceiling</div>
            <div class="metric-value">Pre-modeled</div>
            <div class="metric-note">Worst-case payout tables documented before launch.</div>
          </div>
          <div class="metric">
            <div class="metric-label">Payout latency</div>
            <div class="metric-value">&lt; 60 seconds</div>
            <div class="metric-note">Gift cards + cash apps, fraud-aware routing.</div>
          </div>
        </div>

        <div class="hero-actions">
          <button class="btn-primary">Request full investor brief (PDF)</button>
          <button class="btn-ghost">View risk model snapshot</button>
        </div>
        <p class="tagline">
          Built in the Ozarks, designed for transparent, auditable, and repeatable returns.
        </p>
      </div>

      <aside class="hero-right" aria-label="Risk and return snapshot">
        <div class="hero-right-header">
          <div>
            <div class="hero-right-title">Scenario model — launch cohort</div>
            <div style="font-size: 10px; color: var(--muted); margin-top: 2px;">
              Illustrative only — full tables available in the data room.
            </div>
          </div>
          <div class="hero-right-tag">Capped exposure</div>
        </div>

        <div class="hero-chart">
          <div class="hero-chart-grid"></div>
          <div class="hero-chart-content">
            <div class="hero-chart-row">
              <span>Investor capital at risk (modeled)</span>
              <strong>$50,000</strong>
            </div>
            <div class="hero-chart-row">
              <span>Hard loss ceiling (worst case)</span>
              <strong class="table-highlight">-35%</strong>
            </div>
            <div class="hero-chart-row">
              <span>Targeted upside (fast-learning)</span>
              <strong class="table-highlight">+40–80%</strong>
            </div>

            <div class="hero-chart-bars">
              <div class="hero-chart-bar">
                <div class="hero-chart-bar-fill.low"></div>
              </div>
              <div class="hero-chart-bar">
                <div class="hero-chart-bar-fill.mid"></div>
              </div>
              <div class="hero-chart-bar">
                <div class="hero-chart-bar-fill.high"></div>
              </div>
            </div>
            <div class="hero-chart-labels">
              <span>Worst-case</span>
              <span>Base case</span>
              <span>Fast-learning</span>
            </div>

            <p class="hero-footnote">
              All scenarios are pre-modeled using sweepstakes coin flows, bonus throttles,
              and payout ceilings. No “black box” volatility.
            </p>
          </div>
        </div>
      </aside>
    </section>

    <!-- WHY THIS EXISTS -->
    <section class="section">
      <div class="section-header">
        <div>
          <div class="section-kicker">Context</div>
          <h2 class="section-title">Why Ozark Casino exists</h2>
        </div>
        <span class="badge-soft">Operator-first, investor-fluent</span>
      </div>
      <div class="section-body">
        <p>
          The online casino space is crowded with high-burn, opaque operations that treat
          investor capital as fuel, not as a constrained resource. Ozark Casino is built
          from the opposite direction: every promotion, payout, and bonus is modeled
          against a hard ceiling before a single coin is given away.
        </p>
        <p>
          The engine is a sweepstakes model—players receive free coins, can optionally
          acquire more through compliant mechanisms, and can redeem winnings via instant,
          fraud-aware payout rails. The business is not about chasing whales; it’s about
          disciplined, repeatable unit economics and trust.
        </p>
      </div>
    </section>

    <!-- MODEL & RISK -->
    <section class="section">
      <div class="section-header">
        <div>
          <div class="section-kicker">Model</div>
          <h2 class="section-title">How the sweepstakes engine and risk ceiling work</h2>
        </div>
        <span class="badge">Capped-risk architecture</span>
      </div>

      <div class="two-col">
        <div>
          <p class="section-body">
            At the core is a simple rule: <strong>no promotion launches without a
            worst-case table.</strong> For each campaign, we model:
          </p>
          <ul class="list">
            <li><strong>Free coin outflow</strong> — maximum coins that can be granted.</li>
            <li><strong>Conversion bands</strong> — conservative, base, and aggressive
              assumptions.</li>
            <li><strong>Payout ceilings</strong> — maximum daily and weekly cash exposure.</li>
            <li><strong>Bonus throttles</strong> — automatic tightening if metrics drift.</li>
          </ul>
          <p class="section-body">
            The result is a sweepstakes casino that behaves more like a risk-controlled
            trading system than a “let’s see what happens” marketing budget.
          </p>
        </div>

        <div>
          <table class="table" aria-label="Illustrative risk snapshot">
            <thead>
              <tr>
                <th>Scenario</th>
                <th>Investor capital</th>
                <th>Modeled outcome</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td>Worst-case</td>
                <td>$50,000</td>
                <td class="table-highlight">-$17,500 (35% drawdown)</td>
              </tr>
              <tr>
                <td>Base case</td>
                <td>$50,000</td>
                <td class="table-highlight">+$22,500 (45% return)</td>
              </tr>
              <tr>
                <td>Fast-learning</td>
                <td>$50,000</td>
                <td class="table-highlight">+$40,000 (80% return)</td>
              </tr>
            </tbody>
          </table>
          <p class="tagline">
            Full spreadsheets, assumptions, and sensitivity analysis are available in the
            investor data room.
          </p>
        </div>
      </div>
    </section>

    <!-- GROWTH ENGINE -->
    <section class="section">
      <div class="section-header">
        <div>
          <div class="section-kicker">Growth</div>
          <h2 class="section-title">Influencer-driven, compounding acquisition</h2>
        </div>
        <span class="badge">Creator-aligned incentives</span>
      </div>

      <div class="section-body">
        <p>
          Instead of spraying ad spend across generic channels, Ozark Casino is designed
          to grow through a small, curated roster of creators who understand sweepstakes,
          trust, and long-term audience value. Each creator gets:
        </p>
      </div>

      <div class="section-grid">
        <div class="card">
          <div class="card-title">Transparent rev-share</div>
          <p>
            Creators see exactly how their traffic performs—deposits, redemptions, and
            retention—without guessing what the house is making.
          </p>
        </div>
        <div class="card">
          <div class="card-title">Instant payout hooks</div>
          <p>
            “Win on stream, cash out in under a minute” is a powerful, repeatable story
            for creators to tell.
          </p>
        </div>
        <div class="card">
          <div class="card-title">Compounding cohorts</div>
          <p>
            Each creator’s audience is treated as a cohort with its own risk and bonus
            profile, allowing precise tuning instead of blunt, site-wide changes.
          </p>
        </div>
      </div>
    </section>

    <!-- OPERATIONAL DISCIPLINE -->
    <section class="section">
      <div class="section-header">
        <div>
          <div class="section-kicker">Operations</div>
          <h2 class="section-title">Founder operating system and daily discipline</h2>
        </div>
        <span class="badge-soft">Documented, not improvised</span>
      </div>

      <div class="two-col">
        <div>
          <p class="section-body">
            Ozark Casino is built around a written operating manual, not vibes. Before
            launch, we lock in:
          </p>
          <ul class="list">
            <li><strong>Daily and weekly checklists</strong> for payouts, fraud review,
              and bonus adjustments.</li>
            <li><strong>Alert thresholds</strong> for payout spikes, conversion anomalies,
              and suspicious behavior.</li>
            <li><strong>Audit trails</strong> for every manual override and promotion
              change.</li>
          </ul>
          <p class="section-body">
            The goal is simple: any investor should be able to read the manual and see
            exactly how their capital is being protected and deployed.
          </p>
        </div>
        <div>
          <div class="card">
            <div class="card-title">Instant payout stack</div>
            <p>
              Payouts are routed through a mix of bulk gift cards and cash apps, with
              rules that:
            </p>
            <ul class="list">
              <li>Cap daily outflow per rail.</li>
              <li>Flag unusual patterns for manual review.</li>
              <li>Preserve player delight without opening fraud floodgates.</li>
            </ul>
          </div>
        </div>
      </div>
    </section>

    <!-- RISKS & HOW WE ADDRESS THEM -->
    <section class="section">
      <div class="section-header">
        <div>
          <div class="section-kicker">Risk</div>
          <h2 class="section-title">Key risks and how we treat them</h2>
        </div>
        <span class="badge-danger">Named, not ignored</span>
      </div>

      <div class="section-grid">
        <div class="card">
          <div class="card-title">Acquisition underperformance</div>
          <p>
            If creator traffic underperforms, we tighten bonuses, pause new campaigns,
            and preserve capital. The system is designed to fail slowly, not suddenly.
          </p>
        </div>
        <div class="card">
          <div class="card-title">Payout volatility</div>
          <p>
            Daily and weekly payout ceilings, plus dynamic bonus throttles, prevent a
            single outlier day from wrecking the month.
          </p>
        </div>
        <div class="card">
          <div class="card-title">Operational bottlenecks</div>
          <p>
            Workflows are designed to be automatable—AI-assisted review, templated
            responses, and clear handoffs—so the founder isn’t the only operator forever.
          </p>
        </div>
      </div>
    </section>

    <!-- CALL TO ACTION -->
    <section class="section">
      <div class="section-header">
        <div>
          <div class="section-kicker">Next steps</div>
          <h2 class="section-title">If this matches your risk appetite</h2>
        </div>
        <span class="badge">Early-stage, operator-led</span>
      </div>

      <div class="two-col">
        <div>
          <p class="section-body">
            Ozark Casino is currently assembling a small, aligned investor group to fund
            the initial sweepstakes bankroll, creator onboarding, and payout rails. The
            emphasis is on:
          </p>
          <ul class="list">
            <li>Clear, written expectations around risk and time horizon.</li>
            <li>Access to live dashboards and scenario models.</li>
            <li>Regular, plain-language updates—not just vanity metrics.</li>
          </ul>
        </div>
        <div>
          <p class="section-body">
            If you’d like to review the full deck, spreadsheets, and operating manual:
          </p>
          <ul class="list">
            <li>Request the <strong>Investor PDF + risk tables</strong>.</li>
            <li>Schedule a <strong>30-minute working session</strong> to walk through
              assumptions.</li>
            <li>Discuss <strong>check size, structure, and governance</strong>.</li>
          </ul>
          <button class="btn-primary" style="margin-top: 8px;">
            Request full materials
          </button>
        </div>
      </div>
    </section>

    <section>
      <p class="footnote">
        © 2026 Ozark Casino. This page is an illustrative investor overview and does not
        constitute a public offering or solicitation. All figures are hypothetical and
        subject to change as modeling is refined.
      </p>
    </section>
  </main>
</body>
</html>
