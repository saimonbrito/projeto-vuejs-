<script lang="ts">
    import cards from './Cards.vue';
    

    export default {
  components: {cards}, 
  data() {
        return {
          imagePath: new URL('', import.meta.url).href,
        }
      }
}

</script>



<template>
    <div class="container">
        <div class="container__conteudo">
             <cards/>
             <cards/>
             <cards/>
             <cards/>
             <cards/>  
             <cards/>
             <cards/>
             <cards/>
          
            
        </div>
    </div>
</template>

<style scoped>
.container {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    width: 100vw;
   
   
    
   
}

.container__conteudo {
 
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    height: 100vh;

    background-color: rgb(121, 143, 155);
    max-width: 1324px;
    border-radius: 20px;
    margin-top: 20px;
}
</style>