<script setup>
import ArrowRightIcon from "./icons/arrow-right.svg";
import AppleIcon from "./icons/apple.svg";
import playstoreIcon from "./icons/play-store.svg";
</script>

<template>
  <div class="relative min-h-screen w-full bg-gray-800 text-white">
    <img
      src="/img/circle.svg"
      class="lef-0 absolute top-0 -translate-x-1/4 -translate-y-1/4 opacity-40"
      alt=""
    />
    <div class="absolute inset-y-0 right-0 w-2/5 bg-gray-900"></div>
    <div class="relative mx-auto max-w-7xl px-4 pt-8">
      <nav class="flex items-center justify-between">
        <div class="flex items-center gap-32">
          <a href="#" class="text-2xl font-bold">Razor</a>
          <ul class="flex items-center gap-12 font-medium text-gray-500">
            <li><a href="#" class="hover:text-white">Product</a></li>
            <li><a href="#" class="hover:text-white">Resoureces</a></li>
            <li><a href="#" class="hover:text-white">Support</a></li>
            <li><a href="#" class="hover:text-white">Pricing</a></li>
            <li><a href="#" class="hover:text-white">Blog</a></li>
          </ul>
        </div>
        <div class="flex items-center gap-4 font-medium text-gray-500">
          <a href="#" class="hover:text-white">Sign In</a>
          <a href="#" class="relative hover:text-white">
            <span>Request Demo</span>
            <img
              src="/img/decoration.svg"
              class="absolute left-0 w-32"
              alt=""
            />
          </a>
        </div>
      </nav>
      <div class="grid grid-cols-2 pt-6">
        <div class="max-w-xl pr-24">
          <div>
            <div
              class="bordet-t flex w-36 items-center gap-6 border-gray-700 pt-2"
            >
              <span class="text-sm text-teal-500">Sales@razor.uk</span>
              <ArrowRightIcon class="h-4 w-4 text-teal-500" />
            </div>
            <div class="pt-16">
              <span>&#8212;Get the app</span>
              <h2
                class="bg-gradient-to-br from-blue-400 to-emerald-400 bg-clip-text pt-16 text-6xl font-bold tracking-tight text-transparent"
              >
                Enter you email <br />
                &#8212; We´ll send you a download link
              </h2>
              <img src="/img/decoration.svg" class="-mt-2 w-96" alt="" />
              <div
                class="mt-10 flex items-center rounded-xl shadow-glow focus-within:shadow-teal-500/40 transition-shadow ease-out"
              >
                <input
                  type="text"
                  class="flex-1 rounded-l-xl border-2 border-r-0 border-gray-700 bg-gray-900 px-8 py-4 leading-6 outline-none"
                  placeholder="Sales@dstudio.digital"
                />
                <button
                  class="rounded-r-xl border-2 border-l-0 border-gray-700 bg-teal-500 px-8 py-4 text-lg font-bold leading-6 text-gray-900"
                >
                  Get Link
                </button>
              </div>
              <p class="pt-8 font-normal tracking-wide text-gray-600">
                By singing up, I agree to the Razor
                <a href="#" class="text-gray-500 underline">Privacy Policy</a> &
                <a href="#" class="text-gray-500 underline">Terms of Service</a>
              </p>
              <div class="flex items-center gap-4 pt-12">
                <button
                  class="flex items-center gap-2 rounded-xl bg-gray-900 px-6 py-4 text-gray-500 shadow-glow transition ease-out hover:shadow-teal-500/40" 
                >
                  <playstoreIcon class="h-7 w-7" /> Play Store
                </button>
                <button
                  class="flex items-center gap-2 rounded-xl bg-gray-900 px-6 py-4 text-gray-500 shadow-glow transition ease-out hover:shadow-teal-500/40" 
                >
                  <AppleIcon class="h-7 w-7" /> App Store
                </button>
              </div>
            </div>
          </div>
        </div>
        <div class="mt-10">
          <div class="flex items-center gap-8">
            <img src="/img/screen-1.png" class="h-full w-64 animate-hover" alt=""  />
            <img src="/img/screen-2.png" class="h-full w-64 pt-20 animate-hover" alt=""  />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
