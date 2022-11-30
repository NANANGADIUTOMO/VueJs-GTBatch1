<template>
  <div id="app">
      <navbar></navbar>
      <breadcrumb></breadcrumb>
      <gallery :thisimg="cardimage" :thistext="cardTitle" :thistext2="cardPrice"></gallery>
      <slider @changepicture="gantigambarfunc" ></slider>
     <Footer></Footer>
     <copyright></copyright>
  </div>
</template>

<script>
import navbar from './components/navbar.vue'
import breadcrumb from './components/breadcrumb.vue'
import gallery from './components/gallery.vue'
import slider from './components/slider.vue'
import Footer from './components/footer.vue'
import copyright from './components/copyright.vue'
export default {
  name: 'App',
  components: {
    navbar,
    breadcrumb,
    gallery,
    slider,
    Footer,
    copyright
  },
  methods : {
    gantigambarfunc : function(cardimage, cardTitle, cardPrice){
      this.cardimage = cardimage
      this.cardTitle = cardTitle
      this.cardPrice = cardPrice
    }
  },
  data(){
    return{
      cardimage: "chair",
      cardTitle : "chair thaty",
      cardPrice : "IDR. 12.000.000"
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  color: #2c3e50;

  
}
</style>
