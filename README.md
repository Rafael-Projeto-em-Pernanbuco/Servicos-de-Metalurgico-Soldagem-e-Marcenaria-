
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Serviços de Metalurgia, Soldagem e Marcenaria</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f5faff;
      color: #001f3f;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #001f3f;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background-color: #0074D9;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }
    section {
      padding: 20px;
    }
    .services {
      background-color: #E0F7FA;
      padding: 20px;
      border-radius: 10px;
      margin-top: 20px;
    }
    .services h2, .contact h2 {
      color: #0074D9;
    }
    .map-container {
      margin-top: 20px;
    }
    footer {
      background-color: #001f3f;
      color: white;
      text-align: center;
      padding: 10px;
    }
    .chat-icons {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 10px;
      margin-top: 20px;
    }
    .chat-icons a {
      text-decoration: none;
      color: white;
      background-color: #0074D9;
      padding: 10px 15px;
      border-radius: 5px;
      transition: background-color 0.3s;
    }
    .chat-icons a:hover {
      background-color: #005fa3;
    }
    form input[type="email"] {
      padding: 10px;
      width: 250px;
      margin-right: 10px;
    }
    form input[type="submit"] {
      padding: 10px 20px;
      background-color: #001f3f;
      color: white;
      border: none;
      cursor: pointer;
    }
  </style>
</head>
<body>

  <header>
    <h1>Serviços de Metalurgia, Soldagem e Marcenaria</h1>
    <p>Rua Maj. Bizarrias N°</p>
  </header>

  <nav>
    <a href="#servicos">Serviços</a>
    <a href="#contato">Contato</a>
    <a href="#localizacao">Localização</a>
  </nav>

  <!-- Google Translate -->
  <div id="google_translate_element" style="float: right; margin: 10px;"></div>
  <script type="text/javascript">
    function googleTranslateElementInit() {
      new google.translate.TranslateElement({ pageLanguage: 'pt' }, 'google_translate_element');
    }
  </script>
  <script type="text/javascript" src="//translate.google.com/translate_a/element.js?cb=googleTranslateElementInit"></script>

  <section id="servicos" class="services">
    <h2>Nossos Serviços</h2>
    <ul>
      <li>Soldagem MIG/MAG - R$ 100,00</li>
      <li>Soldagem TIG - R$ 120,00</li>
      <li>Conserto de Portões - R$ 150,00</li>
      <li>Fabricação de Grades - R$ 200,00</li>
      <li>Montagem de Móveis - R$ 80,00</li>
      <li>Marcenaria Sob Medida - Sob consulta</li>
    </ul>
  </section>

  <section id="contato" class="contact">
    <h2>Contato</h2>
    <p>Cadastre seu e-mail para receber orçamentos e promoções:</p>
    <form action="#" method="post">
      <input type="email" name="email" placeholder="Digite seu e-mail" required>
      <input type="submit" value="Cadastrar">
    </form>

    <div class="chat-icons">
      <a href="https://wa.me/5587981732937" target="_blank">WhatsApp</a>
      <a href="https://www.instagram.com/SEUUSUARIO" target="_blank">Instagram</a>
      <a href="https://www.kwai.com/@SEUUSUARIO" target="_blank">Kwai</a>
      <a href="https://twitter.com/SEUUSUARIO" target="_blank">Twitter</a>
      <a href="https://facebook.com/SEUUSUARIO" target="_blank">Facebook</a>
      <a href="https://t.me/SEUUSUARIO" target="_blank">Telegram</a>
      <a href="mailto:contato@seudominio.com">Atendimento Online</a>
    </div>
  </section>

  <section id="localizacao" class="map-container">
    <h2>Onde Estamos</h2>
    <iframe
      src="https://www.google.com/maps?q=Rua+Maj.+Bizarrias N°124 Bairro Popular Nova Exu-PE&output=embed"
      width="100%" height="300" style="border:0;" allowfullscreen=""
      loading="lazy"></iframe>
  </section>

  <footer>
    <p>&copy; 2025 - Todos os direitos reservados</p>
  </footer>

</body>
</html>
