<template>
  <!-- <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="You did it!" />
    </div>
  </header> -->
  <!-- header -->
  <div class="header">
    <h4>Header</h4>
    <h4>NavBar</h4>
  </div>
  <!-- main -->
  <div class="main">
      <h4>Welcom to a Furry world!</h4>
      <ul>
        <li>Furry_1</li>
        <li>Furry_2</li>
        <li>Furry_3</li>
        <li>Furry_4</li>
        <li>Furry_5</li>
        <li>Furry_6</li>
      </ul>
  </div>
  <!-- footer -->
  <div class="footer">
    <h4>Footer</h4>
  </div>

  <main>
    <TheWelcome />
  </main>
</template>

<script>
export default {
  name: "App",
  // components: {}
}
</script>

<style>
.header, .main, .footer{
  border: 1px solid #999;
  margin-bottom: 4px;
}
/* #app {
  font-family: Arial, Helvetica, sans-serif;
  -webkit-font-smoothing: antialiased;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
</style>
