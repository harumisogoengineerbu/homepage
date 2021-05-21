<template>
  <div class="member">
    <p class="h1 mb-5">Member</p>
    <div class="row">
      <div class="col-sm-6 mb-4">
        <div><img src="@/assets/kuri.jpg"></div>
        <div class="py-3">
          <p class="h3 fw-bold">KURI</p>
          <p>Engineer</p>
        </div>
      </div>
      <div class="col-sm-6 mb-4">
        <div>
          <img src="@/assets/take.jpg">
        </div>
        <div class="py-3">
          <p class="h3 fw-bold"> TAKE</p>
          <p>Engineer</p>
        </div>
      </div>
    </div>
    <div class="row justify-content-center">
      <div class="col-sm-6">
        <div>
          <img src="@/assets/shika.jpg">
        </div>
        <div class="py-3">
          <p class="h3 fw-bold">SHIKA</p>
          <p>Servant</p>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.member {
  margin: 0 10vw;
}
img {
  width: 200px;
  height: 200px;
  border-radius: 50%;
}
</style>
