<template>
  <div class="home">

    <router-view/>
  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from '@/components/HelloWorld.vue'

import Login from './login'

export default {
  name: 'home',
  components: {
    Login
  }
}
</script>
