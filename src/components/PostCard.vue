<template>
  <!-- From Uiverse.io by Yaya12085 -->
  <div class="card">
    <div class="header">
      <span class="title">Emmanuel Ramirez Ramirez</span>
      <span class="subtittle">Ingeniero sistemas computacionales</span>
    </div>
    <p class="desc">Manejo de lenguajes de programacion y administracion de bases de datos.</p>
    <ul class="lists">
      <li class="list">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 20 20"
          fill="currentColor"
        >
          <path
            fill-rule="evenodd"
            d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
            clip-rule="evenodd"
          ></path>
        </svg>
        <span>Java,Python,C++</span>
      </li>
      <li class="list">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 20 20"
          fill="currentColor"
        >
          <path
            fill-rule="evenodd"
            d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
            clip-rule="evenodd"
          ></path>
        </svg>
        <span>MySQL,PostgresSQL,MongoDB</span>
      </li>
      <li class="list">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 20 20"
          fill="currentColor"
        >
          <path
            fill-rule="evenodd"
            d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
            clip-rule="evenodd"
          ></path>
        </svg>
        <span>Ingles Intermedio</span>
      </li>
    </ul>
    <PostBotton/>
  </div>
</template>

<script lang="ts" setup>
import PostBotton from "./PostBotton.vue";
</script>

<style scoped>
/* From Uiverse.io by Yaya12085 */
.card {
  margin-left: -1rem;
  margin-right: -1rem;
  display: flex;
  flex-wrap: wrap;
  align-items: stretch;
  margin-bottom: 2rem;
  width: 320px;
  display: flex;
  flex-direction: column;
  border-radius: 0.25rem;
  background-color: rgba(17, 24, 39, 1);
  padding: 1.5rem;
}

.header {
  display: flex;
  flex-direction: column;
}

.title {
  font-size: 1.5rem;
  line-height: 2rem;
  font-weight: 700;
  color: #fff;
}

.subtittle {
  font-size: 2.00rem;
  line-height: 1;
  font-weight: 700;
  color: #fff;
}

.desc {
  margin-top: 0.75rem;
  margin-bottom: 0.75rem;
  line-height: 1.625;
  color: rgba(156, 163, 175, 1);
}

.lists {
  margin-bottom: 1.5rem;
  flex: 1 1 0%;
  color: rgba(156, 163, 175, 1);
}

.lists .list {
  margin-bottom: 0.5rem;
  display: flex;
  margin-left: 0.5rem;
}

.lists .list svg {
  height: 1.5rem;
  width: 1.5rem;
  flex-shrink: 0;
  margin-right: 0.5rem;
  color: rgba(167, 139, 250, 1);
}

.action {
  border: none;
  outline: none;
  display: inline-block;
  border-radius: 0.25rem;
  background-color: rgba(167, 139, 250, 1);
  padding-left: 1.25rem;
  padding-right: 1.25rem;
  padding-top: 0.75rem;
  padding-bottom: 0.75rem;
  text-align: center;
  font-weight: 600;
  letter-spacing: 0.05em;
  color: rgba(17, 24, 39, 1);
}
</style>
