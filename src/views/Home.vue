<template>
  <div>
    <header>
      <Background />
    </header>

    <main>
      <section class="section-about">
        <div class="u-centered-text u-margin-bottom-big">
          <h2 class="heading-secondary">Exciting tours for adventurous people</h2>
        </div>
        <div class="row">
          <div class="col-1-of-2">
            <h3
              class="heading-tertiary u-margin-bottom-small"
            >You're going to fall in love with nature</h3>
            <p class="paragraph">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsa cum
              libero porro? Enim aperiam numquam neque architecto impedit quis
              at amet? Quae sunt autem neque vel nemo totam, labore nam?
            </p>

            <h3
              class="heading-tertiary u-margin-bottom-small"
            >Live adventures like you never have before</h3>
            <p class="paragraph">
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Reprehenderit eius autem aliquid molestias culpa laboriosam harum.
              Sit necessitatibus est eius fugit eaque adipisci, mollitia ea
              voluptatibus sint beatae velit fuga?
            </p>

            <a href="#" class="btn-text">Learn More &rarr;</a>
          </div>
          <div class="col-1-of-2">
            <div class="composition">
              <img
                src="../assets/img/nat-1-large.jpg"
                alt="Photo 1"
                class="composition__photo composition__photo--p1"
              />
              <img
                src="../assets/img/nat-2-large.jpg"
                alt="Photo 2"
                class="composition__photo composition__photo--p2"
              />
              <img
                src="../assets/img/nat-3-large.jpg"
                alt="Photo 3"
                class="composition__photo composition__photo--p3"
              />
            </div>
          </div>
        </div>
      </section>

      <section class="section-features">
        <div class="row">
          <div class="col-1-of-4">
            <div class="feature-box">
              <i class="feature-box__icon icon-basic-world"></i>
              <h3 class="heading-tertiary u-margin-bottom-small">Explore the world</h3>
              <p class="feature-box__text">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Labore,
                quis optio eum iusto unde distinctio incidunt
              </p>
            </div>
          </div>
          <div class="col-1-of-4">
            <div class="feature-box">
              <i class="feature-box__icon icon-basic-compass"></i>
              <h3 class="heading-tertiary u-margin-bottom-small">Meet Nature</h3>
              <p class="feature-box__text">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Labore,
                quis optio eum iusto unde distinctio incidunt
              </p>
            </div>
          </div>
          <div class="col-1-of-4">
            <div class="feature-box">
              <i class="feature-box__icon icon-basic-map"></i>
              <h3 class="heading-tertiary u-margin-bottom-small">Find your way</h3>
              <p class="feature-box__text">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Labore,
                quis optio eum iusto unde distinctio incidunt
              </p>
            </div>
          </div>
          <div class="col-1-of-4">
            <div class="feature-box">
              <i class="feature-box__icon icon-basic-heart"></i>
              <h3 class="heading-tertiary u-margin-bottom-small">Live a Healthier life</h3>
              <p class="feature-box__text">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Labore,
                quis optio eum iusto unde distinctio incidunt
              </p>
            </div>
          </div>
        </div>
      </section>

      <section id="#section-tours" class="section-tours">
        <div class="u-centered-text u-margin-bottom-big">
          <h2 class="heading-secondary">Most popular tours</h2>
        </div>

        <div class="row">
          <div class="col-1-of-3">
            <div class="card">
              <div class="card__side card__side--front">
                <div class="card__picture card__picture--1">&nbsp;</div>
                <h4 class="card__heading">
                  <span class="card__heading-span card__heading-span--1">The Sea Explorer</span>
                </h4>
                <div class="card__details">
                  <ul>
                    <li>3 day tours</li>
                    <li>Up to 30 people</li>
                    <li>2 tour guides</li>
                    <li>Sleep in cozy hotels</li>
                    <li>Difficulty: easy</li>
                  </ul>
                </div>
              </div>
              <div class="card__side card__side--back card__side--back-1">
                <div class="card__cta">
                  <div class="card__price-box">
                    <p class="card__price-only">Only</p>
                    <p class="card__price-value">$297</p>
                  </div>
                  <a href="#popup" class="btn btn-white">Book now!</a>
                </div>
              </div>
            </div>
          </div>
          <div class="col-1-of-3">
            <div class="card">
              <div class="card__side card__side--front">
                <div class="card__picture card__picture--2">&nbsp;</div>
                <h4 class="card__heading">
                  <span class="card__heading-span card__heading-span--2">The Forest Hiker</span>
                </h4>
                <div class="card__details">
                  <ul>
                    <li>7 day tours</li>
                    <li>Up to 40 people</li>
                    <li>6 tour guides</li>
                    <li>Sleep in provided tents</li>
                    <li>Difficulty: medium</li>
                  </ul>
                </div>
              </div>
              <div class="card__side card__side--back card__side--back-2">
                <div class="card__cta">
                  <div class="card__price-box">
                    <p class="card__price-only">Only</p>
                    <p class="card__price-value">$497</p>
                  </div>
                  <a href="#popup" class="btn btn-white">Book now!</a>
                </div>
              </div>
            </div>
          </div>
          <div class="col-1-of-3">
            <div class="card">
              <div class="card__side card__side--front">
                <div class="card__picture card__picture--3">&nbsp;</div>
                <h4 class="card__heading">
                  <span class="card__heading-span card__heading-span--3">The Snow Adventure</span>
                </h4>
                <div class="card__details">
                  <ul>
                    <li>5 day tours</li>
                    <li>Up to 15 people</li>
                    <li>3 tour guides</li>
                    <li>Sleep in provided tents</li>
                    <li>Difficulty: hard</li>
                  </ul>
                </div>
              </div>
              <div class="card__side card__side--back card__side--back-3">
                <div class="card__cta">
                  <div class="card__price-box">
                    <p class="card__price-only">Only</p>
                    <p class="card__price-value">$897</p>
                  </div>
                  <a href="#popup" class="btn btn-white">Book now!</a>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="u-centered-text u-margin-top-huge">
          <a href="#" class="btn btn--green">Discover all tours</a>
        </div>
      </section>

      <section class="section-stories">
        <div class="bg-video">
          <video class="bg-video__content" autoplay muted loop>
            <source src="./../assets/img/video.mp4" type="video/mp4" />
            <source src="./../assets/img/video.webm" type="video/webm" />Your Browser is not supported.
          </video>
        </div>

        <div class="u-centered-text u-margin-bottom-big">
          <h2 class="heading-secondary">We make people genuinely happy</h2>
        </div>

        <div class="row">
          <div class="story">
            <figure class="story__shape">
              <img
                class="story__image"
                src="./../assets/img/nat-8.jpg"
                alt="Person on a tour testimonial"
              />
              <figcaption class="story__caption">Mary Smith</figcaption>
            </figure>
            <div class="story__text">
              <h3
                class="heading-tertiary u-margin-bottom-small"
              >I had the best week ever with my family</h3>
              <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quidem, in debitis, voluptas aliquid non minus vero odit excepturi, quasi pariatur consequatur! Dolorum neque harum at! Distinctio hic tempora ut facilis?</p>
            </div>
          </div>
        </div>

        <div class="row">
          <div class="story">
            <figure class="story__shape">
              <img
                class="story__image"
                src="./../assets/img/nat-9.jpg"
                alt="Person on a tour testimonial"
              />
              <figcaption class="story__caption">Jack Wilson</figcaption>
            </figure>
            <div class="story__text">
              <h3 class="heading-tertiary u-margin-bottom-small">Wow! Amazing</h3>
              <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quidem, in debitis, voluptas aliquid non minus vero odit excepturi, quasi pariatur consequatur! Dolorum neque harum at! Distinctio hic tempora ut facilis?</p>
            </div>
          </div>
        </div>

        <div class="u-centered-text u-margin-top-huge">
          <a href="#" class="btn-text">Read All Stories &rarr;</a>
        </div>
      </section>

      <section class="section-book">
        <div class="row">
          <div class="book">
            <div class="book__form">
              <form action class="form" autocomplete="off">
                <div class="u-margin-bottom-medium">
                  <h2 class="heading-secondary">Start Booking Now</h2>
                </div>
                <div class="form__group">
                  <input
                    id="name"
                    type="text"
                    class="form__input"
                    placeholder="Full Name"
                    pattern="[^0-9]+"
                    required
                    @keypress="preventNumbers($event)"
                  />
                  <label for="name" class="form__label">&#10003; Full Name</label>
                </div>

                <div class="form__group">
                  <input
                    id="email"
                    type="email"
                    class="form__input"
                    placeholder="Email address"
                    required
                  />
                  <label for="email" class="form__label">&#10003; Email</label>
                </div>
                <div class="form__group">
                  <div class="form__radio-group u-margin-bottom-small">
                    <input id="small" type="radio" class="form__radio-input" name="size" />
                    <label for="small" class="form__radio-label">
                      <span class="form__radio-button"></span>
                      Small tour Group
                    </label>
                  </div>
                  <div class="form__radio-group">
                    <input id="large" type="radio" class="form__radio-input" name="size" />
                    <label for="large" class="form__radio-label">
                      <span class="form__radio-button"></span>
                      Large tour Group
                    </label>
                  </div>
                </div>
                <div class="form__group">
                  <button class="btn btn--green">Next Step &rarr;</button>
                </div>
              </form>
            </div>
          </div>
        </div>
      </section>
    </main>

    <footer class="footer">
      <div class="footer__logo-box">
        <picture class="footer__logo">
          <source
            srcset="./../assets/img/logo-green-small-1x.png 1x, ./../assets/img/logo-green-small-2x.png 2x"
            media="(max-width: 37.5em)"
          />
          <img
            class="footer__logo"
            srcset="./../assets/img/logo-green-1x.png 1x, ./../assets/img/logo-green-2x.png 2x"
            alt="Full logo"
          />
        </picture>
      </div>
      <div class="row">
        <div class="col-1-of-2">
          <div class="footer__navigation">
            <ul class="footer__list">
              <li class="footer__item">
                <a href="#" class="footer__link">Company</a>
              </li>
              <li class="footer__item">
                <a href="#" class="footer__link">Contact us</a>
              </li>
              <li class="footer__item">
                <a href="#" class="footer__link">Carreers</a>
              </li>
              <li class="footer__item">
                <a href="#" class="footer__link">Privacy Policy</a>
              </li>
              <li class="footer__item">
                <a href="#" class="footer__link">Terms and Conditions</a>
              </li>
            </ul>
          </div>
        </div>
        <div class="col-1-of-2">
          <p class="footer__copyright">
            Built, and extended using Vue.js, by
            <a href="#" class="footer__link">Pierre Davis</a> after following,
            <a href="#" class="footer__link">Jonas Schedtmann's</a> online course
            <a href="#" class="footer__link">Advance CSS and SASS</a>. The original author's design is protected by Copyright &copy;.
          </p>
        </div>
      </div>
    </footer>

    <div id="popup" class="popup">
      <div class="popup__content">
        <div class="popup__left">
          <img src="./../assets/img/nat-8.jpg" alt="Tour Photo" class="popup__img" />
          <img src="./../assets/img/nat-9.jpg" alt="Tour Photo" class="popup__img" />
        </div>
        <div class="popup__right">
          <a href="#section-tours" class="popup__close">&times;</a>
          <h2 class="heading-secondary u-margin-bottom-small">Start Booking Now</h2>
          <h3
            class="heading-tertiary u-margin-bottom-small"
          >Important &ndash; Please read thse terms before booking.</h3>
          <p
            class="popup__text"
          >Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ratione neque eligendi voluptates consequatur illum natus veniam repellendus praesentium distinctio maxime! Voluptate a, corrupti iste sapiente consectetur quidem quis dolore porro.</p>
          <a href="#popup" class="btn btn--green">Book Now!</a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import Background from "@/components/BackgroundComponent.vue";
export default {
  name: "Home",
  components: {
    Background
  },
  methods: {
    preventNumbers(event) {
      if (!/[A-Za-zÀ-ÿ]/.test(String.fromCharCode(event.keyCode))) {
        event.preventDefault();
      }
    }
  }
};
</script>
