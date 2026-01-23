<script setup lang="ts">
import { ref } from "vue";

defineProps<{ msg: string }>();

const count = ref(0);
</script>

<template>
  <h1 class="text-5xl leading-tight font-bold">{{ msg }}</h1>
  <div class="p-8">
    <button
      type="button"
      class="rounded-lg border border-transparent bg-gray-100 px-5 py-2.5 text-base font-medium text-gray-900 transition-colors hover:border-indigo-500 focus:outline-4 dark:bg-gray-900 dark:text-white"
      @click="count++"
    >
      count is {{ count }}
    </button>
    <p class="mt-4">
      Edit
      <code
        class="rounded bg-gray-100 px-1 py-0.5 font-mono text-gray-900 dark:bg-gray-800 dark:text-white"
      >
        components/HelloWorld.vue
      </code>
      to test HMR
    </p>
  </div>

  <p>
    Check out
    <a
      href="https://vuejs.org/guide/quick-start.html#local"
      target="_blank"
      class="font-medium text-indigo-500 hover:text-indigo-400"
    >
      create-vue
    </a>
    , the official Vue + Vite starter
  </p>
  <p>
    Learn more about IDE Support for Vue in the
    <a
      href="https://vuejs.org/guide/scaling-up/tooling.html#ide-support"
      target="_blank"
      class="font-medium text-indigo-500 hover:text-indigo-400"
    >
      Vue Docs Scaling up Guide
    </a>
    .
  </p>
  <p class="text-gray-500">Click on the Vite and Vue logos to learn more</p>
</template>
