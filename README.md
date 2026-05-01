<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Privacy Policy — Sindh Prison Act 2019</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600;700&family=Source+Serif+4:ital,wght@0,300;0,400;0,600;1,300&display=swap" rel="stylesheet">
<style>
  :root {
    --blue: #1565C0;
    --blue-dark: #0D47A1;
    --blue-light: #E3F2FD;
    --gold: #F9A825;
    --text: #1A237E;
    --body: #263238;
    --muted: #546E7A;
    --bg: #F8FAFE;
    --white: #FFFFFF;
    --border: #BBDEFB;
  }

  * { margin: 0; padding: 0; box-sizing: border-box; }

  body {
    font-family: 'Source Serif 4', Georgia, serif;
    background: var(--bg);
    color: var(--body);
    line-height: 1.8;
    min-height: 100vh;
  }

  /* Header */
  header {
    background: linear-gradient(135deg, var(--blue-dark) 0%, var(--blue) 60%, #1976D2 100%);
    color: white;
    padding: 0;
    position: relative;
    overflow: hidden;
  }

  header::before {
    content: '';
    position: absolute;
    top: -60px; right: -60px;
    width: 300px; height: 300px;
    background: rgba(255,255,255,0.04);
    border-radius: 50%;
  }

  header::after {
    content: '';
    position: absolute;
    bottom: -40px; left: -40px;
    width: 200px; height: 200px;
    background: rgba(255,255,255,0.03);
    border-radius: 50%;
  }

  .header-inner {
    max-width: 860px;
    margin: 0 auto;
    padding: 48px 32px 40px;
    position: relative;
    z-index: 1;
  }

  .badge {
    display: inline-flex;
    align-items: center;
    gap: 8px;
    background: rgba(255,255,255,0.12);
    border: 1px solid rgba(255,255,255,0.2);
    border-radius: 40px;
    padding: 6px 16px;
    font-size: 11px;
    letter-spacing: 1.5px;
    text-transform: uppercase;
    margin-bottom: 20px;
    font-family: 'Source Serif 4', serif;
    font-weight: 600;
  }

  .badge::before {
    content: '🏛️';
    font-size: 14px;
  }

  header h1 {
    font-family: 'Playfair Display', serif;
    font-size: clamp(26px, 5vw, 38px);
    font-weight: 700;
    letter-spacing: -0.5px;
    margin-bottom: 10px;
    line-height: 1.2;
  }

  header h1 span {
    color: var(--gold);
  }

  .header-sub {
    font-size: 14px;
    opacity: 0.80;
    font-style: italic;
    margin-top: 8px;
  }

  .header-meta {
    display: flex;
    gap: 24px;
    margin-top: 28px;
    flex-wrap: wrap;
  }

  .meta-item {
    display: flex;
    align-items: center;
    gap: 8px;
    font-size: 12px;
    opacity: 0.85;
    background: rgba(255,255,255,0.10);
    padding: 6px 14px;
    border-radius: 6px;
    border: 1px solid rgba(255,255,255,0.15);
  }

  /* Main content */
  main {
    max-width: 860px;
    margin: 0 auto;
    padding: 48px 32px 80px;
  }

  /* Summary box */
  .summary-box {
    background: var(--blue-light);
    border-left: 4px solid var(--blue);
    border-radius: 0 10px 10px 0;
    padding: 20px 24px;
    margin-bottom: 40px;
    font-size: 14px;
    color: var(--text);
    line-height: 1.7;
  }

  .summary-box strong {
    display: block;
    font-size: 13px;
    letter-spacing: 0.8px;
    text-transform: uppercase;
    color: var(--blue);
    margin-bottom: 8px;
    font-family: 'Source Serif 4', serif;
  }

  /* Sections */
  .section {
    margin-bottom: 40px;
    background: var(--white);
    border-radius: 12px;
    border: 1px solid var(--border);
    overflow: hidden;
    box-shadow: 0 2px 12px rgba(21,101,192,0.06);
  }

  .section-header {
    background: linear-gradient(90deg, var(--blue) 0%, #1976D2 100%);
    padding: 14px 24px;
    display: flex;
    align-items: center;
    gap: 12px;
  }

  .section-num {
    background: rgba(255,255,255,0.20);
    color: white;
    width: 28px; height: 28px;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 12px;
    font-weight: 700;
    flex-shrink: 0;
  }

  .section-header h2 {
    font-family: 'Playfair Display', serif;
    font-size: 17px;
    font-weight: 600;
    color: white;
    letter-spacing: 0.2px;
  }

  .section-body {
    padding: 22px 24px;
  }

  .section-body p {
    font-size: 14.5px;
    color: var(--body);
    margin-bottom: 14px;
    line-height: 1.85;
  }

  .section-body p:last-child { margin-bottom: 0; }

  /* Highlight list */
  .highlight-list {
    list-style: none;
    margin: 12px 0;
  }

  .highlight-list li {
    display: flex;
    align-items: flex-start;
    gap: 10px;
    font-size: 14px;
    padding: 8px 0;
    border-bottom: 1px solid #F0F4FF;
    color: var(--body);
    line-height: 1.6;
  }

  .highlight-list li:last-child { border-bottom: none; }

  .highlight-list li::before {
    content: '✓';
    color: var(--blue);
    font-weight: 700;
    font-size: 13px;
    margin-top: 2px;
    flex-shrink: 0;
    background: var(--blue-light);
    width: 20px; height: 20px;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  /* Info grid */
  .info-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 12px;
    margin: 8px 0;
  }

  .info-card {
    background: var(--blue-light);
    border-radius: 8px;
    padding: 14px 16px;
    border: 1px solid var(--border);
  }

  .info-card .label {
    font-size: 10.5px;
    text-transform: uppercase;
    letter-spacing: 1px;
    color: var(--blue);
    font-weight: 700;
    margin-bottom: 4px;
    font-family: 'Source Serif 4', serif;
  }

  .info-card .value {
    font-size: 13.5px;
    color: var(--text);
    font-weight: 600;
  }

  /* Contact box */
  .contact-box {
    background: linear-gradient(135deg, var(--blue-dark), var(--blue));
    border-radius: 12px;
    padding: 28px 28px;
    color: white;
    margin-top: 40px;
    text-align: center;
  }

  .contact-box h3 {
    font-family: 'Playfair Display', serif;
    font-size: 20px;
    margin-bottom: 8px;
    color: var(--gold);
  }

  .contact-box p {
    font-size: 14px;
    opacity: 0.88;
    margin-bottom: 16px;
    line-height: 1.7;
  }

  .contact-box a {
    display: inline-block;
    background: white;
    color: var(--blue);
    padding: 10px 28px;
    border-radius: 6px;
    text-decoration: none;
    font-size: 13px;
    font-weight: 700;
    letter-spacing: 0.3px;
    transition: opacity 0.2s;
  }

  .contact-box a:hover { opacity: 0.9; }

  /* Footer */
  footer {
    background: var(--blue-dark);
    color: rgba(255,255,255,0.7);
    text-align: center;
    padding: 20px;
    font-size: 12px;
    line-height: 1.8;
  }

  footer strong { color: white; }

  @media (max-width: 600px) {
    .header-inner, main { padding-left: 20px; padding-right: 20px; }
    .info-grid { grid-template-columns: 1fr; }
    header h1 { font-size: 24px; }
  }
</style>
</head>
<body>

<header>
  <div class="header-inner">
    <div class="badge">Government of Sindh</div>
    <h1>Privacy Policy<br><span>Sindh Prison Act 2019</span></h1>
    <p class="header-sub">Sindh Prisons & Correctional Service — Mobile Application</p>
    <div class="header-meta">
      <div class="meta-item">📅 Effective: April 2026</div>
      <div class="meta-item">🔄 Version 2.1.0</div>
      <div class="meta-item">📱 Android App</div>
    </div>
  </div>
</header>

<main>

  <div class="summary-box">
    <strong>Summary</strong>
    The Sindh Prison Act 2019 app is a <strong>100% offline reference tool</strong> for Sindh Prisons & Corrections Service staff.
    This app does <strong>not collect, store, or share any personal data</strong>.
    All data remains on your device only.
  </div>

  <div class="section">
    <div class="section-header">
      <div class="section-num">1</div>
      <h2>About This Application</h2>
    </div>
    <div class="section-body">
      <p>
        The <strong>Sindh Prison Act 2019</strong> app is an official reference application developed for
        Sindh Prisons & Corrections Service (SPCS), Government of Sindh. It provides offline access
        to the Sindh Prisons Act 2019, Rules 2019, Dietary Regulations, Schedules, and Affirmation Roll.
      </p>
      <div class="info-grid">
        <div class="info-card">
          <div class="label">Developer</div>
          <div class="value">M. Jawaid Phull</div>
        </div>
        <div class="info-card">
          <div class="label">Organization</div>
          <div class="value">SPCS, Govt. of Sindh</div>
        </div>
        <div class="info-card">
          <div class="label">App Version</div>
          <div class="value">2.1.0 (Build 7)</div>
        </div>
        <div class="info-card">
          <div class="label">Platform</div>
          <div class="value">Android</div>
        </div>
      </div>
    </div>
  </div>

  <div class="section">
    <div class="section-header">
      <div class="section-num">2</div>
      <h2>Information We Do NOT Collect</h2>
    </div>
    <div class="section-body">
      <p>This app does not collect any personal information. The following data is <strong>never collected</strong>:</p>
      <ul class="highlight-list">
        <li>Personal identification (name, CNIC, email, phone number)</li>
        <li>Device identifiers or hardware information</li>
        <li>Location data or GPS coordinates</li>
        <li>Usage analytics or behavior tracking</li>
        <li>Search queries or browsing history</li>
        <li>Camera, microphone, or contacts access</li>
        <li>Financial or payment information</li>
        <li>Any data transmitted to external servers</li>
      </ul>
    </div>
  </div>

  <div class="section">
    <div class="section-header">
      <div class="section-num">3</div>
      <h2>Data Stored Locally on Your Device</h2>
    </div>
    <div class="section-body">
      <p>The following data is stored <strong>only on your device</strong> using Android SharedPreferences and is never transmitted anywhere:</p>
      <ul class="highlight-list">
        <li>Bookmarked rules and Act chapters (stored as rule IDs)</li>
        <li>Highlighted rules with color preferences</li>
        <li>Dark mode preference (on/off)</li>
        <li>Font size preference</li>
        <li>App settings and display preferences</li>
      </ul>
      <p>
        You can clear all locally stored data at any time by clearing the app data from your
        Android device's Settings → Apps → Sindh Prison Act 2019 → Clear Data.
      </p>
    </div>
  </div>

  <div class="section">
    <div class="section-header">
      <div class="section-num">4</div>
      <h2>Internet & Permissions</h2>
    </div>
    <div class="section-body">
      <p>
        This app operates <strong>100% offline</strong>. No internet connection is required or used
        during normal operation.
      </p>
      <p>
        The only permissions this app may request are:
      </p>
      <ul class="highlight-list">
        <li><strong>Storage permission</strong> — Only to save exported PDF files to your device's Downloads folder</li>
        <li><strong>No other permissions</strong> are requested or required</li>
      </ul>
      <p>
        When sharing content via WhatsApp or exporting PDFs, the app uses Android's built-in
        sharing mechanism. No data is sent to our servers.
      </p>
    </div>
  </div>

  <div class="section">
    <div class="section-header">
      <div class="section-num">5</div>
      <h2>Third-Party Services</h2>
    </div>
    <div class="section-body">
      <p>
        This app does <strong>not</strong> use any third-party analytics, advertising networks,
        crash reporting services, or external APIs.
      </p>
      <ul class="highlight-list">
        <li>No Google Analytics or Firebase</li>
        <li>No Facebook SDK or social tracking</li>
        <li>No advertisements or ad networks</li>
        <li>No crash reporting to external servers</li>
        <li>No cloud sync or backup services</li>
      </ul>
      <p>
        The app uses the following open-source Flutter packages purely for local functionality:
        PDF generation (printing), file sharing (share_plus), and local storage (shared_preferences).
        None of these transmit data externally.
      </p>
    </div>
  </div>

  <div class="section">
    <div class="section-header">
      <div class="section-num">6</div>
      <h2>Children's Privacy</h2>
    </div>
    <div class="section-body">
      <p>
        This application is intended for use by <strong>Sindh Prisons & Corrections Service
        staff and legal professionals</strong>. It is not directed at children under the age of 13.
        Since no personal data is collected by this app, there are no special provisions required
        for children's data protection beyond our standard policy of collecting no data whatsoever.
      </p>
    </div>
  </div>

  <div class="section">
    <div class="section-header">
      <div class="section-num">7</div>
      <h2>Data Security</h2>
    </div>
    <div class="section-body">
      <p>
        Since this app does not collect or transmit any personal data, there is minimal
        security risk. All preferences and bookmarks stored locally on your device are
        protected by Android's built-in app sandboxing security.
      </p>
      <p>
        The legal content (rules, regulations, act chapters) bundled with the app is
        official public-domain government material from the Government of Sindh Gazette.
      </p>
    </div>
  </div>

  <div class="section">
    <div class="section-header">
      <div class="section-num">8</div>
      <h2>Changes to This Policy</h2>
    </div>
    <div class="section-body">
      <p>
        We may update this Privacy Policy if the app's functionality changes. Any updates
        will be reflected in the app's Play Store listing and in the updated date shown
        at the top of this page.
      </p>
      <p>
        Continued use of the application after changes to this policy constitutes acceptance
        of the revised policy. We encourage users to review this policy periodically.
      </p>
    </div>
  </div>

  <div class="contact-box">
    <h3>Questions or Concerns?</h3>
    <p>
      For any questions about this Privacy Policy or the Sindh Prison Act 2019 application,
      please contact the IT Department of Sindh Prisons & Corrections Service.
    </p>
    <a href="mailto:mjavedphull1990@gmail.com">mjavedphull1990@gmail.com</a>
  </div>

</main>

<footer>
  <strong>Sindh Prison Act 2019</strong> — Sindh Prisons & Corrections Service, Government of Sindh<br>
  Developed by M. Jawaid Phull, Junior Prison Officer — IT Department<br>
  Privacy Policy last updated: April 2026 | Version 2.1.0
</footer>

</body>
</html>
