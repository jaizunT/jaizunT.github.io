<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Jason Trinh</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      max-width: 800px;
      margin: auto;
      padding: 20px;
    }
    details {
      margin-bottom: 1em;
    }
    summary {
      font-weight: bold;
      cursor: pointer;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 1em;
    }
    th, td {
      border: 1px solid #ccc;
      padding: 8px;
      text-align: left;
    }
    th {
      background-color: #f4f4f4;
    }
    a {
      color: #0645ad;
    }
  </style>
</head>
<body>
  <h1>Jason Trinh</h1>

  <h2>About Me</h2>
  <p>
    I'm a student at the University of California, Berkeley, majoring in Electrical Engineering and Computer Sciences (EECS). I'm passionate about a broad range of fields across computing and applied mathematics—including machine learning, computer architecture, optimization, and theoretical statistics. I enjoy building systems, solving technical challenges, and exploring how theory connects with real-world engineering.
  </p>
  <ul>
    <li><u>Education</u>: University of California, Berkeley</li>
    <li><u>Major</u>: Electrical Engineering and Computer Science (EECS)</li>
    <li><u>Grade</u>: 4.0</li>
    <li><u>Interested in</u>: Machine learning, computer architecture, optimization, and theoretical statistics</li>
    <li><u>How to reach me</u>: <a href="mailto:jasontrinh@berkeley.edu">jasontrinh@berkeley.edu</a></li>
  </ul>

  <h2>Coursework (UC Berkeley)</h2>
  <table>
    <tr><th>Course Code</th><th>Course Name</th><th>Grade</th></tr>
    <tr><td>EECS 16A</td><td>Designing Information Devices and Systems I</td><td>A</td></tr>
    <tr><td>CS 61A</td><td>The Structure and Interpretation of Computer Programs</td><td>A</td></tr>
    <tr><td>CS 61B</td><td>Data Structures</td><td>A</td></tr>
    <tr><td>CS 70</td><td>Discrete Mathematics and Probability Theory</td><td>A+</td></tr>
    <tr><td>EECS 126</td><td>Probability and Random Processes</td><td>A</td></tr>
    <tr><td>EECS 127</td><td>Optimization Models in Engineering</td><td>A</td></tr>
    <tr><td>CS 61C</td><td>Great Ideas in Computer Architecture (Machine Structures)</td><td></td></tr>
  </table>

  <h2>Connect with Me</h2>
  <p><a href="https://www.linkedin.com/in/jason-trinh-4590a8315">LinkedIn Profile</a></p>

  <h2>Resume</h2>
  <p><a href="https://raw.githubusercontent.com/jaizunT/jaizunT.github.io/main/Resume%207-25-27_img.jpg">View PDF version</a></p>
  <details>
    <summary>Click to view image</summary>
    <p align="center">
      <img src="https://raw.githubusercontent.com/jaizunT/jaizunT.github.io/main/Resume%207-25-27_img.jpg" alt="Resume" width="70%">
    </p>
  </details>

  <h2>Play My Game - Lights Off</h2>
  <p>I built a game you can try out — no installation needed beyond Java.</p>
  <p><a href="https://raw.githubusercontent.com/jaizunT/jaizunT.github.io/main/byow-game.jar">Download the game (.jar)</a></p>
  <p>To run:</p>
  <ol>
    <li>Make sure you have Java installed (JDK or JRE).</li>
    <li>Download the <code>.jar</code> file from the link above.</li>
    <li>Open a terminal and navigate to the download location.</li>
    <li>Run: <code>java -jar byow-game.jar</code></li>
  </ol>
  <details>
    <summary>Click to view game screenshot</summary>
    <p align="center">
      <a href="https://raw.githubusercontent.com/jaizunT/jaizunT.github.io/main/game_preview.png" target="_blank">
        <img src="https://raw.githubusercontent.com/jaizunT/jaizunT.github.io/main/game_preview.png" alt="Lights Off Game Screenshot" width="80%">
      </a>
    </p>
  </details>

  <details>
    <summary>How to Play</summary>
    <ul>
      <li>Explore the world</li>
      <li>Find keys scattered across the map and place them in "the zone"</li>
      <li>Enter the portal to win</li>
      <li>Collect orbs to use abilities</li>
      <li>Avoid "the entity"</li>
    </ul>
    <ul>
      <li><code>n</code>: Start new game</li>
      <li><code>l</code>: Load game</li>
      <li><code>q</code>: Quit</li>
    </ul>
    <ul>
      <li>Move: <code>w</code>, <code>a</code>, <code>s</code>, <code>d</code></li>
      <li><code>j</code>: Pick up / place key</li>
      <li><code>k</code>: Dash</li>
      <li><code>m</code>: Teleport</li>
    </ul>
    <ul>
      <li><code>z</code>: Toggle lights</li>
      <li><code>x</code>: Show path</li>
      <li><code>v</code>: Save</li>
      <li><code>l</code>: Load</li>
      <li><code>r</code>: Restart</li>
      <li><code>:</code> then <code>q</code>: Quit</li>
    </ul>
    <ul>
      <li>HUD: Facing, keys, orbs, cursor tile</li>
    </ul>
  </details>

  <h2>Visualizing Quantum Systems</h2>
  <p>Here's a visualization of an electron's probability density evolving in a 2D lattice structure. The simulation was computed by evolving the wavefunction over time using a Hamiltonian matrix, leveraging linear algebra techniques to capture quantum behavior on a discrete spatial grid.</p>
  <details>
    <summary>Click to view quantum probability density GIF</summary>
    <p align="center">
      <a href="https://raw.githubusercontent.com/jaizunT/jaizunT.github.io/main/electron.gif" target="_blank">
        <img src="https://raw.githubusercontent.com/jaizunT/jaizunT.github.io/main/electron.gif" alt="Electron Density in 2D Lattice" width="70%">
      </a>
    </p>
  </details>

  <h2>Speech Classifier Visualization</h2>
  <p>This section showcases visualizations used in a speech classifier. The first plot is a spectrogram representing time-frequency features of spoken audio. The second plot shows clustered embeddings of the processed signals.</p>
  <details>
    <summary>Click to view spectrogram and clustering plots</summary>
    <p align="center">
      <a href="https://raw.githubusercontent.com/jaizunT/jaizunT.github.io/main/spectrogram.png" target="_blank">
        <img src="https://raw.githubusercontent.com/jaizunT/jaizunT.github.io/main/spectrogram.png" alt="Spectrogram" width="50%">
      </a>
    </p>
    <p align="center">
      <a href="https://raw.githubusercontent.com/jaizunT/jaizunT.github.io/main/cluster.png" target="_blank">
        <img src="https://raw.githubusercontent.com/jaizunT/jaizunT.github.io/main/cluster.png" alt="Embedding Clusters" width="50%">
      </a>
    </p>
  </details>
</body>
</html>
