<template>
  <v-app>
    <v-main>
      <Header/>
      <div class="content">
        <Yo/>
      </div>      
    </v-main>
  </v-app>
</template>

<script>
import Yo from './components/Yo.vue';
import Header from './components/Header.vue'
export default {
  name: 'App',

  components: {
    Header,
    Yo,
  },

  data: () => ({
    //
  }),
}
</script>
