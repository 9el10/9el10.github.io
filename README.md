<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>YUE's Playground</title>
  <link href="https://fonts.googleapis.com/css2?family=Fira+Code&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      font-family: 'Fira Code', monospace;
      box-sizing: border-box;
    }
    body {
      background: linear-gradient(135deg, #0f0f0f, #1e1e1e);
      color: #eee;
      padding: 2rem;
    }
    .center {
      text-align: center;
      margin-bottom: 3rem;
    }
    h1 {
      font-size: 2.8rem;
      color: #66ff99;
      margin-bottom: 0.5rem;
    }
    .typing {
      font-size: 1.4rem;
      color: #00ffcc;
      white-space: nowrap;
      overflow: hidden;
      border-right: 3px solid;
      width: 0;
      animation: typing 4s steps(40, end) forwards, blink 1s step-end infinite;
    }
    @keyframes typing {
      from { width: 0 }
      to { width: 100% }
    }
    @keyframes blink {
      50% { border-color: transparent }
    }
    .card {
      background: #1f1f1f;
      border-radius: 16px;
      padding: 1.5rem;
      margin: 1rem auto;
      max-width: 600px;
      box-shadow: 0 0 16px #00ffcc55;
    }
    .card h2 {
      color: #ffdd57;
      margin-bottom: 0.5rem;
    }
    .card p {
      font-size: 1rem;
      line-height: 1.6;
    }
    footer {
      text-align: center;
      font-size: 0.9rem;
      margin-top: 4rem;
      color: #888;
    }
  </style>
</head>
<body>
  <div class="center">
    <h1>Hi, I'm YUE 👋</h1>
    <div class="typing">I build motorized MIDI faders, Arduino projects & more!</div>
  </div>

  <div class="card">
    <h2>🎛 Current Projects</h2>
    <p>
      Building a motorized fader system using Arduino Uno + Leonardo, with PID control and MIDI integration.<br>
      Reverse engineering GrandMA2 SysEx messages into usable MIDI CC signals.<br>
      Designing smooth touch-sensitive automation hardware.
    </p>
  </div>

  <div class="card">
    <h2>🧰 Tools I Use</h2>
    <p>
      Arduino • Python • CapacitiveSensor • Control-Surface • KiCad • MIDI-OX • loopMIDI • nRF52840
    </p>
  </div>

  <div class="card">
    <h2>🌈 Fun Facts</h2>
    <p>
      🧪 Sometimes 10MΩ makes the difference between magic and noise.<br>
      🎧 I believe motorized faders should glide like butter.<br>
      🔌 My faders know when you touch them—literally.
    </p>
  </div>

  <footer>
    Built with 🧡 by YUE (9el10) | Hosted on GitHub Pages
  </footer>
</body>
</html>
