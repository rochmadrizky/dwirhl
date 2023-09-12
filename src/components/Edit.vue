<script setup>
import BtnFirst from "./BtnFirst.vue";
</script>
<template>
  <section id="edit">
    <div class="mx-auto my-16 max-w-3xl bg-slate-100">
      <div
        class="mx-auto flex max-h-screen items-center justify-center px-6 pt-12"
      >
        <div class="mx-auto rounded-lg">
          <img
            src="https://fastly.picsum.photos/id/12/400/400.jpg?hmac=_x7bdkIicWlWJj5_Ps41JHkOLSYMGUICCRq-lCytIZA"
            alt=""
            class="rounded-lg"
          />
        </div>
      </div>

      <a href="#" class="flex items-center justify-center pb-12 pt-2">
        <span class="text-sm font-semibold md:text-base">Change photo</span>
      </a>

      <form action="">
        <div class="mb-8 w-full px-4">
          <label for="deskripsi" class="text-sm text-slate-500"
            >CAPTION/HASTAG</label
          >
          <textarea
            type="text"
            id="deskripsi"
            class="h-24 w-full rounded-md bg-slate-200 p-3 focus:outline-none"
          ></textarea>
        </div>

        <div class="mb-8 w-full px-4">
          <label for="schedule" class="text-sm text-slate-500">SCHEDULE</label>
          <input
            type="text"
            id="schedule"
            class="w-full rounded-md bg-slate-200 p-3 focus:outline-none"
          />
        </div>
      </form>

      <div class="flex items-center justify-center pb-7">
        <BtnFirst>Submit</BtnFirst>
      </div>
    </div>
  </section>
</template>
