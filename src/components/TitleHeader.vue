<template>
    <div class="container-fluid d-flex justify-content-center header mb-5">
        <h2 class="title">{{ msg }}</h2>
    </div>
</template>

<script>
export default {
    name: 'TitleHeader',
    props: {
        msg: String
    }
}
</script>

<style scoped>
.title {
    text-align: center;
}
.header {
    height: 30vh;
    align-items: center;
    background: rgb(217,253,251);
    background: linear-gradient(0deg, rgba(217,253,251,1) 27%, rgba(255,255,255,1) 90%);
}
</style>