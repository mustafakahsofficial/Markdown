<div class="card">
<div class="card__info">

### <div align="center" class="card__logo">__Frontend__</div>


<div class="card__logo">  
<a href="https://en.wikipedia.org/wiki/HTML5" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/html5-original-wordmark.svg" alt="HTML5" height="50" /></a>  
<a href="https://www.w3schools.com/css/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/css3-original-wordmark.svg" alt="CSS3" height="50" /></a>  
<a href="https://www.javascript.com/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/javascript-original.svg" alt="JavaScript" height="50" /></a>  
<a href="https://getbootstrap.com/docs/3.4/javascript/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/bootstrap-plain.svg" alt="Bootstrap" height="50" /></a>  
<a href="https://sass-lang.com/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/sass-original.svg" alt="Sass" height="50" /></a>  
</div>  



<div class="card__texture"></div>
        </div>
</div>

<style>
.card,
.card__texture {
  animation-duration: 3s;
  animation-timing-function: ease-in-out;
  animation-iteration-count: infinite;
}

.card {
  overflow: hidden;
  position: relative;
  animation-name: rotate_500;
  background-color: #4158D0;
  background-image: linear-gradient(43deg, #4158D0 0%, #C850C0 46%, #FFCC70 100%);
  box-shadow: rgba(0, 0, 0, 0.17) 0px -23px 25px 0px inset, rgba(0, 0, 0, 0.15) 0px -36px 30px 0px inset, rgba(0, 0, 0, 0.1) 0px -79px 40px 0px inset, rgba(0, 0, 0, 0.06) 0px 2px 1px, rgba(0, 0, 0, 0.09) 0px 4px 2px, rgba(0, 0, 0, 0.09) 0px 8px 4px, rgba(0, 0, 0, 0.09) 0px 16px 8px, rgba(0, 0, 0, 0.09) 0px 32px 16px;
  border-radius: 0.5em;
  color: hsl(0,0%,100%);
  width: 300px;
  height: 180px;
  transform: translate3d(0,0,0);
}

.card__info,
.card__texture {
  position: absolute;
}

.card__texture {
  animation-name: texture;
  top: 0;
  left: 0;
  width: 200%;
  height: 100%;
}

.card__info {
  font: 0.75em/1 "DM Sans", sans-serif;
  display: flex;
  align-items: center;
  flex-wrap: wrap;
  padding: 0.75rem;
  inset: 0;
}

.card__logo{
    display: flex;
  align-items: center;
}

.card__logo {
  font-weight: bold;
  font-style: italic;
}

.card__texture {
  animation-name: texture;
  background-image: linear-gradient(-80deg,hsla(0,0%,100%,0.3) 25%,hsla(0,0%,100%,0) 45%);
}


/* Animation */
@keyframes rotate_500 {
  from,
    to {
    animation-timing-function: ease-in;
    box-shadow: 0 0 0 hsl(0,0%,80%),
            0.1rem 0 0 hsl(0,0%,100%),
            -0.2rem 0 0.75rem 0 hsla(0,0%,0%,0.3);
    transform: rotateY(-10deg);
  }

  25%,
    75% {
    animation-timing-function: ease-out;
    box-shadow: 0 0 0 hsl(0,0%,80%),
            0 0 0 hsl(0,0%,100%),
            -0.25rem -0.05rem 1rem 0.15rem hsla(0,0%,0%,0.3);
    transform: rotateY(0deg);
  }

  50% {
    animation-timing-function: ease-in;
    box-shadow: -0.1rem 0 0 hsl(0,0%,80%),
            0 0 0 hsl(0,0%,100%),
            -0.3rem -0.1rem 1.5rem 0.3rem hsla(0,0%,0%,0.3);
    transform: rotateY(10deg);
  }
}

@keyframes texture {
  from,
    to {
    transform: translate3d(0,0,0);
  }

  50% {
    transform: translate3d(-50%,0,0);
  }
}                
    </style>