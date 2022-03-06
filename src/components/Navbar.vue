<template>
  <nav class="navbar container">
    <router-link :to="{ name: 'Home' }">
      <img src="../assets/logo.png" alt="logo" />
    </router-link>
    <div class="main-menu">
        <button><i class="fa fa-bars" aria-hidden="true"></i></button>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Navbar",
  data() {
    return {
      msg: "Welcome to Your Vue.js App",
    };
  },
};
</script>


<style>
@import url("https://fonts.googleapis.com/css2?family=Philosopher:ital,wght@1,700&family=Roboto:wght@300;400;500;700;900&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Philosopher:ital,wght@1,700&family=Roboto:wght@300;400;500;700;900&display=swap");

* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

:root {
  --default-font-size: 16px;
  --background-color: hsl(0, 0%, 0%);

  --default-font-color: hsl(0, 0%, 100%);
}

.container{
    max-width: 1200px;
    margin: 0 auto;
}

body {
  width: 100vw;
  height: 100vh;
  overflow-x: hidden;
  background-color: var(--background-color);
}

/* h1 {
  font-family: "Philosopher", sans-serif;
  color: var(--default-font-color);
}
h2 {
  font-family: "Philosopher", sans-serif;
} */

.main-menu i{
    color: #fff;
    text-shadow: 1px 1px 1px #ccc;
    font-size: 1.8rem;
}

.main-menu button{
    background-color: transparent;
    border: none;
    cursor: pointer;
}

.navbar{
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-top: 1rem;
}
</style>
