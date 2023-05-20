<script>
import AppHeader from './components/AppHeader.vue';
import AppContent from './components/AppContent.vue';
import AppFooter from './components/AppFooter.vue';


export default {
  components: {
    AppHeader,
    AppFooter,
    AppContent,
  },
};



</script>

<template>

<app-header></app-header>

<app-content></app-content>

<app-footer></app-footer>

</template>

<style>
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
</style>