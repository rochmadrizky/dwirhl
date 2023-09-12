<script setup>
import BtnFirst from "./BtnFirst.vue";
</script>
<template>
  <section id="profile">
    <div class="mx-auto pt-14 md:max-w-3xl">
      <div class="mx-auto px-4">
        <div class="mx-auto flex items-center justify-between py-8">
          <div class="mx-auto flex items-center justify-center px-2 md:px-16">
            <img
              src="https://fastly.picsum.photos/id/877/300/300.jpg?hmac=uJHO3bgLZAfdAOBmDOE-V7vqPsOBtYgAxRYpNtIIDmw"
              alt="welcome"
              class="h-20 w-20 rounded-full md:h-40 md:w-40"
            />

            <div class="mx-auto px-1 md:px-16">
              <div class="mx-auto flex items-center justify-center gap-5 pb-4">
                <h1 class="text-base font-semibold md:text-xl">Dwi Rahayu</h1>

                <BtnFirst>
                  <span class="font-semibold">Follow</span>
                </BtnFirst>
              </div>

              <ul class="mx-auto">
                <li class="flex gap-2 px-6 md:gap-5">
                  <button class="space-x-1 text-xs md:text-base">
                    <span>50</span>
                    <span>Post</span>
                  </button>

                  <button class="space-x-1 text-xs md:text-base">
                    <span>1000</span>
                    <span>Follower</span>
                  </button>

                  <button class="space-x-1 text-xs md:text-base">
                    <span>100</span>
                    <span>Following</span>
                  </button>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
