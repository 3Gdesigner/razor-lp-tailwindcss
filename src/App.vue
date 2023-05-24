<script setup>
import ArrowRightIcon from "./icons/arrow-right.svg";
</script>

<template>
  <div class="min-h-screen w-full bg-gray-800 text-white">
    <div class="mx-auto max-w-7xl px-4 pt-8">
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
          <a href="#" class="hover:text-white">Request Demo</a>
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
              <div class="mt-10 flex items-center">
                <input
                  type="text"
                  class="flex-1 rounded-l-xl border-2 border-r-0 border-gray-700 bg-gray-900 px-6 py-4 leading-6 outline-none"
                />
                <button
                  class="rounded-r-xl border-2 border-l-0 border-gray-700 bg-teal-500 px-6 py-4 text-lg font-bold leading-6 text-gray-900"
                >
                  Get Link
                </button>
              </div>
              <p>
                By singing up, I agree to the Razor Privacy Policy & Terms of
                Service
              </p>
              <div>
                <button>Play Store</button>
                <button>App Store</button>
              </div>
            </div>
          </div>
        </div>
        <div class=""></div>
      </div>
    </div>
  </div>
</template>
