<script >





</script>

<template>
    <header>

        <section class="riga-nera"></section>
        <section class="navbar">
            <div>
                <img src="../assets/img/dc-logo.png" alt="dc-logo">
            </div>
            <div>
                <ul>
                    <li>Characters</li>
                    <li class="active">Comics <div class="riga-active"></div> </li>
                    <li>Movies</li>
                    <li>Tv</li>
                    <li>Games</li>
                    <li>Collectibiles</li>
                    <li>Videos</li>
                    <li>Fans</li>
                    <li>News</li>
                    <li>Shop</li>
                </ul>
            </div>
        </section>
        <section class="jumbo">

        </section>
    </header>

</template>

<style scoped>

.jumbo{
    background-image: url(../assets/img/jumbotron.jpg);
    height: 450px;
}
.riga-nera{
        height: 25px;
        background-color: black;
    }

    .navbar{
        padding: 0.5rem;
        display: flex;
        justify-content: space-around;
        align-items: center;
        position: relative;
    }

    ul{
        display: flex;
        list-style-type: none;
    }
    
    li{
        padding: 0 1rem;
        font-weight: bold;
    }

    .active{
        color: blue;
    }

    .riga-active{
        border: 2px solid blue;
        position: absolute;
        bottom: 0;
        width: 50px;
    }
</style>
