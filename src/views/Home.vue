<template>
  <div class="home">
      <First /> 
      <Head />
      <Provider/>
      <Boxservice/>
      <Aboutus/>
      <Ourserves/>
      <Ourteam/>
      <End/>
  </div>
</template>

<script>
// @ is an alias to /src
  import First from '../components/first'; 
  import Head from '../components/head';
  import Provider from '../components/provider';
  import Boxservice from '../components/boxservice';
  import Aboutus from '../components/aboutus';
  import Ourserves from '../components/ourserves';
  import Ourteam from '../components/ourteam';
  import End from '../components/end'
export default {
  name: "Home",
  components: {
   First,
   Head,
   Provider, 
   Boxservice,
   Aboutus,
   Ourserves,
   Ourteam,
   End
  }
};
</script>

<style scoped>
.home {
 font-family: 'Lato', sans-serif;
}

</style>
