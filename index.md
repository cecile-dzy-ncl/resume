---
layout: default
title: Cécile Dezy | Junior Fullstack Developer
---

<!-- ---- ABOUT SECTION ---- -->
<div class="section" id="about">
  <div class="title text-center">
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
  <div class="profile">
  </div>
  <div class="content text-center">
    <img src="{{ site.baseurl }}/assets/images/profile.png" alt="profile pic" id="profile-pic">
    <div class="text-about">
      <p><strong>I am a Fullstack Web Developer living in Paris.</strong></p>
      <p>After studying import/export and realise I needed a job with more purpose, so I did a Master in International Cooperation to work in NGOs. I joined Handicap International for an internship in communication and then Oxfam France, for 5 years in digital communication and customer success for their events.</p>
      <p>It was then that I decided to dig the digital side and learn to code with le Wagon Paris (batch#200).</p>
      <p>The code is creative, it's concrete! I love making stuff: sewing clothes, making my own cosmetics, embroidering ... I even start learning to tattoo! :)</p>
      <p>I'm impressed by everything I can do w/ back-end, but I have a strong sensitivity for front-end development.</p>
      <p>I'm currently working as a Teaching Assistant at Le Wagon in Paris and looking for a job.</p>
    </div>
  </div>
</div>

<!-- ---- WORK SECTION ---- -->
<div class="section" id="work">
  <div class="title text-center">
    <h1>WORK</h1>
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
  <div class="content text-center" id="work-content" onclick="incWidth()">
    <main class="cd-main">
    <ul class="cd-gallery">
      <li class="cd-item mtm">
        <a href="item-1.html">
          <div>
            <h2>Mind the Map</h2>
            <b>View More</b>
          </div>
        </a>
      </li>
      <li class="cd-item ram">
        <a href="item-2.html">
          <div>
            <h2>Rent a mobile</h2>
            <b>View More</b>
          </div>
        </a>
      </li>
    </ul>
    </main>
    <div class="cd-folding-panel">
      <div class="fold-left">
      </div> <!-- this is the left fold -->
      <div class="fold-right">
      </div> <!-- this is the right fold -->
      <div class="cd-fold-content mtm">
         <!-- content will be loaded using javascript -->
        <h2>Mind the Map</h2>
        <img src="{{ site.baseurl }}/assets/images/mu-mtm.png" alt="mind the map">
        <p>Mind the Map is a geographic game, for every people who want to know better their city.</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consectetur autem quidem ipsa, eveniet unde distinctio! Fuga sunt iste, natus doloremque temporibus sed porro dolorem, est quidem amet consequuntur quae maiores.
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Deserunt architecto, doloribus eaque et nostrum, quos a velit. Adipisci porro rerum aspernatur, doloribus temporibus at. Aperiam nemo, perferendis tempore est recusandae.
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Error minus assumenda modi, harum repellat! Alias pariatur inventore ut ex, tempore voluptatum. Deleniti, ipsum, error. Placeat eveniet ipsam, dolor fugiat possimus.
        </p>
      </div>
    </div>
  </div>
</div>

<!-- ---- SKILLS SECTION ---- -->
<div class="section" id="skills">
  <div class="title text-center">
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
<div class="section" id="contact">
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
      <p><a href="mailto:cecile.dezy@gmail.com">cecile.dezy@gmail.com</a></p>
      <p>+33 (0)6 77 13 65 54</p>
    </div>
    <div class="socials">
      <a href="https://www.linkedin.com/in/c%C3%A9cile-dezy-193b8226/" target="_blank"><i class="fab fa-linkedin-in icon"></i></a>
      <a href="https://github.com/cecile-dzy-ncl" target="_blank"><i class="fab fa-github icon"></i></a>
      <a href="https://twitter.com/Cecile_Dzy_Ncl" target="_blank"><i class="fab fa-twitter icon"></i></a>
    </div>
  </div>
</div>

<script type="text/javascript">
  const incWidth = () => {
    const work = document.getElementById("work-content");
    work.addEventListener("click", (event) => {
      work.style.width = 100 + '%';
    });
  }
</script>

<script type="text/javascript">
  /* open folding content */
  $('.cd-gallery a').on('click', function(event){
     event.preventDefault();
     openItemInfo($(this).attr('href'));
  });
  function openItemInfo(url) {
     /* check if mobile or desktop */
     var mq = viewportSize();
     if( $('.cd-gallery').offset().top > $(window).scrollTop() && mq != 'mobile') {
        /* if content is visible above the .cd-gallery - scroll before opening the folding panel */
        $('body,html').animate({
           'scrollTop': $('.cd-gallery').offset().top
        }, 100, function(){
           toggleContent(url, true);
        });

     } else {
        toggleContent(url, true);
     }
  }

  function toggleContent(url, bool) {
     if( bool ) {
        /* load and show new content */
        $('.cd-fold-content').load(url+' .cd-fold-content > *', function(event){
           $('body').addClass('overflow-hidden');
           $('.cd-folding-panel').addClass('is-open');
           $('.cd-main').addClass('fold-is-open');
        });
     } else {
        /* close the folding panel */
        $('.cd-folding-panel').removeClass('is-open')
        $('.cd-main').removeClass('fold-is-open');
        /* ...*/
     }
  }
</script>
