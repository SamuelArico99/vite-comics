<script>

export default {
    name: "AppHeader",
}

</script>

<template>
    <header>
        <img src="../assets/img/dc-logo.png" alt="">
        <ul>
            <li>
                <a href="#">CHARTERS</a>
            </li>
            <li>
                <a href="#">COMICS</a>
            </li>
            <li>
                <a href="#">MOVIES</a>
            </li>
            <li>
                <a href="#">TV</a>
            </li>
            <li>
                <a href="#">GAMES</a>
            </li>
            <li>
                <a href="#">COLLECTIBLES</a>
            </li>
            <li>
                <a href="#">VIDEOS</a>
            </li>
            <li>
                <a href="#">FANS</a>
            </li>
            <li>
                <a href="#">NEWS</a>
            </li>
            <li>
                <a href="#">SHOP</a>
            </li>
        </ul>
    </header>
</template>

<style lang="scss" scoped>
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 80%;
    margin: 0 auto;
    height: 150px;

}

img:hover {
    cursor: pointer;
}

ul {
    display: flex;
    text-decoration: none;
    height: 100%;
    align-items: center;

    li {
        padding: 20px;
        list-style: none;
        height: 100%;

        &:hover {
            border-bottom: 2px solid #0282f9;

        }


        a {
            color: black;
            text-decoration: none;
            height: 100%;
            display: flex;
            align-items: center;
            font-weight: bold;

            &:hover {
                color: #0282f9;
            }


        }



    }
}
</style>