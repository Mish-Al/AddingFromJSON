<template>
    <div>
        <nav class="navbar navbar-expand-lg bg-body-tertiary">
  <div class="container-fluid">
    <a class="navbar-brand" href="https://i.postimg.cc/V5QN8Rkb/Screenshot-2023-06-10-224958-removebg-preview.png">
        <img src="https://i.postimg.cc/V5QN8Rkb/Screenshot-2023-06-10-224958-removebg-preview.png" alt="logo">
    </a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="../views/HomeView.vue">Home</a>
        </li>
      </ul>
    </div>
  </div>
</nav>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
.container-fluid{
    background-color: rgb(40, 40, 40);;
}
.container-fluid .navbar-brand img{
    height: 10rem;
}
#navbarSupportedContent li a{
    color: rgb(129, 127, 127);
}

</style>