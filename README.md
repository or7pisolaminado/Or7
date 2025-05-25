# Or7
Piso laminado
<!DOCTYPE html><html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>OR7 Pisos Laminados</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #ffffff; }
    header { background-color: #4CAF50; color: white; padding: 20px; text-align: center; }
    nav { background-color: #333; overflow: hidden; }
    nav a { float: left; color: white; padding: 14px 16px; text-decoration: none; }
    nav a:hover { background-color: #ddd; color: black; }
    .banner { background: url('https://example.com/banner.jpg') center/cover no-repeat; color: white; padding: 100px 20px; text-align: center; }
    .section { padding: 40px 20px; text-align: center; }
    .services { display: flex; justify-content: space-around; flex-wrap: wrap; }
    .service { width: 250px; margin: 20px; padding: 20px; border: 1px solid #ddd; border-radius: 8px; }
    form { max-width: 500px; margin: auto; text-align: left; }
    input, textarea { width: 100%; padding: 10px; margin: 8px 0; border: 1px solid #ccc; border-radius: 4px; }
    .whatsapp-btn { background-color: #25D366; color: white; border: none; padding: 12px; width: 100%; border-radius: 4px; font-size: 16px; cursor: pointer; }
    .whatsapp-btn:hover { background-color: #20b858; }
    footer { background-color: #f1f1f1; text-align: center; padding: 20px; }
  </style>
</head>
<body><header>
  <h1>OR7 Pisos Laminados</h1>
</header><nav>
  <a href="#sobre">Sobre</a>
  <a href="#servicos">Serviços</a>
  <a href="#orcamento">Orçamento</a>
  <a href="#contato">Contato</a>
</nav><section class="banner">
  <h2>Transforme seu ambiente com elegância e praticidade</h2>
</section><section id="servicos" class="section">
  <h2>Nossos Serviços</h2>
  <div class="services">
    <div class="service">
      <h3>Instalação de Piso Laminado</h3>
      <p>Serviço profissional com acabamento impecável.</p>
    </div>
    <div class="service">
      <h3>Manutenção</h3>
      <p>Reparo e cuidados para prolongar a vida do seu piso.</p>
    </div>
    <div class="service">
      <h3>Consultoria Técnica</h3>
      <p>Ajuda especializada para escolher o melhor piso.</p>
    </div>
  </div>
</section><section id="orcamento" class="section">
  <h2>Solicite seu Orçamento</h2>
  <form onsubmit="enviarWhatsapp(event)">
    <input type="text" id="nome" placeholder="Nome" required>
    <input type="tel" id="telefone" placeholder="Telefone (WhatsApp)" required>
    <input type="text" id="endereco" placeholder="Endereço">
    <textarea id="mensagem" placeholder="Serviço desejado"></textarea>
    <button type="submit" class="whatsapp-btn">Enviar pelo WhatsApp</button>
  </form>
</section><footer>
  <p>OR7 Pisos Laminados - Contato: (21) 96436-4469</p>
  <p>
    <a href="https://www.instagram.com/piso_laminado_rj/" target="_blank">Instagram</a> |
    <a href="https://www.facebook.com/pisosrj/" target="_blank">Facebook</a>
  </p>
</footer><script>
  function enviarWhatsapp(event) {
    event.preventDefault();
    const nome = document.getElementById('nome').value;
    const tel = document.getElementById('telefone').value;
    const end = document.getElementById('endereco').value;
    const msg = document.getElementById('mensagem').value;
    const texto = `Olá, me chamo ${nome}. Meu telefone é ${tel}. Quero serviço no endereço: ${end}. Detalhes: ${msg}`;
    const link = `https://wa.me/5521964364469?text=${encodeURIComponent(texto)}`;
    window.open(link, '_blank');
  }
</script></body>
</html>
