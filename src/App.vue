<template>
  <v-app>
    <div class="d-flex align-center">
      <router-link to="/">Home</router-link> ||
      <router-link to="/signup">signup</router-link> ||
      <router-link to= "/DashBoard">dashboard</router-link>||
      <router-link to= "/user">user</router-link>
    </div>
    <v-main>
      <router-view/>
    </v-main>
  </v-app>
</template>
<script>
  export default {
    name: 'App',

    data: () => ({
    //
    }),
  };
</script>
