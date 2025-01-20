<script>
export default {
  name: 'app',
  components: {

  },
  data() {
    return {
      selected: "home"
    }
  }
}
</script>

<template>
  <div>
    <div class="text-xl p-3 flex justify-between fixed top-0 w-full z-20" id="nav-container">
      <a href="https://humanity.gdoc.fr"><p class="font-semibold">Retour au GDoc</p></a>
    </div>
  </div>
</template>

<style scoped>
#nav-container {
  backdrop-filter: blur(8px);
  background-color: #101010A0;
}
</style>
