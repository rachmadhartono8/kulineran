<template>
  <div class="about">
    <h1>This is an about page</h1>
    <HelloWorld msg="About"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/About.vue'

export default {
  name: 'AboutView',
  components: {
    HelloWorld
  }
}
</script>
