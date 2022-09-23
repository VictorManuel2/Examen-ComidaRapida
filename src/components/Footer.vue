<template>
  <footer class="bg-primary text-center text-lg-start">
    <div class="text-center p-3" style="background-color: rgba(0, 0, 0, 0.2)">
      <p>{{ fecha }}</p>
    </div>
  </footer>
</template>
<script>
export default {
  props: {
    fecha: {
      String,
    },
  },
};
</script>
