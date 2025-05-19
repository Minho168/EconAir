# EconAir<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>EconAIR - Economic Administration & International Relations</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet" />
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Inter', sans-serif;
    }
    body {
      background-color: #f5f7fa;
      color: #333;
    }
    header {
      background-color: #0a1f44;
      color: white;
      padding: 2rem 1rem;
      text-align: center;
    }
    .logo {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 1rem;
      margin-bottom: 0.75rem;
    }
    .logo img {
      width: 50px;
      height: 50px;
    }
    header h1 {
      font-size: 2.5rem;
      font-weight: 800;
    }
    header p {
      font-size: 1.2rem;
      opacity: 0.9;
    }
    nav {
      background: #102a72;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      padding: 1rem;
      font-size: 1rem;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0.5rem 1.5rem;
      font-weight: 600;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #ffcc00;
    }
    section {
      padding: 3rem 1rem;
      max-width: 1000px;
      margin: auto;
    }
    h2 {
      color: #0a1f44;
      margin-bottom: 1.5rem;
      font-size: 1.8rem;
    }
    ul {
      list-style: disc;
      padding-left: 1.5rem;
      line-height: 1.8;
    }
    .article-card {
      background-color: white;
      padding: 1.5rem;
      margin-bottom: 1.5rem;
      border-radius: 0.75rem;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.05);
    }
    .article-card h3 {
      margin-bottom: 0.5rem;
      color: #102a72;
    }
    .article-card .meta {
      font-size: 0.9rem;
      color: #666;
      margin-bottom: 0.75rem;
    }
    .article-card p {
      margin-bottom: 0.5rem;
    }
    .article-card a {
      text-decoration: none;
      color: #0a1f44;
      font-weight: 600;
    }
    .article-card a:hover {
      color: #ff6600;
    }
    footer {
      background: #0a1f44;
      color: white;
      text-align: center;
      padding: 1.5rem;
      margin-top: 3rem;
      font-size: 0.9rem;
    }
    @media (max-width: 768px) {
      header h1 {
        font-size: 1.8rem;
      }
      header p {
        font-size: 1rem;
      }
      nav {
        flex-direction: column;
        align-items: center;
      }
      nav a {
        margin: 0.5rem 0;
      }
      section {
        padding: 2rem 1rem;
      }
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">
      <img src="logo.png" alt="EconAIR Logo" />
      <h1>EconAIR</h1>
    </div>
    <p>Connecting Policy, Economics, and Global Affairs</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#articles">Articles</a>
    <a href="#resources">Resources</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About EconAIR</h2>
    <p>
      EconAIR is a forward-thinking platform focused on Economic Administration and International Relations. Our mission is to bridge the gap between policy and practice by offering thought leadership, deep-dive analysis, and a collaborative hub for learners and experts alike.
    </p>
  </section>

  <section id="articles">
    <h2>Articles & Analysis</h2>
    <div class="article-card">
      <h3>Public Financial Management in Southeast Asia</h3>
      <div class="meta">By Sean Liho | May 2025</div>
      <p>
        Exploring fiscal frameworks, challenges, and innovations in emerging markets through the lens of Southeast Asian economies.
      </p>
      <a href="#">Read More →</a>
    </div>
    <div class="article-card">
      <h3>Understanding ASEAN Trade Agreements</h3>
      <div class="meta">By Sean Liho | May 2025</div>
      <p>
        A comprehensive guide to regional integration, economic cooperation, and trade dynamics within the ASEAN community.
      </p>
      <a href="#">Read More →</a>
    </div>
    <div class="article-card">
      <h3>Case Study: Cambodia's Economic Reforms</h3>
      <div class="meta">By Sean Liho | May 2025</div>
      <p>
        Analyzing Cambodia’s policy shifts, investment climate improvements, and economic growth trajectory over the last decade.
      </p>
      <a href="#">Read More →</a>
    </div>
    <div class="article-card">
      <h3>Digital Economy and Development</h3>
      <div class="meta">By Sean Liho | May 2025</div>
      <p>
        Examining how digital transformation influences governance, public service delivery, and inclusive economic growth.
      </p>
      <a href="#">Read More →</a>
    </div>
    <div class="article-card">
      <h3>Geopolitics of Global Trade</h3>
      <div class="meta">By Sean Liho | May 2025</div>
      <p>
        Insight into how international diplomacy and strategic alliances shape global trade patterns and economic policies.
      </p>
      <a href="#">Read More →</a>
    </div>
  </section>

  <section id="resources">
    <h2>Learning Resources</h2>
    <ul>
      <li><strong>Study Guides:</strong> Simplified overviews and summaries on key economic topics.</li>
      <li><strong>Glossary of IR Terms:</strong> Understand the essential language of diplomacy and global relations.</li>
      <li><strong>Downloadables:</strong> Presentations, charts, and cheat sheets for quick learning.</li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>
      We welcome collaboration and feedback. Reach us at <a href="mailto:seanliho11@gmail.com">seanliho11@gmail.com</a>
    </p>
  </section>

  <footer>
    <p>&copy; 2025 EconAIR. All rights reserved.</p>
  </footer>
</body>
</html>
