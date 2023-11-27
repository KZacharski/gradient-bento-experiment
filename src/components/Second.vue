<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="p-3 w-1/3 h-full">
  <div class="card w-full h-full bg-gradient-to-b from-white to-green-100 ring-1 ring-inset ring-black ring-opacity-10">
    
  </div>
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

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
} .card {
  border-radius: 30px;
}
</style>
