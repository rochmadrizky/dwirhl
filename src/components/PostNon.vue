<script setup></script>
<template>
  <div
    class="group relative flex aspect-square items-center justify-center overflow-hidden rounded-sm"
  >
    <a href="" class="text-center">
      Lorem ipsum dolor sit amet consectetur adipisicing elit.
    </a>

    <button
      type="button"
      onclick="alert('it works')"
      class="absolute left-0 top-0 hidden h-full w-full items-center justify-center bg-black opacity-70 transition-opacity group-hover:flex"
    >
      <span class="rounded-lg bg-white px-4 py-1 font-semibold text-black">
        Edit
      </span>
    </button>
  </div>
</template>
