<template>
  <div class="Coreteam">
     <First/>
     <Head />
     <Onback/>
     <Team/>
     
      <Ended/> 
   
  </div>
</template>

<script>
 
   import First from '../components/first'; 
  import Head from '../components/head';
  import Onback from '../components/coreteam/oneback';
  import Team from '../components/coreteam/team';
    
  import Ended from '../components/end'
export default {
  name: "Coreteam",
  components: {
    First,
    Head,
    Onback,
    Team,
    Ended
  }
};
</script>

<style scoped>
 .Coreteam {
    font-family: 'Lato', sans-serif;
 }

</style>
