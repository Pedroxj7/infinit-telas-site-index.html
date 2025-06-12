<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Protec&Persianas - Consertos Profissionais</title>
  <script src="https://unpkg.com/feather-icons"></script>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-50 text-gray-800 font-sans">

  <!-- Cabeçalho -->
  <header class="bg-blue-600 text-white p-6 shadow">
    <div class="max-w-6xl mx-auto flex justify-between items-center">
      <h1 class="text-2xl font-bold">Protec&Persianas</h1>
      <nav class="space-x-4">
        <a href="#servicos" class="hover:underline">Serviços</a>
        <a href="#sobre" class="hover:underline">Sobre</a>
        <a href="#contato" class="hover:underline">Contato</a>
      </nav>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="bg-blue-100 py-16">
    <div class="max-w-5xl mx-auto grid md:grid-cols-2 items-center px-6 gap-8">
      <div>
        <h2 class="text-4xl font-bold mb-4">Conserto de Telas de Proteção e Persianas</h2>
        <p class="text-lg mb-4">Serviço rápido, seguro e profissional para sua casa ou empresa.</p>
        <a href="#contato" class="bg-blue-600 text-white px-6 py-3 rounded hover:bg-blue-700">Solicite um orçamento</a>
      </div>
      <img src="https://images.unsplash.com/photo-1597699401135-7c0e60f6a1d1?auto=format&fit=crop&w=600&q=80" alt="Proteção" class="rounded-xl shadow-lg" />
    </div>
  </section>

  <!-- Serviços -->
  <section id="servicos" class="py-16 bg-white">
    <div class="max-w-6xl mx-auto px-6">
      <h3 class="text-3xl font-semibold mb-8 text-center">Nossos Serviços</h3>
      <div class="grid md:grid-cols-2 gap-10">
        <div class="flex items-start space-x-4 bg-gray-100 p-6 rounded-lg shadow">
          <i data-feather="shield" class="text-blue-600 w-10 h-10"></i>
          <div>
            <h4 class="text-xl font-bold mb-2">Conserto de Telas de Proteção</h4>
            <p>Troca e reparo de telas rasgadas, com materiais resistentes e mão de obra especializada.</p>
          </div>
        </div>
        <div class="flex items-start space-x-4 bg-gray-100 p-6 rounded-lg shadow">
          <i data-feather="sliders" class="text-blue-600 w-10 h-10"></i>
          <div>
            <h4 class="text-xl font-bold mb-2">Conserto de Persianas</h4>
            <p>Manutenção de persianas verticais, horizontais, rolo e blackout com rapidez e qualidade.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Sobre Nós -->
  <section id="sobre" class="py-16 bg-gray-50">
    <div class="max-w-6xl mx-auto px-6 grid md:grid-cols-2 gap-10 items-center">
      <img src="https://images.unsplash.com/photo-1616628182506-bd1aa273b16d?auto=format&fit=crop&w=600&q=80" alt="Equipe de conserto" class="rounded-xl shadow-md" />
      <div>
        <h3 class="text-3xl font-semibold mb-4">Sobre Nós</h3>
        <p class="text-lg mb-4">Com mais de 10 anos de experiência, a Protec&Persianas é referência em consertos residenciais e comerciais. Nosso compromisso é com a sua segurança e conforto. Atendemos com agilidade, qualidade e preço justo.</p>
      </div>
    </div>
  </section>

  <!-- Contato -->
  <section id="contato" class="py-16 bg-white">
    <div class="max-w-4xl mx-auto px-6">
      <h3 class="text-3xl font-semibold mb-8 text-center">Fale Conosco</h3>
      <form class="space-y-4 max-w-xl mx-auto">
        <input type="text" placeholder="Seu nome" class="w-full border border-gray-300 p-3 rounded" required />
        <input type="email" placeholder="Seu e-mail" class="w-full border border-gray-300 p-3 rounded" required />
        <textarea placeholder="Sua mensagem" rows="5" class="w-full border border-gray-300 p-3 rounded" required></textarea>
        <button type="submit" class="bg-blue-600 text-white px-6 py-3 rounded hover:bg-blue-700">Enviar Mensagem</button>
      </form>
    </div>
  </section>

  <!-- Rodapé -->
  <footer class="bg-blue-600 text-white text-center p-4 mt-10">
    <p>&copy; 2025 Protec&Persianas. Todos os direitos reservados.</p>
  </footer>

  <script>
    feather.replace();
  </script>
</body>
</html>
