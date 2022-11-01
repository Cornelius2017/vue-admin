<template>
  <v-app>
   <SideBar />
    <v-main>
      <Home />
     <router-view></router-view>
    </v-main>
  </v-app>
</template>

<script>
import SideBar from './components/SideBar';
import Home from './views/Home';

export default {
  name: 'App',
  components: {
    SideBar,
    Home
  },
  data: () => ({
    //
  }),
};
</script>