<template>
    <div>
        <landing-view />
        <!-- <slide-show /> -->
        <about />
        <what-we-do />
        <sec1 />
        <sec2 />
        <sec3 />
        <sec4 />
        <sec5 />
        <mary />
        <jamie />
        <elizabeth/>
        <samantha />
        <thomas />
        <!-- <sophia /> -->
        <talk-to-us />
        <!-- <career /> -->
        <footer-view />
    </div>
</template>

<script>
import AOS from 'aos';
import 'aos/dist/aos.css';
import career from '~/components/career.vue';

export default {
  components: { career },
  mounted() {
    AOS.init(
      {
      offset: 200,
      duration: 400,
      easing: 'ease-in-out',
      // delay: 100,
    }
    );
  },
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Sofia+Sans:ital,wght@0,1..1000;1,1..1000&family=Sora:wght@100..800&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,500;0,600;0,700;1,300;1,400;1,500;1,600;1,700&display=swap');
  body, p, h2, i, button, ul, li, a {
    /* font-family: 'Montserrat', sans-serif; */
    /* font-family: "Sofia Sans", sans-serif; */

    font-family: "Cormorant Garamond", serif;}
</style>
