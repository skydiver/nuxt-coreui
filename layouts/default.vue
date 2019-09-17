<template>
  <client-only placeholder="Loading...">
    <default-container>
      <nuxt />
    </default-container>
  </client-only>
</template>

<script>
const DefaultContainer = async () => {
  // eslint-disable-next-line no-return-await
  return await import('~/components/containers/DefaultContainer');
};

export default {
  components: {
    DefaultContainer
  }
};
</script>

<style lang="scss">
$fa-font-path: '~font-awesome/fonts/';
$simple-line-font-path: '~simple-line-icons/fonts/';

@import '@coreui/icons/css/coreui-icons.min.css';
@import 'font-awesome/scss/font-awesome.scss';
@import 'simple-line-icons/scss/simple-line-icons.scss';
@import 'flag-icon-css/css/flag-icon.min.css';
@import 'bootstrap-vue/dist/bootstrap-vue.css';
@import 'assets/scss/style';
</style>
