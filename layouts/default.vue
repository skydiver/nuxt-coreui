<template>
  <default-container>
    <nuxt />
  </default-container>
</template>

<script>
import DefaultContainer from '~/components/containers/DefaultContainer';

export default {
  components: {
    DefaultContainer
  }
};
</script>

<style lang="scss">
@import '@coreui/icons/css/coreui-icons.min.css';
$fa-font-path: '~font-awesome/fonts/';
@import 'font-awesome/scss/font-awesome.scss';
$simple-line-font-path: '~simple-line-icons/fonts/';
@import 'simple-line-icons/scss/simple-line-icons.scss';
@import 'flag-icon-css/css/flag-icon.min.css';
@import 'bootstrap-vue/dist/bootstrap-vue.css';
// Import Main styles for this application
@import 'assets/scss/style';
</style>
