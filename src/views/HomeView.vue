<template>
<Video_banner />
<Portfolio />
<Servicos />
</template>

<script>
import Video_banner from "/src/components/Video_banner.vue"
import Portfolio from "/src/components/Portfolio.vue"
import Servicos from "/src/components/Servicos.vue"

export default {
  name: "HomeView",
  components: {
  Video_banner,
  Portfolio,
  Servicos
}
}

</script>

<style scoped>


</style>