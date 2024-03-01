<template>
    <div class="image-container" >
        <video autoplay muted loop src="/public/Videos/filmeAntigo.mp4"></video>
    <div class="image-text">
        <h1> <u>SERVIÇOS</u></h1>
    </div>
    </div>
</template>

<script>
export default {
    name: "Servicos"
}
</script>

<style scoped>

video {
        width: 100%;
}

.image-container {
    position: relative;
}

.image-text {
    position: absolute;
    top: 10%;
    left: 44%;


    color: white;
}

</style>