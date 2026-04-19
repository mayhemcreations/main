<template>
  <div id="app-root">
    <header>
      <h1>Welcome to Vue GitHub Pages</h1>
      <p>{{ message }}</p>
    </header>
    <main>
      <button @click="count++">Count: {{ count }}</button>
    </main>
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: 'Hello from Vue 3!',
      count: 0
    }
  }
}
</script>

<style scoped>
#app-root {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

header {
  background-color: #42b983;
  color: white;
  padding: 20px;
  margin-bottom: 30px;
}

button {
  background-color: #42b983;
  color: white;
  padding: 10px 20px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
  font-size: 16px;
}

button:hover {
  background-color: #359268;
}
</style>