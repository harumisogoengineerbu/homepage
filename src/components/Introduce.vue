<template>
    <div class="section section-introduce">
        <div class="main-section">
            <div class="section-title">
                <h1>What is attractive in Japan?</h1>
            </div>
            <div class="first-line">
                <div class="items">
                    <img src="../assets/icon-sushi.svg" height="100">
                    <h3 class="item-title">Food</h3>
                    <div class="item-description"></div>
                </div>
                <div class="items">
                    <img src="../assets/icon-key.svg" height="100">
                    <h3 class="item-title">Safety</h3>
                    <div class="item-description"></div>
                </div>
                <div class="items">
                    <img src="../assets/icon-fuji.svg" height="100">
                    <h3 class="item-title">Nature</h3>
                    <div class="item-description"></div>
                </div>
            </div>
            <div class="second-line">
                <div class="items">
                    <img src="../assets/icon-samurai.svg" height="100">
                    <h3 class="item-title">History</h3>
                    <div class="item-description"></div>
                </div>
                <div class="items">
                    <img src="../assets/icon-figure.svg" height="100">
                    <h3 class="item-title">Mentality</h3>
                    <div class="item-description"></div>
                </div>
                <div class="items">
                    <img src="../assets/icon-game.svg" height="100">
                    <h3 class="item-title">Pop Culture</h3>
                    <div class="item-description"></div>
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

    .section-introduce .main-section .first-line, .section-introduce .main-section .second-line {
        display: flex;
        justify-content: center;
        margin-top: 80px;
    }

    .section-introduce .main-section .items {
        width: 33%;
        
    }

    .section-introduce .main-section .first-line .item-title , .section-introduce .main-section .second-line .item-title {
        margin-top: 30px;
    }
</style>