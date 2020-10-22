<template>
<div>
  <navbar/>
  <h1>Menu Makanan</h1>
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue'

export default {
  name: 'Foods',
  components: {
    Navbar
  }
}
</script>