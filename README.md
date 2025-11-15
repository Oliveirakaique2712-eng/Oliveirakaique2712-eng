<!doctype html>
<html lang="pt-BR" class="h-full">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Futebol Digital Pro</title>
  <script src="https://cdn.tailwindcss.com"></script>

  <style>
    body {
      box-sizing: border-box;
      background-color: #0d0d0d;
      color: white;
    }

    .neon-green {
      color: #00ff88;
    }

    .btn-primary {
      background: linear-gradient(90deg, #00ff88, #0affb8);
      color: black;
      font-weight: 700;
      transition: 0.2s;
    }

    .btn-primary:hover {
      opacity: 0.8;
      transform: scale(1.05);
    }

    .card {
      background: #111;
      border: 1px solid #1f1f1f;
    }

    .gradient-hero {
      background: radial-gradient(circle at top, #00ff88 0%, #0d0d0d 60%);
    }

    .pulse {
      animation: pulse 2s infinite;
    }

    @keyframes pulse {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.04); }
    }
  </style>
</head>

<body class="font-sans">

<!-- HERO -->
<section class="gradient-hero min-h-screen flex items-center text-center px-6">
  <div class="max-w-4xl mx-auto">
    <h1 class="text-5xl md:text-7xl font-bold mb-6 neon-green">
      Transforme seu Jogo com o Futebol Digital
    </h1>
    <p class="text-xl md:text-2xl text-gray-300 max-w-3xl mx-auto mb-10">
      Métodos modernos, materiais profissionais e treinamentos que realmente geram evolução no campo.
    </p>

    <button class="btn-primary px-10 py-4 rounded-full text-xl shadow-xl pulse">
      Começar Agora 🚀
    </button>

    <p class="mt-6 text-gray-400 text-sm">
      +12.000 jogadores treinando com nossos materiais
    </p>
  </div>
</section>

<!-- PRODUTOS -->
<section class="py-20 bg-black">
  <div class="container mx-auto px-6 text-center">
    <h2 class="text-4xl md:text-5xl font-bold neon-green mb-12">Nossos Produtos</h2>

    <div class="grid md:grid-cols-3 gap-10 max-w-6xl mx-auto">

      <!-- Card 1 -->
      <div class="card p-8 rounded-2xl shadow-xl hover:scale-105 duration-300">
        <div class="text-4xl mb-4">⚽</div>
        <h3 class="text-2xl font-bold mb-4">Treinos Personalizados</h3>
        <p class="text-gray-400 mb-6">
          Treinos estruturados para qualquer posição, nível e rotina.
        </p>
        <ul class="text-left space-y-3 text-gray-300 mb-6">
          <li>✓ Exercícios profissionais</li>
          <li>✓ Vídeos explicativos</li>
          <li>✓ Planejamento semanal</li>
        </ul>
        <div class="text-3xl font-bold neon-green mb-4">R$ 97</div>
        <button class="btn-primary px-6 py-3 w-full rounded-lg">Adquirir</button>
      </div>

      <!-- Card 2 -->
      <div class="card p-8 rounded-2xl shadow-xl border border-green-400 hover:scale-105 duration-300 relative">
        <span class="absolute top-[-12px] left-1/2 transform -translate-x-1/2 bg-green-500 text-black px-4 py-1 rounded-full font-bold text-sm">
          MAIS VENDIDO
        </span>
        <div class="text-4xl mb-4">🏆</div>
        <h3 class="text-2xl font-bold mb-4">Táticas de Elite</h3>
        <p class="text-gray-400 mb-6">
          Análises profissionais e estratégias dos maiores clubes do mundo.
        </p>
        <ul class="text-left space-y-3 text-gray-300 mb-6">
          <li>✓ Esquemas modernos</li>
          <li>✓ Análises completas</li>
          <li>✓ Aulas com especialistas</li>
        </ul>
        <div class="text-3xl font-bold text-green-400 mb-4">R$ 197</div>
        <button class="btn-primary px-6 py-3 w-full rounded-lg">Adquirir</button>
      </div>

      <!-- Card 3 -->
      <div class="card p-8 rounded-2xl shadow-xl hover:scale-105 duration-300">
        <div class="text-4xl mb-4">📊</div>
        <h3 class="text-2xl font-bold mb-4">Performance Analytics</h3>
        <p class="text-gray-400 mb-6">
          Ferramentas para acompanhar sua evolução no campo.
        </p>
        <ul class="text-left space-y-3 text-gray-300 mb-6">
          <li>✓ Relatórios avançados</li>
          <li>✓ Métricas detalhadas</li>
          <li>✓ Comparação com atletas</li>
        </ul>
        <div class="text-3xl font-bold text-green-400 mb-4">R$ 147</div>
        <button class="btn-primary px-6 py-3 w-full rounded-lg">Adquirir</button>
      </div>

    </div>
  </div>
</section>

<!-- DEPOIMENTOS -->
<section class="py-20 bg-[#0f0f0f]">
  <div class="container mx-auto px-6 text-center max-w-5xl">
    <h2 class="text-4xl md:text-5xl font-bold neon-green mb-12">O que os atletas dizem</h2>

    <div class="grid md:grid-cols-3 gap-10">

      <div class="card p-6 rounded-xl shadow">
        <p class="text-gray-300 mb-4 italic">
          “Melhorei minha resistência e minha leitura de jogo em menos de um mês.”
        </p>
        <h4 class="font-bold text-green-400">— Lucas Andrade</h4>
      </div>

      <div class="card p-6 rounded-xl shadow border border-green-900">
        <p class="text-gray-300 mb-4 italic">
          “Os treinos são muito completos. É quase como ter um personal coach no bolso.”
        </p>
        <h4 class="font-bold text-green-400">— Pedro Santos</h4>
      </div>

      <div class="card p-6 rounded-xl shadow">
        <p class="text-gray-300 mb-4 italic">
          “Melhor investimento que já fiz para meu desenvolvimento no futebol.”
        </p>
        <h4 class="font-bold text-green-400">— Matheus Ribeiro</h4>
      </div>

    </div>
  </div>
</section>

<!-- FAQ -->
<section class="py-20 bg-black">
  <div class="container mx-auto px-6 max-w-4xl">
    <h2 class="text-4xl font-bold neon-green text-center mb-12">Perguntas Frequentes</h2>

    <div class="space-y-6 text-gray-300">

      <div class="border-b border-gray-700 pb-4">
        <h3 class="font-bold text-lg">Posso acessar pelo celular?</h3>
        <p class="text-gray-400 mt-2">Sim, todo conteúdo é 100% mobile.</p>
      </div>

      <div class="border-b border-gray-700 pb-4">
        <h3 class="font-bold text-lg">Quanto tempo tenho acesso?</h3>
        <p class="text-gray-400 mt-2">Acesso vitalício a todos os materiais.</p>
      </div>

      <div class="border-b border-gray-700 pb-4">
        <h3 class="font-bold text-lg">Tem garantia?</h3>
        <p class="text-gray-400 mt-2">Sim, garantia incondicional de 7 dias.</p>
      </div>

    </div>
  </div>
</section>

<!-- CTA FINAL -->
<section class="py-20 gradient-hero text-center">
  <h2 class="text-5xl font-bold neon-green mb-6">
    Eleve seu jogo agora mesmo
  </h2>
  <p class="text-gray-300 mb-8 text-xl">
    Entre para a nova geração de jogadores evoluídos digitalmente.
  </p>

  <button class="btn-primary px-10 py-4 rounded-full text-xl shadow-xl">
    Quero começar agora
  </button>
</section>

<!-- FOOTER -->
<footer class="py-10 bg-black border-t border-gray-800 text-center text-gray-500 text-sm">
  © 2024 Futebol Digital Pro — Todos os direitos reservados
</footer>

</body>
</html>
