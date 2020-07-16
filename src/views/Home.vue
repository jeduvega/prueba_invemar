<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <Crud msg=""/>
  </div>
</template>

<script>
// @ is an alias to /src
import Crud from '@/components/Crud.vue'

export default {
  name: 'Home',
  components: {
    Crud
  }
}
</script>
