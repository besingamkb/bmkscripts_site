<template>
  <div id="app">
    <SiteHeader></SiteHeader>
        <Layout></Layout>
    <SiteFooter></SiteFooter>
  </div>
</template>

<script>
// import Hello from './components/Hello'
// importing all components here
import SiteHeader from './components/site-header'
import Layout from './components/layout'
import SiteFooter from './components/site-footer'

export default {
  name: 'app',
  components: {
    SiteHeader, Layout, SiteFooter
  }
}
</script>

<style>

</style>
