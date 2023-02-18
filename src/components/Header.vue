<template>
    <header class="header row justify-content-center h-25">
        <div class="col-6 d-flex flex-column align-items-center justify-content-center">
            <router-link to="/">
                <img class="img-fluid" src="../assets/logo.png" alt="logo image">
            </router-link>
        </div>
    </header>
</template>

<script setup>

</script>

<style scoped>
.header {
    background-image: linear-gradient(to bottom, rgba(255, 255, 255, 0.397),white), url('../assets/header-bg.jpg');
    background-position: center;
    background-size: cover;
}
</style>