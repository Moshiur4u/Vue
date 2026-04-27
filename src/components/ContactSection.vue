<script setup>
import ContactSection from './Contact/ContactSection.vue';
import MessageSection from './Contact/MessageSection.vue';
</script>

<template>

  <section class="p-4 py-20">
    <div class="mx-auto max-w-7xl w-full">
      <div class="grid lg:grid-cols-2 grid-cols-1 items-center">
        
        <ContactSection/>
        <MessageSection/>
      </div>
    </div>
  </section>

</template>

<style scoped>
</style>