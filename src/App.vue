<template>
 <div class="container">

  <div class="box">Wellcome check it </div>
  <Header/>
  <Footer/>
 </div>
 
</template>

<script>
  import Header from './components/Header.vue'
  import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Footer,
    
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.container{

margin: auto;
  width: 50%;
  border: 3px solid green;
  padding: 10px;
   text-align: center;

}
.box{

border: #2c3e50 solid 2px ;
border-radius: 25px;
max-width: 150px;
  margin: auto;
background: #2c3e50;
color: beige;

}



</style>
