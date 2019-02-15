---
layout: default
title: Cécile Dezy | Front-end Developper
---

<!-- ---- ABOUT SECTION ---- -->
<div class="section ass" id="about">
  <div class="title text-center ">
    <div class="title-about">
      <h1>ABOUT</h1>
    </div>
    <div class="menu-section">
      <h4><a href="#about" class="smoothScroll">About</a></h4>
      <h4>.</h4>
      <h4><a href="#work" class="smoothScroll">Work</a></h4>
      <h4>.</h4>
      <h4><a href="#skills" class="smoothScroll">Skills</a></h4>
      <h4>.</h4>
      <h4><a href="#contact" class="smoothScroll">Contact</a></h4>
    </div>
  </div>
  <div class="content text-center">
    <img src="{{ site.baseurl }}/assets/images/profile.png" alt="profile pic" id="profile-pic">
    <div class="text-about">
      <p><strong>I am a Front-end Developer living in Paris.</strong></p>
      <p>After studying import/export and realise I needed a job with more purpose, so I did a Master in International Cooperation to work in NGOs. I joined Handicap International for an internship in communication and then Oxfam France, for 5 years in digital communication and customer success for their events.</p>
      <p>It was then that I decided to dig the digital side and learn to code with le Wagon Paris (batch#200).</p>
      <p>The code is creative, it's concrete! I love making stuff: sewing clothes, making my own cosmetics, embroidering ... I even start learning to tattoo! :)</p>
      <p>I'm impressed by everything I can do w/ back-end, but I have a strong sensitivity for front-end development.</p>
      <p>I'm currently working as a Teaching Assistant at Le Wagon in Paris and looking for a job.</p>
    </div>
  </div>
</div>

<!-- ---- WORK SECTION ---- -->

<div class="container section wcs" id="work">
  <div class="title text-center wcs" id="work-menu">
    <div class="work">
      <div class="w">
        <h1>W</h1>
      </div>
      <div class="ork">
        <h1>ORK</h1>
      </div>
    </div>
    <div class="menu-section work-menu-section">
        <h4><a href="#about" class="smoothScroll">About</a></h4>
        <h4>.</h4>
        <h4><a href="#work" class="smoothScroll">Work</a></h4>
        <h4>.</h4>
        <h4><a href="#skills" class="smoothScroll">Skills</a></h4>
        <h4>.</h4>
        <h4><a href="#contact" class="smoothScroll">Contact</a></h4>
    </div>
  </div>
  <div class="content text-center work-content" id="work-content">
    <div class="entry mtm">
      <div class="entry-title">
        <h1>Mind the Map</h1>
      </div>
      <div class="details">
        <!-- si on veut mettre le logo de MtM -->
        <!-- <a href="http://www.mindthemapgame.com/" target="_blank" class="pic-mtm"><img src="{{ site.baseurl }}/assets/images/logo-mtm.svg" alt="mind the map"></a> -->
        <div class="details-text">
          <p>
            You just arrived in Paris, you have heard about all the great monuments and sightseeing but can place them on a map?
            Discover your city and have fun playing <a href="http://www.mindthemapgame.com/" target="_blank">Mind the Map</a>!<br>
            The game if simple : be the quickest and nearest to pin a given location on the map to be on the top of the leaderboard!
          </p>
          <hr>
          <div class="details-technos">
            <p><strong>Technology</strong> - Ruby on Rails, Git, Cloudinary, PostegreSQL, Heroku</p>
            <p><strong>Practices</strong> - Continuous Delivery</p>
          </div>
          <ul class="technos">
            <li><i class="fas fa-check"></i>Ruby on Rails backend</li>
            <li><i class="fas fa-check"></i>Authentication via Devise</li>
            <li><i class="fas fa-check"></i>Geocoding via Google API</li>
            <li><i class="fas fa-check"></i>Image upload via Cloudinary</li>
            <li><i class="fas fa-check"></i>Solo and Duo play modes</li>
            <li><i class="fas fa-check"></i>Dynamic loading with Ajax</li>
          </ul>
        </div>
        <div class="details-img">
          <a href="http://www.mindthemapgame.com/" target="_blank"><img src="{{ site.baseurl }}/assets/images/mu-mtm.png" alt="mind the map" style="width: 100%;"></a>
          <div class="details-btn">
            <div class="btn-mtm">
              <a href="https://youtu.be/ICliaJ8Krpg?t=2208" target="_blank">See demo</a>
            </div>
            <div class="btn-mtm">
              <a href="http://www.mindthemapgame.com/" target="_blank">See website</a>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="entry ram">
      <div class="entry-title">
        <h1>Rent a mobile</h1>
      </div>
      <div class="details">
        <div class="details-text">
          <p>You think buying a new mobile every year is a waste of money? You only need a phone for a few days? You have unused phones in you drawer? If you said yes to one of these questions, welcome to <a href="http://rent-a-mobile.herokuapp.com/" target="_blank">Rent a Mobile</a>, where you can find phones to rent!</p>
          <hr>
          <div class="details-technos">
            <p><strong>Technology</strong> - Ruby on Rails, Git, Cloudinary, PostegreSQL, Heroku</p>
            <p><strong>Practices</strong> - Continuous Delivery</p>
          </div>
          <ul class="technos">
            <li><i class="fas fa-check"></i>Ruby on Rails backend</li>
            <li><i class="fas fa-check"></i>Authentication via Devise</li>
            <li><i class="fas fa-check"></i>Geocoding via Google API</li>
            <li><i class="fas fa-check"></i>Image upload via Cloudinary</li>
            <li><i class="fas fa-check"></i>Reviews & rating feature</li>
            <li><i class="fas fa-check"></i>Datepicker feature</li>
            <li><i class="fas fa-check"></i>Search via pg_search</li>
            <li><i class="fas fa-check"></i>Bootstrap CSS frontend</li>
          </ul>
        </div>
        <div class="details-img">
          <a href="http://rent-a-mobile.herokuapp.com/" target="_blank"><img src="{{ site.baseurl }}/assets/images/mu-ram.png" alt="rent a mobile" style="width: 100%;"></a>
          <div class="details-btn">
            <div class="btn-ram">
              <a href="http://rent-a-mobile.herokuapp.com/" target="_blank">See website</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- ---- SKILLS SECTION ---- -->
<div class="section ass" id="skills">
  <div class="title text-center ass">
    <h1>SKILLS</h1>
    <div class="menu-section">
      <h4><a href="#about" class="smoothScroll">About</a></h4>
      <h4>.</h4>
      <h4><a href="#work" class="smoothScroll">Work</a></h4>
      <h4>.</h4>
      <h4><a href="#skills" class="smoothScroll">Skills</a></h4>
      <h4>.</h4>
      <h4><a href="#contact" class="smoothScroll">Contact</a></h4>
    </div>
  </div>

  <div class="content text-center">
    <div class="menu-skills">
      <div class="front-end">
        <h2>Front-end</h2>
        <div class="rows">
          <div class="skill">
            <img src="{{ site.baseurl }}/assets/images/html5.png" alt="HTML5">
            <p>HTML5</p>
          </div>
          <div class="skill">
            <img src="{{ site.baseurl }}/assets/images/css3.png" alt="CSS3">
            <p>CSS3 / SASS</p>
          </div>
          <div class="skill">
            <img src="{{ site.baseurl }}/assets/images/js.png" alt="JS">
            <p>Javascript / ES6</p>
          </div>
          <div class="skill">
            <img src="{{ site.baseurl }}/assets/images/bootstrap.png" alt="Bootstrap">
            <p>Bootstrap</p>
          </div>
        </div>
      </div>
      <div class="back-end">
        <h2>Back-end</h2>
        <div class="rows">
          <div class="skill">
            <img src="{{ site.baseurl }}/assets/images/ruby.png" alt="Ruby" id="r">
            <p>Ruby</p>
          </div>
          <div class="skill">
            <img src="{{ site.baseurl }}/assets/images/ror.png" alt="Rails">
            <p>Rails</p>
          </div>
          <div class="skill">
            <img src="{{ site.baseurl }}/assets/images/jekyll.png" alt="Jekyll">
            <p>Jekyll</p>
          </div>
        </div>
      </div>
      <div class="devops">
        <h2>Devops</h2>
        <div class="rows">
          <div class="skill">
            <img src="{{ site.baseurl }}/assets/images/heroku.png" alt="Heroku">
            <p>Heroku</p>
          </div>
          <div class="skill">
            <img src="{{ site.baseurl }}/assets/images/github.svg" alt="Github" id="g">
            <p>Github</p>
          </div>
          <div class="skill">
            <img src="{{ site.baseurl }}/assets/images/git.png" alt="Git" id="g">
            <p>Git</p>
          </div>
          <div class="skill">
            <img src="{{ site.baseurl }}/assets/images/postgresql.png" alt="PostGreSQL">
            <p>PostGreSQL</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- ---- CONTACT SECTION ---- -->
<div class="section wcs" id="contact">
  <div class="title text-center">
    <h1>CONTACT</h1>
    <div class="menu-section">
      <h4><a href="#about" class="smoothScroll">About</a></h4>
      <h4>.</h4>
      <h4><a href="#work" class="smoothScroll">Work</a></h4>
      <h4>.</h4>
      <h4><a href="#skills" class="smoothScroll">Skills</a></h4>
      <h4>.</h4>
      <h4><a href="#contact" class="smoothScroll">Contact</a></h4>
    </div>
  </div>

  <div class="content content-contact text-center">
    <div class="contact-text">
      <p>If you want to collaborate on crafting amazing experience for people – you are very welcome to contact me.</p>
      <p><strong>I am available for freelance projects and full-time employment.</strong></p>
    </div>
    <div class="contact-info">
      <h5>Cécile Dezy</h5>
      <p>Junior Fullstack Developer</p>
      <p><a href="mailto:cecile.dezy@gmail.com" id="email">cecile.dezy@gmail.com</a></p>
      <p>+33 (0)6 77 13 65 54</p>
    </div>
    <div class="socials">
      <a href="https://www.linkedin.com/in/c%C3%A9cile-dezy-193b8226/" target="_blank"><i class="fab fa-linkedin-in icon"></i></a>
      <a href="https://github.com/cecile-dzy-ncl" target="_blank"><i class="fab fa-github icon"></i></a>
      <a href="https://twitter.com/Cecile_Dzy_Ncl" target="_blank"><i class="fab fa-twitter icon"></i></a>
    </div>
  </div>
</div>

<script>

  function clearSections(){
    document.querySelectorAll(".selected").forEach((item)=>{
      item.classList.remove("selected");
    });
  }

  function reset(){
    clearSections();
    const container = document.querySelector(".container");
    const work = document.querySelector(".work");
    const menu = document.querySelector(".work-menu-section");
    const w = document.querySelector(".w");
    const ork = document.querySelector(".ork");

    container.classList.remove("open");
    w.classList.remove("change");
    ork.classList.remove("disappear");
    work.classList.remove("change");
    menu.classList.remove("disappear");
  }


  function selectEntry(event){
    const t = event.target.closest(".entry");
    const container = document.querySelector(".container");
    const w = document.querySelector(".w");
    const ork = document.querySelector(".ork");
    const work = document.querySelector(".work");
    const menu = document.querySelector(".work-menu-section");
    // const w = document.querySelector("#work-menu h1").innerText.charAt(0);


    if(t.classList.contains("selected")){
      clearSections();
      container.classList.remove("open");
      w.classList.remove("change");
      ork.classList.remove("disappear");
      work.classList.remove("change");
      menu.classList.remove("disappear");
    }else{
      clearSections();
      container.classList.add("open");
      t.classList.add("selected");
      work.classList.add("change");
      w.classList.add("change");
      ork.classList.add("disappear");
      menu.classList.add("disappear");
    }
  }


  function init(){
    document.querySelector("#work-content").addEventListener('click' ,selectEntry);
    document.querySelector("#work-menu").addEventListener('click', reset);
  }


  document.addEventListener("DOMContentLoaded", init);
</script>

