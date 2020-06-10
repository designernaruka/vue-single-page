<template>
    <header class="site-header">
      <nav class="navbar navbar-default">
        <div class="header-inner">
          <div class="container">
            <div class="row">
              <div class="col-md-12">
                <div class="brand">
                  <a href="#">
                    <h1>Logo</h1>
                  </a>
                </div>
                <nav  id="nav-wrap" class="main-nav">
                  <a id="toggle-btn" href="#"><i class="fa fa-bars"></i> </a>
                  <ul class="sf-menu">
                    <li class="current"> <a href="index.html">Home</a> </li>
                    <li> <a href="about-us.html">About Us </a></li>
                    <li> <a href="products.html">Products</a></li>
                    <li> <a href="exports.html">Exports</a></li>
                    <li> <a href="clients.html">Clients</a> </li>
                    <li> <a href="contact.html">Contact</a> </li>
                  </ul>
                </nav>
              </div>
            </div>
          </div>
        </div>
      </nav>
    </header>
</template>
<script>
  export default {
    name: 'header',
  }
</script>
<style>
  h3 {
  margin-bottom: 5%;
  }
</style>