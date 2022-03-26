<template>
  <div class="hello"> 
    <section id="banner">
      <h1>{{ prova }}</h1>
    </section>
  </div>
</template>

<script>
export default {
  name: 'HeroBanner',
  data (){ 
    return{
      prova: "Camine Passante"
      }
    
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped> 
section#banner h1{ 
  position: absolute;
  top:30%; 
  font-size: 3rem;
  
}
#banner{ 
  height: 50vh;
  background: url("../assets/192860.jpg") center/ cover;  

}

</style>
