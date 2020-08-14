<template>
  <article id="profile">
    <p>profile 페이지다</p>
  </article>
</template>

<script>
  import { mapState, mapMutations, mapActions } from 'vuex';

  export default {
    data: () => ({
      title: ''
    }),
    methods: {}
  }
</script>

<style lang="scss">
#profile {padding: 50px;}
</style>