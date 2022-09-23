<template>
  <header>
    
    <div id="icon-container">
        <img src="../assets/img/DC_iconjpg.jpg" alt="">    
    </div>

    <div id="header-links">
        <ul>
            <li><a href="#">CHARACTERS</a></li>
            <li><a href="#">COMICS</a></li>
            <li><a href="#">MOVIES</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">GAMES</a></li>
            <li><a href="#">COLLECTIBLES</a></li>
            <li><a href="#">VIDEOS</a></li>
            <li><a href="#">FANS</a></li>
            <li><a href="#">NEWS</a></li>
            <li><a href="#">SHOP</a></li>

        </ul>
    </div>
  </header>
</template>

<script>
export default {
    name:'headerComponent',
};
</script>

<style  scoped>
    header{
        display: flex;
        justify-content: space-around;
        padding: 40px 0px;
    }

    #icon-container{
        max-width: 70px;
        height: 70px;
    }

    #icon-container  img{
            width: 100%;
        }
    
    
     #header-links{
        display: flex;
        align-items: center;
     }
    
    #header-links ul{
        display: flex;
        list-style-type: none;

    }

    #header-links ul li{
        margin: 0px 15px;   
    }

    #header-links ul li a{
        text-decoration: none;
        color: rgb(34, 34, 34);
    }

</style>
