<script setup>
import { ref } from 'vue';
  const copyRight = ref(Date());
</script>

<template>

  <footer>
    <p>&copy;  {{copyRight}}</p>
  </footer>

</template>

<style scoped>
  footer {
      position:fixed;
      bottom:0;
      padding-bottom:20px;
  }

  footer p {
    color: blue;
  }
</style>