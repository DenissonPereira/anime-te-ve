<template>
    <div class="slogam">
        <h1>ANIME TE VE: O Portal dos Sonhos Animados, Onde a Magia Ganha Vida!</h1>
    </div>
    <div class="body">
        <div class="grupo_corpo">
            <div class="image">
                <img src="/images/news/pxfuel.jpg" alt="">
            </div>
            <div class="text">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Laborum repellendus dolore totam placeat beatae
                    temporibus.</p>
            </div>
        </div>
        <div class="grupo_corpo">
            <div class="image">
                <img src="/images/news/yugioh.jpg" alt="">
            </div>
            <div class="text">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Laborum repellendus dolore totam placeat beatae
                temporibus.</p>
            </div>
        </div>
        <div class="grupo_corpo">
            <div class="image">
                <img src="/images/news/dragon.jpg" alt="">
            </div>
            <div class="text">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Laborum repellendus dolore totam placeat beatae
                temporibus.</p>
            </div>
        </div>
    </div>
</template>

<style>
    .slogam {
        margin-top: 6em;
        text-align: center;
    }
    .body {
        margin-top: 2em;
        display: flex;
        justify-content: center;
        gap: 2em;
        align-content: space-around;
    }
    .grupo_corpo img {
        width: 19em;
        height: 17em;
        border-radius: 1em;
    }
    .grupo_corpo {
        display: flex;
        flex-direction: column;
        align-content: center;
        align-items: center;
        margin: 0;
        padding: 0;
        outline: none;
    }
    .text {
        width: 22em;
        font-size: 1em;
        text-align: center;
        padding: 1em;
    }

</style>