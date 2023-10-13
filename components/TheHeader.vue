<template>
  <nav class="site-header sticky-top py-1">
    <div class="container d-flex flex-md-row justify-content-between">
    <a class="py-2" href="/">
      <img src="~/assets/logo.svg">
    </a>
    <a
      v-for="item in navItems"
      :key="item"
      :href="item.route"
      :target="item.target"
      class="py-2 d-none d-md-inline-block"
    >
      {{ item.name }}
    </a>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'TheHeader',
  data () {
    return {
      navItems: [
        {name: 'Menu', route: '/menu', target: '_self'},
        {name: 'About', route: '/about', target: '_self'},
        {name: 'Restaurants', route: '/restaurants', target: '_self'},
        {name: 'Offers', route: '/offers', target: '_self'},  
        {name: 'Order', route: 'http://doordash.com/store/23u82328', target: 'blank'}
      ]
    }
  }
}
</script>

<style lang="scss">
nav {
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.25);
}

nav a {
  color: #dd0031 !important;
  font-weight: 600;
}
</style>