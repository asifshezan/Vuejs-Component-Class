<script setup>
import tagLine from './components/tagLine.vue';
import hero from './components/hero.vue';
import videoButton from './components/videoButton.vue';
import logo from './/components/logo.vue';
</script>

<template>
<section class="bg-white dark:bg-gray-900">
    <div class="py-8 px-4 mx-auto max-w-screen-xl text-center lg:py-16 lg:px-12">
      <tagLine/>
        <hero/>
        <div class="flex flex-col mb-8 lg:mb-16 space-y-4 sm:flex-row sm:justify-center sm:space-y-0 sm:space-x-4">
          <videoButton/>
        </div>
        <logo/>
    </div>
</section>
</template>

<style scoped>

</style>
