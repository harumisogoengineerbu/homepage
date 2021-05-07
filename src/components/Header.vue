<template>
  <header>
    <nav class="navbar navbar-dark bg-dark">
      <div>
        <a class="navbar-brand font-weight-bold" href="#">JAPAN-PR</a>
      </div>
      <div class="links">
        <a class="navbar-brand" href="#">Food</a>
        <a class="navbar-brand" href="#">Culture</a>
        <a class="navbar-brand" href="#">About Us</a>
        <a class="navbar-brand" href="#">Team</a>
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
  .navbar-brand:not(:last-child) {
    margin-right: 2rem;
  }
}
</style>
