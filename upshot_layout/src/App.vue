<template>
  <div id="app">
 
    <nav class="navbar navbar-expand-sm fixed-top navbar-dark">
        <div class="container">
            <img src="./assets/Vector-Smart-Object.svg" class="navbar-brand" alt="...">
            <a class="navbar-brand" href="#">SVG LOGO</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbar1">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbar1">
 <!--                <ul class="navbar-nav">
                    <li class="nav-item active">
                        <a class="nav-link" href="#">Link2</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Link3</a>
                    </li>
                </ul> -->
                <ul class="navbar-nav ml-auto">
                    <li class="nav-item">
                        <router-link to="/" class="nav-link">Home</router-link>
                    </li>
                    <li class="nav-item">
                        <router-link to="/about" class="nav-link">About</router-link>
                    </li>
                    <li class="nav-item">
                        <router-link to="/products" class="nav-link">Products</router-link>
                    </li>
                    <li class="nav-item">
                        <router-link to="/help" class="nav-link">Help</router-link>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
<!--     <header>

    </header> -->
<!--     <div id="nav">
      <img alt="Leathery background image" src="./assets/tim-johnson-754973-unsplash.png">

      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/products">Products</router-link> |
      <router-link to="/help">Help</router-link>
    </div> -->
    <router-view/>
  </div>
</template>

<script>
</script>

<style>
#app {
  font-family: 'Open Sans', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 100px;
  text-align: right;
  background: none;
/*  background-color: transparent;
*/

}

header {
/*  height:100vh;*/
  min-height:400px;
  background-size:cover;
  background-image: url('./assets/Banner1.png');
}


#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
