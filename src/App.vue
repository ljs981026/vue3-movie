<template>
  <Header1 />
  <RouterView />
  <Footer1 />
</template>

<script>
  import Header1 from '~/components/Header'
  import Footer1 from '~/components/Footer'

  export default {
    components: {
      Header1,
      Footer1
    }
  }
</script>
<style lang="scss">
@import "~/scss/main";
</style>