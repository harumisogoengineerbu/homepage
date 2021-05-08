<template>
    <div id="foods" class="section section-foods">
        <div class="main-section">
            <div class="section-title">
                <h1>Japanese Foods</h1>
            </div>
            <div class="first-line">
                <div class="left-column">
                    <img src="../assets/sushi.jpg" height="400" />
                </div>
                <div class="right-column">
                    <h1>Sushi</h1>
                    <p></p>
                </div>
            </div>
            <div class="second-line">
                <div class="left-column">
                    <h1>Okonomiyaki</h1>
                    <p></p>
                </div>
                <div class="right-column">
                    <img src="../assets/okonomiyaki.jpg" height="400" />
                </div>
            </div>
            <div class="third-line">
                <div class="left-column">
                    <img src="../assets/ramen.jpg" height="400" />
                </div>
                <div class="right-column">
                    <h1>Ramen</h1>
                    <p></p>
                </div>
            </div>
        </div>
    </div>
</template>

<style>
    @import "../css/main.css";

    .section-foods {
        max-width: 1250px;
    }

    .section-foods .main-section {
        flex-direction: column;
    }

    .section-foods .main-section .section-title {
        margin-bottom: 80px;
    }

    .section-foods .first-line, .section-foods .second-line, .section-foods .third-line {
        display: flex;
        margin-top: 20px;
    }

    .section-foods .first-line .left-column,
    .section-foods .first-line .right-column,
    .section-foods .second-line .left-column,
    .section-foods .second-line .right-column,
    .section-foods .third-line .left-column,
    .section-foods .third-line .right-column {
        width: 50%;
    }
</style>
