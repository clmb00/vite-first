<script>
  import AppTitle from './components/AppTitle.vue';
  import AppMain from './components/AppMain.vue';

  export default{
    name: 'App',
    components:{
      AppTitle,
      AppMain
    }
  }
</script>

<template>

  <AppTitle/>
  
  <div id="back">
    <AppMain/>
  </div>

</template>

<style>
#back{
  width: 100%;
  height: calc(100vh - 120px);
  background: linear-gradient(to top, #fc00ff, #00dbde);
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>
