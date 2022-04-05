<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>John Shalinath Portfolio Website</title>
    <link rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/normalize/7.0.0/normalize.min.css">
    <link rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.11.2/css/all.css"
    integrity="sha256-46qynGAkLSFpVbEBog43gvNhfrOj+BmwXdxFgVK/Kvc=" crossorigin="anonymous" />

    <!-- fonts -->
    <link href="https://fonts.googleapis.com/css?family=Source+Code+Pro:400,900|Source+Sans
    +Pro:300,900&display=swap" rel="stylesheet">

    <link rel="stylesheet" href="../css/style.css">

  </head>
  <body>
    <header>
      <div class="logo">
        <img
      </div>
      <button class="nav-toggle" aria-label="toggle navigation">
        <span class="hamburger"></span>
      </button>
      <span class="nav">
            <ul class="nav__List">
                <li class="nav__item"><a href="#home" class="nav__link">Home</a></li>
                <li class="nav__item"><a href="#services" class="nav__link">My Services</a></li>
                <li class="nav__item"><a href="#about" class="nav__link">About me</a></li>
                <li class="nav__item"><a href="#work" class="nav__link">My Work</a></li>
            </ul>
        </nav>
    </header>





     <!-- Introduction -->
        <section class="intro" id="home">
          <h1 class="section__title section__title--intro">
              Hi, I am <strong>John Shalinath</strong>
          </h1>
          <p class="section__subtitle section__subtitle--intro">Chill n Art!</p>
          <img src="../images/JohnS.jpg" class="intro__img">
        </section>


        <!-- My services -->
        <section class="my-services" id="services">
            <h2 class="section__title section__title--services">What I do</h2>
            <div class="services">
                <div class="service">
                    <h3>Graphic Designing</h3>
                    <p>Have done graphic designing for almost 7 years now and I just love
                      doing some great designs for fun and for companies In mind.</p>
                </div> <!-- / service -->

                <div class="service">
                    <h3>Photography</h3>
                    <p>Have done Photography for 4 years but I'm still learning more about
                      It over time and will get even more better at It.</p>
                </div> <!-- / service -->

                <div class="service">
                    <h3>Photoshop, Illustrator</h3>
                    <p>Have done Photoshop and illustrator for 7 years so I have more
                      experience on It so I'm more used to how to use it.</p>
                </div> <!-- / service -->
            </div> <!-- / service -->

            <a href="#work" class="btn">My Work</a>
        </section>


        <!-- About me -->
        <section class="about-me" id="about">
            <h2 class="section__title section__title--about">Who I am</h2>
            <p class="section__subtitle section__subtitle--about">Designer & Artist based out of
            Chicago</p>

            <div class="about-me__body">
              <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                 eiusmod tempor incididunt ut labore et dolore magna aliqua.
                 Ut enim ad minim veniam, quis nostrud exercitation ullamco
                 laboris nisi ut aliquip ex ea commodo consequat.</p>
              <p>in reprehenderit in voluptate velit esse cillum dolore eu fugiat
                 nulla pariatur. Excepteur sint occaecat cupidatat non proident,
                 sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
           </div>

           <img src="../images/love me like you do.jpg" class="about-me__img">
        </section>

        <!-- My work -->
        <section class="my-work" id="work">
            <h2 class="section__title section__title--work">My work</h2>
            <p class="section__subtitle section__subtitle--work">A selection of my range of work</p>

            <div class="portfolio">
                  <a href="#" class="portfolio__item">
                    <img src="../images/Before and after.jpg" alt="" class="portfolio__img">
                  </a>

                  <a href="#" class="portfolio__item">
                    <img src="../images/Before and after 2.jpg" alt="" class="portfolio__img">
                  </a>

                  <a href="#" class="portfolio__item">
                    <img src="../images/Christmas Fashion Magazine.jpg" alt="" class="portfolio__img">
                  </a>

                  <a href="#" class="portfolio__item">
                    <img src="../images/Fashion Magazine.jpg" alt="" class="portfolio__img">
                  </a>

                  <a href="#" class="portfolio__item">
                    <img src="../images/Fashion Magazine Artboard 2.jpg" alt="" class="portfolio__img">
                  </a>

                  <a href="#" class="portfolio__item">
                    <img src="../images/Fashion Magazine Artboard 3.jpg" alt="" class="portfolio__img">
                  </a>

                  <a href="#" class="portfolio__item">
                    <img src="../images/Fashion Magazine Artboard 4.jpg" alt="" class="portfolio__img">
                  </a>

                  <a href="#" class="portfolio__item">
                    <img src="../images/magazine fashion.jpg" alt="" class="portfolio__img">
                  </a>

                  <a href="#" class="portfolio__item">
                    <img src="../images/bandposter.jpg" alt="" class="portfolio__img">
                  </a>

                  <a href="#" class="portfolio__item">
                    <img src="../images/W14D4_E - Double Exposure Exercise.jpg" alt="" class="portfolio__img">
                  </a>
            </div>
        </section>

        <!-- Footer -->
        <footer class="footer">
            <!-- email address -->
            <a href="Jay891589@gmail.com" class="footer__link">Jay891583@gmail.com</a>
            <ul class="social-list">
                <li class="social-list__item">
                  <a class="social-list__link" href="https://codepen.io">
                      <i class="fab fa-codepen"></i>
                    </a>
                </li>
                <li class="social-list__item">
                  <a class="social-list__link" href="http://dribbble.com">
                      <i class="fab fa-dribbble"></i>
                    </a>
                </li>
                <li class="social-list__item">
                  <a class="social-list__link" href="https://twitter.com">
                      <i class="fab fa-twitter"></i>
                    </a>
                </li>
                <li class="social-list__item">
                  <a class="social-list__link" href="https://github.com">
                      <i class="fab fa-github"></i>
                    </a>
                </li>
            </ul>
        </footer>


        <script scr="js/index.js"></script>

    </body>
</html>
