<template>
  <footer class="bg-dark">
    <p class="h2 text-light fw-bold mb-4">JAPAN-PR</p>
    <nav class="navbar navbar-dark bg-dark mb-4">
      <div class="container-fluid">
        <div class="links">
          <a class="navbar-brand text-secondary" href="#">Food</a>
          <a class="navbar-brand text-secondary" href="#">Culture</a>
          <a class="navbar-brand text-secondary" href="#">About Us</a>
          <a class="navbar-brand text-secondary" href="#">Team</a>
        </div>
      </div>
    </nav>
    <div class="mb-5">
      <i class="bi bi-twitter text-light"></i>
      <i class="bi bi-facebook text-light"></i>
      <i class="bi bi-instagram text-light"></i>
    </div>
    <p class="text-secondary">Copyright ©2021 All rights reserved | This is made with by harumisogoengineerbu</p>
  </footer>
</template>

<style scoped>
footer {
  padding: 5rem 1rem 1rem 1rem;
}
.container-fluid {
  justify-content: center !important;
}
i {
  font-size: 1.5rem;
  cursor: pointer;
}
i:not(:last-child) {
  margin-right: 1.5rem;
}
@media screen and (max-width: 767px) {
  .links {
    width: 100%;
    display: flex;
    justify-content: space-between;
  }
  .navbar-brand {
    margin: 0;
  }
}
@media screen and (min-width: 768px) {
  .navbar-brand:not(:last-child) {
    margin-right: 1.5rem;
  }
}
</style>
