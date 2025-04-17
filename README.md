<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>D'ELLATSUKY | Revenda de Roupas</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }

    body {
      font-family: 'Montserrat', sans-serif;
      background-color: #0a0a0a;
      color: #fff;
    }

    header {
      background-color: #1a1a1a;
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-bottom: 2px solid #8B0000;
    }

    header img {
      height: 60px;
    }

    nav a {
      color: #f0f0f0;
      margin-left: 20px;
      text-decoration: none;
      font-weight: bold;
      font-size: 16px;
    }

    .hero {
      background: url('https://cdn.wallpapersafari.com/50/17/gqlzoL.jpg') no-repeat center center/cover;
      padding: 120px 40px;
      text-align: center;
      color: #fff;
      background-size: cover;
    }

    .hero h1 {
      font-size: 72px;
      font-weight: 700;
      color: #8B0000;
      text-transform: uppercase;
    }

    .hero p {
      font-size: 22px;
      margin-top: 20px;
      font-weight: 300;
    }

    .produtos {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
      gap: 20px;
      padding: 60px;
      background-color: #111;
    }

    .produto {
      background-color: #1a1a1a;
      padding: 20px;
      border-radius: 10px;
      border: 2px solid #8B0000;
      text-align: center;
      box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
      transition: transform 0.3s ease;
    }

    .produto:hover {
      transform: translateY(-10px);
    }

    .produto img {
      width: 100%;
      border-radius: 10px;
    }

    .produto h2 {
      font-size: 20px;
      margin: 10px 0;
      color: #8B0000;
    }

    .produto p {
      font-size: 16px;
      color: #f0f0f0;
    }

    .pagamento {
      background-color: #111;
      padding: 60px;
      text-align: center;
      color: #fff;
    }

    .pagamento h2 {
      color: #8B0000;
      margin-bottom: 20px;
      font-size: 28px;
      font-weight: 700;
    }

    .pagamento img {
      width: 200px;
      margin-bottom: 20px;
    }

    .contato {
      background-color: #1a1a1a;
      padding: 40px;
      text-align: center;
    }

    .contato h2 {
      font-size: 24px;
      color: #8B0000;
      font-weight: 700;
    }

    .contato a {
      color: #8B0000;
      font-size: 20px;
      text-decoration: none;
      font-weight: bold;
    }

    footer {
      text-align: center;
      padding: 20px;
      background-color: #0a0a0a;
      font-size: 16px;
      color: #555;
    }

    footer a {
      color: #8B0000;
      text-decoration: none;
    }
  </style>
</head>
<body>

  <header>
    <img src="logo.png" alt="Logo D’ELLATSUKY"> <!-- Troque "logo.png" pela sua logo -->
    <nav>
      <a href="#produtos">Produtos</a>
      <a href="#pagamento">Pagamento</a>
      <a href="#contato">Contato</a>
    </nav>
  </header>

  <section class="hero">
    <h1>D'ELLATSUKY</h1>
    <p>Revenda de roupas exclusivas, modernas e de alta qualidade.</p>
  </section>

  <section id="produtos" class="produtos">
    <div class="produto">
      <img src="https://via.placeholder.com/300x400" alt="Produto 1">
      <h2>Camisa Oversized</h2>
      <p>R$ 79,90</p>
    </div>
    <div class="produto">
      <img src="https://via.placeholder.com/300x400" alt="Produto 2">
      <h2>Moletom Premium</h2>
      <p>R$ 129,90</p>
    </div>
    <!-- Adicione mais produtos aqui -->
  </section>

  <section id="pagamento" class="pagamento">
    <h2>Pagamento via PIX</h2>
    <p>Chave PIX: 542.431.338-83</p>
    <img src="https://api.qrserver.com/v1/create-qr-code/?data=542.431.338-83&size=200x200" alt="QR Code PIX">
    <p>Escaneie o QR Code acima para realizar o pagamento.</p>
  </section>

  <section id="contato" class="contato">
    <h2>Fale conosco via WhatsApp</h2>
    <p><a href="https://wa.me/5511993105539" target="_blank">(11) 99310-5539</a></p>
  </section>

  <footer>
    &copy; 2025 D'ELLATSUKY. Todos os direitos reservados. | <a href="#">Política de Privacidade</a>
  </footer>

</body>
</html>
