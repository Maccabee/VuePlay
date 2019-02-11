<template>
  <header>
    <h1>Blog Name</h1>
    <nav>
      <router-link to="/">Home</router-link>
      <router-link to="/about">About</router-link>
    </nav>
  </header>
</template>

<script>
export default {};
</script>

<style scoped>
header {
  display: flex;
  font-size: 1.1em;
  background-color: #575757;
  color: #bbbbbb;
  align-content: center;
  padding: 10px 10px;
}
h1 {
  display: inline;
}
nav {
  display: flex;
  align-content: center;
}
nav a {
  color: #bbbbbb;
  padding: 35px 40px;
  margin-left: 10px;
  text-decoration: none;
}
.router-link-exact-active {
  background-color: #404040;
}
</style>
