<template>
  <div>
    <Navigation/>
    <Toolbar/>
  </div>
</template>
//--------------------
<script>
import Navigation from './components/Navigation'
import Toolbar from './components/Toolbar'
export default {
   name : 'App',
   components:{
    Navigation,Toolbar
  }
  
}
</script>
//----------------
<style lang="scss">
*{
  margin:0px;
  padding:0px;
}
</style>