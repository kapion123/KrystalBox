<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Krystalboxmc – Serwer Minecraft</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      background: linear-gradient(to bottom, #004488, #001f33);
      color: white;
    }
    header {
      text-align: center;
      padding: 40px 20px 20px;
    }
    header img {
      width: 120px;
      border-radius: 50%;
      box-shadow: 0 0 10px rgba(0,0,0,0.3);
    }
    main {
      max-width: 1000px;
      margin: auto;
      padding: 30px;
    }
    .section {
      background-color: rgba(255, 255, 255, 0.05);
      padding: 20px;
      border-radius: 12px;
      margin-bottom: 30px;
    }
    h1, h2, h3 {
      color: #00aaff;
    }
    .button {
      display: inline-block;
      background: #0077cc;
      color: white;
      padding: 12px 20px;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
    }
    .button:hover {
      background: #005fa3;
    }
    .team-grid {
      display: flex;
      gap: 20px;
      flex-wrap: wrap;
    }
    .team-member {
      background: rgba(255,255,255,0.05);
      border-radius: 12px;
      padding: 15px;
      text-align: center;
      flex: 1;
      min-width: 150px;
    }
    .team-member img {
      width: 100px;
      border-radius: 50%;
      margin-bottom: 10px;
      border: 2px solid #00aaff;
    }
    .gallery-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
      gap: 15px;
    }
    .gallery-grid img {
      width: 100%;
      border-radius: 10px;
      border: 2px solid #00aaff;
    }
    input, textarea {
      width: 100%;
      padding: 10px;
      border-radius: 8px;
      border: none;
      margin-top: 10px;
    }
    footer {
      text-align: center;
      padding: 20px;
      font-size: 0.9em;
      color: #ccc;
      background: #001a2b;
    }
  </style>
</head>
<body>

  <header>
    <img src="https://i.imgur.com/yj0eTEx.png" alt="Logo serwera" />
    <h1>Krystalboxmc</h1>
    <p>Twój serwer Minecraft z pasją!</p>
  </header>

  <main>
    <div class="section">
      <h2>O nas</h2>
      <p>Krystalboxmc to społeczność graczy Minecraft, oferująca unikalne tryby gry, aktywną administrację i świetną zabawę. Dołącz do nas i zobacz sam, co przygotowaliśmy!</p>
    </div>

    <div class="section">
      <h2>Zespół</h2>
      <div class="team-grid">
        <div class="team-member">
          <img src="https://i.imgur.com/TFSEKXs.png" alt="Kapion123" />
          <h3>Kapion123</h3>
          <p>Właściciel</p>
        </div>
        <div class="team-member">
          <img src="https://i.imgur.com/m72FnPw.png" alt="Kreatywny" />
          <h3>Kreatywny</h3>
          <p>Właściciel</p>
        </div>
      </div>
    </div>

    <div class="section">
      <h2>Dlaczego warto grać u nas?</h2>
      <ul>
        <li>✅ Stabilny serwer 24/7</li>
        <li>✅ Aktywna administracja</li>
        <li>✅ Unikalne systemy i pluginy</li>
        <li>✅ Przyjazna społeczność</li>
      </ul>
    </div>

    <div class="section">
      <h2>Statystyki serwera Minecraft</h2>
      <p><strong>IP:</strong> <code>83.168.69.7:30010</code></p>
      <p><em>Status online będzie można dodać automatycznie w przyszłości przez API.</em></p>
    </div>

    <div class="section">
      <h2>Aktualności</h2>
      <p>🔥 Już niedługo nowy event z nagrodami! Śledź nasze ogłoszenia na Discordzie!</p>
    </div>

    <div class="section">
      <h2>Galeria zdjęć z serwera</h2>
      <div class="gallery-grid">
        <img src="" alt="screen1">
        <img src="" alt="screen2">
        <img src="" alt="screen3">
      </div>
    </div>

    <div class="section">
      <h2>Twoja opinia</h2>
      <p>Napisz, co sądzisz o naszym serwerze:</p>
      <form>
        <input type="text" placeholder="Nick z Minecrafta" required>
        <textarea rows="4" placeholder="Twoja opinia..." required></textarea>
        <button class="button" type="submit">Wyślij opinię</button>
      </form>
    </div>

    <div class="section">
      <h2>Kontakt & Społeczność</h2>
      <p>Masz pytania? Dołącz do naszego Discorda!</p>
      <a href="https://discord.gg/bfHsnGQ23m" class="button" target="_blank">Dołącz na Discorda</a>
    </div>

    <div class="section">
      <h2>Sklep serwera</h2>
      <p>Wspomóż nasz rozwój i kup specjalne przedmioty w naszym sklepie!</p>
      <a href="https://vishop.pl/shop/21903" class="button" target="_blank">Przejdź do ItemShopu</a>
    </div>
  </main>

  <footer>
    &copy; 2025 Krystalboxmc. Wszelkie prawa zastrzeżone.
  </footer>

</body>
</html>
