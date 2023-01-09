<script>





</script>

<template>

    <footer>
        <section class="sfondo-footer">
            <div class="flex">
                <ul>
                    <li class="bold">DC COMICS</li>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>Tv</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                    <li class="bold">SHOP</li>
                    <li>Shop DC</li>
                    <li>Shop DC Collectibiles</li>
                </ul>
                <ul>
                    <li class="bold">DC</li>
                    <li>Term of use</li>
                    <li>Priovate police(new)</li>
                    <li>Ad Choice</li>
                    <li>Advertising</li>
                    <li>Job</li>
                    <li>Subscriptions</li>
                    <li>Talent Workshop</li>
                    <li>CPSC Certificates</li>
                    <li>Ratings</li>
                    <li>Shop Help</li>
                    <li>Contact Us</li>
                </ul>
                <ul>
                    <li class="bold">SITIES</li>
                    <li>Dc</li>
                    <li>MAD Megazine </li>
                    <li>Dc kids</li>
                    <li>Dc Unvierse</li>
                    <li>Dc Power VIsa</li>
                </ul>
            </div>
            <div class="img-footer">
                <img src="../assets/img/dc-logo-bg.png" alt="dc-logo">
            </div>
        </section>
        <section></section>
        <section></section>
    </footer>

</template>

<style scoped>
.sfondo-footer{
        background-image: url(../assets/img/footer-bg.jpg);
        background-repeat: no-repeat;
        background-size: cover;
        display: flex;
        justify-content: space-around;
        height: 350px;
    }

    .img-footer{
        width: 560px;
        height: 350px;
        overflow: hidden;
        position: relative;
    }

    img{
        position: absolute;
        top: -75px;
    }

    .flex{
        display: flex;
    }

    ul{
        color: gray;
        list-style-type: none;
        font-size: 0.8rem;
    }

    li{
        padding: 0.25rem 0;
    }

    .bold{
        padding: 0.5rem 0;
        color: white;
        font-weight: bold;
    }
</style>
