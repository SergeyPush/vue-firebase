<template>
  <div>
    <nav>
      <ul>
        <li>
          <a href="http://" target="_blank" rel="noopener noreferrer">Home </a>
        </li>
        <li>
          <a href="http://" target="_blank" rel="noopener noreferrer">About</a>
        </li>
        <li>
          <a href="http://" target="_blank" rel="noopener noreferrer"
            >Contact</a
          >
        </li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  }
};
</script>

<style lang="css" scoped>
nav {
  text-align: center;
}
nav ul {
  padding: 0;
}

nav li {
  display: inline-block;
  list-style-type: none;
  margin: 5px;
}
a {
  text-decoration: none;
  color: royalblue;
  font-weight: bold;
}
</style>