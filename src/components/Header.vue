<template>
  <header>
    <h1>Blog Name</h1>
    <nav>
      <ul>
        <li>
          <a href>Home</a>
        </li>
        <li>
          <a href>About</a>
        </li>
      </ul>
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
}
h1 {
  display: inline;
  padding: 0px 20px;
}
nav {
  display: flex;
  align-content: center;
}
ul {
  display: inline-flex;
}
li {
  display: inline;
  padding: 20px 10px;
}
nav ul li a {
  color: #bbbbbb;
  text-decoration: none;
}
</style>
