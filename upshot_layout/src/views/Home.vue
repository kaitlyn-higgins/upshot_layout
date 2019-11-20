<template>
  <div class="home">

<!--     <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/products">Products</router-link> |
      <router-link to="/help">Help</router-link>
    </div>

    <img alt="Leathery background image" src="../assets/tim-johnson-754973-unsplash.png"> -->
    
    <header>
    </header>


    <container>
      <div class="row container-main">
        <div class="col-3 text-align">
          <ul class="nav flex-column">
            <li class="nav-item">
              <a class="nav-link active" href="#">Footwear</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Water Fountains</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Garage Door Openers</a>
            </li>
            <li class="nav-item">
              <a class="nav-link active" href="#">Smart Home Tech</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Beverages</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Education</a>
            </li>
          </ul>
        </div>
        <div class="col">
          <div class="row">
            <div class="card-deck">
              <div class="card padding">
                <img src="../assets/paul-gaudriault-661082-unsplash.png" class="card-img-top" alt="...">
                <div class="card-body">
                  <h5 class="card-title">Title with Two Very Very Long Long Lines</h5>
                  <p class="card-text">And a very long desciption to boot.  Why bother descibing something with so many words?</p>
                </div>
                <div class="footer">
                  <button type="button" class="btn btn-danger btn-block">BUY NOW</button>

                </div>
              </div>
              <div class="card padding">
                <img src="../assets/marek-szturc-755349-unsplash.png" class="card-img-top" alt="...">
                <div class="card-body">
                  <h5 class="card-title">One Short Title</h5>
                  <p class="card-text">And a very long desciption to boot.  Why bother descibing something with so many words?</p>
                </div>
                <div class="footer">
                  <button type="button" class="btn btn-danger btn-block">BUY NOW</button>

                </div>
              </div>
              <div class="card padding">
                <img src="../assets/paul-gaudriault-661082-unsplash.png" class="card-img-top" alt="...">
                <div class="card-body">
                  <h5 class="card-title">One Short Title</h5>
                  <p class="card-text">With a short description.</p>
                </div>
                <div class="footer">
                  <button type="button" class="btn btn-danger btn-block">BUY NOW</button>

                </div>
              </div>
            </div>
            <br>
            <div class="card-deck">
              <div class="card padding">
                <img src="../assets/mikkel-bech-748940-unsplash.png" class="card-img-top" alt="...">
                <div class="card-body">
                  <h5 class="card-title">Title with Two Very Very Long Long Lines</h5>
                  <p class="card-text">With a short description.</p>
                </div>
                <div class="footer">
                  <button type="button" class="btn btn-danger btn-block">BUY NOW</button>

                </div>
              </div>
              <div class="card padding">
                <img src="../assets/paul-gaudriault-661082-unsplash.png" class="card-img-top" alt="...">
                <div class="card-body">
                  <h5 class="card-title">Title with Two Very Very Long Long Lines</h5>
                  <p class="card-text">And a very long desciption to boot.  Why bother descibing something with so many words?</p>
                </div>
                <div class="footer">
                  <button type="button" class="btn btn-danger btn-block">BUY NOW</button>

                </div>
              </div>
              <div class="card padding">
                <img src="../assets/marek-szturc-755349-unsplash.png" class="card-img-top" alt="...">
                <div class="card-body">
                  <h5 class="card-title">Title with Two Very Very Long Long Lines</h5>
                  <p class="card-text">And a very long desciption to boot.  Why bother descibing something with so many words?</p>
                </div>
                <div class="footer">
                  <button type="button" class="btn btn-danger btn-block">BUY NOW</button>

                </div>
              </div>
            </div>
          </div>
<!--           <div class="row">
            <div class="col">
              <div class="card">
                <img src="../assets/paul-gaudriault-661082-unsplash.png" class="card-img-top" alt="...">
                <div class="card-body">
                  <h5 class="card-title">Title with Two Very Very Long Long Lines</h5>
                  <p class="card-text">With a short description.</p>
                  <a href="#" class="btn btn-primary">Buy Now</a>
                </div>
              </div>
            </div>
            <div class="col">
              <div class="card">
                <img src="../assets/paul-gaudriault-661082-unsplash.png" class="card-img-top" alt="...">
                <div class="card-body">
                  <h5 class="card-title">Title with Two Very Very Long Long Lines</h5>
                  <p class="card-text">And a very long desciption to boot.  Why bother descibing something with so many words?</p>
                  <a href="#" class="btn btn-primary">Buy Now</a>
                </div>
              </div>
            </div>
            <div class="col">
              <div class="card">
                <img src="../assets/paul-gaudriault-661082-unsplash.png" class="card-img-top" alt="...">
                <div class="card-body">
                  <h5 class="card-title">Title with Two Very Very Long Long Lines</h5>
                  <p class="card-text">And a very long desciption to boot.  Why bother descibing something with so many words?</p>
                  <a href="#" class="btn btn-primary">Buy Now</a>
                </div>
              </div>
            </div>
          </div> -->


        </div>
      </div>
    </container>

    <!-- b- grid with cards and side nav -->

  </div>
</template>

<style>
  .text-align{
    text-align: left;
  }
  .padding{
    padding: 15px;
  }
  header {
/*  height:100vh;*/
  min-height:400px;
  background-size:cover;
  background-image: url('../assets/Banner1.png');
  }
  
  .container-main {
  padding: 50px;
  }
</style>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

// export default {
//   name: 'home',
//   components: {
//     HelloWorld
//   }
// }
</script>
