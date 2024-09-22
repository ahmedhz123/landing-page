<template>
  <section class="landing">
    <div class="container">
      <div class="nav">
        <h2>LAVA</h2>
        <div class="icon" style="cursor: pointer">
          <v-icon @click="showListNav()">mdi-menu</v-icon>
          <v-icon @click="deleteListNav()">mdi-close</v-icon>
        </div>
        <nav>
          <a href="#">HOME</a>
          <a href="#">ABOUT</a>
          <a href="#">TESTIMONIALS</a>
          <a href="#">CONTACT US</a>
          <a
            href="#"
            style="position: relative"
            class="hover"
            @click="hideNav()"
            @mouseover="displayNav()"
            >DROP DOWN <v-icon>mdi-chevron-down</v-icon>
            <v-icon style="display: none">mdi-close</v-icon>
            <nav class="pseudo">
              <ul>
                <li><a href="#">ABOUT US</a></li>
                <li><a href="#">FEATURES</a></li>
                <li><a href="#">FAQ'S</a></li>
                <li><a href="#">BLOG</a></li>
              </ul>
            </nav></a
          >
        </nav>
      </div>

      <div class="create">
        <div class="container">
          <p class="simple">
            Simple App <br />
            that we <span>CREATE</span>
          </p>
          <p class="link">
            Lava <a href="#">HTML landing page</a> template is provided by
            <a href="#">TemplateMo</a>. You can modify and use it for your
            commercial websites for free of charge. This template is last
            updated on 29 Oct 2019.
          </p>
          <button><a href="#">KNOW US BETTER</a></button>
        </div>
      </div>
    </div>
    <img src="../assets/images/banner-bg.png" />
  </section>
  <!-- CARDS -->
  <section class="cards">
    <div class="container">
      <transition name="fade_1" appear="true" mode="in-out">
        <div class="card one">
          <img src="../assets/images/features-icon-1.png" />
          <h3>Trend Analysis</h3>
          <p>
            Curabitur pulvinar vel odio sed sagittis. Nam maximus ex diam, nec
            consectetur diam.
          </p>
          <button><a href="#">READ MORE</a></button>
        </div>
      </transition>
      <transition name="fade_2" appear="true" mode="in-out">
        <div class="card two">
          <img src="../assets/images/features-icon-2.png" />
          <h3>Site Optmization</h3>
          <p>
            Curabitur pulvinar vel odio sed sagittis. Nam maximus ex diam, nec
            consectetur diam.
          </p>
          <button><a href="#">DISCOVER MORE</a></button>
        </div>
      </transition>
      <transition name="fade_3" appear="true" mode="in-out">
        <div class="card three">
          <img src="../assets/images/features-icon-3.png" />
          <h3>Email Design</h3>
          <p>
            Curabitur pulvinar vel odio sed sagittis. Nam maximus ex diam, nec
            consectetur diam.
          </p>
          <button><a href="#">MORE DETAIL</a></button>
        </div>
      </transition>
    </div>
  </section>
  <!-- Phone -->
  <section class="phone">
    <img class="decor" src="../assets/images/left-bg-decor.png" />
    <div class="container">
      <transition name="fade_img" appear="true" mode="in-out">
        <img src="../assets/images/left-image.png" />
      </transition>
      <div class="boxes">
        <transition name="fade_box1" appear="true" mode="in-out">
          <div class="box">
            <img src="../assets/images/about-icon-01.png" />
            <div class="info">
              <h2>Vestibulum pulvinar rhoncus</h2>
              <p>
                lease do not redistribute this template ZIP file for a download
                purpose. You may <a href="#">contact</a> us for additional
                licensing of our template or to get a PSD file.
              </p>
            </div>
          </div>
        </transition>
        <transition name="fade_box2" appear="true" mode="in-out">
          <div class="box">
            <img src="../assets/images/about-icon-02.png" />
            <div class="info">
              <h2>Sed blandit quam in velit</h2>
              <p>
                You can <a href="#"> download Lava Template</a> from our
                website. Duis viverra, ipsum et scelerisque placerat, orci magna
                consequat ligula.
              </p>
            </div>
          </div>
        </transition>
        <transition name="fade_box3" appear="true" mode="in-out">
          <div class="box">
            <img src="../assets/images/about-icon-03.png" />
            <div class="info">
              <h2>Aenean faucibus venenatis</h2>
              <p>
                Phasellus in imperdiet felis, eget vestibulum nulla. Aliquam nec
                dui nec augue maximus porta. Curabitur tristique lacus.
              </p>
            </div>
          </div>
        </transition>
      </div>
    </div>
  </section>
  <!--About-->
  <section class="about">
    <img src="../assets/images/right-bg-decor.png" />
    <div class="container">
      <p class="first">What They Think <span>About Us</span></p>
      <p class="second">
        Suspendisse vitae laoreet mauris. Fusce a nisi dapibus, euismod purus
        non, convallis odio. Donec vitae magna ornare, pellentesque ex vitae,
        aliquet urna.
      </p>
    </div>
    <div class="container_2">
      <div class="cards">
        <transition name="fade_one" appear="true" mode="in-out">
          <div class="card one">
            <ul>
              <li><v-icon size="15">mdi-star</v-icon></li>
              <li><v-icon size="15">mdi-star</v-icon></li>
              <li><v-icon size="15">mdi-star</v-icon></li>
              <li><v-icon size="15">mdi-star</v-icon></li>
              <li><v-icon size="15">mdi-star</v-icon></li>
            </ul>
            <h2>Jonathan Smart</h2>
            <p>
              “Nullam hendrerit, elit a semper pharetra, ipsum nibh tristique
              tortor, in tempus urna elit in mauris.”
            </p>
            <h6>Besta CTO</h6>
            <img src="../assets/images/testimonial-author-1.png" />
          </div>
        </transition>
        <transition name="fade_two" appear="true" mode="in-out">
          <div class="card two">
            <ul>
              <li><v-icon size="15">mdi-star</v-icon></li>
              <li><v-icon size="15">mdi-star</v-icon></li>
              <li><v-icon size="15">mdi-star</v-icon></li>
              <li><v-icon size="15">mdi-star</v-icon></li>
              <li><v-icon size="15">mdi-star</v-icon></li>
            </ul>
            <h2>Martino Tino</h2>
            <p>
              “Morbi non mi luctus felis molestie scelerisque. In ac libero
              viverra, placerat est interdum, rhoncus leo.”
            </p>
            <h6>Web Analyst</h6>
            <img src="../assets/images/testimonial-author-1.png" />
          </div>
        </transition>
        <transition name="fade_three" mode="in-out" appear="true">
          <div class="card three">
            <ul>
              <li><v-icon size="15">mdi-star</v-icon></li>
              <li><v-icon size="15">mdi-star</v-icon></li>
              <li><v-icon size="15">mdi-star</v-icon></li>
            </ul>
            <h2>George Tasa</h2>
            <p>
              “Fusce rutrum in dolor sit amet lobortis. Ut at vehicula justo.
              Donec quam dolor, congue a fringilla sed, maximus et urna.”
            </p>
            <h6>System Admin</h6>
            <img src="../assets/images/testimonial-author-1.png" />
          </div>
        </transition>
        <transition name="fade_four" appear="true" mode="in-out">
          <div class="card four">
            <ul>
              <li><v-icon size="15">mdi-star</v-icon></li>
              <li><v-icon size="15">mdi-star</v-icon></li>
              <li><v-icon size="15">mdi-star</v-icon></li>
              <li><v-icon size="15">mdi-star</v-icon></li>
            </ul>
            <h2>Sir James</h2>
            <p>
              "Fusce rutrum in dolor sit amet lobortis. Ut at vehicula justo.
              Donec quam dolor, congue a fringilla sed, maximus et urna."
            </p>
            <h6>New Vilager</h6>
            <img src="../assets/images/testimonial-author-1.png" />
          </div>
        </transition>
      </div>
    </div>
  </section>
  <!-- Footer -->
  <footer>
    <div class="container">
      <form method="GET">
        <div class="form_text">
          <input type="text" placeholder="Full Name" required />
          <input type="email" placeholder="E-Mail Address" />
        </div>
        <textarea placeholder="Your Message"></textarea>
        <input type="submit" value="SEND MESSAGE NOW" />
      </form>
      <div class="info">
        <h1>More About <span>Lava</span></h1>
        <p>
          phasellus dapibus urna vel lacus accumsan, iaculis eleifend leo
          auctor. Duis at finibus odio. Vivamus ut pharetra arcu, in porta
          metus. Suspendisse blandit pulvinar ligula ut elementum.
        </p>
        <br />
        <p>
          If you need this contact form to send email to your inbox, you may
          follow our <a href="https://templatemo.com/contact">contact</a> page
          for more detail.
        </p>
        <div class="icons">
          <div class="icon">
            <v-icon color="white">mdi-facebook</v-icon>
          </div>
          <div class="icon">
            <v-icon color="white">mdi-twitter</v-icon>
          </div>
          <div class="icon">
            <v-icon color="white">mdi-linkedin</v-icon>
          </div>
          <div class="icon">
            <v-icon color="white">mdi-wifi</v-icon>
          </div>
          <div class="icon">
            <v-icon color="white">mdi-earth</v-icon>
          </div>
        </div>
      </div>
      <hr />
      <p class="footer">
        Copyright &copy; 2020 Lava Landing Page | Designed by TemplateMo
      </p>
    </div>
  </footer>
</template>

<style scoped lang="scss">
/*Transitions*/
.fade_1-enter-from {
  opacity: 0;
  transform: translateX(-100px);
}
.fade_1-leave-to {
  opacity: 1;
  transform: translateX(0);
}
.fade_1-enter-active {
  transition: all 0.8s ease;
}
.fade_1-leave-active {
  transition: all 0.8s ease;
}
// fade_2
.fade_2-enter-from {
  transform: translateY(100px);
  opacity: 0;
}
.fade_2-leave-to {
  transform: translateY(0);
  opacity: 1;
}
.fade_2-enter-active,
.fade_2-leave-active {
  transition: all 0.8s ease;
}
// fade_3
.fade_3-enter-from {
  transform: translateX(100px);
  opacity: 0;
}
.fade_3-leave-to {
  transform: translateX(0px);
  opacity: 1;
}
.fade_3-enter-active,
.fade_3-leave-active {
  transition: all 0.8s ease;
}
//.fade_img
.fade_img-enter-from {
  opacity: 0;
  transform: translateX(-100px);
}
.fade_img-leave-to {
  opacity: 1;
  transform: translateX(0);
}
.fade_img-enter-active,
.fade_img-leave-active {
  transition: all 0.8s ease;
}
// fade of boxes
.fade_box1-enter-from,
.fade_box2-enter-from,
.fade_box3-enter-from {
  opacity: 0;
  transform: translateX(100px);
}
.fade_box1-leave-to,
.fade_box2-leave-to,
.fade_box3-leave-to {
  opacity: 1;
  transform: translateX(0px);
}
.fade_box1-enter-active {
  transition: all 0.8s ease;
}
.fade_box1-leave-active {
  transition: all 0.8s ease;
}
.fade_box2-enter-active {
  transition: all 0.8s 0.2s ease;
}
.fade_box2-leave-active {
  transition: all 0.8s ease;
}
.fade_box3-enter-active {
  transition: all 0.8s 0.4s ease;
}
.fade_box3-leave-active {
  transition: all 0.8s ease;
}
// fade of boxes
.fade_one-enter-from {
  transform: translateY(70px);
  opacity: 0;
}
.fade_one-leave-to {
  transform: translateY(0);
  opacity: 1;
}
.fade_one-enter-active {
  transition: all 0.8s ease;
}
.fade_one-leave-active {
  transition: all 0.8s ease;
}
.fade_two-enter-from {
  transform: translateY(90px);
  opacity: 0;
}
.fade_two-leave-to {
  transform: translateY(0);
  opacity: 1;
}
.fade_two-enter-active {
  transition: all 0.8s 0.4s ease;
}
.fade_two-leave-active {
  transition: all 0.8s ease;
}
.fade_three-enter-from {
  transform: translateY(100px);
  opacity: 0;
}
.fade_three-leave-to {
  transform: translateY(0);
  opacity: 1;
}
.fade_three-enter-active {
  transition: all 0.8s 0.6s ease;
}
.fade_three-leave-active {
  transition: all 0.8s 0.6s ease;
}
.fade_four-enter-from {
  transform: translateY(110px);
  opacity: 0;
}
.fade_four-leave-to {
  transform: translateY(0);
  opacity: 1;
}
.fade_four-enter-active {
  transition: all 0.8s 0.8s ease;
}
.fade_four-leave-active {
  transition: all 0.8s 0.8s ease;
}
/*Landing*/
section.landing {
  position: relative;
  div.container {
    div.nav {
      div.icon {
        @media (min-width: 992px) {
          & {
            display: none;
          }
        }
        :last-child {
          display: none;
        }
      }
      @media (max-width: 991px) {
        & {
          background-color: #f9f4f4;
          display: flex;
          align-items: center;
          padding: 1em;
          h2 {
            margin-top: auto;
          }
        }
      }
      nav.pseudo {
        background: white;
        width: 170%;
        z-index: 5;
        margin: 0;
        padding: 0;
        position: absolute;
        left: 0;
        top: 130%;
        display: none;
        transition: 0.3s;
        ul {
          width: 100%;
          display: flex;
          flex-direction: column;
          align-items: flex-start;
          margin-left: 0;
          li {
            width: 100%;
            &:hover {
              border-left: 5px solid #fba70b;
              padding-left: 5px;
            }
            list-style: none;
            transition: 0.2s;
            width: 100%;
            padding-top: 0.5em;
            padding-bottom: 0.5em;
            text-align: left;
            &:not(:last-child) {
              border-bottom: 0.1px solid #dfdcdc;
            }
            a {
              text-decoration: none;
              color: #7a7a7a;
              margin: 0 0.5em;
              font-size: 0.9rem;
              font-weight: 500;
              padding: 1em;
              &:hover {
                color: #f4813f;
              }
            }
          }
        }
      }
      display: flex;
      align-items: center;
      justify-content: space-around;
      width: 100%;
      h2 {
        margin-left: 2em;
        color: #191a20;
        font-size: 1.75rem;
      }
      nav {
        margin-right: 15em;
        margin-top: 1em;
        padding: 0.4em 0.3em;
        background-color: white;
        @media (max-width: 991px) {
          & {
            display: none;
          }
        }
        li {
          padding: 0;
          a.hover {
            position: relative;
          }
        }
        a {
          &:first-child {
            color: #fba70b;
          }
          &:hover {
            color: #fba70b;
          }
          text-decoration: none;
          margin-left: 2em;
          transition: 0.5s;
          font-size: 0.85rem;
          color: #7a7a7a;
          font-weight: 500;
          padding: 0;
        }
      }
    }
    div.create {
      width: 50%;
      margin-top: 10em;
      @media (max-width: 1200px) {
        & {
          margin: 50em 0 0;
        }
      }
      @media (max-width: 991px) {
        & {
          width: 100%;
          margin: 45em 0 0;
        }
      }
      div.container {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: flex-start;
        margin-left: 3em;
        p.simple {
          color: #191a20;
          font-size: 3.2rem;
          font-weight: 900;
          text-align: left;
          span {
            color: #fba70b;
          }
        }
        p.link {
          color: #7a7a7a;
          font-size: 1.1rem;
          font-weight: 300;
          text-align: left;
          width: 70%;
          a {
            text-decoration: none;
            color: #007bff;
          }
        }
        button {
          background-color: #fba70b;
          border: none;
          padding: 1.2em 2em;
          border-radius: 4em;
          transition: 0.5s;
          margin-top: 2em;
          a {
            color: white;
            text-decoration: none;
            font-weight: 600;
          }
          cursor: pointer;
          &:hover {
            background-color: #e83e8c;
          }
        }
      }
    }
  }
  img {
    position: absolute;
    right: 0;
    top: 0;
    z-index: -2;
    @media (max-width: 991px) {
      & {
        width: 100%;
      }
    }
  }
}
/*CARDS*/
section.cards {
  margin-top: 25em;
  div.container {
    width: 80%;
    display: grid;
    margin: 0 auto;
    grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
    grid-column-gap: 2em;
    grid-row-gap: 1em;
    justify-items: center;
    @media (max-width: 991px) {
      & {
        width: 75%;
        display: flex;
        flex-direction: column;
        justify-content: center;
      }
    }
    div.one {
      position: relative;
    }
    div.one::before {
      content: "01";
      position: absolute;
      color: #fdefe9;
      font-size: 6.5rem;
      font-weight: 600;
      left: 12%;
      z-index: -1;
      top: -5%;
    }
    div.two {
      position: relative;
    }
    div.two::before {
      content: "02";
      position: absolute;
      color: #fdefe9;
      font-size: 6.5rem;
      font-weight: 600;
      left: 12%;
      z-index: -1;
      top: -5%;
    }
    div.three {
      position: relative;
    }
    div.three::before {
      content: "03";
      position: absolute;
      color: #fdefe9;
      font-size: 6.5rem;
      font-weight: 600;
      left: 12%;
      z-index: -1;
      top: -5%;
    }
    div.card {
      display: flex;
      flex-direction: column;
      align-items: center;
      box-shadow: 1px 1px 5px 1px #dedcdc;
      padding: 2em 1em;
      span {
        color: #fdefe9;
        font-size: 6rem;
        z-index: -1;
        font-weight: 600;
      }
      h3 {
        color: #191a20;
        font-weight: 500;
      }
      p {
        color: #7a7a7a;
        font-size: 0.9rem;
        width: 60%;
        text-align: center;
      }
      button {
        border: none;
        background-color: #f4813f;
        transition: 0.5s;
        padding: 1.2em 1.7em;
        border-radius: 2em;
        margin-top: 1em;
        &:hover {
          background-color: #e83e8c;
        }
        a {
          color: white;
          text-decoration: none;
          font-weight: bold;
        }
      }
    }
  }
}
/*Phone*/
section.phone {
  position: relative;
  display: flex;
  align-items: center;
  justify-content: center;
  margin-top: 15em;
  img.decor {
    position: absolute;
    left: 0;
    z-index: -1;
  }
  div.container {
    @media (max-width: 767px) {
      & {
        display: grid;
        grid-template-columns: repeat(auto-fill, minmax(100%, 1fr));
        img {
          width: 50%;
        }
        div.boxes {
          display: grid;
          grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
        }
        div.box {
          display: grid;
          grid-template-columns: 25% 75%;
          h2 {
            text-align: center;
          }
          p {
            text-align: center;
          }
          img {
            align-self: center;
          }
        }
      }
    }
    @media (max-width: 991px) {
      & {
        display: flex;
        flex-direction: column;
        align-items: center;
        width: 150%;
        img {
          width: 50%;
        }
        div.boxes {
          width: 150%;
          margin: 1em auto;
          align-self: start;
          display: flex;
          flex-direction: column;
          align-items: start;
          .box {
            width: 150%;
            margin-left: 2em;
            box-sizing: border-box;
          }
        }
      }
    }
    display: flex;
    justify-content: center;
    align-items: end;
    div.boxes {
      width: 50%;
      margin-left: 3em;
      align-self: end;
    }
    div.box {
      display: flex;
      justify-content: space-between;
      &:not(:last-child) {
        margin-bottom: 3em;
      }
      img {
        width: 6em;
        height: 6em;
        align-self: center;
      }
      h2 {
        color: #1e1e1e;
        font-weight: 500;
        font-size: 1.2rem;
      }
      p {
        color: #7a7a7a;
        a {
          color: #007bff;
          text-decoration: none;
        }
      }
      div.info {
        text-align: left;
        margin-left: 2em;
      }
    }
  }
}
/*About*/
section.about {
  position: relative;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  margin-top: 15em;
  img {
    position: absolute;
    right: 0;
    z-index: -1;
  }
  div.container {
    p.first {
      color: #1e1e1e;
      font-size: 2.5rem;
      font-weight: 700;
      span {
        color: #f4813f;
      }
    }
    p.second {
      width: 60%;
      color: #7a7a7a;
      margin: 0 auto;
    }
  }
  div.container_2 {
    margin-top: 5em;
    @media (max-width: 500px) {
      & {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        width: 40%;
      }
    }
    @media (max-width: 991px) {
      & {
        margin-top: 4em;
        width: 70%;
        display: flex;
        align-items: center;
        div.card {
          position: relative;
          img {
            position: absolute;
            left: 50%;
          }
        }
      }
    }
    div.cards {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(350px, 1fr));
      grid-template-rows: repeat(auto-fill, minmax(300, 1fr));
      grid-column-gap: 4.5em;
      grid-row-gap: 4.5em;
      div.card {
        display: flex;
        flex-direction: column;
        position: relative;
        justify-content: space-around;
        align-items: center;
        height: 40vh;
        color: #ffffff;
        background-image: linear-gradient(
          145deg,
          rgba(244, 129, 63, 1) 0%,
          rgba(241, 85, 106, 1) 100%
        );
        img {
          position: absolute;
          left: -10%;
          top: -15%;
          z-index: 2;
          width: 6em;
          height: 6em;
        }
        ul {
          display: flex;
          justify-content: center;
          align-items: center;
          margin: 1em 0;
          li {
            list-style: none;
          }
        }
        h2 {
          margin: 1em 0;
          font-size: 1.3rem;
          font-weight: 500;
        }
        p {
          margin: 1em 0;
          font-style: italic;
          font-size: 0.9rem;
          font-weight: 200;
        }
        h6 {
          margin: 1em 0;
          font-weight: 200;
        }
      }
    }
  }
}
/*Footer*/
footer {
  margin-top: 12em;
  background-image: url("../assets/images/footer-bg.png");
  overflow: hidden;
  background-size: cover;
  padding: 20em;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  gap: 1em;
  align-items: center;
  @media (max-width: 767px) {
    & {
      padding-left: 0;
      padding-right: 0;
      margin: 0 auto;
      div.container {
        display: flex;
        flex-direction: column;
        align-items: center;
        width: 100%;
        div.info {
          display: flex;
          flex-direction: column;
          width: 100%;
        }
        form {
          width: 90%;
          margin-left: 15% !important;
          textarea {
            padding-left: 10px !important;
            font-size: 0.8em !important;
            padding-right: 0 !important;
          }
          input {
            padding-right: 0 !important;
            padding-left: 10px !important;
            &::placeholder {
              font-size: 0.8em !important;
            }
          }
          input[type="submit"] {
            width: 180px !important;
            height: 100px !important;
            border-radius: 100em !important;
            font-size: 0.8rem !important;
          }
        }
      }
    }
  }
  @media (max-width: 991px) {
    & {
      div.container {
        display: flex;
        flex-direction: column;
        align-items: center;
        div.info {
          display: flex;
          flex-direction: column;
          align-items: center;
        }
        form {
          div.form_text {
            display: flex;
            flex-direction: column;
            input {
              width: 100%;
            }
          }
        }
        p.footer {
          margin: 0 auto;
          width: 100%;
        }
      }
    }
  }
  width: 100%;
  position: relative;
  div.container {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 5em;
    width: 100%;
    div.info {
      padding: 2em;
      div.icons {
        display: flex;
        gap: 1em;
        margin-top: 1em;
        div.icon {
          border: 1px solid white;
          padding: 0.5em;
          border-radius: 50%;
          background-color: transparent;
          transition: 0.5s;
          cursor: pointer;
          &:hover {
            background-color: #fba70b;
          }
        }
      }
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: flex-start;
      text-align: left;
      margin-right: 2.8em;
      p {
        color: white;
        width: fit-content;
        a {
          text-decoration: none;
          color: white;
          &:hover {
            color: #fba70b;
          }
        }
      }
      p:first-child {
        margin-bottom: 2em;
      }
      h1 {
        font-size: 2.5rem;
        color: white;
        width: 140%;
        span {
          color: #fba70b;
        }
      }
    }
    form {
      background-color: white;
      padding: 1em 2em;
      padding-bottom: 0;
      box-sizing: border-box;
      display: flex;
      flex-direction: column;
      justify-content: flex-start;
      height: 60vh;
      gap: 1em;
      border-radius: 5px;
      margin-right: 4em;
      div.form_text {
        display: flex;
        gap: 1em;
      }
      input,
      textarea {
        border: 0.5px solid #dedcdc;
        padding: 0.75em 6em;
        &:focus {
          outline: none;
        }
      }
      textarea {
        height: 25vh;
      }
      input[type="submit"] {
        background-color: #f4813f;
        width: 45%;
        padding: 1em 0.5em;
        margin: 2em auto;
        border-radius: 2em;
        color: white;
        font-weight: 500;
        font-size: 0.9rem;
        transition: 0.5s;
        &:hover {
          background-color: #e83e8c;
        }
      }
    }
  }
  hr {
    width: 80%;
    border-color: white;
    border-width: 0.5px;
    position: absolute;
    bottom: 10%;
  }
  p.footer {
    margin-top: 2em;
    position: absolute;
    bottom: 5%;
    color: white;
    font-weight: 200;
  }
}
</style>

<script>
export default {
  methods: {
    displayNav() {
      let aHover = document.querySelector("a.hover");
      let hiddenNav = document.querySelector("nav.pseudo");
      hiddenNav.style.display = "block";
      let list = aHover.children;
      list[0].style.display = "none";
      list[1].style.display = "inline-block";
    },
    hideNav() {
      let hiddenNav = document.querySelector("nav.pseudo");
      let aHover = document.querySelector("a.hover");
      let list = aHover.children;
      hiddenNav.style.display = "none";
      list[1].style.display = "none";
      list[0].style.display = "inline-block";
    },
    showListNav() {
      let nav = document.querySelector("div.nav nav");
      let divNav = document.querySelector("div.nav");
      let icons = document.querySelector("div.icon").children;
      let lis = document.querySelectorAll("div.nav nav a");
      let aHover = document.querySelector("a.hover");
      aHover.style.position = "relative";
      let pseudo = document.querySelector("nav.pseudo");
      pseudo.style.cssText = `
        left: 0;
        top: 100%;
      `;
      lis.forEach((e) => {
        e.style.cssText = `
          padding: 1em;
          width: 60%;
          display: flex;
          justify-content: center;
          aling-items: center;
        `;
      });
      let lisd = document.querySelectorAll(
        "div.nav nav ul li:not(:last-child)"
      );
      lisd.forEach((e) => {
        e.style.cssText = `
          width: 100%;
        `;
      });
      icons[0].style.display = "none";
      icons[1].style.display = "inline-block";
      divNav.style.position = "relative";
      nav.style.cssText = `
        position: absolute;
        width: 100%;
        top: 75%;
        left: 0;
        display: flex;
        flex-direction: column;
        align-items: center;
      `;
    },
    deleteListNav() {
      let nav = document.querySelector("div.nav nav");
      let icons = document.querySelector("div.icon").children;
      icons[1].style.display = "none";
      icons[0].style.display = "inline-block";
      nav.style.display = "none";
    },
  },
};
</script>
