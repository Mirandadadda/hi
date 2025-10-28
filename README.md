<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Momonga's Fluffy Fan Page</title>

  <!-- Inter font -->
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">

  <!-- Tailwind CDN -->
  <script src="https://cdn.tailwindcss.com"></script>

  <!-- Tailwind config -->
  <script>
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
          }
        }
      }
    }
  </script>

  <!-- Estilos finos adicionais -->
  <style>
    /* Look suave, hover e contornos de texto */
    .card-shadow {
      box-shadow: 0 10px 15px -3px rgba(255, 105, 180, 0.10),
                  0  4px  6px -2px rgba(255, 105, 180, 0.05);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .card-shadow:hover {
      transform: translateY(-2px);
      box-shadow: 0 15px 20px -5px rgba(255, 105, 180, 0.20),
                  0  8px 10px -6px rgba(255, 105, 180, 0.10);
    }
    .text-outline {
      text-shadow:
        1px  1px 0 #fff,
       -1px -1px 0 #fff,
        1px -1px 0 #fff,
       -1px  1px 0 #fff;
    }
  </style>
</head>

<body class="min-h-screen bg-momonga-bg text-momonga-text font-sans antialiased">
  <div class="max-w-5xl mx-auto px-4 py-10">

    <!-- Header & Título -->
    <header class="text-center mb-12">
      <div class="inline-block bg-white/80 backdrop-blur-sm p-4 sm:p-6 rounded-3xl card-shadow border-4 border-momonga-pink">
        <h1 class="text-4xl sm:text-6xl font-extrabold text-momonga-accent tracking-tight text-outline">
          🌸 Momonga's Fan Club 🌸
        </h1>
        <p class="mt-2 text-base sm:text-lg text-gray-600 font-medium">
          The most adorable friend from Chiikawa!
        </p>
      </div>
    </header>

    <!-- Grid Principal -->
    <main class="max-w-4xl mx-auto grid grid-cols-1 gap-8">

      <!-- Seção: Introdução -->
      <section>
        <div class="bg-white p-6 sm:p-8 rounded-3xl card-shadow">
          <h2 class="text-3xl font-bold text-momonga-accent mb-4 border-b-2 border-momonga-pink pb-2">
            Introduction
          </h2>
          <p class="text-lg leading-relaxed">
            Momonga is a fluffy and timid little creature from the popular series Chiikawa. He is easily recognized by his white fur, big expressive eyes, and his signature pink cheeks. Despite often being nervous or scared, Momonga has a very kind heart and is a loyal friend to Chiikawa and Hachiware. His adorable reactions and gentle nature make him a beloved character.
          </p>
        </div>
      </section>

      <!-- Seção: Foto + Link estético -->
      <section>
        <figure class="bg-white p-6 sm:p-8 rounded-3xl card-shadow">
          <img
            src="Miranda/Chi.jpg.webp"
            alt="Chi, amiga de Momonga, em estilo fofo"
            class="w-full h-auto rounded-2xl border-2 border-momonga-pink"
            loading="lazy"
          />
          <figcaption class="mt-4 flex items-center justify-between gap-3 flex-wrap">
            <span class="text-sm text-gray-500">
              Imagem carregada da pasta <code>Miranda/</code>.
            </span>
            <a
              href="Miranda/Chi.jpg.webp"
              target="_blank" rel="noopener"
              class="inline-flex items-center gap-2 px-4 py-2 rounded-2xl border-2 border-momonga-accent text-momonga-accent font-semibold hover:bg-momonga-accent/10 focus:outline-none focus:ring-2 focus:ring-momonga-accent/40"
              aria-label="Abrir a foto Chi em uma nova aba"
            >
              ✨ Ver foto em alta
            </a>
          </figcaption>
        </figure>
      </section>

      <!-- Seção: Fun Facts -->
      <section>
        <div class="bg-white p-6 sm:p-8 rounded-3xl card-shadow">
          <h2 class="text-3xl font-bold text-momonga-accent mb-4 border-b-2 border-momonga-pink pb-2">
            Five Fluffy Facts
          </h2>

          <ol class="space-y-4 text-lg list-none pl-0">
            <li class="p-3 bg-momonga-bg rounded-xl flex items-start shadow-inner">
              <span class="text-momonga-accent font-extrabold text-xl mr-3 mt-0.5">1.</span>
              <p>He has a surprisingly strong and stretchy butt. In one comic, he gets stuck in a tree, and his friends use his elastic rear end like a slingshot to free him.</p>
            </li>

            <li class="p-3 bg-momonga-bg rounded-xl flex items-start shadow-inner">
              <span class="text-momonga-accent font-extrabold text-xl mr-3 mt-0.5">2.</span>
              <p>His full, proper name is actually Momonji, a pun on <em>momo</em> (peach) and <em>momo</em> (thigh), but everyone just calls him Momonga.</p>
            </li>

            <li class="p-3 bg-momonga-bg rounded-xl flex items-start shadow-inner">
              <span class="text-momonga-accent font-extrabold text-xl mr-3 mt-0.5">3.</span>
              <p>He has a habit of dramatically melting into a puddle of despair when he gets overly scared or embarrassed, which is as adorable as it is relatable.</p>
            </li>

            <li class="p-3 bg-momonga-bg rounded-xl flex items-start shadow-inner">
              <span class="text-momonga-accent font-extrabold text-xl mr-3 mt-0.5">4.</span>
              <p>Despite his timid nature, he's a surprisingly talented artist and is often seen drawing detailed and impressive pictures in his sketchbook.</p>
            </li>

            <li class="p-3 bg-momonga-bg rounded-xl flex items-start shadow-inner">
              <span class="text-momonga-accent font-extrabold text-xl mr-3 mt-0.5">5.</span>
              <p>His pink cheeks aren't just for show; they are specifically described as being peach-colored, which ties back into the <em>momo</em> (peach) part of his name.</p>
            </li>
          </ol>
        </div>
      </section>

      <!-- Seção: Mais Info -->
      <section>
        <div class="bg-momonga-accent/10 p-6 sm:p-8 rounded-3xl card-shadow border-2 border-momonga-accent">
          <h2 class="text-3xl font-bold text-momonga-accent mb-4 border-b-2 border-momonga-accent pb-2">
            More on Momonga
          </h2>
          <p class="text-xl italic leading-snug">
            His relatable anxiety and gentle heart make him an incredibly endearing character to root for. You can't help but want to protect him, and his small victories feel like a win for all of us. Ultimately, his unwavering loyalty and pure soul make him the most huggable friend in the entire series.
          </p>
        </div>
      </section>

    </main>

    <!-- Footer -->
    <footer class="mt-12 text-center text-gray-400 text-sm">
      <p>© 2024 Momonga Fan Page. Character rights belong to Nagano / Chiikawa creators.</p>
    </footer>
  </div>
</body>
</html>
