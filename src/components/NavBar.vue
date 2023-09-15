<template>
    <div>
      <v-tabs v-model="tab">
        <v-tab>
            <router-link to="/">Home</router-link>
        </v-tab>

        <v-tab>
            <router-link to="/about">About</router-link>
        </v-tab>

        <v-tab>
            <router-link to="/contact">Contact</router-link>
        </v-tab>
        <v-tabs-slider></v-tabs-slider>
      </v-tabs>

      <router-view></router-view>

  </div>
</template>

<script>
export default {
    name: 'NavBar',
    props: {
        msg: String
    } 
}

</script>