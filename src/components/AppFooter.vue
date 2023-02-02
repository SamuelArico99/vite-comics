<script>

export default {
    name: "AppFooter",
}

</script>

<template>
    <footer>
        <section class="merchandise">
            <div class="container">
                <div>
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                    <span>DIGITAL COMICS</span>
                </div>
                <div>
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                    <span>DIGITAL COMICS</span>
                </div>
                <div>
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                    <span>DIGITAL COMICS</span>
                </div>
                <div>
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                    <span>DIGITAL COMICS</span>
                </div>
                <div>
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                    <span>DIGITAL COMICS</span>
                </div>
            </div>

        </section>
        <section class="contacts-terms">

        </section>
        <section class="sign-up">

        </section>
    </footer>
</template>

<style lang="scss" scoped>
.merchandise {
    width: 100%;
    height: 250px;
    background-color: #0282f9;
    display: flex;
    justify-content: center;

    .container {
        width: 70%;
        height: 100%;
        display: flex;

        div {
            height: 100%;
            width: calc(100%/5);
            display: flex;
            align-items: center;

            &:hover {
                cursor: pointer;
            }

            img {
                width: 80px;
            }

            span {
                margin: 0 10px;
                color: white;
            }
        }

    }




}
</style>