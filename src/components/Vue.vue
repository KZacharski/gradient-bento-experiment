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
  <div class="card w-full h-full bg-gradient-to-b from-white to-green-100 ring-1 ring-inset ring-black ring-opacity-10 relative overflow-hidden hover:shadow-2xl hover:shadow-green-200 transition duration-300 ease-in-out">
    <div class="flex flex-row h-full w-full">
    <div class="flex flex-row w-full items-center justify-center">
      <div class="flex flex-col pl-5 pr-5">
      <h2 class="text-top">Vue whatever</h2>
      <p class="text-bottom">This looked much better in my head help</p>
      </div>
    </div>
    <div class="flex justify-end content-end h-full">
    <img src="../assets/vue.svg" class="image-card align-end justify-end self-end justify-self-end">
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
  width: 25rem;
} .text-top {
  background-image: linear-gradient(180deg, #4ADE80, #22C55E);
  background-clip: text;
  color: transparent;
}
.text-bottom {
  background-image: linear-gradient(180deg, #22C55E, #16A34A);
  background-clip: text;
  color: transparent;
}
</style>
