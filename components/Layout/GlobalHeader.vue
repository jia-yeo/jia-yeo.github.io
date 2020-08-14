<template>
  <header id="header">
    <p>HEADER</p>
  </header>
</template>

<script>
import { mapState, mapMutations } from 'vuex';

export default {
  computed: mapState({
    menuFlag: state => state.ui.menuFlag
  }),
  methods: {
    /*...mapMutations({
      toggleMenu: 'ui/toggleMenu'
    }),*/
    toggleMenu(event) {
      console.log(event);
      this.$store.commit('ui/toggleMenu');
    }
  }
}
</script>

<style lang="scss" scope>
#header {
  p {}
}
</style>