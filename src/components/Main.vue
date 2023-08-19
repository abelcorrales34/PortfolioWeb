<script></script>

<template>
  <div class="wrapper">
    <div class="menu">
      <div class="option">
            <img src="/imgs/logoblack.png" alt="" />
      </div>
      <div class="option">
        <a href="#">Home</a>
      </div>
      <div class="option">
        <a href="#about-me">About Me</a>
      </div>
      <div class="option">
        <a href="#experience">Experience</a>
      </div>
      <div class="option">
        <a href="#knowledge">Knowledge</a>
      </div>
      <div class="option">
        <a href="#contact">Contact</a>
      </div>
      <div class="option">
        <a href="https://www.linkedin.com/in/abel-corrales-vargas/">LinkedIn</a>
      </div>
    </div>
    <div class="main">
      <div class="presentation">
        <h1>Hi, I'm Abel Corrales Vargas</h1>
        <h3>Full-Stack and RPA Developer</h3>
        <p>
          I am an independent software developer focused on Full-Stack <br />
          development and automation solutions to your problems.
        </p>
        <a href="#contact">Get in contact.</a>
      </div>
      <div id="about-me" class="about-me">
        <h2>
          As a software engineer, I prioritize building functional and scalable
          applications, and I recognize the importance of teamwork. My
          experiences have taught me the importance of effective communication,
          cooperation, and leveraging team strengths to deliver quality
          solutions. Valuing the diversities and needs of clients, I have
          learned valuable lessons that contribute to my growth as a developer
          and as a person.
        </h2> <a href="https://drive.google.com/file/d/1LxExGzY6L_WBLtq_UDFDPIwfkWXr4OGL/view?usp=sharing">CV</a>
    
      </div>
      <div id="experience" class="experience">
        <h1>Experience</h1>
        <section class="cards">
          <article class="card card--1">
            <div class="card__info-hover"></div>
            <div class="card__img"></div>
            <a href="#" class="card_link">
              <div class="card__img--hover"></div>
            </a>
            <div class="card__info">
              <span class="card__category">Work</span>
              <h3 class="card__title">IBM - Developer Intern</h3>
              <a>Vue, Node, RPA, SQL, IBM Cloud and Sails</a>
              <br>
              <span class="card__by"
                >Date
                <a href="#" class="card__author" title="author"
                  >May - 2022 to may - 2023</a
                ></span
              >
            </div>
          </article>
          <article class="card card--2">
            <div class="card__info-hover"></div>
            <div class="card__img"></div>
            <a href="#" class="card_link">
              <div class="card__img--hover"></div>
            </a>
            <div class="card__info">
              <span class="card__category"> Project</span>
              <h3 class="card__title">Dungeons And Dragons - Developer </h3>
              <a>Java and SQL</a>
              <br>
              <span class="card__by"
                >Date
                <a href="#" class="card__author" title="author"
                  >June - 2022 to December - 2022</a
                ></span
              >
            </div>
          </article>
          <article class="card card--3">
            <div class="card__info-hover"></div>
            <div class="card__img"></div>
            <a href="#" class="card_link">
              <div class="card__img--hover"></div>
            </a>
            <div class="card__info">
              <span class="card__category"> Project </span>
              <h3 class="card__title">LabStore Costa Rica - Rep Manager</h3>
              <a>.NET, BootStrap, SQL, Azure</a>
              <br>
              <span class="card__by"
                >Date
                <a href="#" class="card__author" title="author"
                  >June - 2022 to December -2022</a
                ></span
              >
            </div>
          </article>
          <article class="card card--4">
            <div class="card__info-hover"></div>
            <div class="card__img"></div>
            <a href="#" class="card_link">
              <div class="card__img--hover"></div>
            </a>
            <div class="card__info">
              <span class="card__category">Work</span>
              <h3 class="card__title">Cenfotec - Representant</h3>
              <br>
              <span class="card__by"
                >Date
                <a href="#" class="card__author" title="author"
                  >Aug - 2022 to Aug - 2023</a
                ></span
              >
            </div>
          </article>
        </section>
      </div>
      <div id="knowledge" class="knowledge">
        <h1>Knowledge</h1>
        <img src="../../public/imgs/habilidades.gif" alt="" />
      </div>
      <section id="contact" class="contact">
        <h1>Lets get in contact</h1>

        <div class="contact-wrapper">
          <!-- Left contact page -->

          <form id="contact-form" class="form-horizontal" role="form">
            <div class="form-group">
              <div class="col-sm-12">
                <input
                  type="text"
                  class="form-control"
                  id="name"
                  placeholder="NAME"
                  name="name"
                  value=""
                  required
                />
              </div>
            </div>

            <div class="form-group">
              <div class="col-sm-12">
                <input
                  type="email"
                  class="form-control"
                  id="email"
                  placeholder="EMAIL"
                  name="email"
                  value=""
                  required
                />
              </div>
            </div>

            <textarea
              class="form-control"
              rows="10"
              placeholder="MESSAGE"
              name="message"
              required
            ></textarea>

            <button
              class="btn btn-primary send-button"
              id="submit"
              type="submit"
              value="SEND"
            >
              <div class="alt-send-button">
                <i class="fa fa-paper-plane"></i
                ><span class="send-text">SEND</span>
              </div>
            </button>
          </form>
        </div>
      </section>

    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {};
  },
  mounted() {},
  methods: {},
};
</script>
<style scoped>
@import url("https://fonts.googleapis.com/css?family=Roboto+Slab:100,300,400,700");
@import url("https://fonts.googleapis.com/css?family=Raleway:300,300i,400,400i,500,500i,600,600i,700,700i,800,800i,900,900i");

#contact {
  width: 100%;
  height: 100%;
}

.section-header {
  text-align: center;
  margin: 0 auto;
  padding: 40px 0;
  font: 300 60px 'Oswald', sans-serif;
  color: black;
  text-transform: uppercase;
  letter-spacing: 6px;
}

.contact-wrapper {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  margin: 0 auto;
  padding: 20px;
  position: relative;
  max-width: 840px;
}

/* Left contact page */
.form-horizontal {
  /*float: left;*/
  max-width: 400px;
  font-family: 'Lato';
  font-weight: 400;
}

.form-control, 
textarea {
  max-width: 150px;
  background-color: #000;
  color: #fff;
  letter-spacing: 1px;
}

.send-button {
  margin-top: 15px;
  height: 34px;
  width: 255px;
  overflow: hidden;
  transition: all .2s ease-in-out;
}

.alt-send-button {
  width: 400px;
  height: 34px;
  transition: all .2s ease-in-out;
}

.send-text {
  display: block;
  margin-top: 10px;
  font: 700 12px 'Lato', sans-serif;
  letter-spacing: 2px;
}

.alt-send-button:hover {
  transform: translate3d(0px, -29px, 0px);
}

/* Begin Right Contact Page */
.direct-contact-container {
  max-width: 400px;
}

/* Location, Phone, Email Section */
.contact-list {
  list-style-type: none;
  margin-left: -30px;
  padding-right: 20px;
}

.list-item {
  line-height: 4;
  color: #aaa;
}

.contact-text {
  font: 300 18px 'Lato', sans-serif;
  letter-spacing: 1.9px;
  color: #bbb;
}

.place {
  margin-left: 62px;
}

.phone {
  margin-left: 56px;
}

.gmail {
  margin-left: 53px;
}

.contact-text a {
  color: #bbb;
  text-decoration: none;
  transition-duration: 0.2s;
}

.contact-text a:hover {
  color: #fff;
  text-decoration: none;
}


/* Social Media Icons */
.social-media-list {
  position: relative;
  font-size: 22px;
  text-align: center;
  width: 100%;
  margin: 0 auto;
  padding: 0;
}

.social-media-list li a {
  color: #fff;
}

.social-media-list li {
  position: relative; 
  display: inline-block;
  height: 60px;
  width: 60px;
  margin: 10px 3px;
  line-height: 60px;
  border-radius: 50%;
  color: #fff;
  background-color: rgb(27,27,27);
  cursor: pointer; 
  transition: all .2s ease-in-out;
}

.social-media-list li:after {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 60px;
  height: 60px;
  line-height: 60px;
  border-radius: 50%;
  opacity: 0;
  box-shadow: 0 0 0 1px #fff;
  transition: all .2s ease-in-out;
}

.social-media-list li:hover {
  background-color: #fff; 
}

.social-media-list li:hover:after {
  opacity: 1;  
  transform: scale(1.12);
  transition-timing-function: cubic-bezier(0.37,0.74,0.15,1.65);
}

.social-media-list li:hover a {
  color: #000;
}

.copyright {
  font: 200 14px 'Oswald', sans-serif;
  color: #555;
  letter-spacing: 1px;
  text-align: center;
}

hr {
  border-color: rgba(255,255,255,.6);
}

/* Begin Media Queries*/
@media screen and (max-width: 850px) {
  .contact-wrapper {
    display: flex;
    flex-direction: column;
  }
  .direct-contact-container, .form-horizontal {
    margin: 0 auto;
  }  
  
  .direct-contact-container {
    margin-top: 60px;
    max-width: 300px;
  }    
  .social-media-list li {
    height: 60px;
    width: 60px;
    line-height: 60px;
  }
  .social-media-list li:after {
    width: 60px;
    height: 60px;
    line-height: 60px;
  }
}

@media screen and (max-width: 569px) {

  .direct-contact-container, .form-wrapper {
    float: none;
    margin: 0 auto;
  }  
  .form-control, textarea {
    
    margin: 0 auto;
  }
 
  
  .name, .email, textarea {
    width: 280px;
  } 
  
  .direct-contact-container {
    margin-top: 60px;
    max-width: 280px;
  }  
  .social-media-list {
    left: 0;
  }
  .social-media-list li {
    height: 55px;
    width: 55px;
    line-height: 55px;
    font-size: 2rem;
  }
  .social-media-list li:after {
    width: 55px;
    height: 55px;
    line-height: 55px;
  }
  
}

@media screen and (max-width: 410px) {
  .send-button {
    width: 99%;
  }
}
/**********************************************/ 
* {
  box-sizing: border-box;
}

body,
html {
  font-family: "Roboto Slab", serif;
  margin: 0;
  width: 100%;
  height: 100%;
  padding: 0;
}

body {
  background-color: #d2dbdd;
  display: flex;
  display: -webkit-flex;
  -webkit-justify-content: center;
  -webkit-align-items: center;
  justify-content: center;
  align-items: center;
}
.experience {
  width: 100%;
  text-align: end;
}

.contact h1{
  font-size: 90px;
  padding: 20px;
  padding-right: 120px;
}
.experience h1 {
  font-size: 90px;
  padding: 20px;
  padding-right: 120px;
}

.knowledge h1 {
  font-size: 90px;
  padding: 20px;
  padding-right: 120px;
}
.knowledge img {
  width: 80%;
}

.cards {
  width: 100%;
  padding: 10px 100px 10px 100px;
  display: flex;
  display: -webkit-flex;
  justify-content: center;
  -webkit-justify-content: center;
}

.card--1 .card__img,
.card--1 .card__img--hover {
  background-image: url("https://images.squarespace-cdn.com/content/v1/5d0b55e167bac40001fd7e65/1571409687376-XNIP8QG1ISWJNDJD7UMP/ibm1.gif");
}

.card--2 .card__img,
.card--2 .card__img--hover {
  background-image: url("https://mir-s3-cdn-cf.behance.net/project_modules/hd/c21e8a124315651.61016b92cde1e.gif");
}
.card--3 .card__img--hover {
  background-image: url("https://laboratoriomartinez.com/wp-content/uploads/2018/11/laboratorio-clinico-en-santa-marta.jpg");
}

.card--4 .card__img--hover {
  background-image: url("https://www.larepublica.net/storage/images/2022/05/04/20220504154150.024.jpg");
}

.card__like {
  width: 18px;
}

.card__clock {
  width: 15px;
  vertical-align: middle;
  fill: #ad7d52;
}
.card__time {
  font-size: 12px;
  color: #ad7d52;
  vertical-align: middle;
  margin-left: 5px;
}

.card__clock-info {
  float: right;
}

.card__img {
  visibility: hidden;
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  width: 100%;
  height: 235px;
  border-top-left-radius: 12px;
  border-top-right-radius: 12px;
}

.card__info-hover {
  position: absolute;
  padding: 16px;
  width: 100%;
  opacity: 0;
  top: 0;
}

.card__img--hover {
  transition: 0.2s all ease-out;
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  width: 100%;
  position: absolute;
  height: 235px;
  border-top-left-radius: 12px;
  border-top-right-radius: 12px;
  top: 0;
}
.card {
  margin-right: 25px;
  transition: all 0.4s cubic-bezier(0.175, 0.885, 0, 1);
  background-color: #fff;
  width: 33.3%;
  position: relative;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0px 13px 10px -7px rgba(0, 0, 0, 0.1);
}
.card:hover {
  box-shadow: 0px 30px 18px -8px rgba(0, 0, 0, 0.1);
  transform: scale(1.1, 1.1);
}

.card__info {
  z-index: 2;
  background-color: #fff;
  border-bottom-left-radius: 12px;
  border-bottom-right-radius: 12px;
  padding: 16px 24px 24px 24px;
}

.card__category {
  font-family: "Raleway", sans-serif;
  text-transform: uppercase;
  font-size: 13px;
  letter-spacing: 2px;
  font-weight: 500;
  color: #868686;
}

.card__title {
  margin-top: 5px;
  margin-bottom: 10px;
  font-family: "Roboto Slab", serif;
}

.card__by {
  font-size: 12px;
  font-family: "Raleway", sans-serif;
  font-weight: 500;
}

.card__author {
  font-weight: 600;
  text-decoration: none;
  color: #ad7d52;
}

.card:hover .card__img--hover {
  height: 100%;
  opacity: 0.3;
}

.card:hover .card__info {
  background-color: transparent;
  position: relative;
}

.card:hover .card__info-hover {
  opacity: 1;
}

/**********************************/
.card:hover .character {
  opacity: 1;
  transform: translate3d(0%, -30%, 100px);
}

html {
  scroll-behavior: smooth;
}

.about-me {
  width: 100%;
  padding: 400px 170px 100px 170px;
}

* {
  scroll-behavior: smooth;
  box-sizing: border-box;
  font-family: "Open Sans", sans-serif;
  /* border: dotted 1px black;*/
}
.presentation img {
  position: fixed;
  bottom: 0;
  padding-left: 200px;
  width: 500px;
}

.presentation a {
  color: black;
}
.presentation p {
  padding-bottom: 0px;
}

.presentation h1 {
  padding-top: 37vh;
  font-size: 80px;
  margin: 5px;
}

.menu {
  opacity: 1;
  position: fixed;
  align-items: center;
  justify-items: center;
  align-items: first baseline;
  width: 15%;
  height: 100vh;
  animation-delay: 3s;
  transition: opacity 2s;
}

.menu img {
  width: 120px;
  padding-top: 40px;
}

.menu .option {
  text-align: center;
  justify-items: center;
  height: 16.6%;
}

.menu a {
  color: black;
  text-decoration: none;
  font-size: large;
  height: 100%;
  writing-mode: vertical-lr;
  transform: rotate(180deg);
  transition-duration: 0.2s;
  border-left: solid 2px white;
}

.menu a:hover {
  padding-left: 10px;
  border-left: solid 2px purple;
  transition-duration: 0.2s;
}

.main {
  width: 100%;
  height: 100vh;
  padding-left: 15%;
  background-image: url("/svgs/layered-steps-haikei.svg");
  background-size: cover;
}

p {
  font-family: "Open Sans", sans-serif;
  font-size: xx-large;
}
.center-text {
  text-align: center;
}

.wrapper {
  display: flex;
  flex-wrap: wrap;
}
</style>
