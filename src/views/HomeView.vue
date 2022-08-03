<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/BlueCross.png" /> -->
    <HomeComponent msg="Adjudication Test Data Maintainer" />
  </div>
</template>

<script>
// @ is an alias to /src
import HomeComponent from "@/components/HomeComponent.vue";

export default {
  name: "HomeView",
  components: {
    HomeComponent,
  },
};
</script>
