<script setup lang="ts">
defineProps<{}>()
</script>

<template>
  <div class="greetings">
    <h1 class="green">Solutions</h1>
    <h3>to Introduction to the Theory Of Computation by Michael Sipser<br /></h3>
    <img
      src="@/assets/cover.jpg"
      class="cover"
      alt="cover of Introduction to the Theory Of Computation"
    />
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.cover {
  display: block;
  margin: 0 auto;
  max-width: 70%;
  height: auto;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
