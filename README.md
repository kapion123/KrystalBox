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
      background: linear-gradient(135deg, #004488, #001f33);
      color: #fff;
    }
    header {
      text-align: center;
      padding: 40px 20px 20px;
    }
    header img {
      width: 120px;
      border-radius: 50%;
      margin-bottom: 15px;
      box-shadow: 0 0 10px rgba(0,0,0,0.3);
    }
    main {
      max-width: 1000px;
      margin: -30px auto 0;
      background: rgba(0,0,0,0.2);
      padding: 30px;
      border-radius: 12px;
    }
    h1, h2, p {
      color: #fff;
    }
    .section {
      margin-bottom: 30px;
    }
    .button {
      display: inline-block;
      background: #0077cc;
      color: white;
      padding: 12px 20px;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
      transition: background 0.3s;
    }
    .button:hover {
      background: #005fa3;
    }
    .team-container {
      display: flex;
      gap: 20px;
      flex-wrap: wrap;
      justify-content: center;
    }
    .team-member {
      background-color: rgba(255,255,255,0.05);
      padding: 20px;
      border-radius: 10px;
      text-align: center;
      width: 180px;
    }
    .team-member img {
      width: 100px;
      height: 100px;
      border-radius: 50%;
      margin-bottom: 10px;
      box-shadow: 0 0 8px rgba(0,0,0,0.4);
    }
    .reviews {
      margin-top: 20px;
    }
    .reviews form {
      display: flex;
      flex-direction: column;
      gap: 10px;
    }
    .reviews textarea {
      resize: vertical;
      padding: 10px;
      border-radius: 6px;
      border: none;
      font-family: inherit;
    }
    .reviews button {
      width: fit-content;
      background: #0077cc;
      color: white;
      border: none;
      padding: 10px 18px;
      border-radius: 5px;
      cursor: pointer;
    }
    .reviews button:hover {
      background: #005fa3;
    }
    footer {
      text-align: center;
      padding: 20px;
      font-size: 0.9em;
      color: #ccc;
      margin-top: 30px;
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
      <h2>Sklep serwera</h2>
      <p>Chcesz wspomóc rozwój serwera lub kupić specjalne przedmioty? Zapraszamy do naszego itemshopu!</p>
      <a href="https://vishop.pl/shop/21903" class="button" target="_blank">Przejdź do ItemShopu</a>
    </div>

    <div class="section">
      <h2>Kontakt & Społeczność</h2>
      <p>Masz pytania? Dołącz do naszego Discorda i porozmawiaj z administracją lub graczami!</p>
      <a href="https://discord.gg/bfHsnGQ23m" class="button" target="_blank">Dołącz na Discorda</a>
    </div>

    <div class="section">
      <h2>Zespół</h2>
      <div class="team-container">
        <div class="team-member">
          <img src="https://i.imgur.com/TFSEKXs.png" alt="Kapion123" />
          <h3>Kapion123</h3>
          <p>Właściciel</p>
        </div>
        <div class="team-member">
          <img src="https://i.imgur.com/m72FnPw.png" alt="Kreatywny" />
          <h3>Kreatywny</h3>
          <p>Administrator</p>
        </div>
      </div>
    </div>

    <div class="section reviews">
      <h2>Twoja opinia</h2>
      <form onsubmit="event.preventDefault(); alert('Dziękujemy za opinię!'); this.reset();">
        <textarea rows="4" placeholder="Napisz swoją opinię o serwerze..." required></textarea>
        <button type="submit">Wyślij opinię</button>
      </form>
    </div>

    <div class="section">
      <h2>IP Serwera Minecraft</h2>
      <p><strong>83.168.69.7:30010</strong></p>
    </div>
  </main>

  <footer>
    &copy; 2025 Krystalboxmc. Wszelkie prawa zastrzeżone.
  </footer>

</body>
</html>
