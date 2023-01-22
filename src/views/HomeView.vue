<template>
  <v-app id="home">
    <NavBar/>
    <v-container fluid>
      <div class="head">

      </div>
    </v-container>

  </v-app>

</template>

<script>
import { defineComponent } from 'vue';

// Components
import NavBar from '@/components/NavBar.vue';

export default defineComponent({
  name: 'HomeView',

  components: {
    NavBar
  },
});
</script>
<style scoped>
  .v-container{
    padding: 16px 0px;
  }
  .head{
    position: relative;
    text-align: center;
    margin-bottom: 6px;
    height: 400px;
    width: 100%;
    color: white;
  }
</style>
