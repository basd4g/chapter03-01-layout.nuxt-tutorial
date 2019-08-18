<template>
  <div>
    <span>defauld layout</span>
    <AppNavigation />
    <hr>
    <footer>
      footer
    </footer>
    <nuxt/>
  </div>
</template>

<script>
import AppNavigation from '~/components/AppNavigation.vue'
export default {
  components:{
    AppNavigation
  }
}
</script>
