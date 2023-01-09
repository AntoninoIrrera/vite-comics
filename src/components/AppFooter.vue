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
                <img class="logo-footer" src="../assets/img/dc-logo-bg.png" alt="dc-logo">
            </div>
        </section>
        <section class="social-footer">
            <div>
                <a href="#">Sign-Up Now!</a>
            </div>
            <div class="socials">
                <h2>Follow Us</h2>
                <img class="img-social" src="../assets/img/footer-facebook.png" alt="facebook">
                <img class="img-social" src="../assets/img/footer-twitter.png" alt="twitter">
                <img class="img-social" src="../assets/img/footer-youtube.png" alt="youtube">
                <img class="img-social" src="../assets/img/footer-pinterest.png" alt="pinteres">
                <img class="img-social" src="../assets/img/footer-periscope.png" alt="periscope">
            </div>
        </section>
        <section class="riga-nera"></section>
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

    .logo-footer{
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

    .social-footer{
        padding: 0.5rem;
        background-color: rgb(27, 25, 25);
        display: flex;
        justify-content: space-around;
        align-items: center;
    }

    a{
        text-decoration: none;
        color: white;
        border: 2px solid blue;
        padding: 0.5rem;

    }
    
    h2{
        color: blue;
        display: inline-block;
        vertical-align: super;
    }

    .img-social{
        margin-left: 0.5rem;
    }

    .riga-nera{
        background-color: black;
        height: 25px;
    }

    .bold{
        padding: 0.5rem 0;
        color: white;
        font-weight: bold;
    }
</style>
