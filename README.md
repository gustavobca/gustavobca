<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Senior Backend Developer</title>

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">

  <style>
    :root {
      --bg: #0f172a;
      --card: #020617;
      --text: #e5e7eb;
      --muted: #9ca3af;
      --accent: #38bdf8;
      --border: #1e293b;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Inter', sans-serif;
    }

    body {
      background: linear-gradient(180deg, #020617, #0f172a);
      color: var(--text);
      min-height: 100vh;
      display: flex;
      justify-content: center;
      padding: 60px 20px;
    }

    .container {
      max-width: 900px;
      width: 100%;
    }

    header {
      margin-bottom: 50px;
    }

    header h1 {
      font-size: 2.6rem;
      font-weight: 700;
      letter-spacing: -1px;
    }

    header span {
      color: var(--accent);
    }

    header p {
      margin-top: 12px;
      font-size: 1.1rem;
      color: var(--muted);
      max-width: 650px;
      line-height: 1.6;
    }

    section {
      background: rgba(2, 6, 23, 0.7);
      border: 1px solid var(--border);
      border-radius: 14px;
      padding: 28px;
      margin-bottom: 28px;
    }

    section h2 {
      font-size: 1.4rem;
      margin-bottom: 18px;
      font-weight: 600;
    }

    .stack {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(140px, 1fr));
      gap: 14px;
    }

    .badge {
      background: #020617;
      border: 1px solid var(--border);
      border-radius: 10px;
      padding: 12px;
      text-align: center;
      font-size: 0.95rem;
      color: var(--text);
      transition: all 0.2s ease;
    }

    .badge:hover {
      border-color: var(--accent);
      color: var(--accent);
      transform: translateY(-2px);
    }

    ul {
      list-style: none;
    }

    li {
      margin-bottom: 12px;
      color: var(--muted);
      line-height: 1.6;
    }

    footer {
      margin-top: 40px;
      text-align: center;
      color: var(--muted);
      font-size: 0.9rem;
    }

    footer a {
      color: var(--accent);
      text-decoration: none;
      margin: 0 8px;
    }

    footer a:hover {
      text-decoration: underline;
    }
  </style>
</head>

<body>
  <div class="container">

    <header>
      <h1>Senior <span>Backend Developer</span></h1>
      <p>
        Focused on building scalable, high-performance backend systems with clean
        architecture, efficient code, and long-term maintainability in mind.
      </p>
    </header>

    <section>
      <h2>🧠 About Me</h2>
      <ul>
        <li>• Senior Software Developer specialized in backend systems</li>
        <li>• Strong focus on performance, scalability, and clean architecture</li>
        <li>• Experience designing reliable systems that scale gracefully</li>
      </ul>
    </section>

    <section>
      <h2>🛠️ Tech Stack</h2>
      <div class="stack">
        <div class="badge">C# / .NET 8</div>
        <div class="badge">Java</div>
        <div class="badge">Python</div>
        <div class="badge">C / C++</div>
        <div class="badge">Lua</div>
        <div class="badge">SQL Databases</div>
        <div class="badge">NoSQL Databases</div>
      </div>
    </section>

    <section>
      <h2>🎯 Interests</h2>
      <ul>
        <li>• High-performance and low-latency systems</li>
        <li>• Scalable backend architectures</li>
        <li>• Clean, maintainable, and well-tested codebases</li>
      </ul>
    </section>

    <footer>
      <p>
        <a href="#">LinkedIn</a> • https://www.linkedin.com/in/gustavovicentin/
      </p>
    </footer>

  </div>
</body>
</html>
