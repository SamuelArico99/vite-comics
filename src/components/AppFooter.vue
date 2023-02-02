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
            <div class="container">
                <div class="container-contacts">
                    <div>
                        <h2>DC COMICS</h2>
                        <ul>
                            <li>
                                <a href="">Charters</a>
                            </li>
                            <li>
                                <a href="">Charters</a>
                            </li>
                            <li>
                                <a href="">Charters</a>
                            </li>
                            <li>
                                <a href="">Charters</a>
                            </li>
                            <li>
                                <a href="">Charters</a>
                            </li>
                            <li>
                                <a href="">Charters</a>
                            </li>
                            <li>
                                <a href="">Charters</a>
                            </li>
                        </ul>
                        <h2>
                            SHOP
                        </h2>
                        <ul>
                            <li>
                                <a href="">Shop DC</a>
                            </li>
                            <li>
                                <a href="">Shop DC</a>
                            </li>
                        </ul>
                    </div>
                    <div>
                        <h2>
                            DC
                        </h2>
                        <ul>
                            <li>
                                <a href="">Shop DC</a>
                            </li>
                            <li>
                                <a href="">Shop DC</a>
                            </li>
                            <li>
                                <a href="">Shop DC</a>
                            </li>
                            <li>
                                <a href="">Shop DC</a>
                            </li>
                            <li>
                                <a href="">Shop DC</a>
                            </li>
                            <li>
                                <a href="">Shop DC</a>
                            </li>
                            <li>
                                <a href="">Shop DC</a>
                            </li>
                            <li>
                                <a href="">Shop DC</a>
                            </li>
                            <li>
                                <a href="">Shop DC</a>
                            </li>
                            <li>
                                <a href="">Shop DC</a>
                            </li>
                            <li>
                                <a href="">Shop DC</a>
                            </li>
                        </ul>
                    </div>
                    <div>
                        <h2>
                            SITES
                        </h2>
                        <ul>
                            <li>
                                <a href="">DC</a>
                            </li>
                            <li>
                                <a href="">DC</a>
                            </li>
                            <li>
                                <a href="">DC</a>
                            </li>
                            <li>
                                <a href="">DC</a>
                            </li>
                            <li>
                                <a href="">DC</a>
                            </li>
                        </ul>
                    </div>
                </div>
                <div class="logo">
                    <img src="../assets/img/dc-logo-bg.png" alt="">
                </div>

            </div>
        </section>
        <section class="sign-up">
            <div class="sign-up-container">
                <button>SIGN-UP NOW</button>
                <div>
                    <a href="">FOLLOW US</a>
                    <img src="../assets/img/footer-facebook.png" alt="">
                    <img src="../assets/img/footer-twitter.png" alt="">
                    <img src="../assets/img/footer-youtube.png" alt="">
                    <img src="../assets/img/footer-pinterest.png" alt="">
                    <img src="../assets/img/footer-periscope.png" alt="">
                </div>
            </div>
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

.contacts-terms {
    width: 100%;
    height: 400px;
    background-image: url(../assets/img/footer-bg.jpg);
    background-size: cover;

    .container {
        width: 80%;
        height: 100%;
        margin: 0 auto;
        display: flex;
        align-items: center;
        justify-content: space-between;

        .container-contacts {
            width: 40%;
            height: 80%;
            display: flex;


            div {
                width: calc(100% / 3);
                padding: 10px;

                h2 {
                    color: white;
                    margin-bottom: 5px;
                }

                li {
                    list-style: none;
                    margin-bottom: 5px;

                    a {
                        text-decoration: none;
                        color: gray;
                    }
                }
            }
        }
    }

    .logo {
        width: 40%;
        height: 100%;
        display: flex;
        align-items: center;
        justify-content: flex-end;



        img {
            height: 80%;



        }

    }
}

.sign-up {
    width: 100%;
    height: 100px;
    background-color: #303030;


    .sign-up-container {
        width: 80%;
        height: 100%;
        margin: 0 auto;
        display: flex;
        align-items: center;
        justify-content: space-between;

        button {
            padding: 10px 15px;
            color: white;
            background-color: #303030;
            border: 2px solid #13528d;
        }

        div {
            height: 100%;
            display: flex;
            align-items: center;

            a {
                text-decoration: none;
                color: #13528d;
                margin-right: 20px;
            }

            img {
                margin-right: 10px;
            }
        }
    }
}
</style>