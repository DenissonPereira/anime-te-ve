<template>
    <div class="susanoo">
        <img src="/images/susanoo.jpg" alt="">
    </div>
    <div class="logo">
        <img src="/images/rinnegan.png" alt="" id="rine">
    </div>
    <div class="titulo">
        <h1><span class="simbolo">&deg;</span> Anime &nbsp; Te &nbsp; Ve <span class="simbolo">&deg;</span></h1>
    </div>
</template>

<style>
    .susanoo {
        position: relative;
    }
    .logo {
        position: absolute;
        left: 50%;
        transform: translate(-50%, -50%);
    }
    .logo img {
        width: 10em;
    }
    .susanoo img {
        width: 100%;
    }
    #rine {
        animation: rotate 3s linear infinite;
    }

    @keyframes rotate {
        0% {
            transform: rotate(0deg);
        }
        100% {
            transform: rotate(360deg);
        }
    }
    @media (max-width: 780px) {
        .logo img {
            width: 3em;
        }
    }
</style>