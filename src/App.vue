<template>
  <nav class="navbar navbar-light bg-light">
    <div class="container-fluid justify-content-start">
      <router-link to="/" class="navbar-brand" href="#">망고노트</router-link>
      <!-- <router-link :to="{ name: 'Home' }" class="navbar-brand" href="#">망고노트</router-link> -->
      <div class="navbar-nav">
        <router-link to="/todos" class="nav-link active">망고의 일정목록</router-link>
        <!-- index.js를 보면 router의 용도를 알 수 있다 -->
        <!-- <router-link :to="{ name: 'Todos' }" class="nav-link active">망고의 일정목록</router-link> -->
      </div>
    </div>
  </nav>
  <div class="container">
    <router-view />
  </div>
</template>

<script>
export default {};
</script>

<style></style>
