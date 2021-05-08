<template>
  <header>
    <nav class="navbar navbar-dark bg-dark">
      <div class="container-fluid">
        <div>
          <a class="navbar-brand fw-bold" href="#">JAPAN-PR</a>
        </div>
        <div class="links">
          <a class="navbar-brand" href="#">Food</a>
          <a class="navbar-brand" href="#">Culture</a>
          <a class="navbar-brand" href="#">About Us</a>
          <a class="navbar-brand" href="#">Team</a>
        </div>
      </div>
    </nav>
  </header>
</template>

<style scoped>
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
  .navbar {
    padding: 1rem 0;
  }
  .navbar-brand:not(:last-child) {
    margin-right: 2rem;
  }
}
</style>
