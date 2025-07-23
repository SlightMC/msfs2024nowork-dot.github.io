
    .ip-box {
      background: #1c1c1c;
      padding: 15px;
      margin-top: 10px;
      border: 2px dashed #ffffff60;
      display: inline-block;
      font-size: 1.5rem;
      border-radius: 8px;
      cursor: pointer;
    }
    .container {
      padding: 30px;
      max-width: 1100px;
      margin: auto;
    }
    section {
      margin-bottom: 40px;
    }
    h2 {
      font-size: 2rem;
      color: #e91e63;
      margin-bottom: 15px;
    }
    ul {
      padding-left: 20px;
    }
    ul li {
      margin-bottom: 10px;
    }
    footer {
      background: #111;
      text-align: center;
      padding: 20px;
      color: #aaa;
    }
    .btn {
      background-color: #e91e63;
      color: white;
      padding: 10px 20px;
      border: none;
      font-weight: bold;
      border-radius: 5px;
      cursor: pointer;
      transition: background 0.3s;
    }
    .btn:hover {
      background-color: #c2185b;
    }
    @media (max-width: 768px) {
      header h1 {
        font-size: 2rem;
      }
      .ip-box {
        font-size: 1.2rem;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Welcome to SlightMC</h1>
    <p>Your Ultimate Minecraft LifeSteal SMP Server</p>
    <div class="ip-box" onclick="copyIP()">SlightMC.aternos.me</div>
    <p style="margin-top: 10px; font-size: 0.9rem;">Click to copy IP</p>
  </header>

  <div class="container">
    <section>
      <h2>🌍 What is LifeSteal?</h2>
      <p>LifeSteal is a Minecraft survival multiplayer mode where you steal hearts from other players when you kill them. The more you fight, the stronger you get. But beware—if you lose all your hearts, you're temporarily banned!</p>
    </section>

    <section>
      <h2>🚀 How to Join</h2>
      <ul>
        <li>Open Minecraft Java Edition</li>
        <li>Click on “Multiplayer”</li>
        <li>Add Server → Name: SlightMC</li>
        <li>Server Address: <strong>SlightMC.aternos.me</strong></li>
        <li>Click “Join” and start surviving!</li>
      </ul>
      <button class="btn" onclick="copyIP()">Copy Server IP</button>
    </section>

    <section>
      <h2>🛠 Server Features</h2>
      <ul>
        <li>❤️ LifeSteal system with heart stealing mechanics</li>
        <li>🛡 Grief protection & anti-cheat</li>
        <li>⚔ Friendly PvP with high-stakes combat</li>
        <li>👑 Active community and events</li>
        <li>📅 Server runs 24/7 via Aternos queue</li>
      </ul>
    </section>

    <section>
      <h2>📜 Rules</h2>
      <ul>
        <li>No hacking or cheating</li>
        <li>No griefing protected bases</li>
        <li>Respect other players</li>
        <li>No spamming or advertising</li>
        <li>Breaking rules = permanent ban</li>
      </ul>
    </section>

    <section>
      <h2>🎮 Discord & Community</h2>
      <p>Join our community for updates, events, and voice chats!</p>
      <a class="btn" href="https://discord.gg/your-link" target="_blank">Join Discord</a>
    </section>
  </div>

  <footer>
    <p>© 2025 SlightMC. All rights reserved. | Server IP: SlightMC.aternos.me</p>
  </footer>

  <script>
    function copyIP() {
      navigator.clipboard.writeText("SlightMC.aternos.me").then(function() {
        alert("IP copied to clipboard!");
      });
    }
  </script>

</body>
</html>
