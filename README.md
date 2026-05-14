<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>EcoLar Sustentável</title>

  <style>

    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
    }

    body{
      font-family: Arial, sans-serif;
      background:#f4f4f4;
      color:#333;
      line-height:1.6;
    }

    header{
      background:#2e8b57;
      color:white;
      padding:20px;
      text-align:center;
    }

    header h1{
      margin-bottom:10px;
      font-size:40px;
    }

    nav{
      margin-top:10px;
    }

    nav a{
      color:white;
      text-decoration:none;
      margin:0 15px;
      font-weight:bold;
      transition:0.3s;
    }

    nav a:hover{
      color:#d4ffd4;
    }

    .banner{
      background:url('https://images.unsplash.com/photo-1509395176047-4a66953fd231?q=80&w=1400&auto=format&fit=crop') center/cover;
      height:400px;
      display:flex;
      align-items:center;
      justify-content:center;
      text-align:center;
      color:white;
    }

    .banner-content{
      background:rgba(0,0,0,0.6);
      padding:30px;
      border-radius:10px;
    }

    .banner h2{
      font-size:42px;
      margin-bottom:15px;
    }

    .section{
      padding:60px 20px;
      max-width:1200px;
      margin:auto;
    }

    .section h2{
      text-align:center;
      margin-bottom:40px;
      color:#2e8b57;
      font-size:35px;
    }

    .empresa{
      text-align:center;
      font-size:18px;
    }

    .produtos-container{
      display:grid;
      grid-template-columns:repeat(auto-fit, minmax(250px,1fr));
      gap:25px;
    }

    .produto{
      background:white;
      border-radius:10px;
      overflow:hidden;
      box-shadow:0 2px 10px rgba(0,0,0,0.1);
      transition:0.3s;
    }

    .produto:hover{
      transform:translateY(-5px);
    }

    .produto img{
      width:100%;
      height:200px;
      object-fit:cover;
    }

    .produto-info{
      padding:20px;
    }

    .produto-info h3{
      color:#2e8b57;
      margin-bottom:10px;
    }

    .faq{
      background:white;
      margin-bottom:15px;
      padding:20px;
      border-radius:8px;
    }

    .faq h3{
      color:#2e8b57;
      margin-bottom:10px;
    }

    .contato{
      background:white;
      padding:30px;
      border-radius:10px;
      max-width:700px;
      margin:auto;
      box-shadow:0 2px 10px rgba(0,0,0,0.1);
    }

    .contato input,
    .contato textarea{
      width:100%;
      padding:12px;
      margin-bottom:15px;
      border:1px solid #ccc;
      border-radius:5px;
    }

    .contato button{
      background:#2e8b57;
      color:white;
      border:none;
      padding:12px 25px;
      border-radius:5px;
      cursor:pointer;
      font-size:16px;
    }

    .contato button:hover{
      background:#246b45;
    }

    footer{
      background:#222;
      color:white;
      text-align:center;
      padding:25px;
      margin-top:40px;
    }

    @media(max-width:768px){

      .banner h2{
        font-size:28px;
      }

      nav a{
        display:block;
        margin:10px 0;
      }

    }

  </style>
</head>

<body>

  <!-- HEADER -->

  <header>

    <h1>🌿 EcoLar Sustentável</h1>

    <p>Tecnologia e Natureza em Harmonia com seu Lar</p>

    <nav>
      <a href="#empresa">Empresa</a>
      <a href="#produtos">Produtos</a>
      <a href="#comunicacao">Comunicação</a>
      <a href="#faq">FAQ</a>
    </nav>

  </header>

  <!-- BANNER -->

  <section class="banner">

    <div class="banner-content">

      <h2>Soluções Sustentáveis Para Sua Casa</h2>

      <p>
        Produtos ecológicos, energia solar e sustentabilidade
        para transformar seu ambiente.
      </p>

    </div>

  </section>

  <!-- EMPRESA -->

  <section class="section" id="empresa">

    <h2>Sobre a Empresa</h2>

    <div class="empresa">

      <p>
        A EcoLar Sustentável é especializada em soluções ecológicas
        para residências e pequenas empresas.
      </p>

      <br>

      <p>
        Trabalhamos com produtos sustentáveis, energia solar,
        compostagem e tecnologias que ajudam o meio ambiente.
      </p>

    </div>

  </section>

  <!-- PRODUTOS -->

  <section class="section" id="produtos">

    <h2>Nossos Produtos</h2>

    <div class="produtos-container">

      <!-- PRODUTO 1 -->

      <div class="produto">

        <img src="https://images.unsplash.com/photo-1466692476868-aef1dfb1e735?q=80&w=1200&auto=format&fit=crop">

        <div class="produto-info">

          <h3>🌱 Compostagem</h3>

          <p>Kit Compostagem Residencial</p>
          <p>Composteira Inteligente</p>
          <p>Adubo Orgânico Natural</p>
          <p>Balde Ecológico</p>

        </div>

      </div>

      <!-- PRODUTO 2 -->

      <div class="produto">

        <img src="https://images.unsplash.com/photo-1509395176047-4a66953fd231?q=80&w=1200&auto=format&fit=crop">

        <div class="produto-info">

          <h3>☀️ Energia Solar</h3>

          <p>Painel Solar Residencial</p>
          <p>Kit Solar Compacto</p>
          <p>Controlador Solar</p>
          <p>Bateria Solar</p>

        </div>

      </div>

      <!-- PRODUTO 3 -->

      <div class="produto">

        <img src="https://images.unsplash.com/photo-1416879595882-3373a0480b5b?q=80&w=1200&auto=format&fit=crop">

        <div class="produto-info">

          <h3>🌿 Jardinagem</h3>

          <p>Horta Vertical</p>
          <p>Vasos Biodegradáveis</p>
          <p>Irrigação Econômica</p>
          <p>Kit Plantio Orgânico</p>

        </div>

      </div>

    </div>

  </section>

  <!-- COMUNICAÇÃO -->

  <section class="section" id="comunicacao">

    <h2>Comunicação</h2>

    <div class="contato">

      <form>

        <input type="text" placeholder="Seu Nome" required>

        <input type="email" placeholder="Seu Email" required>

        <textarea rows="5" placeholder="Digite sua mensagem"></textarea>

        <button type="submit">Enviar Mensagem</button>

      </form>

      <br>

      <p><strong>Telefone:</strong> (33) 99999-9999</p>

      <p><strong>Email:</strong> contato@ecolar.com</p>

      <p><strong>Instagram:</strong> @ecolarsustentavel</p>

    </div>

  </section>

  <!-- FAQ -->

  <section class="section" id="faq">

    <h2>Perguntas Frequentes</h2>

    <div class="faq">

      <h3>Os produtos possuem garantia?</h3>

      <p>
        Sim. Todos os produtos possuem garantia contra defeitos.
      </p>

    </div>

    <div class="faq">

      <h3>A empresa realiza instalação?</h3>

      <p>
        Sim. Fazemos instalação de sistemas solares e hortas.
      </p>

    </div>

    <div class="faq">

      <h3>Como solicitar um orçamento?</h3>

      <p>
        Você pode solicitar pelo formulário de contato.
      </p>

    </div>

    <div class="faq">

      <h3>A EcoLar atende outras cidades?</h3>

      <p>
        Sim. Atendemos toda a região.
      </p>

    </div>

  </section>

  <!-- FOOTER -->

  <footer>

    <p>© 2026 EcoLar Sustentável - Todos os direitos reservados</p>

  </footer>

</body>
</html>
