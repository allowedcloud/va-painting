<template>
  <div class="flex flex-col flex-1">
    <div class="flex-1 flex flex-col items-center justify-center px-6 py-12 text-center brand-font">
      <div class="relative w-full max-w-xl mb-28">
        <img
          class="block w-full h-auto rounded-t-lg mb-1"
          src="/images/michael-painting.jpg"
        >
        <div class="pointer-events-none absolute inset-x-0 bottom-0 h-[100px] bg-gradient-to-t from-white via-white/70 to-transparent" />
        <img
          class="absolute left-1/2 bottom-0 w-48 max-w-[70%] -translate-x-1/2 translate-y-1/2 drop-shadow-md"
          src="/images/logo-final.png"
          alt="VA Painting logo"
        >
      </div>
      <p class="text-base text-gray-600">
        <span class="block">
          We're putting the final brushstrokes on our <span class="whitespace-nowrap">new site.</span>
        </span>
        <span class="mt-3 block">
          Call
          <a
            class="classic-link font-semibold"
            href="tel:+17578176259"
          >
            (757) 817-6259
          </a>
          for a free estimate!
        </span>
      </p>
    </div>
    <footer class="bg-black py-4">
      <p class="text-center text-sm text-white">
        © 2025 VA Painting. All Rights Reserved.
      </p>
    </footer>
  </div>
</template>

<style scoped>
.brand-font {
  font-family: 'Montserrat', sans-serif;
}

.classic-link {
  color: #2e3192;
  text-decoration: underline;
}

.classic-link:focus-visible {
  outline: 2px solid #a5b4fc;
  outline-offset: 2px;
}
</style>
