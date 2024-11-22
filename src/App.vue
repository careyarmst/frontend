<template>
  <v-app>
  <v-app-bar>
    </v-app-bar>

    <v-main>
      <messagesMWord/>
    </v-main>
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
