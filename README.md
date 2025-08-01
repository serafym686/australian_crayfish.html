# australian_crayfish.html
Это сайт для покупки австралийского рака
<!DOCTYPE html><html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Продажа австралийского рака</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-blue-50 font-sans">
  <header class="bg-blue-800 text-white p-4">
    <div class="container mx-auto flex justify-between items-center">
      <h1 class="text-2xl font-bold">Австралийский рак (Cherax Destructor)</h1>
      <nav>
        <a href="#about" class="ml-4 hover:underline">О виде</a>
        <a href="#shop" class="ml-4 hover:underline">Купить</a>
        <a href="#contact" class="ml-4 hover:underline">Контакты</a>
      </nav>
    </div>
  </header>  <section id="lang-switch" class="bg-blue-100 py-2 text-center text-sm">
    <p>
      🇷🇺 Русский | <a href="#" onclick="switchLang('en')" class="underline">🇬🇧 English</a> | <a href="#" onclick="switchLang('de')" class="underline">🇩🇪 Deutsch</a> | <a href="#" onclick="switchLang('fr')" class="underline">🇫🇷 Français</a> | <a href="#" onclick="switchLang('es')" class="underline">🇪🇸 Español</a>
    </p>
  </section>  <section id="hero" class="bg-blue-100 text-center py-12">
    <h2 class="text-3xl font-semibold mb-4" data-lang="ru">Выращенные с заботой, доставим по всей Германии</h2>
    <h2 class="text-3xl font-semibold mb-4 hidden" data-lang="en">Raised with care, delivered across Germany</h2>
    <h2 class="text-3xl font-semibold mb-4 hidden" data-lang="de">Mit Sorgfalt gezüchtet, deutschlandweit geliefert</h2>
    <h2 class="text-3xl font-semibold mb-4 hidden" data-lang="fr">Élevés avec soin, livrés partout en Allemagne</h2>
    <h2 class="text-3xl font-semibold mb-4 hidden" data-lang="es">Creados con esmero, entregados por toda Alemania</h2>
    <p class="text-lg text-gray-700" data-lang="ru">Чистая порода. Отлично подходит для аквариумов и декоративных прудов.</p>
    <p class="text-lg text-gray-700 hidden" data-lang="en">Pure breed. Perfect for aquariums and ornamental ponds.</p>
    <p class="text-lg text-gray-700 hidden" data-lang="de">Reine Zucht. Ideal für Aquarien und Zierteiche.</p>
    <p class="text-lg text-gray-700 hidden" data-lang="fr">Race pure. Idéal pour aquariums et bassins décoratifs.</p>
    <p class="text-lg text-gray-700 hidden" data-lang="es">Raza pura. Perfecto para acuarios y estanques ornamentales.</p>
  </section>  <!-- Остальная часть сайта остаётся на русском. Можно добавить аналогичные блоки с data-lang при необходимости. -->  <script>
    function switchLang(lang) {
      document.querySelectorAll('[data-lang]').forEach(el => {
        el.classList.add('hidden');
        if (el.getAttribute('data-lang') === lang) {
          el.classList.remove('hidden');
        }
      });
    }
  </script></body>
</html>
