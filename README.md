# FinEase.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Aditya Kharkhande - Portfolio</title>
  <style>
    body { font-family: 'Segoe UI', sans-serif; margin: 0; padding: 0; background: #f0f2f5; }
    header {
      background: linear-gradient(135deg, #1f2937, #4b5563);
      color: white;
      padding: 70px 20px;
      text-align: center;
      position: relative;
      overflow: hidden;
    }
    header::after {
      content: "";
      position: absolute;
      top: 0; left: 0;
      width: 100%; height: 100%;
      background: radial-gradient(circle at top right, rgba(255,255,255,0.15), transparent 50%);
      pointer-events: none;
    }
    h1 { margin: 0; font-size: 2.8rem; letter-spacing: 1px; }
    p.subtitle { margin-top: 10px; font-size: 1.1rem; opacity: 0.9; }

    .section {
      padding: 25px; max-width: 900px; margin: auto; background: white;
      margin-top: 30px; border-radius: 15px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.08);
      transition: transform 0.2s ease, box-shadow 0.2s ease;
    }
    .section:hover {
      transform: translateY(-4px);
      box-shadow: 0 8px 20px rgba(0,0,0,0.12);
    }

    h2 { color: #1f2937; margin-bottom: 15px; font-size: 1.6rem; position: relative; }
    h2::after {
      content: "";
      position: absolute;
      bottom: -5px; left: 0;
      width: 50px; height: 3px;
      background: #4b5563;
      border-radius: 2px;
    }

    ul { line-height: 1.8; padding-left: 20px; }

    .skills span {
      background: #e5e7eb;
      padding: 8px 15px;
      border-radius: 25px;
      margin: 6px;
      display: inline-block;
      font-size: 0.9rem;
      transition: background 0.2s;
    }
    .skills span:hover { background: #d1d5db; }

    /* Add smooth fade-in animation */
    .section { animation: fadeIn 0.8s ease; }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(10px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>
  <header>
    <h1>Aditya Kharkhande</h1>
    <p>CA Final Student | GST & Accounting Services | Financial Support Consultant</p>
  </header>

  <div class="section">
    <h2>About Me</h2>
    <p>I am a CA Final student and a service provider specializing in GST coordination, basic accounting, documentation management, and financial process support. With a strong academic background in commerce and ongoing Chartered Accountancy training, I aim to offer reliable, organized, and professional support to individuals and small businesses.</p>
  </div>

  <div class="section">
    <h2>Education</h2>
    <ul>
      <li><strong>CA Final (Appearing)</strong> – ICAI</li>
      <li><strong>CA Intermediate</strong> – ICAI</li>
      <li><strong>CA Foundation</strong> – ICAI</li>
      <li><strong>B.Com</strong> – Indira College of Arts, Commerce & Science</li>
      <li><strong>HSC</strong> – Jai Hind Junior College</li>
      <li><strong>SSC</strong> – Infant Jesus High School</li>
    </ul>
  </div>

  <div class="section">
    <h2>Skills</h2>
    <div class="skills">
      <span>Accounting</span>
      <span>GST Documentation</span>
      <span>Bookkeeping</span>
      <span>Invoice Preparation</span>
      <span>Excel Management</span>
      <span>Financial Coordination</span>
      <span>Compliance Support</span>
      <span>Client Communication</span>
    </div>
  </div>

  <div class="section">
    <h2>Services I Offer</h2>
    <ul>
      <li>GST Filing Coordination & Documentation</li>
      <li>Basic Accounting & Bookkeeping Support</li>
      <li>Invoice Creation & Financial Document Preparation</li>
      <li>ITR Filing Assistance (Document Preparation Only)</li>
      <li>Vendor–Client Middleman/Coordination Support</li>
      <li>Excel Templates for Billing, Expense Tracking & Reports</li>
    </ul>
  </div>

  <div class="section">
    <h2>Contact</h2>
    <p>Email: adi.kharkande1610@gmail.com</p>
    <p>Phone: +91 7249826401</p>
  </div>
</body>
</html>

