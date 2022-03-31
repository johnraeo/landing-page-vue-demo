<script>
export default {
  name: 'Navbar',
}
</script>

<template>
  <nav class="navbar navbar-expand-lg navbar-light">
    <div class="container">
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarTogglerDemo01" aria-controls="navbarTogglerDemo01" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <a class="navbar-brand" href="#">
        <img src="assets/png-branch.png" alt="" width="45" class="d-inline-block align-text-top">
      </a>
      <div class="collapse navbar-collapse" id="navbarTogglerDemo01">
        <a class="navbar-brand" href="#">SAMPLE</a>
        <div class="me-auto"></div>
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link" aria-current="page" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">About Us</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Services +</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Contact Us</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<style scoped>
  .navbar-brand {
    font-weight: 900;
    font-size: 2rem;
  }
  .nav-link {
    font-weight: 620;
    padding-right: 1.5rem !important;
    padding-left: 1.5rem !important;
  }
</style>