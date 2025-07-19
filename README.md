<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>IPL Data Analysis Project</title>
  <style>
    :root {
      --main-color: #2e86de;
      --secondary-color: #dff9fb;
      --text-color: #333;
      --bg-color: #f9f9f9;
      --card-color: #fff;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      background-color: var(--bg-color);
      color: var(--text-color);
    }

    .container {
      max-width: 1100px;
      margin: auto;
      padding: 30px 20px;
    }

    header {
      background-color: var(--main-color);
      color: white;
      padding: 40px 20px;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }

    .preview {
      background: var(--card-color);
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.05);
      border-radius: 12px;
      padding: 20px;
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      gap: 20px;
      margin-top: -60px;
    }

    .preview img {
      max-width: 300px;
      border-radius: 10px;
      width: 100%;
    }

    .preview-content {
      flex: 1;
    }

    .preview-content h2 {
      color: var(--main-color);
      margin-top: 0;
    }

    h2 {
      color: var(--main-color);
      margin-top: 40px;
    }

    ul {
      list-style-type: disc;
      padding-left: 20px;
    }

    pre {
      background: #272822;
      color: #f8f8f2;
      padding: 15px;
      border-radius: 6px;
      overflow-x: auto;
    }

    code {
      background-color: #f4f4f4;
      padding: 3px 5px;
      border-radius: 3px;
    }

    .highlight {
      background-color: var(--secondary-color);
      border-left: 5px solid var(--main-color);
      padding: 10px 15px;
      margin: 20px 0;
    }

    footer {
      text-align: center;
      font-size: 0.9rem;
      margin-top: 50px;
      padding-top: 20px;
      border-top: 1px solid #ddd;
    }

    @media (max-width: 768px) {
      .preview {
        flex-direction: column;
        text-align: center;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>🏏 IPL Data Analysis & Visualization</h1>
    <p>Explore the Indian Premier League with Python and Data Science</p>
  </header>

  <div class="container">

    <div class="preview">
      <img src="images/matches_per_season.png" alt="IPL Preview Chart" />
      <div class="preview-content">
        <h2>Project Overview</h2>
        <p>This Python project uses IPL match data to create insightful visualizations like match trends, team stats, win percentages, player performances, and more.</p>
      </div>
    </div>

    <h2>📁 Project Structure</h2>
    <pre>
ipl-data-analysis/
├── main.py
├── deliveries.csv
├── matches.csv
└── README.html
    </pre>

    <h2>🧠 Features</h2>
    <ul>
      <li>Matches played per season (2008–2020)</li>
      <li>Total matches and wins by each team</li>
      <li>Win percentage calculation</li>
      <li>Compare two teams by wins</li>
      <li>Analyze player stats (e.g., Virat Kohli)</li>
      <li>Top 10 wicket-takers</li>
      <li>Top Player of the Match award winners</li>
    </ul>

    <h2>📌 Requirements</h2>
    <pre><code>pip install pandas numpy matplotlib</code></pre>

    <h2>📂 Input Files</h2>
    <div class="highlight">
      Required files:
      <ul>
        <li><code>matches.csv</code> — Match-level IPL data</li>
        <li><code>deliveries.csv</code> — Ball-by-ball delivery data</li>
      </ul>
      Place them in the same directory as <code>main.py</code>.
    </div>

    <h2>▶️ How to Run</h2>
    <pre><code>python main.py</code></pre>

    <h2>🧭 Menu Options</h2>
    <ul>
      <li>1. Matches per Season</li>
      <li>2. Total Matches Played by Each Team</li>
      <li>3. Total Wins by Each Team</li>
      <li>4. Win Percentage by Each Team</li>
      <li>5. Comparison Between Two Teams</li>
      <li>6. Player Stats</li>
      <li>7. Most Wickets</li>
      <li>8. Most Player of the Match Awards</li>
      <li>9. Exit</li>
    </ul>

    <h2>📷 More Visualizations</h2>
    <img src="images/top_wickets.png" alt="Top Wicket Takers" />
    <img src="images/mom_awards.png" alt="Player of the Match Winners" />

    <h2>👨‍💻 Author</h2>
    <p><strong>Bonthala Sai Pavan Pujith</strong></p>

    <footer>
      <p>📃 Licensed under the <strong>MIT License</strong> | Designed for learning and exploration</p>
    </footer>
  </div>

</body>
</html>

