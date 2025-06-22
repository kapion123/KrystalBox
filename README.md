<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Krystalboxmc – Serwer Minecraft</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      background-color: #0b1a3d; /* ciemny niebieski */
      color: #d0d9ff; /* jasny niebieski / biały */
    }
    header {
      background: linear-gradient(135deg, #3a69d8, #0a2a72);
      color: #e6ecff;
      padding: 40px 20px 20px;
      text-align: center;
      box-shadow: 0 2px 10px rgba(0, 0, 50, 0.7);
    }
    header img {
      width: 120px;
      border-radius: 50%;
      margin-bottom: 15px;
      box-shadow: 0 0 15px rgba(58, 105, 216, 0.7);
    }
    main {
      max-width: 900px;
      margin: -30px auto 0;
      background: #13275c; /* ciemniejszy niebieski */
      padding: 30px;
      box-shadow: 0 5px 20px rgba(0, 0, 50, 0.5);
      border-radius: 12px;
    }
    h1, h2 {
      color: #b0c7ff; /* jaśniejszy niebieski */
    }
    .section {
      margin-bottom: 30px;
    }
    .button {
      display: inline-block;
      background: #3a69d8;
      color: white;
      padding: 12px 20px;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
      transition: background 0.3s;
      box-shadow: 0 0 8px rgba(58, 105, 216, 0.7);
    }
    .button:hover {
      background: #274ea6;
      box-shadow: 0 0 12px rgba(39, 78, 166, 0.9);
    }
    footer {
      text-align: center;
      padding: 20px;
      font-size: 0.9em;
      color: #99aaff;
      margin-top: 30px;
      background: #0a1f4a;
      box-shadow: inset 0 1px 3px rgba(0,0,0,0.5);
      border-radius: 0 0 12px 12px;
    }
    img[alt="Status serwera Discord"] {
      box-shadow: 0 0 15px rgba(58, 105, 216, 0.7);
      border-radius: 12px;
      max-width: 100%;
      height: auto;
      display: block;
      margin-top: 10px;
    }

    /* Nowe style dla zespołu */
    .team-container {
      display: flex;
      gap: 30px;
      justify-content: center;
      flex-wrap: wrap;
    }
    .team-member {
      background: #1d367d;
      border-radius: 12px;
      padding: 15px;
      width: 140px;
      text-align: center;
      box-shadow: 0 0 12px rgba(58, 105, 216, 0.6);
      transition: transform 0.3s;
    }
    .team-member:hover {
      transform: scale(1.05);
      box-shadow: 0 0 18px rgba(90, 150, 255, 0.9);
    }
    .team-member img {
      width: 120px;
      height: 120px;
      object-fit: cover;
      border-radius: 12px;
      margin-bottom: 10px;
      box-shadow: 0 0 12px rgba(58, 105, 216, 0.8);
    }
    .team-member-name {
      font-weight: bold;
      color: #c1d1ff;
      font-size: 1.1em;
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
      <h2>Statystyki Discord</h2>
      <img src="https://discord.com/api/guilds/1370865731218047208/widget.png?style=banner2" alt="Status serwera Discord" />
    </div>

    <div class="section">
      <h2>Zespół</h2>
      <div class="team-container">
        <div class="team-member">
          <img src="https://i.imgur.com/TFSEKXs.png" alt="Kapion123" />
          <div class="team-member-name">Kapion123</div>
        </div>
        <div class="team-member">
          <img src="https://minotar.net/avatar/Kreatywny/120" alt="Kreatywny" />
          <div class="team-member-name">Kreatywny</div>
        </div>
      </div>
    </div>

    <div class="section">
      <h2>O nas</h2>
      <p>Krystalboxmc to społeczność graczy Minecraft, oferująca unikalne tryby gry, aktywną administrację i świetną zabawę. Dołącz do nas i zobacz sam, co przygotowaliśmy!</p>
    </div>

    <div class="section">
      <h2>Sklep serwera</h2>
      <p>Chcesz wspomóc rozwój serwera lub kupić specjalne przedmioty? Zapraszamy do naszego itemshopu!</p>
      <a href="https://vishop.pl/shop/21903" class="button" target="_blank" rel="noopener noreferrer">Przejdź do ItemShopu</a>
    </div>

    <div class="section">
      <h2>Kontakt & Społeczność</h2>
      <p>Masz pytania? Dołącz do naszego Discorda i porozmawiaj z administracją lub graczami!</p>
      <a href="https://discord.gg/bfHsnGQ23m" class="button" target="_blank" rel="noopener noreferrer">Dołącz na Discorda</a>
    </div>
  </main>

  <footer>
    &copy; 2025 Krystalboxmc. Wszelkie prawa zastrzeżone.
  </footer>

</body>
</html>
