<template>
    <div class="post-container">
        <PostCard/>
    </div>
</template>

<script lang="ts" setup>
import PostCard from './PostCard.vue';
</script>

<style>

.post-container{
    display: flex;
    justify-content: center; /* Horizontal */
    align-items: center; /*Vertical*/
    height: 100vh; /*Ocupa toda la pantalla*/
}
</style>