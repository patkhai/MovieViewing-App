<template>
  <header class="header">
    <h1>Let's Watch!</h1>
  </header>
</template>

<script>
export default {
  name: "Header"
};
</script>

<style scoped>
.header {
  color: #169cfc;
  background-color: transparent;
  text-align: center;
  border: none;
  padding: 1.5rem;
}

.header h1 {
  font-size: 5rem;
  font-weight: 700;
  font-family: sans-serif;
}

.header a {
  color: #fff;
  padding-right: 10px;
  text-decoration: none;
}
</style>
