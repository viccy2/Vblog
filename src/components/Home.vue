<template>
    <div>
      <Navbar/>
      <div>
      <h3> Home Page</h3>
      <button v-on:click='Alertclick()'>Display Date</button>
      </div>
    </div>
</template>


<script>
import Navbar from './Navbar.vue'
export default {
    name:'Home',
    components:{
        Navbar
    },
   methods:{
       Alertclick(){
           alert(Date());
       }
   }
  
}
</script>


<style scoped>
    h3{
        float:left
    }
</style>