# Ma-mie-yummies-
Restaurant 
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ma mie Yummies - Menu Restaurant</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    body {
      background-color: #f9f7fb;
      color: #3b0764;
      font-family: 'Poppins', sans-serif;
    }
    .section {
      transition: all 0.3s ease;
    }
    img {
      border-radius: 1rem;
      width: 100%;
      height: 180px;
      object-fit: cover;
      margin-bottom: 10px;
    }
  </style>
</head>
<body class="p-4">

  <h1 class="text-3xl font-bold text-center mb-6 text-purple-800">🍽️ Menu Ma mie Yummies</h1>

  <!-- Familles -->
  <div class="space-y-4">

    <!-- Plat du jour -->
    <div>
      <button onclick="toggleSection('plats')"
        class="w-full text-left text-2xl font-semibold bg-purple-700 text-white p-3 rounded-2xl shadow-md">● Plat du jour</button>
      <div id="plats" class="section hidden bg-white rounded-2xl p-4 mt-2 shadow">
        <img src="https://images.unsplash.com/photo-1625944230948-5a3c7c60f8cb?auto=format&fit=crop&w=800&q=80" alt="Plat du jour">
        <h3 class="font-bold text-lg mt-2">Lundi</h3>
        <p>Yassa poulet : 3000f</p>
        <p>Fakoye : 3000f</p>

        <h3 class="font-bold text-lg mt-2">Mardi</h3>
        <p>Maffé : 3000f</p>
        <p>Thiep poisson ou poulet : 3000f</p>

        <h3 class="font-bold text-lg mt-2">Mercredi</h3>
        <p>Saga saga : 3000f</p>
        <p>Sauce tomate : 3000f</p>

        <h3 class="font-bold text-lg mt-2">Jeudi</h3>
        <p>Woudjila : 3000f</p>
        <p>Atieké : 3000f</p>

        <h3 class="font-bold text-lg mt-2">Vendredi</h3>
        <p>Tôt : 3000f</p>
        <p>Tièp poisson ou poulet : 3000f</p>

        <a href="https://wa.me/22372910000?text=Bonjour%2C+je+souhaite+commander+un+plat+du+jour+chez+Ma+mie+Yummies+🍽️"
           class="block mt-4 text-center bg-green-500 text-white font-bold py-2 rounded-xl hover:bg-green-600">Commander sur WhatsApp</a>
      </div>
    </div>

    <!-- Fast Food -->
    <div>
      <button onclick="toggleSection('fast')"
        class="w-full text-left text-2xl font-semibold bg-purple-700 text-white p-3 rounded-2xl shadow-md">● Les Fast-Food</button>
      <div id="fast" class="section hidden bg-white rounded-2xl p-4 mt-2 shadow">
        <img src="https://images.unsplash.com/photo-1606756790138-261f92b27f9d?auto=format&fit=crop&w=800&q=80" alt="Fast-food">
        <p>Découvrez nos délicieux fast-foods à prix doux 🍔🍟</p>
        <a href="https://wa.me/22372910000?text=Je+veux+commander+un+fast-food+chez+Ma+mie+Yummies+🍔"
           class="block mt-4 text-center bg-green-500 text-white font-bold py-2 rounded-xl hover:bg-green-600">Commander sur WhatsApp</a>
      </div>
    </div>

    <!-- Sandwich -->
    <div>
      <button onclick="toggleSection('sandwich')"
        class="w-full text-left text-2xl font-semibold bg-purple-700 text-white p-3 rounded-2xl shadow-md">● Nos Sandwichs</button>
      <div id="sandwich" class="section hidden bg-white rounded-2xl p-4 mt-2 shadow">
        <img src="https://images.unsplash.com/photo-1604908812758-b84efb0c53f3?auto=format&fit=crop&w=800&q=80" alt="Sandwich">
        <p>Sandwich viande hachée : 1000f</p>
        <p>Sandwich poulet : 2000f</p>
        <p>Sandwich thon : 2000f</p>
        <p>Sandwich foie : 2000f</p>
        <p>Sandwich rognon : 2000f</p>
        <p>Sandwich steak : 1500f</p>
        <a href="https://wa.me/22372910000?text=Je+veux+commander+un+Sandwich+chez+Ma+mie+Yummies+🥪"
           class="block mt-4 text-center bg-green-500 text-white font-bold py-2 rounded-xl hover:bg-green-600">Commander sur WhatsApp</a>
      </div>
    </div>

    <!-- Shawarma -->
    <div>
      <button onclick="toggleSection('shawarma')"
        class="w-full text-left text-2xl font-semibold bg-purple-700 text-white p-3 rounded-2xl shadow-md">● Nos Shawarmas</button>
      <div id="shawarma" class="section hidden bg-white rounded-2xl p-4 mt-2 shadow">
        <img src="https://images.unsplash.com/photo-1618213745714-b9143f8f6f0b?auto=format&fit=crop&w=800&q=80" alt="Shawarma">
        <p>Shawarma poulet : 2500f</p>
        <p>Shawarma bœuf : 2000f</p>
        <a href="https://wa.me/22372910000?text=Je+veux+commander+un+Shawarma+chez+Ma+mie+Yummies+🌯"
           class="block mt-4 text-center bg-green-500 text-white font-bold py-2 rounded-xl hover:bg-green-600">Commander sur WhatsApp</a>
      </div>
    </div>

    <!-- Tacos -->
    <div>
      <button onclick="toggleSection('tacos')"
        class="w-full text-left text-2xl font-semibold bg-purple-700 text-white p-3 rounded-2xl shadow-md">● Nos Tacos</button>
      <div id="tacos" class="section hidden bg-white rounded-2xl p-4 mt-2 shadow">
        <img src="https://images.unsplash.com/photo-1627308595229-7830a5c91f9f?auto=format&fit=crop&w=800&q=80" alt="Tacos">
        <p>Tacos viande : 2500f</p>
        <p>Le régal : 3500f</p>
        <p>Tacos yummies : 4500f</p>
        <a href="https://wa.me/22372910000?text=Je+veux+commander+un+Tacos+chez+Ma+mie+Yummies+🌮"
           class="block mt-4 text-center bg-green-500 text-white font-bold py-2 rounded-xl hover:bg-green-600">Commander sur WhatsApp</a>
      </div>
    </div>

    <!-- Burger -->
    <div>
      <button onclick="toggleSection('burger')"
        class="w-full text-left text-2xl font-semibold bg-purple-700 text-white p-3 rounded-2xl shadow-md">● Nos Burgers</button>
      <div id="burger" class="section hidden bg-white rounded-2xl p-4 mt-2 shadow">
        <img src="https://images.unsplash.com/photo-1606755962773-0c8f4d9d3b88?auto=format&fit=crop&w=800&q=80" alt="Burger">
        <p>Burger Smile : 3000f</p>
        <p>Burger Chicken Masala : 3000f</p>
        <p>Burger Yummies : 4000f</p>
        <a href="https://wa.me/22372910000?text=Je+veux+commander+un+Burger+chez+Ma+mie+Yummies+🍔"
           class="block mt-4 text-center bg-green-500 text-white font-bold py-2 rounded-xl hover:bg-green-600">Commander sur WhatsApp</a>
      </div>
    </div>

  </div>

  <script>
    function toggleSection(id) {
      const section = document.getElementById(id);
      section.classList.toggle('hidden');
    }
  </script>

  <footer class="text-center text-sm mt-8 text-purple-700">
    © 2025 Ma mie Yummies - Tous droits réservés 🍽️
  </footer>

</body>
</html>
