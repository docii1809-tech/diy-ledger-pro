
</body>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>DIY Ledger Pro | Free Budget and Bookkeeping Tools</title>
  <meta name="description" content="Organize your money with free budgeting tools, income and expense tracking, and practical downloadable bookkeeping templates.">
  <meta name="theme-color" content="#12352b">
  <link rel="canonical" href="https://diyledgerpro.com/">
  <style>
    :root {
      --green: #12352b;
      --green-light: #214c3e;
      --lime: #d7f36b;
      --cream: #f7f7f0;
      --ink: #1d2924;
      --muted: #65716a;
      --white: #ffffff;
      --border: #e2e8e1;
    }

    * { box-sizing: border-box; }

    html { scroll-behavior: smooth; }

    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      color: var(--ink);
      background: var(--cream);
      line-height: 1.65;
    }

    a { color: inherit; }

    a:focus-visible, button:focus-visible {
      outline: 3px solid #8aab30;
      outline-offset: 3px;
    }

    .container {
      width: min(1100px, 100% - 40px);
      margin-inline: auto;
    }

    header {
      background: var(--white);
      border-bottom: 1px solid var(--border);
    }

    .nav {
      min-height: 76px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 20px;
      flex-wrap: wrap;
      padding-block: 15px;
    }

    .brand {
      font-size: 1.35rem;
      font-weight: 800;
      color: var(--green);
      text-decoration: none;
      letter-spacing: -0.5px;
    }

    .brand span { color: #759522; }

    nav {
      display: flex;
      flex-wrap: wrap;
      gap: 18px;
    }

    nav a {
      text-decoration: none;
      font-size: 0.94rem;
      font-weight: 600;
    }

    nav a:hover { color: #58751c; }

    .hero {
      background:
        radial-gradient(ellipse at 90% 10%, #315b43 0%, transparent 45%),
        var(--green);
      color: var(--white);
      padding: 78px 0 86px;
    }

    .eyebrow {
      display: inline-block;
      color: var(--lime);
      font-size: 0.78rem;
      font-weight: 800;
      letter-spacing: 2px;
      text-transform: uppercase;
    }

    h1 {
      max-width: 760px;
      margin: 20px 0;
      font-size: clamp(2.5rem, 7vw, 4.6rem);
      line-height: 1.08;
      letter-spacing: -2px;
    }

    .hero p {
      max-width: 650px;
      color: #e2ebe4;
      font-size: 1.12rem;
    }

    .actions {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
      margin-top: 28px;
    }

    .button {
      display: inline-block;
      padding: 13px 19px;
      border: 2px solid var(--lime);
      border-radius: 9px;
      background: var(--lime);
      color: var(--green);
      font-weight: 800;
      text-decoration: none;
      text-align: center;
    }

    .button:hover { filter: brightness(0.95); }

    .button.secondary {
      background: transparent;
      color: var(--white);
      border-color: #8aa295;
    }

    .trust-strip {
      background: var(--white);
      border-bottom: 1px solid var(--border);
    }

    .trust-items {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 18px;
      padding-block: 20px;
      text-align: center;
      font-size: 0.92rem;
      font-weight: 700;
      color: var(--green);
    }

    .section { padding-block: 64px; }

    .section-heading {
      max-width: 700px;
      margin-bottom: 28px;
    }

    .section h2 {
      margin: 0 0 10px;
      color: var(--green);
      font-size: clamp(1.8rem, 4vw, 2.5rem);
      line-height: 1.2;
      letter-spacing: -0.7px;
    }

    .intro {
      margin: 0;
      color: var(--muted);
      max-width: 680px;
    }

    .cards {
      display: grid;
      grid-template-columns: repeat(3, minmax(0, 1fr));
      gap: 18px;
    }

    .card {
      display: flex;
      flex-direction: column;
      align-items: flex-start;
      background: var(--white);
      border: 1px solid var(--border);
      border-radius: 15px;
      padding: 25px;
      min-width: 0;
    }

    .symbol {
      display: grid;
      place-items: center;
      width: 50px;
      height: 50px;
      border-radius: 12px;
      background: #edf3df;
      font-size: 1.65rem;
    }

    .card h3 {
      margin: 17px 0 8px;
      color: var(--green);
      font-size: 1.15rem;
      line-height: 1.35;
    }

    .card p {
      margin: 0 0 18px;
      color: var(--muted);
      font-size: 0.96rem;
    }

    .card a {
      margin-top: auto;
      color: #47651a;
      font-weight: 800;
      text-decoration: none;
    }

    .card a:hover { text-decoration: underline; }

    .downloads {
      background: #edf1e5;
    }

    .offer {
      display: grid;
      grid-template-columns: 1.5fr 1fr;
      gap: 28px;
      align-items: center;
      background: var(--white);
      border: 1px solid var(--border);
      border-radius: 18px;
      padding: 32px;
    }

    .offer h3 {
      margin: 0 0 10px;
      color: var(--green);
      font-size: 1.5rem;
      line-height: 1.3;
    }

    .offer p { color: var(--muted); }

    .offer-note {
      background: var(--cream);
      border-radius: 12px;
      padding: 20px;
    }

    .offer-note strong {
      display: block;
      color: var(--green);
      margin-bottom: 8px;
    }

    .offer-note p {
      font-size: 0.92rem;
      margin-bottom: 0;
    }

    .steps {
      display: grid;
      grid-template-columns: repeat(3, minmax(0, 1fr));
      gap: 20px;
      margin-top: 28px;
    }

    .step {
      border-top: 3px solid #a6c64d;
      padding-top: 17px;
    }

    .step-number {
      color: #65851d;
      font-weight: 800;
      font-size: 0.85rem;
      letter-spacing: 1px;
    }

    .step h3 { color: var(--green); }

    .step p { color: var(--muted); }

    .faq {
      max-width: 780px;
    }

    details {
      background: var(--white);
      border: 1px solid var(--border);
      border-radius: 10px;
      padding: 17px 19px;
      margin-top: 12px;
    }

    summary {
      color: var(--green);
      font-weight: 800;
      cursor: pointer;
    }

    details p { color: var(--muted); }

    footer {
      background: var(--green);
      color: var(--white);
      padding: 38px 0;
    }

    .footer-inner {
      display: flex;
      justify-content: space-between;
      gap: 24px;
      flex-wrap: wrap;
    }

    footer p {
      color: #dce7df;
      font-size: 0.9rem;
    }

    .footer-links {
      display: flex;
      flex-wrap: wrap;
      gap: 15px;
      align-content: flex-start;
    }

    .footer-links a {
      color: var(--lime);
      font-size: 0.92rem;
    }

    .copyright {
      padding-top: 20px;
      border-top: 1px solid #426354;
      margin-top: 25px;
    }

    @media (max-width: 760px) {
      .cards { grid-template-columns: repeat(2, minmax(0, 1fr)); }
      .offer { grid-template-columns: 1fr; }
      .steps { grid-template-columns: 1fr; }
      .hero { padding: 58px 0 64px; }
    }

    @media (max-width: 520px) {
      .container { width: min(100% - 30px, 1100px); }
      .nav { align-items: flex-start; }
      nav { gap: 12px; }
      .cards { grid-template-columns: 1fr; }
      .trust-items { grid-template-columns: 1fr; gap: 8px; }
      .section { padding-block: 45px; }
      .offer { padding: 23px; }
      h1 { letter-spacing: -1px; }
    }
  </style>
</head>

<body>
  <header>
    <div class="container nav">
      <a class="brand" href="index.html">DIY Ledger<span>Pro</span></a>
      <nav aria-label="Main navigation">
        <a href="#tools">Free Tools</a>
        <a href="#downloads">Downloads</a>
        <a href="#guides">Money Guides</a>
      </nav>
    </div>
  </header>

  <main>
    <section class="hero">
      <div class="container">
        <span class="eyebrow">Simple tools. Smarter money decisions.</span>
        <h1>Get your money organized. One step at a time.</h1>
        <p>
          Take control of everyday budgeting and small-business
          recordkeeping with straightforward tools and practical templates.
          Start free, get organized, and build better money habits.
        </p>
        <div class="actions">
          <a class="button" href="#tools">Explore Free Tools</a>
          <a class="button secondary" href="#downloads">Browse Downloads</a>
        </div>
      </div>
    </section>

    <div class="trust-strip">
      <div class="container trust-items">
        <div>✓ Practical and easy to use</div>
        <div>✓ Free tools to get started</div>
        <div>✓ Built for everyday recordkeeping</div>
      </div>
    </div>

    <section class="container section" id="tools">
      <div class="section-heading">
        <h2>Free tools to get you started</h2>
        <p class="intro">
          Understand your numbers with simple tools designed to make
          budgeting and tracking less stressful.
        </p>
      </div>

      <div class="cards">
        <article class="card">
          <div class="symbol" aria-hidden="true">📊</div>
          <h3>Monthly Budget Calculator</h3>
          <p>
            Compare monthly income and expenses to estimate how much
            money remains after your planned spending.
          </p>
          <a href="budget-calculator.html">Explore budget tool →</a>
        </article>

        <article class="card">
          <div class="symbol" aria-hidden="true">🧾</div>
          <h3>Income &amp; Expense Ledger</h3>
          <p>
            Organize money coming in and going out with a simple
            income and expense record.
          </p>
          <a href="income-expense-ledger.html">Explore ledger →</a>
        </article>

        <article class="card">
          <div class="symbol" aria-hidden="true">🎯</div>
          <h3>Debt Payoff Calculator</h3>
          <p>
            Estimate a possible repayment timeline using your balance,
            interest rate, and planned monthly payment.
          </p>
          <a href="debt-payoff-calculator.html">Explore debt tool →</a>
        </article>
      </div>
    </section>

    <section class="downloads" id="downloads">
      <div class="container section">
        <div class="section-heading">
          <h2>Templates that make life easier</h2>
          <p class="intro">
            Spend less time building spreadsheets from scratch and
            more time keeping useful, organized records.
          </p>
        </div>

        <div class="offer">
          <div>
            <span class="eyebrow" style="color:#65851d;">Digital downloads</span>
            <h3>The DIY Ledger Starter Bundle</h3>
            <p>
              Our planned starter collection will bring together
              practical budget worksheets, income and expense records,
              and monthly review pages.
            </p>
            <a class="button" href="products.html">Explore the Store</a>
          </div>

          <div class="offer-note">
            <strong>Coming soon</strong>
            <p>
              We are preparing the first downloadable products.
              Checkout will be added after the files are ready.
              No purchase is available from this page yet.
            </p>
          </div>
        </div>
      </div>
    </section>

    <section class="container section" id="guides">
      <div class="section-heading">
        <h2>Learn as you go</h2>
        <p class="intro">
          Straightforward educational guides for household budgeting
          and small-business recordkeeping.
        </p>
      </div>

      <div class="cards">
        <article class="card">
          <div class="symbol" aria-hidden="true">📁</div>
          <h3>Small-Business Expense Tracking</h3>
          <p>
            Learn how to group expenses, keep receipts, and maintain
            a consistent record of business spending.
          </p>
          <a href="small-business-expense-tracker.html">Read the guide →</a>
        </article>

        <article class="card">
          <div class="symbol" aria-hidden="true">🗓️</div>
          <h3>How to Build a Monthly Budget</h3>
          <p>
            Learn a repeatable way to plan income, bills, savings,
            and everyday spending.
          </p>
          <a href="monthly-budget-template.html">Read the guide →</a>
        </article>

        <article class="card">
          <div class="symbol" aria-hidden="true">📌</div>
          <h3>Why Consistent Records Matter</h3>
          <p>
            Explore simple habits that make it easier to review
            your finances and prepare organized records.
          </p>
          <a href="about.html">About our approach →</a>
        </article>
      </div>
    </section>

    <section class="container section">
      <div class="section-heading">
        <h2>A simpler way to stay organized</h2>
        <p class="intro">
          <strong>1. Start with a free tool.</strong>
          Get a clearer picture of your income, spending, or repayment goals.
        </p>
        <p class="intro">
          <strong>2. Build a routine.</strong>
          Review your numbers regularly and keep your records consistent.
        </p>
        <p class="intro">
          <strong>3. Use templates when you're ready.</strong>
          Downloadable products will help you maintain records without
          starting every worksheet from scratch.
        </p>
      </div>
    </section>

    <section class="container section">
      <div class="section-heading">
        <h2>Frequently asked questions</h2>
      </div>

      <div class="faq">
        <details>
          <summary>Are the tools free?</summary>
          <p>
            The site is being developed with free tools as the starting
            point. Any paid products will be clearly labeled before purchase.
          </p>
        </details>

        <details>
          <summary>What kinds of downloads will be available?</summary>
          <p>
            Planned products include budget worksheets, income and expense
            ledgers, and small-business recordkeeping templates.
          </p>
        </details>

        <details>
          <summary>Can this site replace an accountant or financial adviser?</summary>
          <p>
            No. The tools are for general organization and education.
            They do not replace individualized financial, tax, accounting,
            or legal advice.
          </p>
        </details>
      </div>
    </section>
  </main>

  <footer>
    <div class="container">
      <div class="footer-inner">
        <div>
          <a class="brand" href="index.html" style="color:white;">
            DIY Ledger<span>Pro</span>
          </a>
          <p>Simple tools for better everyday recordkeeping.</p>
        </div>

        <div class="footer-links">
          <a href="about.html">About</a>
          <a href="contact.html">Contact</a>
          <a href="privacy.html">Privacy</a>
          <a href="terms.html">Terms</a>
          <a href="disclaimer.html">Disclaimer</a>
        </div>
      </div>

      <div class="copyright">
        <p>
          Information and tools are for general educational purposes only
          and are not financial, tax, accounting, or legal advice.
        </p>
        <p>© <span id="year"></span> DIY Ledger Pro</p>
      </div>
    </div>
  </footer>

  <script>
    document.getElementById("year").textContent =
      new Date().getFullYear();
  </script>
</body>
</html>

