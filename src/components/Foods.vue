<template>
    <div id="foods" class="section section-foods">
        <div class="main-section">
            <div class="section-title">
                <h1>Japanese Foods</h1>
            </div>
            <div class="first-line">
                <div class="left-column">
                    <img src="../assets/sushi.jpg" height="500" />
                </div>
                <div class="right-column">
                    <h1>How can you eat sushi correctly?</h1>
                    <p v-on:click="showAnswerSushi =! showAnswerSushi">hallo</p>
                    <p v-show="showAnswerSushi">yes</p>
                </div>
            </div>
            <div class="second-line">
                <div class="left-column">
                    <h1>What do you put in okonomiyaki?</h1>
                    <p></p>
                </div>
                <div class="right-column">
                    <img src="../assets/okonomiyaki.jpg" height="500" />
                </div>
            </div>
            <div class="third-line">
                <div class="left-column">
                    <img src="../assets/ramen.jpg" height="500" />
                </div>
                <div class="right-column">
                    <h1>Introduction to the various ramen shops</h1>
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

    .section-foods .first-line, .section-foods .second-line, .section-foods .third-line {
        display: flex;
        margin-top: 80px;
    }

    .section-foods .first-line .left-column,
    .section-foods .first-line .right-column,
    .section-foods .second-line .left-column,
    .section-foods .second-line .right-column,
    .section-foods .third-line .left-column,
    .section-foods .third-line .right-column {
        width: 50%;
    }

    .section-foods .first-line .left-column,
    .section-foods .second-line .right-column,
    .section-foods .third-line .left-column {
        background-image: url(../assets/black-circle.jpeg);
        background-repeat: no-repeat;
        background-size: contain;
        background-position: center;
    }

    .section-foods .first-line .right-column,
    .section-foods .second-line .left-column,
    .section-foods .third-line .right-column {
        background-color: #2c3e50;
        border-radius: 5%;
    }

    .section-foods .left-column h1,
    .section-foods .right-column h1 {
        font-size: 2.0em;
        color: #fff;
        padding-top: 10px;
    }

    .section-foods .left-column p,
    .section-foods .right-column p {
        color: #fff;
        margin: 0;
    }

    .section-foods .first-line .left-column img,
    .section-foods .second-line .right-column img,
    .section-foods .third-line .left-column img {
        padding: 100px;
        border-radius: 30%;
    }
</style>
