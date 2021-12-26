<template>
  <button
  class="bg-gray-100 hover:bg-gray-200 p-2 w-full text-2xl md:text-4xl text-gray-500"
  @click="submit">
  {{ $attrs.label }}
  </button>
</template>

<script lang="ts">
export default {
  methods: {
    submit(num: number) {
      console.log(this)
    }
  },
};
</script>
