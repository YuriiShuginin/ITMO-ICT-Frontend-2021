<template>

  <div class="container">
    <div class="row justify-content-between mt-4">
      <div class="col-1">
        <router-link to="/home">
          <span class="d-flex align-items-left mb-3 mb-md-0 me-md-auto text-dark">Моя погода</span>
        </router-link>
      </div>
      <div class="col-1">
        <router-link to="/weatherhere">
          <span class="d-flex align-items-left mb-3 mb-md-0 me-md-auto text-dark">Погода здесь</span>
        </router-link>
      </div>
      <div class="col-1">
        <router-link to="/search">
          <span class="d-flex align-items-left mb-3 mb-md-0 me-md-auto text-dark text-decoration-none">Поиск</span>
        </router-link>
      </div>
      <div class="col-1">
        <router-link to="/settings">
          <span class="d-flex align-items-left mb-3 mb-md-0 me-md-auto text-dark text-decoration-none">Выбор городов</span>
        </router-link>
      </div>
      <div class="col-1">
        <router-link to="/">
          <span class="d-flex align-items-left mb-3 mb-md-0 me-md-auto text-dark text-decoration-none">Выйти</span>
        </router-link>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style scoped>

</style>
