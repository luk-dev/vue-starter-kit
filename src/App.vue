<template>
  <div id="app">
    <the-navigation/>
    <div>
      Change Language to:
      <TheLanguageSwitcher/>
    </div>
    <router-view/>
  </div>
</template>

<script>
import TheLanguageSwitcher from '@/components/TheLanguageSwitcher'
import TheNavigation from '@/components/TheNavigation'

export default {
  name: 'app',
  components: {
    TheLanguageSwitcher,
    TheNavigation
  }
}
</script>

<style lang="scss">
  @import "/assets/scss/style.scss";
</style>
