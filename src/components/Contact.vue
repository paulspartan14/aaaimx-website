<template>
  <!-- Contact -->
  <section
    id="contact"
    class="section"
    style="background-image: url('./static/img/banners/map-image-bg.png');"
  >
    <!-- container -->
    <div class="container">
      <div class="row">
        <div class="col-lg-12 text-center">
          <h2 class="section-heading text-uppercase">Contact Us</h2>
        </div>
      </div>
      <!-- row -->
      <div class="row">
        <!-- contact information -->
        <div class="col-md-12 col-md-offset-1">
          <ul class="contact-details">
            <li class="white-text">
              <i class="fas fa-graduation-cap"></i>
              <strong>Mérida Institute of Technology, Yucatán, México</strong>
            </li>
            <li class="white-text">
              <i class="fa fa-envelope"></i>
              <strong>
                <a href="mailto:contact@aaaimx.org">contact@aaaimx.org</a>
              </strong>
            </li>
            <li class="white-text">
              <a
                target="_blank"
                href="https://www.facebook.com/AAAI-Student-Chapter-Yucat%C3%A1n-M%C3%A9xico-408189306626213/"
              >
                <i class="fab fa-facebook-f"></i>
                <strong>AAAI Student Chapter México</strong>
              </a>
            </li>
            <li class="white-text">
              <i class="fas fa-map-marker-alt"></i>
              <strong>Perif. de Mérida Lic. Manuel Berzunza, Zona Dorada, Mérida, Yuc.</strong>
            </li>
          </ul>
        </div>
        <!-- contact information -->

        <!-- contact form -->
        <div class="col-md-6">
          <div class="contact-form">
            <form></form>
          </div>
        </div>
        <!-- /contact form -->
      </div>
      <!-- /row -->
    </div>
    <!-- /container -->
  </section>
  <!-- /Contact -->
</template>

<style scoped>
body {
  font-family: "Open Sans", sans-serif;
  font-size: 15px;
  font-weight: 400;
  overflow-x: hidden;
}

a:hover,
a:focus {
  text-decoration: none;
  outline: none;
  color: #800040;
  opacity: 0.9;
}

ul,
ol {
  margin: 0;
  padding: 0% 15% 0% 15%;
  list-style: none;
}

.white-text {
  color: #fff;
}

/* --- Section --- */
.section {
  position: relative;
  padding-top: 80px;
  padding-bottom: 80px;
}

.section-hr {
  margin-top: 80px;
  margin-bottom: 80px;
  border-color: #ebebeb;
}

@media only screen and (max-width: 767px) {
  .navbar-brand {
    margin-left: 15px;
  }
  body {
    color: #800040;
  }
}

/* -- Mobile Nav -- */
@media only screen and (max-width: 767px) {
  #nav {
    position: fixed;
    top: 0;
    right: 0;
    width: 0%;
    max-width: 250px;
    height: 100vh;
    background: #fff;
    -webkit-box-shadow: 0px 5px 10px 0px rgba(0, 0, 0, 0.1);
    box-shadow: 0px 5px 10px 0px rgba(0, 0, 0, 0.1);
    padding-top: 80px;
    padding-bottom: 40px;
    -webkit-transform: translateX(100%);
    -ms-transform: translateX(100%);
    transform: translateX(100%);
    -webkit-transition: 0.4s all cubic-bezier(0.77, 0, 0.18, 1);
    transition: 0.4s all cubic-bezier(0.77, 0, 0.18, 1);
    z-index: 9;
  }

  #header.nav-collapse #nav {
    width: 100%;
    -webkit-transform: translateX(0%);
    -ms-transform: translateX(0%);
    transform: translateX(0%);
  }

  .main-menu {
    margin: 0;
  }

  .main-menu li a {
    color: #374050 !important;
    display: inline-block;
    margin-left: 40px;
  }
}

/*------------------------------------*\
-- Contact Page --
\*------------------------------------*/

/* -- Contact Information -- */
.contact-details li {
  margin-bottom: 20px;
}

.contact-details li i {
  color: #ebebeb;
  margin-right: 15px;
  border: 1px solid #ebebeb;
  border-radius: 50%;
  width: 40px;
  height: 40px;
  line-height: 40px;
  text-align: center;
}

/* -- Contact Map -- */
#contact-map {
  height: 260px;
  border-radius: 4px;
}
</style>
