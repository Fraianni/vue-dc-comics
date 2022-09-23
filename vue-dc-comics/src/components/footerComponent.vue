<template>
    <div id="footerComponent">
        <iconsComponent/>
        <div class="under-icons">
        
            <div class="dc-links">
                <div class="comics-and-shop">
                    <ul>
                        DC comics
                        <li><a href="#">Characters</a></li>
                        <li><a href="#">Comics</a></li>
                        <li><a href="#">Movies</a></li>
                        <li><a href="#">TV</a></li>
                        <li><a href="#">Games</a></li>
                        <li><a href="#">Videos</a></li>
                        <li><a href="#">News</a></li>
                    </ul>
                    <ul></ul>
                </div>
                <div class="dc"></div>
                <div class="sites"></div>
            </div>
        

            <div class="bg-img">
                <img src="../assets/img/dc-logo-bg.png" alt="">
            </div>
        </div>
        
    </div>


</template>

<script>
import iconsComponent from './footer_components/iconsComponent.vue'




export default {
    name:'footerComponent',
    components:{
    iconsComponent,
   
}
}
</script>

<style scoped>
    .under-icons{
        background-image: url('../assets/img/footer-bg.jpg');
        display: flex;
        justify-content: space-between;
        position: relative;
        padding: 50px;
        height: 500px;

    }

    .bg-img{
        position: absolute;
        top: -100px;
        right: 200px;
    }

    .dc-links ul{
        list-style-type: none;
        color: white;
        text-decoration: none;
        
    }

    .dc-links  a{
        color:whitesmoke;
        text-decoration: none;
    }

</style>