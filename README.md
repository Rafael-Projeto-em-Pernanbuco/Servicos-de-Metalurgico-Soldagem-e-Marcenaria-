<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Serviços Metalúrgicos, Soldagem e Marcenaria</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #ccc; /* cinza claro */
      color: #000;
    }
    header {
      background-color: #b30000; /* vermelho escuro */
      color: orange;
      padding: 20px;
      text-align: center;
    }
    nav {
      background-color: #333; /* cinza escuro */
      text-align: center;
      padding: 10px;
    }
    nav a {
      color: orange;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 20px;
    }
    .services {
      background-color: #eee;
      border-radius: 10px;
      padding: 20px;
      margin: 20px 0;
    }
    .services h2, .contact h2 {
      color: #b30000;
    }
    .services ul {
      list-style-type: square;
    }
    .services li {
      color: #000;
      margin-bottom: 8px;
    }
    .map-container {
      margin-top: 20px;
    }
    footer {
      background-color: #b30000;
      color: orange;
      text-align: center;
      padding: 10px;
    }
    .chat-icons {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 10px;
      margin-top: 20px;
    }
    .chat-icons a {
      text-decoration: none;
      color: white;
      background-color: #444;
      padding: 10px 15px;
      border-radius: 5px;
      transition: 0.3s;
    }
    .chat-icons a:hover {
      background-color: #000;
    }
    form input[type="email"] {
      padding: 10px;
      width: 250px;
      margin-right: 10px;
    }
    form input[type="submit"] {
      padding: 10px 20px;
      background-color: #b30000;
      color: orange;
      border: none;
      cursor: pointer;
    }
    #google_translate_element {
      text-align: right;
      margin: 10px 20px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Serviços Metalúrgicos, Soldagem e Marcenaria</h1>
    <p>Rua Maj. Bizarrias Nº 124, Bairro Popular - Nova Exu, PE</p>
  </header>

  <nav>
    <a href="#servicos">Serviços</a>
    <a href="#contato">Contato</a>
    <a href="#localizacao">Localização</a>
  </nav>

  <!-- Google Tradutor -->
  <div id="google_translate_element"></div>
  <script type="text/javascript">
    function googleTranslateElementInit() {
      new google.translate.TranslateElement({ pageLanguage: 'pt' }, 'google_translate_element');
    }
  </script>
  <script type="text/javascript" src="//translate.google.com/translate_a/element.js?cb=googleTranslateElementInit"></script>

  <section id="servicos" class="services">
    <h2>Lista de Serviços</h2>
    <ul>
      <li>Soldagem MIG/MAG - R$ 100,00</li>
      <li>Soldagem TIG - R$ 120,00</li>
      <li>Soldagem Elétrica - R$ 90,00</li>
      <li>Soldagem Mix - R$ 130,00</li>
      <li>Conserto de Portões e Grades - R$ 150,00</li>
      <li>Fabricação de Estruturas Metálicas - Sob Consulta</li>
      <li>Montagem de Móveis Planejados - R$ 80,00</li>
      <li>Marcenaria sob medida - A partir de R$ 200,00</li>
    </ul>
  </section>

  <section id="contato" class="contact">
    <h2>Cadastre seu E-mail</h2>
    <p>Receba orçamentos e promoções diretamente no seu e-mail:</p>
    <form action="#" method="post">
      <input type="email" name="email" placeholder="Digite seu e-mail" required>
      <input type="submit" value="Cadastrar">
    </form>

    <div class="chat-icons">
      <a href="https://wa.me/5587981732937" 
target="_blank">Whatsapp</a>
      <a
href="https://wa.me/5587981784874" target="_blank">WhatsApp</a>
      <a href="https://www.instagram.com/SEUUSUARIO" target="_blank">Instagram</a>
      <a href="https://www.kwai.com/@SEUUSUARIO" target="_blank">Kwai</a>
      <a href="https://twitter.com/SEUUSUARIO" target="_blank">Twitter</a>
      <a href="https://facebook.com/SEUUSUARIO" target="_blank">Facebook</a>
      <a href="https://t.me/SEUUSUARIO" target="_blank">Telegram</a>
      <a href="mailto:contato@seudominio.com">Atendimento Online</a>
    </div>
  </section>

  <section id="localizacao" class="map-container">
    <h2>Localização</h2>
    <iframe
      src="https://www.google.com/maps?q=Rua+Maj.+Bizarrias+124,+Nova+Exu,+PE&output=embed"
      width="100%" height="300" style="border:0;" allowfullscreen="" loading="lazy">
    </iframe>
  </section>

  <footer>
    <p>&copy; 2025 - Todos os direitos reservados | Prestação de Serviços Metalúrgicos</p>
  </footer>

</body>
</html>
