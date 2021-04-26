<template>
  <footer>
    <p>Copyright &copy; {{getYear()}}</p>
    <router-link to="/about">About</router-link>
  </footer>
</template>

<script>
export default {
  name: 'Footer',
  methods: {
    getYear() {
      let currentYear = new Date().getFullYear()
      return currentYear
    }
  }
}
</script>

<style scoped> 
footer {
  text-align: center;
  margin-top: 30px;
}

a {
  color: #333
}
</style>