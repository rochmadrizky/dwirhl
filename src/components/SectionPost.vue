<script setup>
import Post from "./Post.vue";
</script>
<template>
  <section id="post">
    <div class="mx-auto pb-16 md:max-w-3xl">
      <button type="button" class="w-full pt-1">
        <div class="flex h-12 w-full items-center justify-center bg-slate-300">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="icon icon-tabler icon-tabler-plus"
            width="20"
            height="20"
            viewBox="0 0 24 24"
            stroke-width="2"
            stroke="currentColor"
            fill="none"
            stroke-linecap="round"
            stroke-linejoin="round"
          >
            <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
            <path d="M12 5l0 14"></path>
            <path d="M5 12l14 0"></path>
          </svg>

          <h1 class="text-sm">ADD A ROW</h1>
        </div>
      </button>

      <div class="grid grid-cols-3 gap-1 py-1">
        <Post text="Lorem satu" />
        <Post text="Lorem dua" />
        <Post text="Lorem tiga" />

        <Post image="https://picsum.photos/200" />
        <Post
          image="https://surabayadev.org/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Flogo.81c74ae0.png&w=640&q=75"
        />
        <Post image="https://picsum.photos/200" />
      </div>
    </div>
  </section>
</template>
