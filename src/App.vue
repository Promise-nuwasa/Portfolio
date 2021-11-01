
<template>

  <header>
    
      <a href="#" class="nav__togglebtn">
        <i class="fa fa-bars"></i>
      </a>
      <ul class="nav__list">
        <li class="nav__item"><a href="#homepage" class="nav__link">HOME</a></li>
        <li class="nav__item"><a href="#about" class="nav__link">ABOUT</a></li>
        <li class="nav__item"><a href="#portfolio" class="nav__link">PROJECTS</a></li>
        <li class="nav__item"><a href="#contactme" class="nav__link">CONTACT </a></li>
      </ul>


  </header>


 
    <!--Home Page-->
    <section class="home" id="homepage">
      <div class="home__profile">
        <img class="home__img" src="./assets/slack-rb.png" alt="profilephoto">
      </div>
      <div class="home__desc">
        <h2 class="greeting"> Hello, I am</h2>
        <h1 class="home__name">Promise Nuwasasira</h1>
        <p class="home__profession">Software Developer</p>
       
      </div>
      
    </section>
    <!--About Me-->
    <section id="about" class="about">
      <div class="about__container">
        <div class="about__desc">
          <h2 class="about__title">About Me</h2>
          <p>I am  a passionate Software developer, with an innate love for writing </p>
          <p>code to solve complex issues.</p> 
          <p> I am able to translate designs and wireframes into high quality code that is
           reusable and maintainable.</p>
          <p>I also have the ability to understand business ideas and translate them into 
            technical requirements based on client needs</p>
          <p>I am adaptive and receptive to learning, fascinated by innovation and creativity. </p>
            
        </div>
        <div class="about__skills">
          <h3> Skills</h3>
          <ul class="about__list">
            <li class="about__item">HTML5</li>
            <li class="about__item"> CSS3</li>
            <li class="about__item"> SCSS</li>
            <li class="about__item"> JavaScript</li>
            <li class="about__item"> React.js</li>
            <li class="about__item"> Bootstrap</li>
            <li class="about__item"> Github</li>
            <li class="about__item"> Python</li>
            <li class="about__item"> Django</li>
            <li class="about__item"> Kotlin</li>
            <li class="about__item"> UI/UX Design</li>
            <li class="about__item"> IoT</li>
            
          </ul>
        </div>
      </div>
      <a href="PromiseCV.pdf" target="blank" class="btn">Resume</a> 
    </section>

    <section id="portfolio" class="portfolio">
      <h2>Projects</h2>
      <div class="container">
        
        <div class="card">
          <img class="card__image" src="./assets/today.png" alt="project2-img">
          <div class="card__body">
            <h3 class="card__title">Week Days App</h3>
            <p class="card__desc">Built using HTML, CSS and JavaScript</p>
            <div class="card__btn">
              <a href="https://weekdays-app.vercel.app/" target="_blank">See it live</a>
              <a href="https://github.com/Promise-nuwasa/weekdays-app" target="_blank">Code</a>
            </div>
          </div>
        </div>
        <div class="card">
          <img class="card__image" src="./assets/local-timer.png" alt="project4-img">
          <div class="card__body">
            <h3 class="card__title">Digital clock</h3>
            <p class="card__desc"> Built with javascript HTML and CSS </p>
            <div class="card__btn">
              <a href="https://local-timer.vercel.app/" target="_blank">See it live</a>
              <a href="https://github.com/Promise-nuwasa/local-timer" target="_blank"> Code</a>
            </div>
          </div>
        </div>
        <div class="card">
          <img class="card__image" src="./assets/drawing-tool.png" alt="project3-img">
          <div class="card__body">
          <h3 class="card__title">Drawing App</h3>
          <p class="card__desc">Built with HTML, CSS and JavaScript</p>
          <div class="card__btn">
          <a href="https://drawing-app-steel.vercel.app/" target="_blank">See it live</a>
          <a href="https://github.com/Promise-nuwasa/drawing-app" target="_blank"> Code</a>
          </div>
          </div>
        </div>
        <div class="card">
          <img class="card__image" src="./assets/freshop.png" alt="project4-img">
          <div class="card__body">
            <h3 class="card__title">Fruity website</h3>
            <p class="card__desc"> Built using Javascript HTML and CSS </p>
            <div class="card__btn">
              <a href="https://fruits-shoping-site.vercel.app/" target="_blank"> See it live</a>
              <a href="https://github.com/Promise-nuwasa/fruits-shoping-site" target="_blank"> Code</a>
            </div>
          </div>
        </div>
        
        <div class="card">
          <img class="card__image" src="./assets/fruity.png" alt="project4-img">
          <div class="card__body">
            <h3 class="card__title">Fresh Juice website</h3>
            <p class="card__desc">Built  with HTML and CSS</p>
            <div class="card__btn">
              <a href="https://fruity-website.vercel.app/" target="_blank">See it live</a>
              <a href="https://github.com/Promise-nuwasa/Fruity-website" target="_blank"> Code</a>
            </div>
          </div>
        </div>
        <div class="card">
          <img class="card__image" src="./assets/ss.png" alt="project4-img">
          <div class="card__body">
            <h3 class="card__title">School system</h3>
            <p class="card__desc">Built with Python/Django</p>
            <div class="card__btn">
              <a href="https://arcane-earth-16652.herokuapp.com/ " target="_blank">See it live</a>
              <a href="https://github.com/Promise-nuwasa/School-management-system" target="_blank"> Code</a>
            </div>
          </div>
        </div>
        
       
      </div>
    </section>
    <!--contact me-->

      <!-- <h2>Contact Me</h2> -->
  <footer>
      <h2 class="footer__title">Let's connect</h2>
      <div class="footer__social">
        <a href="https://www.linkedin.com/in/promise-nuwasasira-699aa4207/" target="_blank"><i class="fa fa-linkedin"></i></a>
        <a href="https://github.com/Promise-nuwasa?tab=repositories" target="_blank"> <i class="fa fa-github"></i></a>
        <a href="https://twitter.com/PNuwasasira" target="_blank"> <i class="fa fa-twitter"></i></a>
      </div>
      <p class="footer__desc">Promise Nuwasasira &#169; 2021</p>
  </footer>
</template>

<script>

export default {
  name: 'App',
  methods: {

}
}
</script>

<style>

:root {
    --primary-color:rgb(16, 32, 78);
  }
  * {
    margin: 0;
    padding: 0;
    -webkit-box-sizing: border-box;
            box-sizing: border-box;
    scroll-behavior: smooth;
  }
  

  
 /* * Media Queries: Tablet Landscape * */
@media screen and (max-width: 1060px) {
    #primary { width:67%; }
    #secondary { width:30%; margin-left:3%;}  
}


/* Media Queries: Tabled Portrait */
@media screen and (max-width:568px) {
    #primary { width:100%; }
    #secondary { width:100%; margin:0; border:none; }
}
img { max-width: 100%; height: auto; }


@media (min-device-width:600px) {
  img[data-src-600px] {
      content: attr(data-src-600px, url);
  }
}

@media (min-device-width:800px) {
  img[data-src-800px] {
      content: attr(data-src-800px, url);
  }
}
  .btn {
    margin-bottom: 0%;
    margin-top: 20px;
    background-color: DodgerBlue;
    border: none;
    color: white;
    padding: 12px 30px;
    cursor: pointer;
    font-size: 18px;
    width: 200px;
    margin-left: 530px;
    border-radius: 30px;
    margin-top: 30px;
    text-decoration: none;
    
  }
  
  /* Darker background on mouse-over */
  .btn:hover {
    background-color: RoyalBlue;
  }
  body {
    font-family: 'Kumbh Sans', sans-serif;
  }
  main {
    padding: 0;
  }
  h2 {
    text-align: center;
    color: var(--primary-color);
  }
  #header {
    position: fixed;
    z-index: 1000;
    left: 0;
    top: 0;
    width: 100vw;
    height: auto;
  }
  #header .header {
    min-height: 8vh;
    background-color: rgba(31, 30, 30, 0.24);
    transition: .3s ease background-color;
  }
  #header .nav-bar {
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 100%;
    height: 100%;
    max-width: 1300px;
    padding: 0 10px;
  }
  
  /*Navigation*/
  .nav {
    /* background-color: #1a1919; */
    height: 4rem;
    width: 100%;
  }
  .nav__togglebtn {
    color: white;
    position: relative;
    top: 0.6rem;
    left: 1rem;
    font-size: 2rem;
    width: -webkit-fit-content;
    width: -moz-fit-content;
    width: fit-content;
  }
  .nav__list {
    list-style: none;
    background-color: var(--primary-color);
    font-weight: 700;
    width: 100%;
    height: 100vh;
    display: none;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
        -ms-flex-direction: column;
            flex-direction: column;
    -webkit-box-pack: center;
        -ms-flex-pack: center;
            justify-content: center;
    -webkit-box-align: center;
        -ms-flex-align: center;
            align-items: center;
    position: absolute;
  }
  .nav__item {
    text-align: center;
    margin-bottom: 2rem;
  }
  .nav__link {
    color: white;
    text-decoration: none;
  }
  .nav__link:hover {
    color: black;
  }
  .active {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
  }

  marquee{
    background-color: var(--first-color);
    color:#fff;
    padding-top:3px;
    padding-bottom:3px;
    position:relative; 
    top:0;
    left:0;
    z-index:100;
  }
  marquee em{
    margin-right:10%;
  }
  div.maq{
    width:80%;
    margin:0 auto;
  }
  div.maq span{
    color:#fff;
    font-size: 17px;
    padding-right:10px;
    transform:translateY(10%);
  }
  /*Home Page*/
  .home {
    height: 100vh;
    display: -ms-grid;
    display: grid;
    -ms-grid-columns: 1fr;
        grid-template-columns: 1fr;
  }
  .home__profile {
    margin: 1rem 0;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-pack: center;
        -ms-flex-pack: center;
            justify-content: center;
    -webkit-box-align: center;
        -ms-flex-align: center;
            align-items: center;
            padding-top: 50px;
  }
  .home__img {
    background: var(--primary-color);
    width: -webkit-fit-content;
    width: -moz-fit-content;
    width: fit-content;
    height: auto;
    border-radius: 50%;
    background-position: center;
    background-repeat: no-repeat;
  }
  .home__desc {
    display: block;
    text-align: center;
    margin-right: 3rem;
    padding-top: 50px;
  }
  .home__name {
    margin-bottom: 0.5rem;
  }
  .home__profession {
    margin-bottom: 2rem;
    color: blue;
    font-size: xx-large;
    font-weight: bold;

  }
  .social {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    list-style: none;
    -webkit-box-pack: center;
        -ms-flex-pack: center;
            justify-content: center;
  }
  .social li {
    margin-right: 0.5rem;
  }
  .social li a {
    width: 60px;
    height: 60px;
    padding: 12px;
    border-radius: 50%;
    background-color: var(--primary-color);
    font-size: 16px;
    color: white;
    -webkit-transition: all 0.3s ease;
    transition: all 0.3s ease;
  }
  .social li a:hover {
    background-color: white;
    color: var(-primary--color);
    border: 1px solid var(--primary-color);
  }
  /*About Me*/
  .about {
    margin-bottom: 2rem;
    background-color: var(--primary-color);
    color: white;
    padding: 1rem;
  }
  .about p{
    padding: 5px 5px 5px;
  }
  .about__title {
    text-align: center;
    color: white;
    margin-bottom: 1rem;
  }
  .about__container {
    text-align: center;
    font-size: 1.2rem;
  }
  .about__skills {
    width: 100%;
    margin-top: 2rem;
    margin-left: 5rem;
  }
  .about__skills h3 {
    color: white;
    margin-bottom: 1rem;
  }
  .about__list {
    list-style: none;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -ms-flex-wrap: wrap;
        flex-wrap: wrap;
        padding-left: 30px;

  }
  .btn{
    text-align: center;
    font-size: 1.2rem;
    font-weight: bold;
  }
  button{
    margin-left: 45%;
    margin-top: 10px;
    border-radius: 20px;
    height: 50px;
    width: 150px;
    background-color: blue;
  }
  .about__item {
    margin-left: 2.2rem;
    margin-bottom: 1.2rem;
    padding: 25px 15px;
    width: -webkit-fit-content;
    width: -moz-fit-content;
    width: fit-content;    
    font-weight: 600;
  }
  
  /*Portfolio*/
  .portfolio {
    margin-bottom: 2rem;
    padding: 0 1rem;
  }
  .container {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
        -ms-flex-direction: column;
            flex-direction: column;
  }
  .card {
    width: 100%;
    height: 400px;
    border-radius: 10px;
    margin: 0 0 2rem 0;
    padding: 10px;
    -webkit-box-shadow: -10px 10px 20px rgba(0, 0, 0, 0.3);
            box-shadow: -10px 10px 20px rgba(0, 0, 0, 0.3);
  }
  .card__image {
    width: 100%;
    height: 55%;
    margin-bottom: 0.6rem;
  }
  .card__title {
    margin-bottom: 0.6rem;
  }
  .card__desc {
    margin-bottom: 2rem;
  }
  .card__btn {
    height: 50px;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-pack: center;
        -ms-flex-pack: center;
            justify-content: center;
    -webkit-box-align: center;
        -ms-flex-align: center;
            align-items: center;
  }
  .card__btn a {
    background-color: var(--primary-color);
    border: none;
    border-radius: 18px;
    padding: 10px 20px;
    color: white;
    text-decoration: none;
    -webkit-transition: all 0.3s ease;
    transition: all 0.3s ease;
  }
  .card:hover{
    background-color: rgb(243, 235, 235);
    transform: 3s;
  }
  .card__btn a:hover {
    background-color: white;
    color: var(--primary-color);
    border: 2px solid var(--primary-color);
  }
  .card__btn a:first-of-type {
    margin-right: 10px;
  }
  
  footer {
    background-color: rgb(24, 47, 110);
    color: white;
    margin-top: 1rem;
    padding: 50px 20px 20px 20px;
    text-align: center;
    width: 100%;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
        -ms-flex-direction: column;
            flex-direction: column;
    -ms-flex-pack: distribute;
        justify-content: space-around;
    -webkit-box-align: center;
        -ms-flex-align: center;
            align-items: center;
  }
  .footer__title {
    color: whitesmoke;
  }
  .footer__social {
    width: 100%;
    margin: 30px 0;
    
  }
  .footer__social a i {
    margin-right: 20px;
    font-size: 26px;
    color: white;
    -webkit-transition: all 0.3s ease;
    transition: all 0.3s ease;
  }
  .footer__social a i:hover {
    color: var(--primary-color);
  }
  .footer__social a i:nth-last-of-type(2) {
    margin-right: 0;
  }
  /* @media only screen and (min-width: 768px) { */
    main {
      padding: 0;
    }
    .nav {
      background-color: var(--primary-color);
      width: 100%;
      height: 4rem;
      position: fixed;
      top: 0;
    }
    .nav__togglebtn {
      display: none;
    }
    .nav__list {
      position: absolute;
      overflow: hidden;
      left: 0px;
      right: 0px;
      height: -webkit-fit-content;
      height: -moz-fit-content;
      height: fit-content;
      width: 100%;
      display: -webkit-box;
      display: -ms-flexbox;
      display: flex;
      -webkit-box-orient: horizontal;
      -webkit-box-direction: normal;
          -ms-flex-direction: row;
              flex-direction: row;
      -webkit-box-pack: end;
          -ms-flex-pack: end;
              justify-content: flex-end;
      -webkit-box-align: center;
          -ms-flex-align: center;
              align-items: center;
      margin-top: 1.5rem;
    }
    .nav__item {
      margin-bottom: 0;
      margin-right: 1.5rem;
    }
    /*Home page*/
    .home {
      display: -ms-grid;
      display: grid;
      -ms-grid-columns: 1fr 1fr;
          grid-template-columns: 1fr 1fr;
      -webkit-box-align: center;
          -ms-flex-align: center;
              align-items: center;
      z-index: 2;
    }
    .greeting{
      margin: 0;
      display: -webkit-box;
      display: -ms-flexbox;
      display: flex;
      margin-bottom: 1rem;
      color: black;
      font-weight:500;
      
    }
    .home__profile {
      margin: 0;
      display: -webkit-box;
      display: -ms-flexbox;
      display: flex;
      -webkit-box-pack: end;
          -ms-flex-pack: end;
              justify-content: flex-end;
    }
    .home__desc {
      text-align: left;
      margin-left: 2rem;
    }
    .home__name {
      font-size: 2rem;
      font-weight: 100;
      margin-bottom: 1rem;

    }
    .social {
      display: -webkit-box;
      display: -ms-flexbox;
      display: flex;
      -webkit-box-pack: start;
          -ms-flex-pack: start;
              justify-content: flex-start;
    }
    /*About me*/
    .about {
      padding: 3rem;
    }
    .about__container {
      display: -ms-grid;
      display: grid;
      -ms-grid-columns: 1fr 1fr;
          grid-template-columns: 1fr 1fr;
    }
    .about__desc {
      text-align: left;
    }
    .about__skills {
      margin: 0;
    }
    /*Portfolio*/
    .portfolio {
      padding: 3rem;
    }
    .portfolio h2 {
      margin-bottom: 60px;
    }
    .container {
      display: -ms-grid;
      display: grid;
      -ms-grid-columns: 1fr 1fr;
          grid-template-columns: 1fr 1fr;
      -ms-grid-rows: 1fr 1fr;
          grid-template-rows: 1fr 1fr;
      grid-gap: 2rem;
    }
    .card {
      width: 100%;
      margin: 0;
    }
    /*Contact me*/
    .contact {
      width: 500px;
    }
    .contact__title {
      margin-right: 80px;
    }

  

  @media only screen and (min-width: 1024px) {
    .container {
      display: -ms-grid;
      display: grid;
      -ms-grid-columns: 1fr 1fr 1fr;
          grid-template-columns: 1fr 1fr 1fr;
      -ms-grid-rows: 1fr;
          grid-template-rows: 1fr;
      grid-gap: 2rem;
    }
  }
</style>
