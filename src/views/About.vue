<template>
  <div class="About">
     <First/>
     <Head/>
     <Firstback />
     <Aboutin/>
     <Workprocess/>
      <Ourteam />
      <End/>
  </div>
</template>

<script>
// @ is an alias to /src
   import First from '../components/first';
   import Head from '../components/head';
   import Firstback from '../components/About/Firstback';
   import Aboutin from '../components/About/aboutin';
   import Workprocess from '../components/About/workprocess';
   import Ourteam from '../components/ourteam';
     import End from '../components/end'
export default {
  
  name: "About",
  components: {
   First,
   Head,
   Firstback,
   Aboutin,
   Workprocess,
  Ourteam,
  End
  }
};
</script>

<style scoped>
 .About {
   font-family: 'Lato', sans-serif;
 }
</style>
