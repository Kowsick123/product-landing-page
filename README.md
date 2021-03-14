# product-landing-page
PRODUCT LANDING PAGE
<script src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js"></script>
<link
  rel="stylesheet"
  href="https://use.fontawesome.com/releases/v5.8.1/css/all.css"
  integrity="sha384-50oBUHEmvpQ+1lW4y57PTFmhCaXp0ML5d60M1M7uH2+nqUivzIebhndOJK28anvf"
  crossorigin="anonymous"
/>
<div id="page-wrapper">
  <header id="header">
    <div class="logo">
      <img
        id="header-img"
        src="https://www.google.com/search?q=watches+logo+png&rlz=1C1ONGR_enIN930IN930&sxsrf=ALeKk03OvDyKR8DkVhhWzUfS4j_dX1wLWQ:1615693633731&tbm=isch&source=iu&ictx=1&fir=ZFUR790vjCglvM%252CWv9dEhfVi1uaYM%252C_&vet=1&usg=AI4_-kQpxxRE6rJlvsywaFLPUdk373ZsJg&sa=X&ved=2ahUKEwihrero767vAhXixDgGHQpqCdAQ9QF6BAgLEAE&biw=1366&bih=625#imgrc=ZFUR790vjCglvM.png"
        alt="WATCH LOGO"
      />
    </div>

    <nav id="nav-bar">
      <ul>
        <li><a class="nav-link" href="#features">Features</a></li>
        <li><a class="nav-link" href="#how-it-works">How It Works</a></li>
        <li><a class="nav-link" href="#pricing">Pricing</a></li>
      </ul>
    </nav>
  </header>

  <div class="container"></div>

  <section id="hero">
    <h2>Handcrafted, home-made masterpieces</h2>
    <form id="form" action="https://www.freecodecamp.com/email-submit">
      <input
        name="email"
        id="email"
        type="email"
        placeholder="Enter your email address"
        required
      />
      <input id="submit" type="submit" value="Get Started" class="btn" />
    </form>
  </section>

  <div class="container">
    <section id="features">
      <div class="grid">
        <div class="icon"><i class="fa fa-3x fa-fire"></i></div>
        <div class="desc">
          <h2>Premium Materials</h2>
          <p>
            Our WATCHES are INDIAN MADE.This will increase the longevity of your purchase.
          </p>
        </div>
      </div>
      <div class="grid">
        <div class="icon"><i class="fa fa-3x fa-truck"></i></div>
        <div class="desc">
          <h2>Fast Shipping</h2>
          <p>
            We make sure you recieve your wacth as soon as we have finished. We also provide free returns if you are not satisfied.
          </p>
        </div>
      </div>
      <div class="grid">
        <div class="icon">
          <i class="fa fa-3x fa-battery-full" aria-hidden="true"></i>
        </div>
        <div class="desc">
          <h2>Quality Assurance</h2>
          <p>
            For every purchase you make, we will ensure there are no damages ,faults and we will check and test the pitch of your instrument.
          </p>
        </div>
      </div>
    </section>
    <section id="how-it-works">
      <iframe
        id="video"
        height="315"
        src="https://www.youtube.com/watch?v=dNs6zUqu3ek"
        frameborder="0"
        allowfullscreen
      ></iframe>
    </section>
    <section id="pricing">
      <div class="product" id="tenor">
        <div class="level">SMART WATCH</div>
        <h2>Rs.3500</h2>
        <ol>
          <li>.</li>
          <li>On-the-wrist health and wellness monitoring doesn’t get more thorough than this.</li>
          <li>Leave the phone at home. Your favorite music and playlists are right on your watch.</li>
          <li>Bright color display and up to 6 days of battery life? Yep — two more reasons to love this watch.</li>
        </ol>
        <button class="btn">Select</button>
      </div>
      <div class="product" id="bass">
        <div class="level">Digital watches</div>
        <h2>Rs.2999</h2>
        <ol>
          <li>Water resistance.</li>
          <li>Displays body's temperature.</li>
          <li>Long-life.</li>
          <li>Easy to wear.</li>
        </ol>
        <button class="btn">Select</button>
      </div>
      <div class="product" id="valve">
        <div class="level">Analog watches</div>
        <h2>RS.400</h2>
        <ol>
          <li>Life long</li>
          <li>Easy to wear.</li>
          <li>Cheap price.</li>
          <li>Water resistant.</li>
        </ol>
        <button class="btn">Select</button>
      </div>
    </section>
    <footer>
      <ul>
        <li><a href="#">Privacy</a></li>
        <li><a href="#">Terms</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
      <span>Copyright 2016, Original Watches</span>
    </footer>
  </div>
</div>


@import 'https://fonts.googleapis.com/css?family=Lato:400,700';

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  background-color: pink;
  font-family: 'Arial', sans-serif;
}

#page-wrapper {
  position: relative;
}

li {
  list-style: none;
}

a {
  color: #000;
  text-decoration: none;
}

/** global classes styling **/

.container {
  max-width: 1000px;
  width: 100%;
  margin: 0 auto;
}

.btn {
  padding: 0 20px;
  height: 40px;
  font-size: 1em;
  font-weight: 900;
  text-transform: uppercase;
  border: 3px black solid;
  border-radius: 2px;
  background: transparent;
  cursor: pointer;
}

.grid {
  display: flex;
}

header {
  position: fixed;
  top: 0;
  min-height: 75px;
  padding: 0px 20px;
  display: flex;
  justify-content: space-around;
  align-items: center;
  background-color: #eee;
}

@media (max-width: 600px) {
  header {
    flex-wrap: wrap;
  }
}

.logo {
  width: 60vw;
}

@media (max-width: 650px) {
  .logo {
    margin-top: 15px;
    width: 100%;
    position: relative;
  }
}

.logo > img {
  width: 100%;
  height: 100%;
  max-width: 300px;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  margin-left: 20px;
}

@media (max-width: 650px) {
  .logo > img {
    margin: 0 auto;
  }
}

nav {
  font-weight: 400;
}

@media (max-width: 650px) {
  nav {
    margin-top: 10px;
    width: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    padding: 0 50px;
  }
  nav li {
    padding-bottom: 5px;
  }
}

nav > ul {
  width: 35vw;
  display: flex;
  flex-direction: row;
  justify-content: space-around;
}

@media (max-width: 650px) {
  nav > ul {
    flex-direction: column;
  }
}

#hero {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-align: center;
  height: 200px;
  margin-top: 50px;
}

#hero > h2 {
  margin-bottom: 20px;
  word-wrap: break-word;
}

#hero input[type='email'] {
  max-width: 275px;
  width: 100%;
  padding: 5px;
}

#hero input[type='submit'] {
  max-width: 150px;
  width: 100%;
  height: 30px;
  margin: 15px 0;
  border: 0;
  background-color: #f1c40f;
}

#hero input[type='submit']:hover {
  background-color: orange;
  transition: background-color 1s;
}

@media (max-width: 650px) {
  #hero {
    margin-top: 120px;
  }
}

#features {
  margin-top: 30px;
}

#features .icon {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 125px;
  width: 20vw;
  color: darkorange;
}

@media (max-width: 550px) {
  #features .icon {
    display: none;
  }
}

#features .desc {
  display: flex;
  flex-direction: column;
  justify-content: center;
  height: 125px;
  width: 80vw;
  padding: 5px;
}

@media (max-width: 550px) {
  #features .desc {
    width: 100%;
    text-align: center;
    padding: 0;
    height: 150px;
  }
}

@media (max-width: 650px) {
  #features {
    margin-top: 0;
  }
}

#how-it-works {
  margin-top: 50px;
  display: flex;
  justify-content: center;
}

#how-it-works > iframe {
  max-width: 560px;
  width: 100%;
}

#pricing {
  margin-top: 60px;
  display: flex;
  flex-direction: row;
  justify-content: center;
}

.product {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  width: calc(100% / 3);
  margin: 10px;
  border: 1px solid #000;
  border-radius: 3px;
}

.product > .level {
  background-color: #ddd;
  color: black;
  padding: 15px 0;
  width: 100%;
  text-transform: uppercase;
  font-weight: 700;
}

.product > h2 {
  margin-top: 15px;
}

.product > ol {
  margin: 15px 0;
}

.product > ol > li {
  padding: 5px 0;
}

.product > button {
  border: 0;
  margin: 15px 0;
  background-color: #f1c40f;
  font-weight: 400;
}

.product > button:hover {
  background-color: red;
  transition: background-color 3s;
}

@media (max-width: 800px) {
  #pricing {
    flex-direction: column;
  }
  .product {
    max-width: 200px;
    width: 100%;
    margin: 0 auto;
    margin-bottom: 10px;
  }
}

footer {
  margin-top: 30px;
  background-color: #ddd;
  padding: 20px;
}

footer > ul {
  display: flex;
  justify-content: flex-end;
}

footer > ul > li {
  padding: 0 10px;
}

footer > span {
  margin-top: 15px;
  display: flex;
  justify-content: flex-end;
  font-size: 1.9em;
  color: green;
}
