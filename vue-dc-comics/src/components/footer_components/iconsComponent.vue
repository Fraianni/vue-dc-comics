<template>
  <div id="container">
    <div class="img-container">
        <img src="../../assets/img/buy-comics-digital-comics.png" alt="digital-comics">
        <p>DC COMICS</p>
    </div>
    <div class="img-container"> 
        <img src="../../assets/img/buy-comics-merchandise.png" alt="merchandise">
        <p>DC MERCHANDISE</p>

    </div>
    <div class="img-container">
        <img src="../../assets/img/buy-comics-subscriptions.png" alt="subscriptions">
        <p>SUBSCRIPTION</p>

    </div>
    <div class="img-container">
        <img src="../../assets/img/buy-comics-shop-locator.png" alt="location">
        <p>COMIC SHOP LOCATION</p>

    </div>
    <div class="img-container">    
        <img src="../../assets/img/buy-dc-power-visa.svg" alt="power-visa">
        <p>DC POWER VISA</p>

    </div>
  </div>
</template>

<script>
export default {
name:'iconsComponent',
};
</script>

<style scoped>
    #container{
        background-color: hsl(209deg 98% 49%);
        display: flex;
        justify-content: space-around;
    }

    .img-container{
        color: white;
        display: flex;
        justify-content: center;
        align-items: center;
        margin: 50px;
    }

    .img-container img{
        width: 50px;
        margin: 10px;   
    }

    .img-container p{
        font-size: 0.8rem;
    }
</style>