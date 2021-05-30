<template>
  <div class="section section-introduce">
    <div class="main-section">
      <div class="section-title">
        <h1>What is attractive in Japan?</h1>
      </div>
      <div class="first-line">
        <div class="items">
          <img src="../assets/icon-sushi.svg" height="100" />
          <h3 class="item-title">Food</h3>
          <div class="item-description">
            Delicious, Healthy and Beautiful. Japanese food is not only about
            sushi, but also about many other dishes!
          </div>
        </div>
        <div class="items">
          <img src="../assets/icon-key.svg" height="100" />
          <h3 class="item-title">Safety</h3>
          <div class="item-description">
            "Even if you leave your bag on the street for one day, it will still
            be there or in police station." Japan is one of the safest countries
            in the world.
          </div>
        </div>
        <div class="items">
          <img src="../assets/icon-fuji.svg" height="100" />
          <h3 class="item-title">Nature</h3>
          <div class="item-description">
            Beaches, Mountains and Lakes. Let's see the spectacular views of
            Japan and feel the jaanese nature.
          </div>
        </div>
      </div>
      <div class="second-line">
        <div class="items">
          <img src="../assets/icon-samurai.svg" height="100" />
          <h3 class="item-title">History</h3>
          <div class="item-description">
            Samurai, Ninja are no longer alive ,but there is still a lot of
            culture left! You can learn about it on our site.
          </div>
        </div>
        <div class="items">
          <img src="../assets/icon-figure.svg" height="100" />
          <h3 class="item-title">Mentality</h3>
          <div class="item-description">
            "Omotenashi","Mottainai", "Shoganai". Some of the japanese mentality
            has been spreading around the world. On this site, we would like to
            explain this mentality a little more.
          </div>
        </div>
        <div class="items">
          <img src="../assets/icon-game.svg" height="100" />
          <h3 class="item-title">Pop Culture</h3>
          <div class="item-description">
            Anime, Manga, Computer Games. These are one of Japan's major
            products. On this site, you can learn not only those contents, but
            also songs, films and so on.
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
@import "../css/main.css";

.section-introduce .main-section {
  flex-direction: column;
  max-width: 1200px;
  margin: 0 auto;
}

.section-introduce .main-section .first-line,
.section-introduce .main-section .second-line {
  display: flex;
  justify-content: center;
  margin-top: 80px;
}

.section-introduce .main-section .items {
  width: 33%;
  padding: 0 20px;
}

.section-introduce .main-section .first-line .item-title,
.section-introduce .main-section .second-line .item-title {
  margin-top: 30px;
}
</style>