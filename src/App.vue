<script  lang="ts">
import heder from './components/Heder.vue';
import corpo from './components/Corpo.vue';
import Ofertas from './components/Ofertas.vue';
import Footer from './components/Foote.vue';


export default {
  components: {heder,corpo,Ofertas,Footer},
  
  
}


</script>

<template>
     <heder/>
     <div class="img">
        <div class="img_text">
            <p>"Oferecendo as melhores motos usadas com qualidade e preço justo. " </p>
              <samp>Sua satisfação é o nosso sucesso.</samp>
        </div>
     </div>
     <ofertas/>
     <corpo/>
      <Footer/>

     

</template>

<style scoped>
.img {
 background-image: url('../public/folden.jpg');
 background-size: cover;
 background-position:center;
 
 height: 30vh;
 width: 100%;
 margin-bottom: 10px;

}

.img_text {
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: end;
}
.img p {
  color: rgb(53, 150, 101);
  font-size: 20px;
  text-align: center;
  
  font-family: 'Courier New', Courier, monospace;
}
.img samp {
 
  color: rgb(42, 146, 89);
  font-size: 20px;
  text-align: center;
  
  font-family: 'Courier New', Courier, monospace;
}



</style>
