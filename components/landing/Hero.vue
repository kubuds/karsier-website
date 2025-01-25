<template>
  <main class="grid lg:grid-cols-1 place-items-center pt-16 pb-8 md:pt-8">
    <div class="p-16 hidden md:block">
      <img
        class="rounded-full transition-transform transform hover:scale-125"
        src="~/assets/img/hero.jpg"
        alt="KarsierOS"
        loading="eager"
        format="avif"
        width="256"
        height="256"
      />
    </div>

    <div class="place-items-center">
      <div
        class="text-4xl md:order-1 lg:text-6xl xl:text-7xl lg:tracking-tight"
      >
        <span class="font-bold text-slate-800">Karsier</span
        ><span class="text-slate-500">OS</span>
      </div>

      <p class="text-lg mt-4 text-slate-600 max-w-xl">
        For Speed, For Flex, For Tomorrow<wbr />
      </p>
      <div class="mt-6 flex flex-col sm:flex-row gap-3">
        <LandingLink href="/download" rel="noopener">Download</LandingLink>
        <LandingLink size="lg" styleName="outline" rel="noopener" href="/about"
          >About</LandingLink
        >
      </div>
    </div>
  </main>
</template>
