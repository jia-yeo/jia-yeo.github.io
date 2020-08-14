<template>
  <article id="main">
    <p>여지아's homepage</p>

    <nuxt-link to="/profile">Profile 페이지로 이동</nuxt-link>
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
#main {padding: 50px;
  .greet {font-family: 'Roboto'; font-size: 16px; line-height: 1.5; letter-spacing: 0.05em;}
}

@media screen and (max-width: 750px) {
  #main {
    .greet {font-size: 24px;}
  }
}
</style>