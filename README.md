<!doctype html>
<html lang="pt">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Momonga's Fluffy Fan Page</title>

    <!-- Tailwind CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
      /* Tailwind config */
      tailwind.config = {
        theme: {
          extend: {
            colors: {
              'momonga-pink': '#FFC0CB',
              'momonga-accent': '#FF69B4',
              'momonga-bg': '#FFF5F7',
              'momonga-text': '#525252',
            },
            fontFamily: {
              sans: ['Inter', 'sans-serif'],
            },
          },
        },
      };
    </script>

    <style>
      /* Estilos suaves e "fluffy" */
      .card-shadow {
        box-shadow: 0 10px 15px -3px rgba(255, 105, 180, 0.1),
                    0 4px 6px -2px rgba(255, 105, 180, 0.05);
        transition: transform 0.3s ease, box-shadow 0.3s ease;
      }
      .card-shadow:hover {
        transform: translateY(-2px);
        box-shadow: 0 15px 20px -5px rgba(255, 105, 180, 0.2);
      }
      .text-outline {
        text-shadow: 1px 1px 0 #fff,
                     -1px -1px 0 #fff,
                     1px -1px 0 #fff,
                     -1px 1px 0 #fff;
      }
    </style>
  </head>
  <body class="min-h-screen bg-momonga-bg/60 font-sans text-momonga-text antialiased">
    <!-- Header & Title -->
    <header class="text-center mb-12 pt-10">
      <div class="inline-block bg-white/80 backdrop-blur-sm p-4 rounded-3xl card-shadow border-4 border-momonga-pink">
        <h1 class="text-4xl sm:text-6xl font-extrabold text-momonga-accent tracking-tight text-outline">
          🌸 Momonga's Fan Club 🌸
        </h1>
        <p class="mt-2 text-lg text-gray-600 font-medium">
          The most adorable friend from Chiikawa!
        </p>
      </div>
    </header>

    <!-- Main Content -->
    <main class="max-w-4xl mx-auto grid grid-cols-1 gap-8 px-4 pb-16">
      <!-- Photo Section -->
      <section aria-labelledby="photo-title">
        <div class="bg-white p-6 sm:p-8 rounded-3xl card-shadow text-center">
          <h2 id="photo-title" class="text-3xl font-bold text-momonga-accent mb-4 border-b-2 border-momonga-pink pb-2">Momonga Image</h2>
          <img src="file:///C:/Users/ASUS/Downloads/Miranda/Chi.jpg.webp" alt="Momonga Image" width="500" height="600" class="mx-auto rounded-3xl border-4 border-momonga-pink">
        </div>
      </section>

      <!-- Introduction Section -->
      <!-- Image Section -->
      <section aria-labelledby="photo-title">
        <div class="bg-white p-6 sm:p-8 rounded-3xl card-shadow text-center">
          <h2 id="photo-title" class="text-3xl font-bold text-momonga-accent mb-4 border-b-2 border-momonga-pink pb-2">Imagem</h2>
          <img src="file:///C:/Users/ASUS/Downloads/Miranda/Chi.jpg.webp" alt="Momonga Image" width="500" height="600" class="mx-auto rounded-3xl border-4 border-momonga-pink">
        </div>
      </section>

      <!-- Introduction Section -->
      <section aria-labelledby="intro-title">
        <div class="bg-white p-6 sm:p-8 rounded-3xl card-shadow">
          <h2 id="intro-title" class="text-3xl font-bold text-momonga-accent mb-4 border-b-2 border-momonga-pink pb-2">
            Introduction
          </h2>
          <p class="text-lg leading-relaxed">
            Momonga is a fluffy and timid little creature from the popular Chiikawa series. He is easily recognized by his white fur, big expressive eyes, and pink cheeks. Even though he often feels nervous or scared, he has a very kind heart and is a loyal friend to Chiikawa and Hachiware. His adorable reactions and gentle nature make him a beloved character.</p>
        </div>
      </section>

      <!-- Fun Facts Section -->
      <section aria-labelledby="facts-title">
        <div class="bg-white p-6 sm:p-8 rounded-3xl card-shadow">
          <h2 id="facts-title" class="text-3xl font-bold text-momonga-accent mb-4 border-b-2 border-momonga-pink pb-2">
            Five Fluffy Facts
          </h2>
          <ol class="space-y-4 text-lg list-decimal pl-6">
            <li class="p-3 bg-momonga-bg rounded-xl shadow-inner">
              He has a surprisingly strong and stretchy butt. In one comic, he gets stuck in a tree and his friends use his elastic rear end like a slingshot to free him.</li>
            <li class="p-3 bg-momonga-bg rounded-xl shadow-inner">
              His full name is "Momonji," a pun based on the word *momo* meaning both peach and thigh, but everyone simply calls him Momonga.<em>momo</em> (pêssego) e <em>momo</em> (coxa), mas todos o chamam de Momonga.
            </li>
            <li class="p-3 bg-momonga-bg rounded-xl shadow-inner">
              He has a habit of dramatically melting into a puddle of despair when he becomes overly scared or embarrassed.</li>
            <li class="p-3 bg-momonga-bg rounded-xl shadow-inner">
              Despite being shy, he is a surprisingly talented artist and can often be seen drawing detailed illustrations in his sketchbook.</li>
            <li class="p-3 bg-momonga-bg rounded-xl shadow-inner">
              His pink cheeks are not just decoration. They are specifically described as peach-colored, which connects back to the *momo* part of his name.<em>momo</em> do nome.
            </li>
          </ol>
        </div>
      </section>

      <!-- More Info Section -->
      <section aria-labelledby="more-title">
        <div class="bg-momonga-accent/10 p-6 sm:p-8 rounded-3xl card-shadow border-2 border-momonga-accent">
          <h2 id="more-title" class="text-3xl font-bold text-momonga-accent mb-4 border-b-2 border-momonga-accent pb-2">
            More About Momonga
          </h2>
          <p class="text-xl italic leading-snug">
            His relatable anxiety and gentle heart make him an incredibly endearing character. You cannot help but want to protect him, and every small victory he achieves feels like a win for all of us.</p>
        </div>
      </section>
    </main>

    <!-- Footer -->
    <footer class="mt-8 pb-10 text-center text-gray-400 text-sm">
      <p>© 2024 Momonga Fan Page. Os direitos do personagem pertencem a Nagano/Chiikawa.</p>
    </footer>
  </body>
</html>
