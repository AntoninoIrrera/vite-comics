<script>


export default{
    props:{
        pathImg: String,
        title: String,
    }
}




</script>

<template>
   
    <img :src="pathImg" :alt="title">
    <h4>{{ title }}</h4>

</template>

<style scoped>
   
    img{
        width: 60%;
    }

    h4{
        color: white;
        width: 60%;
    }
</style>
