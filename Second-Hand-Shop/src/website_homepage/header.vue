<script setup>

</script>

<template>
  <header class="p-3 bg-dark text-white">
    <div class="container">
      <div class="d-flex flex-wrap align-items-center justify-content-center justify-content-lg-start">
       <!-- <a href="/" class="d-flex align-items-center mb-2 mb-lg-0 text-white text-decoration-none">
          <svg class="bi me-2" width="40" height="32" role="img" aria-label="Bootstrap"><use xlink:href="#bootstrap"></use></svg> 放圖片用
        </a>-->

        <ul class="nav col-12 col-lg-auto me-lg-auto mb-2 justify-content-center mb-md-0">
          <RouterLink to="/" class="nav-link px-5 text-white">首頁</RouterLink>
          <li><a href="#" class="nav-link px-3 text-white">分類</a></li>
          <li><a href="#" class="nav-link px-3 text-white"></a></li>
          <li><a href="#" class="nav-link px-3 text-white">關於我們</a></li>
        </ul>

        <form class="col-12 col-lg-auto mb-3 mb-lg-0 me-lg-3">
          <input type="search" class="form-control form-control-dark" placeholder="Search..." aria-label="Search">
        </form>

        <div class="text-end">
          <RouterLink to="/Login" class="btn btn-outline-light me-3">登入</RouterLink>
          <button type="button" class="btn btn-warning">註冊</button>
        </div>
      </div>
    </div>
  </header>
</template>


<style scoped>


</style>