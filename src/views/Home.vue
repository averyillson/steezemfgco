<template>
  <div class="home">
    <intro/>
  </div>
</template>

<script>
// @ is an alias to /src
import intro from '@/components/intro.vue'

export default {
  name: 'home',
  components: {
    intro
  }
}
</script>
