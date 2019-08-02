<template>
  <div id="app" class="site">
    <page-header/>
    <page-content/>
    <page-footer/>
  </div>
</template>

<script>
import pageHeader from './components/layouts/page-header'
import pageContent from './components/layouts/page-content'
import pageFooter from './components/layouts/page-footer'

export default {
  name: 'app',
  components: {
    pageHeader,
    pageContent,
    pageFooter
  }
}

</script>
