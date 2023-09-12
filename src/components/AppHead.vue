<script setup></script>
<template>
  <header class="fixed left-0 right-0 top-0 z-50">
    <nav class="mx-auto md:max-w-3xl">
      <div
        class="flex h-16 w-full items-center justify-between bg-slate-300 px-2 md:px-4"
      >
        <div class="flex gap-4">
          <button type="button">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="icon icon-tabler icon-tabler-menu-2"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              stroke-width="2"
              stroke="currentColor"
              fill="none"
              stroke-linecap="round"
              stroke-linejoin="round"
            >
              <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
              <path d="M4 6l16 0"></path>
              <path d="M4 12l16 0"></path>
              <path d="M4 18l16 0"></path>
            </svg>
          </button>

          <div>
            <button type="button" class="flex items-center gap-1">
              <img
                src="https://ui-avatars.com/api/?name=d+r"
                alt=""
                class="h-8 w-8 rounded-full md:h-10 md:w-10"
              />

              <span class="text-sm font-semibold md:text-base">
                Dwi Rahayu
              </span>

              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="icon icon-tabler icon-tabler-chevron-down"
                width="24"
                height="24"
                viewBox="0 0 24 24"
                stroke-width="2"
                stroke="currentColor"
                fill="none"
                stroke-linecap="round"
                stroke-linejoin="round"
              >
                <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                <path d="M6 9l6 6l6 -6"></path>
              </svg>
            </button>
          </div>
        </div>

        <div class="flex items-center gap-2">
          <button type="checkbox" class="flex items-center gap-1">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="icon icon-tabler icon-tabler-select"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              stroke-width="2"
              stroke="currentColor"
              fill="none"
              stroke-linecap="round"
              stroke-linejoin="round"
            >
              <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
              <path
                d="M3 3m0 2a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2h-14a2 2 0 0 1 -2 -2z"
              ></path>
              <path d="M9 11l3 3l3 -3"></path>
            </svg>

            <span>Select</span>
          </button>

          <button type="button">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="icon icon-tabler icon-tabler-calendar"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              stroke-width="2"
              stroke="currentColor"
              fill="none"
              stroke-linecap="round"
              stroke-linejoin="round"
            >
              <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
              <path
                d="M4 7a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2h-12a2 2 0 0 1 -2 -2v-12z"
              ></path>
              <path d="M16 3v4"></path>
              <path d="M8 3v4"></path>
              <path d="M4 11h16"></path>
              <path d="M11 15h1"></path>
              <path d="M12 15v3"></path>
            </svg>
          </button>
        </div>
      </div>
    </nav>
  </header>
</template>
