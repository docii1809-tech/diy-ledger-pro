
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>DIY Ledger Pro | Free Budget & Bookkeeping Tools</title>
  <meta name="description" content="Take control of your money with practical budgeting tools, income and expense trackers, and downloadable bookkeeping templates.">
  <meta name="theme-color" content="#12352b">
  <link rel="canonical" href="https://diyledgerpro.com/">
  <style>
    :root {
      --green: #12352b;
      --lime: #d7f36b;
      --cream: #f7f7f0;
      --ink: #1d2924;
      --muted: #65716a;
      --white: #fff;
    }
    * { box-sizing: border-box; }
    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      color: var(--ink);
      background: var(--cream);
      line-height: 1.6;
    }
    a { color: inherit; }
    header {
      background: var(--white);
      border-bottom: 1px solid #e5e9e3;
    }
    .nav {
      max-width: 1100px;
      margin: auto;
      padding: 18px 22px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 18px;
      flex-wrap: wrap;
    }
    .brand {
      font-size: 1.25rem;
      font-weight: 800;
      color: var(--green);
      text-decoration: none;
    }
    .brand span { color: #759522; }
    nav { display: flex; gap: 18px; flex-wrap: wrap; }
    nav a { text-decoration: none; font-size: .94rem; }
    .hero {
      background: var(--green);
      color: var(--white);
      padding: 76px 22px 82px;
    }
    .hero-inner, .section {
      max-width: 1100px;
      margin: auto;
    }
    .eyebrow {
      color: var(--lime);
      text-transform: uppercase;
      font-size: .78rem;
      font-weight: 700;
      letter-spacing: 2px;
    }
    h1 {
      max-width: 720px;
      font-size: clamp(2.4rem, 7vw, 4.5rem);
      line-height: 1.08;
      letter-spacing: -2px;
      margin: 18px 0;
    }
    .hero p {
      max-width: 620px;
      font-size: 1.1rem;
      color: #e1e9e2;
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
      border-radius: 9px;
      font-weight: 700;
      text-decoration: none;
      background: var(--lime);
      color: var(--green);
    }
    .button.secondary {
      background: transparent;
      color: white;
      border: 1px solid #91a99c;
    }
    .section { padding: 54px 22px; }
    .section h2 {
      color: var(--green);
      font-size: clamp(1.7rem, 4vw, 2.3rem);
      line-height: 1.2;
      margin: 0 0 10px;
    }
    .intro { color: var(--muted); max-width: 650px; }
    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 18px;
      margin-top: 28px;
    }
    .card {
      background: white;
      border: 1px solid #e5e9e3;
      border-radius: 15px;
      padding: 24px;
    }
    .card .symbol { font-size: 1.8rem; }
    .card h3 { margin: 12px 0 8px; color: var(--green); }
    .card p { color: var(--muted); font-size: .96rem; }
    .card a { font-weight: 700; color: #47651a; }
    .offer {
      background: #eaf0dc;
      border-radius: 18px;
      padding: 32px;
      margin-top: 26px;
    }
    footer {
      background: var(--green);
      color: white;
      padding: 30px 22px;
      text-align: center;
    }
    footer a { color: var(--lime); margin: 0 8px; }
    footer p { font-size: .9rem; }
    @media (max-width: 520px) {
      .hero { padding-top: 52px; }
      .nav { align-items: flex-start; }
      nav { gap: 12px; }
      .offer { padding: 23px; }
    }
  </style>
</head>
<body>
  <header>
    <div class="nav">
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
      <div class="hero-inner">
        <div class="eyebrow">Simple tools. Smarter money decisions.</div>
        <h1>Get your money organized. One step at a time.</h1>
        <p>Practical budget tools, easy-to-use ledgers, and downloadable templates to help you manage everyday finances and keep better records for your business.</p>
        <div class="actions">
          <a class="button" href="#tools">Explore Free Tools</a>
          <a class="button secondary" href="#downloads">Browse Downloads</a>
        </div>
      </div>
    </section>

    <section class="section" id="tools">
      <h2>Free tools to get you started</h2>
      <p class="intro">Useful, straightforward tools to help you understand where your money goes and plan what comes next.</p>
      <div class="cards">
        <article class="card">
          <div class="symbol" aria-hidden="true">📊</div>
          <h3>Monthly Budget Calculator</h3>
          <p>Compare monthly income and expenses to see what remains.</p>
          <a href="budget-calculator.html">Explore budget tool →</a>
        </article>
        <article class="card">
          <div class="symbol" aria-hidden="true">🧾</div>
          <h3>Income & Expense Ledger</h3>
          <p>Keep track of money coming in and going out with a simple ledger.</p>
          <a href="income-expense-ledger.html">Explore ledger →</a>
        </article>
        <article class="card">
          <div class="symbol" aria-hidden="true">🎯</div>
          <h3>Debt Payoff Calculator</h3>
          <p>Estimate how long debt repayment could take with your planned payments.</p>
          <a href="debt-payoff-calculator.html">Explore debt tool →</a>
        </article>
      </div>
    </section>

    <section class="section" id="downloads">
      <h2>Templates that make life easier</h2>
      <p class="intro">Spend less time building spreadsheets from scratch and more time using your records.</p>
      <div class="offer">
        <h3>Coming soon: The DIY Ledger Starter Bundle</h3>
        <p>A practical collection of budget worksheets, income and expense records, and monthly review pages. We'll add real previews and a secure checkout once the files are ready.</p>
        <a class="button" href="products.html">View digital downloads</a>
      </div>
    </section>

    <section class="section" id="guides">
      <h2>Learn as you go</h2>
      <p class="intro">Clear, practical guidance for everyday budgeting and small-business recordkeeping.</p>
      <div class="cards">
        <article class="card">
          <h3>Small Business Expense Tracking</h3>
          <p>Learn how to organize everyday business expenses and keep consistent records.</p>
          <a href="small-business-expense-tracker.html">Read the guide →</a>
        </article>
        <article class="card">
          <h3>Build a Monthly Budget</h3>
          <p>Learn a simple process for planning income, bills, savings, and spending.</p>
          <a href="monthly-budget-template.html">Read the guide →</a>
        </article>
      </div>
    </section>

    <section class="section">
      <h2>Simple, transparent, practical</h2>
      <p class="intro">DIY Ledger Pro provides tools and educational resources for organizing financial information. Our goal is to make everyday recordkeeping easier, whether you're managing a household budget or a small side business.</p>
    </section>
  </main>

  <footer>
    <strong>DIY Ledger Pro</strong>
    <p>
      <a href="about.html">About</a>
      <a href="contact.html">Contact</a>
      <a href="privacy.html">Privacy</a>
      <a href="terms.html">Terms</a>
      <a href="disclaimer.html">Disclaimer</a>
    </p>
    <p>Tools and educational information only; not financial, tax, or legal advice.</p>
    <p>© <span id="year"></span> DIY Ledger Pro</p>
  </footer>
  <script>
    document.getElementById("year").textContent = new Date().getFullYear();
  </script>
</body>
</html>
# diy-ledger-pro
