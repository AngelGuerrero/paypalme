<script lang="ts" setup>
const message: string = "Hello from TypeScript!";

useMeta({
  title: message
})
</script>

<template>
  <div class="grid items-center justify-center min-h-screen dev">
    <div
      class="
      max-w-sm
      px-4
      py-2
    bg-gray-900
      border
      rounded-sm
    border-gray-50"
    >
      <h1 class="font-sans text-3xl">{{ message }}</h1>
    </div>
  </div>
</template>
