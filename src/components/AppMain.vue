<script>


export default {
    data() {
        return {
            images: [
                {
                    image: '../assets/img/buy-comics-digital-comics.png',
                    title: 'digital comics',
                }, {
                    image: '../assets/img/buy-comics-merchandise.png',
                    title: 'DC Merchandise',
                }, {
                    image: '../assets/img/buy-comics-subscriptions.png',
                    title: 'Subscription',
                }, {
                    image: '../assets/img/buy-comics-shop-locator.png',
                    title: 'Comic Shop Locator',
                }, {
                    image: '../assets/img/buy-dc-power-visa.svg',
                    title: "Dc power visa",
                }
            ]
        }
    },
    methods: {
        getImagePath(imgPath) {
            return new URL(imgPath, import.meta.url).href;
        }
     
    }

}

   



</script>

<template>
    <main>

        <section class="riga-nera">
            <h2 class="contenuto-main">Content goes here</h2>
        </section>
        <section class="riga-blu">
            <div v-for="image in images">
                <img :src="getImagePath(image.image)" :alt="image.title">
                <h4>{{image.title}}</h4>
            </div>
        </section>

    </main>
</template>

<style scoped>
.riga-nera{
        height: 150px;
        background-color: black;
        display: flex;
        align-items: center;
    }

    .riga-blu{
        padding: 3rem;
        background-color: blue;
        display: flex;
        justify-content: center;
        /* align-items: center; */
    }

    img{
        width: 15%;
    }

    h4{
        display: inline-block;
        color: white;
        vertical-align: super;
        margin-left: 0.75rem;
    }
    .contenuto-main{
        color: white;
        margin-left: 20rem;
    }

</style>
