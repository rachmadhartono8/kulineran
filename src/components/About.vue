<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Lagi Belajar Front End Developer Mohon Bimbingan nya Kak,<br>
      Ini Lagi ngembangin Website pake Vue JS
      <a href="https://cli.vuejs.org" target="_blank" rel="noopener">Lihat beberapa gambar homestay kami</a>.
    </p>
    <h3>Find Winahyu Homestay at Traveloka/Booking.com/Tiket.com</h3>
    <ul>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel" target="_blank" rel="noopener">Winahyu Homestay</a></li>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint" target="_blank" rel="noopener">Winahyu Resort Kukup</a></li>
    </ul>
    <h3>Staycation dengan sensasional pantai</h3>
    <ul>
      <li><a href="https://vuejs.org" target="_blank" rel="noopener">Traveloka</a></li>
      <li><a href="https://forum.vuejs.org" target="_blank" rel="noopener">Booking.com</a></li>
      <li><a href="https://chat.vuejs.org" target="_blank" rel="noopener">Agoda</a></li>
      <li><a href="https://twitter.com/vuejs" target="_blank" rel="noopener">Tiket.com</a></li>
      <li><a href="https://news.vuejs.org" target="_blank" rel="noopener">Instagram</a></li>
    </ul>
    <h3>booking sekarang</h3>
    <ul>
      <li><a href="https://router.vuejs.org" target="_blank" rel="noopener">Book Now at Traveloka</a></li>
      <!-- <li><a href="https://vuex.vuejs.org" target="_blank" rel="noopener">vuex</a></li>
      <li><a href="https://github.com/vuejs/vue-devtools#vue-devtools" target="_blank" rel="noopener">vue-devtools</a></li>
      <li><a href="https://vue-loader.vuejs.org" target="_blank" rel="noopener">vue-loader</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">awesome-vue</a></li> -->
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
