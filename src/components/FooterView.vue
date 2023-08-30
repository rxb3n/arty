<template>
    <div class="footer-container">
        <p>© 2023 Arty MakeUp Ivory. All rights reserved.</p>

        <div class="footer-links">
            <img src="../assets/facebook.png" alt="">
            <img src="../assets/insta.webp" alt="">
            <img src="../assets/tiktok.png" alt="">
            <img src="../assets/twitter.png" alt="">
        </div>
    </div>
</template>

<style scoped>

.footer-container {
    font-family: var(--font-primary);
    font-size: calc(.59rem + 0.9vw);
    display: flex;
    justify-content: space-between;
    padding: 5%;
}

.footer-links {
    display: flex;
    justify-content: space-around;
    width: 25%;
}

.footer-links img {
    height: 5dvh;
    width: auto;
}

@media screen and (max-width: 1000px) {
    .footer-container{
        display: flex;
        flex-direction: column;
        justify-content: space-around;
    }

    .footer-links {
        padding-top: 5%;
        display: flex;
        align-items: center;
        justify-content: space-around;
        width: 50%;
    }
}

</style>