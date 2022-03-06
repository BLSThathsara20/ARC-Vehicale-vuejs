<template>
  <div class="home">
    
  </div>
</template>

<script>
export default {
  name: 'Home',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>


<style>
@import url('https://fonts.googleapis.com/css2?family=Philosopher:ital,wght@1,700&family=Roboto:wght@300;400;500;700;900&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Philosopher:ital,wght@1,700&family=Roboto:wght@300;400;500;700;900&display=swap');

*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}

:root{
 --default-font-size: 16px;
 --background-color: hsl(0, 0%, 0%);

 --default-font-color: hsl(0, 0%, 100%);
}

body{
    width: 100vw;
    height: 100vh;
    overflow-x: hidden;
    background-color: var(--background-color);
}

h1{
    font-family: 'Philosopher', sans-serif;
    color: var(--default-font-color);
}
h2{
    font-family: 'Philosopher', sans-serif;
}
</style>
