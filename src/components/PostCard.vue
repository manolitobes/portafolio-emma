<template>
  <div class="post-card">
    <h3>Presentacion</h3>
    <p>
      Ingeniero en sistemas computacionales con especialidad en bases de datos
    </p>
    <PostBotton/>
  </div>
</template>

<script lang="ts" setup>
    import PostBotton from "./PostBotton.vue";
</script>

<style scoped>
.post-card{
    background-color: black;
    border-radius: 15px;
    padding: 10px;
    margin: 5px;
    border: 1px solid white;
}

.post-card p{
    font-style: italic;
    color: white;
}
</style>
