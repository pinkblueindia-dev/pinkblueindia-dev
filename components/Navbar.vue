<script setup>
const menuitems = [
  {
    title: "Shop",
    url: "/",
  },
  {
    title: "Collections",
    url: "/collections",
  },
  {
    title: "Contact",
    url: "/contact",
  },
];
</script>

<template>
  <Container>
    <header class="flex flex-row flex-wrap items-center justify-between my-4 gap-x-6 gap-y-4">

      <!-- Logo -->
      <div class="flex items-center">
        <a href="/" class="flex items-center">
          <img
            src="/images/logo.png"
            alt="PinkBlueIndia"
            class="h-10 w-auto"
          />
        </a>
      </div>

      <!-- Navigation -->
      <nav class="flex w-auto">
        <ul class="flex flex-row gap-3 text-sm">
          <li v-for="item of menuitems" :key="item.title">
            <a
              :href="item.url"
              class="flex px-3 py-2 text-gray-600 border rounded-sm hover:text-gray-900"
            >
              {{ item.title }}
            </a>
          </li>
        </ul>
      </nav>

    </header>
  </Container>
</template>
