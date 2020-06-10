<template>
  <!-- <div class="wrapper">
    <header class="page-header">
      <nav>
        <h2 class="logo">LOGO</h2>
        <ul>
          <li>
            <a href="">Work</a>
          </li>
          <li>
            <a href="">Services</a>
          </li>
          <li>
            <a href="">Team</a>
          </li>
          <li>
            <a href="">Careers</a>
          </li>
        </ul>
        <button class="cta-contact">Get in touch</button>
      </nav>
    </header>
    <main class="page-main">
      <div>
        <h1>We are here to help you</h1>
        <p>One morning, when Gregor Samsa woke from troubled dreams, he found himself transformed in his bed into a horrible vermin.</p>
        <p>It wasn't a dream. His room, a proper human.</p>
      </div>
    </main>
    <footer class="page-footer">
      <small>© Copyright 2018. All rights reserved.</small>
      <ul>
        <li>
          <a href="" target="_blank">
            <i class="icon ion-logo-facebook"></i>
          </a>
        </li>
        <li>
          <a href="" target="_blank">
            <i class="icon ion-logo-twitter"></i>
          </a>
        </li>
        <li>
          <a href="" target="_blank">
            <i class="icon ion-logo-linkedin"></i>
          </a>
        </li>
        <li>
          <a href="" target="_blank">
            <i class="icon ion-logo-github"></i>
          </a>
        </li>
      </ul>
    </footer>
  </div> -->
  <footer class="footer position-absolute font-size">
    <div class="container pt-5 pb-5">
        <div class="row">
            <div class="col-md-3">
              <div></div>
              <h3>Quick contact info</h3>
              <ul>
                <li>Lorem Ipsum has been the industry's standard dummy text ever since the 1500s</li>
                <li>28, Park Ville Chordiya City, Ajmer Road Jaipur - 12</li>
                <li>lipsum@lipsum.com</li>
                <li>+91-8769659799</li>
              </ul>
            </div>
            <div class="col-md-3">two</div>
            <div class="col-md-3">three</div>
            <div class="col-md-3">four</div>
        </div>
    </div>
    <div class="subfooter pt-3 pb-3">
        <div class="container">
            <div class="d-flex">
                <div class="flex-fill align-self-center">
                  <img src="@/assets/images/branding/brand-logo-secondary.svg" class="img-fluid">
                </div>
                <div class="flex-fill align-self-center text-center">
                  © Copyright-2020 | Designer Naruka
                </div>
                <div class="flex-fill align-self-center text-right">
                  <a href="#" class="">
                    <i class="fab fa-facebook-f"></i>
                  </a>
                  <a href="#" class="">
                    <i class="fab fa-twitter"></i>
                  </a>
                  <a href="#" class="">
                    <i class="fab fa-instagram"></i>
                  </a>
                  <a href="#" class="">
                    <i class="fab fa-youtube"></i>
                  </a>
                </div>
            </div>
        </div>
    </div>
  </footer>
</template>
<script>
  export default {
    name: 'Footer',
  }
</script>
<style scoped>
  @import url("https://fonts.googleapis.com/css?family=Dosis:400,700");

:root {
  --main-white-color: #f2f2f2;
  --main-black-color: black;
  --main-purple-color: #9e89b8;
}

* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

button {
  background: none;
  outline: none;
  cursor: pointer;
}

ul {
  list-style: none;
}

a {
  text-decoration: none;
  color: inherit;
}

body {
  font: 16px/1.5 "Dosis", sans-serif;
  /*IE FIX*/
  /*display: flex;
  flex-direction: column;*/
}

/* CONTAINER
–––––––––––––––––––––––––––––––––––––––––––––––––– */
.wrapper {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

.wrapper > * {
  padding: 20px;
}


/* HEADER
–––––––––––––––––––––––––––––––––––––––––––––––––– */
.page-header {
  background: var(--main-white-color);
}
.page-header nav {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  align-items: center;
}

.page-header ul {
  display: flex;
  order: 1;
  width: 100%;
  margin-top: 15px;
}

.page-header ul li:not(:last-child) {
  padding-right: 15px;
}

.page-header .cta-contact {
  font-family: inherit;
  font-size: 1.2rem;
  padding: 5px 18px;
  border: 1px solid;
  border-radius: 5px;
}


/* MAIN
–––––––––––––––––––––––––––––––––––––––––––––––––– */
.page-main {
  display: flex;
  flex-direction: column;
  justify-content: center;
  flex-grow: 1;
  min-height: 350px;
  background: var(--main-purple-color)
    url(https://s3-us-west-2.amazonaws.com/s.cdpn.io/162656/city.jpg) no-repeat
    center / cover;
  background-blend-mode: luminosity;
  color: var(--main-white-color);
}

.page-main div {
  max-width: 500px;
}

.page-main h1 {
  margin-bottom: 20px;
}

.page-main p + p {
  margin-top: 10px;
}


/* FOOTER
–––––––––––––––––––––––––––––––––––––––––––––––––– */
.page-footer {
  display: flex;
  flex-direction: column-reverse;
  background: var(--main-white-color);
}

.page-footer ul {
  display: flex;
  font-size: 1.5rem;
  margin-bottom: 5px;
}

.page-footer ul li:not(:last-child) {
  margin-right: 20px;
}


/* MQ
–––––––––––––––––––––––––––––––––––––––––––––––––– */
@media screen and (min-width: 550px) {
  .page-header ul {
    width: auto;
    margin-top: 0;
  }

  .page-header .cta-contact {
    order: 1;
  }

  .page-footer {
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
  }

  .page-footer ul {
    margin-bottom: 0;
  }
}

@media screen and (min-width: 768px) {
  body {
    font-size: 18px;
  }

  .page-main {
    padding-left: 90px;
  }
}

</style>
