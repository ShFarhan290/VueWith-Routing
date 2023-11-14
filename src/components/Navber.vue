<template>
    <nav class="navbar navbar-expand-lg navbar-light bg-white py-3">
        <div class="container px-5">
            <a class="navbar-brand" href="index.html"><span class="fw-bolder text-primary">Start Bootstrap</span></a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation"><span class="navbar-toggler-icon"></span></button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav ms-auto mb-2 mb-lg-0 small fw-bolder">
                    <li class="nav-item"><RouterLink to="./" class="nav-link">Home</RouterLink></li>
                    <li class="nav-item"><RouterLink to="./resume" class="nav-link">Resume</RouterLink></li>
                    <li class="nav-item"><RouterLink to="./project" class="nav-link">Projects</RouterLink></li>
                    <li class="nav-item"><RouterLink to="./contact" class="nav-link">Contact</RouterLink></li>
                </ul>
            </div>
        </div>
    </nav>
</template>

<script setup>
</script>

<style scoped>
</style>