<template>
  <nav>
    <router-link to="/">Home</router-link> /* localhost:8080/의 주소를 요청하면 주소에 맞는 라우터로 옮겨준다. 라우터는 router/main.js에 있다. */
    <router-link to="/about">About</router-link> /* localhost:8080/about를 열면 주소에 맞는라우터로 옮겨준다.*/
  </nav>
  <router-view/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
