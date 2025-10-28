<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Momonga's Fluffy Fan Page</title>

  <!-- Fix: correct CDN URL -->
  <script src="https://cdn.tailwindcss.com"></script>
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

  <style>
    /* Soft, fluffy look + hovers */
    .card-shadow {
      box-shadow: 0 10px 15px -3px rgba(255,105,180,.10),
                  0 4px 6px -2px rgba(255,105,180,.05);
      transition: transform .3s ease, box-shadow .3s ease;
    }
    .card-shadow:hover {
      transform: translateY(-2px);
      box-shadow: 0 15px 20px -5px rgba(255,105,180,.20);
    }
    .text-outline {
      text-shadow: 1px 1px 0 #fff, -1px -1px 0 #fff,
                   1px -1px 0 #fff, -1px 1px 0 #fff;
    }
  </style>
</head>
<body class="font-sans bg-momonga-bg text-momonga-text antialiased">

  <!-- Header & Title -->
  <header class="text-center mb-12 mt-8">
    <div class="inline-block bg-white/80 backdrop-blur-sm p-4 rounded-3xl card-shadow border-4 border-momonga-pink">
      <h1 class="text-4xl sm:text-6xl font-extrabold text-momonga-accent tracking-tight text-outline">
        🌸 Momonga's Fan Club 🌸
      </h1>
      <p class="mt-2 text-lg text-gray-600 font-medium">
        The most adorable friend from Chiikawa!
      </p>
    </div>
  </header>

  <!-- Main Content Grid -->
  <main class="max-w-4xl mx-auto grid grid-cols-1 gap-8 px-4 pb-12">

    <!-- Introduction Section -->
    <section>
      <div class="bg-white p-6 sm:p-8 rounded-3xl card-shadow">
        <h2 class="text-3xl font-bold text-momonga-accent mb-4 border-b-2 border-momonga-pink pb-2">Introduction</h2>
        <p class="text-lg leading-relaxed">
          Momonga is a fluffy and timid little creature from the popular series Chiikawa. He is easily recognized by his white fur, big expressive eyes, and his signature pink cheeks. Despite often being nervous or scared, Momonga has a very kind heart and is a loyal friend to Chiikawa and Hachiware. His adorable reactions and gentle nature make him a beloved character.
        </p>
      </div>
    </section>

    <!-- NEW: Chi photo, styled and visible -->
    <section>
      <div class="bg-white p-6 sm:p-8 rounded-3xl card-shadow">
        <h2 class="text-3xl font-bold text-momonga-accent mb-4 border-b-2 border-momonga-pink pb-2">Featured Photo: Chi</h2>

        <!-- Wrap keeps the “open full” experience; the <img> makes it display inline -->
        <a href="./Miranda/Chi.jpg" target="_blank" rel="noopener"
           class="group block overflow-hidden rounded-3xl border-2 border-momonga-pink/40 card-shadow">
          <figure class="relative">
            <img
              src="./Miranda/Chi.jpg"
              alt="Chi from Chiikawa smiling"
              class="w-full h-auto object-cover transition-transform duration-300 group-hover:scale-[1.02]"
              loading="lazy"
            />
            <figcaption class="absolute inset-x-0 bottom-0 p-4 sm:p-5">
              <div class="backdrop-blur-sm bg-white/70 rounded-2xl px-4 py-2 inline-flex items-center gap-2">
                <span class="text-momonga-accent font-semibold">Chi</span>
                <span class="text-momonga-text text-sm">open full size</span>
              </div>
            </figcaption>
            <div class="pointer-events-none absolute inset-0 bg-gradient-to-t from-white/0 via-white/0 to-white/10"></div>
          </figure>
        </a>

        <p class="mt-3 text-center text-gray-600 text-sm">Click the image to see it full size.</p>
      </div>
    </section>

    <!-- Fun Facts Section -->
    <section>
      <div class="bg-white p-6 sm:p-8 rounded-3xl card-shadow">
        <h2 class="text-3xl font-bold text-momonga-accent mb-4 border-b-2 border-momonga-pink pb-2">Five Fluffy Facts</h2>
        <ol class="space-y-4 text-lg list-none pl-0">
          <li class="p-3 bg-momonga-bg rounded-xl flex items-start shadow-inner">
            <span class="text-momonga-accent font-extrabold text-xl mr-3 mt-0.5">1.</span>
            <p>He has a surprisingly strong and stretchy butt. In one comic, he gets stuck in a tree, and his friends use his elastic rear end like a slingshot to free him.</p>
          </li>
          <li class="p-3 bg-momonga-bg rounded-xl flex items-start shadow-inner">
            <span class="text-momonga-accent font-extrabold text-xl mr-3 mt-0.5">2.</span>
            <p>His full, proper name is actually Momonji, a pun on momo (peach) and momo (thigh), but everyone just calls him Momonga.</p>
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
            <p>His pink cheeks aren't just for show; they are specifically described as being peach-colored, which ties back into the momo (peach) part of his name.</p>
          </li>
        </ol>
      </div>
    </section>

    <!-- More Info Section -->
    <section>
      <div class="bg-momonga-accent/10 p-6 sm:p-8 rounded-3xl card-shadow border-2 border-momonga-accent">
        <h2 class="text-3xl font-bold text-momonga-accent mb-4 border-b-2 border-momonga-accent pb-2">More on Momonga</h2>
        <p class="text-xl italic leading-snug">
          His relatable anxiety and gentle heart make him an incredibly endearing character to root for. You can't help but want to protect him, and his small victories feel like a win for all of us. Ultimately, his unwavering loyalty and pure soul make him the most huggable friend in the entire series.
        </p>
      </div>
    </section>

  </main>

  <!-- Footer -->
  <footer class="mt-4 mb-10 text-center text-gray-400 text-sm">
    <p>© 2024 Momonga Fan Page. Character rights belong to Nagano / Chiikawa creators.</p>
  </footer>
</body>
</html>
