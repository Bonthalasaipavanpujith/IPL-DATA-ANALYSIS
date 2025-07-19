# IPL-DATA-ANALYSIS
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>IPL Data Analysis & Visualization</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      line-height: 1.6;
      background: #f9f9f9;
      padding: 30px;
      max-width: 900px;
      margin: auto;
      color: #333;
    }

    h1 {
      color: #2e86de;
      border-bottom: 2px solid #2e86de;
      padding-bottom: 10px;
    }

    h2 {
      color: #2e86de;
      margin-top: 40px;
    }

    code {
      background: #f4f4f4;
      padding: 2px 6px;
      border-radius: 4px;
      font-size: 0.95em;
    }

    pre {
      background: #272822;
      color: #f8f8f2;
      padding: 15px;
      border-radius: 6px;
      overflow-x: auto;
    }

    ul {
      list-style: disc inside;
    }

    .highlight {
      background: #dff9fb;
      padding: 10px;
      border-left: 4px solid #2e86de;
      margin: 15px 0;
    }

    img {
      max-width: 100%;
      height: auto;
      border-radius: 8px;
      margin: 10px 0;
    }

    footer {
      margin-top: 40px;
      font-size: 0.9em;
      color: #555;
    }
  </style>
</head>
<body>

  <h1>🏏 IPL Data Analysis & Visualization</h1>

  <p>This interactive Python project visualizes and analyzes Indian Premier League (IPL) data with charts and statistics using <strong>Matplotlib</strong>, <strong>Pandas</strong>, and <strong>NumPy</strong>.</p>

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
    <li>Team vs. team win comparison</li>
    <li>Player stats (e.g., Virat Kohli)</li>
    <li>Top wicket-takers</li>
    <li>Top Player of the Match awardees</li>
  </ul>

  <h2>📌 Requirements</h2>
  <p>Install dependencies:</p>
  <pre><code>pip install pandas numpy matplotlib</code></pre>

  <h2>📂 Input Files</h2>
  <div class="highlight">
    <strong>Required:</strong> Place <code>matches.csv</code> and <code>deliveries.csv</code> in the same folder as <code>main.py</code>.
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

  <h2>📷 Sample Visualizations</h2>
  <img src="images/matches_per_season.png" alt="Matches per Season Chart" />
  <img src="images/top_wickets.png" alt="Top Wicket Takers Chart" />

  <h2>👨‍💻 Author</h2>
  <p><strong>Bonthala Sai Pavan Pujith</strong></p>

  <footer>
    <p>📃 Licensed under the <strong>MIT License</strong>. Feel free to fork and contribute.</p>
  </footer>

</body>
</html>
