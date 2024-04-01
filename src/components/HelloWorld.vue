<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="greetings">
    <h1 class="white">
      ALIF BAGAS SAPUTRA
    </h1>
    <h3>
      WELCOME TO MY BIGOGRAFI
    </h3>
    <h2>
      <a href="https://www.instagram.com/alif_bagas31/" target="_blank" rel="noopener">Instagram</a>
      <a href="https://www.tiktok.com/@alifbagas67?lang=en" target="_blank" rel="noopener">Tiktok</a>
      <a href="https://www.youtube.com/channel/UCaSGQs8rm3EK-u6KRoCnmaQ" target="_blank" rel="noopener">Youtube</a>
    </h2>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 3rem;
  position: relative;
  color: white; 
  top: -15px;
}

h2 a {
  color: #DAEE01; 
  text-decoration: none;
  margin-right: 10px;
}

h3 {
  font-size: 1.5rem;
  position: relative;
  top: -15px;
  color: white; 
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
