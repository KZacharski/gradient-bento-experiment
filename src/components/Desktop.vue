<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="p-3 w-2/3 h-full">
  <div class="card w-full h-full bg-gradient-to-b from-white to-green-100 ring-1 ring-inset ring-black ring-opacity-10 relative overflow-hidden">
    <div class="flex flex-row h-full w-full">
    <div class="flex flex-row w-full items-center justify-center">
      <div class="flex flex-col pl-5 pr-5">
      <h2 class="">Desktop window</h2>
      <p class="">Idk some description lorem ipsum whatever</p>
      </div>
    </div>
    <div class="flex justify-end content-end h-full">
    <img src="../assets/desktop.svg" class="image-card align-end justify-end self-end justify-self-end">
    </div>
    </div>
  </div>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
} p {
  font-size: large;
  font-weight: 500;
  width:;
}

h3 {
  font-size: 1.2rem;
} h2 {
  font-size: xx-large;
  font-weight: 700;
  width:;
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
}  .image-card {
  width: 40rem;
}
</style>
