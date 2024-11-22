<template>
 <v-app>
  <v-toolbar app>
  </v-toolbar>

    
  <v-content>
      <messagesMWord/>
  </v-content>
    
 </v-app>
</template>

<script>
import messagesMWord from './components/messagesMword';

export default {
  name: 'App',

  components: {
    messagesMWord,
  },

  data: () => ({
    //
  }),
};
</script>
