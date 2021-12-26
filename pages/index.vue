<template>
  <div>
    <header class="bg-blue-700 flex justify-center items-center p-10">
      <h1 class="font-bold text-xl md:text-3xl text-white">Simple Calculator</h1>
    </header>
    <div class="bg-gray-200">
      <input class="bg-transparent w-full text-xl md:text-5xl text-gray-700 focus:outline-none focus:border-none border-b-2 border-gray-300 p-2 text-center" type="text" />
    </div>
    <div class="grid grid-cols-4 gap-0">
      <div><btncalc label="1" /></div>
      <div><btncalc label="2" /></div>
      <div><btncalc label="3" /></div>
      <div><btncalc label="+" /></div>
      <div><btncalc label="4" /></div>
      <div><btncalc label="5" /></div>
      <div><btncalc label="6" /></div>
      <div><btncalc label="*" /></div>
      <div><btncalc label="7" /></div>
      <div><btncalc label="8" /></div>
      <div><btncalc label="9" /></div>
      <div><btncalc label="-" /></div>
      <div><btncalc label="0" /></div>
      <div><btncalc label="." /></div>
      <div><btncalc label="%" /></div>
      <div><btncalc label="=" classes="bg-green-500" /></div>

    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({});
</script>
