<!-- Featured Photo Section -->
<section>
  <div class="bg-white p-6 sm:p-8 rounded-3xl card-shadow">
    <h2 class="text-3xl font-bold text-momonga-accent mb-4 border-b-2 border-momonga-pink pb-2">
      Featured Photo: Chi
    </h2>

    <!-- Aesthetic image card with overlay and soft hover -->
    <a href="Miranda/Chi.jpg" target="_blank" rel="noopener"
       class="group block overflow-hidden rounded-3xl border-2 border-momonga-pink/40 card-shadow">
      <figure class="relative">
        <img
          src="Miranda/Chi.jpg"  <!-- Si tu archivo es .png/.webp, cambia la extensión aquí y en el href -->
          alt="Chi de Chiikawa sonriendo"
          class="w-full h-auto object-cover transition-transform duration-300 group-hover:scale-[1.02]"
          loading="lazy"
        />
        <!-- Soft gradient + caption -->
        <figcaption class="absolute inset-x-0 bottom-0 p-4 sm:p-5">
          <div class="backdrop-blur-sm bg-white/70 rounded-2xl px-4 py-2 inline-flex items-center gap-2">
            <span class="text-momonga-accent font-semibold">Chi</span>
            <span class="text-momonga-text text-sm">open full size</span>
          </div>
        </figcaption>

        <!-- Subtle top gradient for depth -->
        <div class="pointer-events-none absolute inset-0 bg-gradient-to-t from-white/0 via-white/0 to-white/10"></div>
      </figure>
    </a>

    <!-- Optional helper text -->
    <p class="mt-3 text-center text-gray-600 text-sm">
      Toca la imagen para verla a tamaño completo.
    </p>
  </div>
</section>
