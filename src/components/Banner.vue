<template>
    <div id = "main-banner">
        <h1>Make Your Burguer</h1>
    </div> 
</template>


<script>
export default{
    name: "Banner"
}
</script>

<style scoped>
    #main-banner{
        background-image: url('/public/img/burger.jpg');
        background-size: cover;
        background-position: 0 -250px;
        display: flex;
        align-items: center;
        height: 500px;
        justify-content: flex-start;
    }

    #main-banner h1{
        color: #fff;
        text-align: center;
        font-size: 60px;
        padding: 20px 40px;
    }

    @media screen and (max-width: 768px){
        #main-banner{
            display: block;
            width: 50vm;
        }

        #main-banner h1{
            display: flex;
            font-size: 30px;
        }
    }

</style>