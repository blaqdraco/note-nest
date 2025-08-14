<template>
  <div class = "flex bg-black h h-screen">

  
    <div class="bg-zinc-900 w-[516px] rounded-xl shadow-lg flex flex-col items-center py-10 px-8">
      <Logo class="mb-8" />
      <h1 class="text-white font-extrabold text-2xl mb-2 tracking-tight">Sign up for a free account</h1>
      <p class="text-zinc-300 text-sm mb-6">Already registered?
        <NuxtLink to="/login" class="font-bold text-[#FFAC00] underline hover:text-amber-400 transition-colors">Log in</NuxtLink> to your account
      </p>

      <form class="w-full space-y-8">
        <div>
          <label for="email" class="block text-zinc-300 text-sm mb-2">Email Address</label>
          <input id="email" name="email" type="email" autocomplete="email" required placeholder="you@example.com"
            class="block w-full bg-zinc-800 border border-zinc-700 focus:border-[#FFAC00] focus:ring-2 focus:ring-[#FFAC00]/30 rounded-md px-4 py-2 placeholder:text-zinc-500 text-sm text-white transition-all duration-150 outline-none" />
        </div>

        <div>
          <label for="password" class="block text-zinc-300 text-sm mb-2">Password</label>
          <input id="password" name="password" type="password" autocomplete="new-password" required placeholder="*************"
            class="block w-full bg-zinc-800 border border-zinc-700 focus:border-[#FFAC00] focus:ring-2 focus:ring-[#FFAC00]/30 rounded-md px-4 py-2 placeholder:text-zinc-500 text-sm text-white transition-all duration-150 outline-none" />
        </div>

        <div>
          <button type="submit" class="w-full mt-2 bg-[#FFAC00] hover:bg-amber-400 text-black font-bold py-2 rounded-md shadow transition-all duration-150 focus:outline-none focus:ring-2 focus:ring-[#FFAC00]/40">Sign Up</button>
        </div>
      </form>
    </div>


    <!-- /sidebar -->
    <!-- note introduction -->
     <div> </div>
    <!-- Right panel / Hero -->
    <div class="flex-1 relative flex items-center justify-center px-14 py-20 overflow-hidden">
      <!-- background gradient -->
      <div class="absolute inset-0 bg-gradient-to-br from-zinc-900 via-zinc-800 to-black"></div>
      <!-- subtle grid -->
      <div class="pointer-events-none absolute inset-0 opacity-20 [mask-image:radial-gradient(circle_at_center,black,transparent)]">
        <div class="absolute inset-0 bg-[linear-gradient(to_right,#27272a_1px,transparent_1px),linear-gradient(to_bottom,#27272a_1px,transparent_1px)] bg-[size:48px_48px]"></div>
      </div>
      <!-- accent orbs -->
      <div class="absolute -top-24 -right-24 h-72 w-72 rounded-full bg-[#FFAC00]/10 blur-3xl"></div>
      <div class="absolute bottom-0 left-10 h-56 w-56 rounded-full bg-amber-500/5 blur-2xl"></div>

      <div class="relative max-w-xl text-zinc-200">
        <div class="inline-flex items-center gap-2 rounded-full border border-zinc-700/60 bg-zinc-800/60 backdrop-blur px-4 py-1.5 text-xs tracking-wide text-zinc-300 shadow-sm">
          <span class="h-2 w-2 rounded-full bg-[#FFAC00] animate-pulse"></span>
          Reimagined note‑taking
        </div>
        <h2 class="mt-6 text-4xl font-bold leading-tight text-white sm:text-5xl">
          Capture ideas at the speed of thought
        </h2>
        <p class="mt-5 text-base leading-relaxed text-zinc-400">
          Organize notes, tasks, and knowledge in one unified space. Powerful search, keyboard‑first design, and real‑time sync help you stay in flow.
        </p>

        <ul class="mt-8 space-y-4 text-sm">
          <li class="flex items-start gap-3">
            <span class="mt-1 inline-flex h-5 w-5 items-center justify-center rounded-md bg-[#FFAC00]/15 text-[#FFAC00]">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-3.5 w-3.5" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="3">
                <path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7"/>
              </svg>
            </span>
            Lightning‑fast full‑text search
          </li>
          <li class="flex items-start gap-3">
            <span class="mt-1 inline-flex h-5 w-5 items-center justify-center rounded-md bg-[#FFAC00]/15 text-[#FFAC00]">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-3.5 w-3.5" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="3">
                <path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7"/>
              </svg>
            </span>
            Secure end‑to‑end encryption
          </li>
          <li class="flex items-start gap-3">
            <span class="mt-1 inline-flex h-5 w-5 items-center justify-center rounded-md bg-[#FFAC00]/15 text-[#FFAC00]">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-3.5 w-3.5" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="3">
                <path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7"/>
              </svg>
            </span>
            Collaborative real‑time editing
          </li>
        </ul>

        <div class="mt-10 flex flex-wrap items-center gap-4 text-xs text-zinc-500">
          <span class="flex items-center gap-2">
            <span class="inline-block h-2 w-2 rounded-full bg-emerald-500"></span>
            99.99% uptime
          </span>
          <span class="flex items-center gap-2">
            <span class="inline-block h-2 w-2 rounded-full bg-sky-500"></span>
            Sync across devices
          </span>
          <span class="flex items-center gap-2">
            <span class="inline-block h-2 w-2 rounded-full bg-fuchsia-500"></span>
            Dark mode native
          </span>
        </div>
      </div>
    </div>
  </div>
</template>
