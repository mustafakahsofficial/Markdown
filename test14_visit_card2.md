# visit card vesion 2 
<div class="card">
    <div class="card__info">
        <div class="card__texture">  
        </div>
        <div class="card__info">
            <img src="https://visitcount.itsvg.in/api?id=mustafakahsofficial&icon=2&color=5" alt="Visit Count">
            </div>
    </div>
</div>

<style>
.card {
  overflow: hidden;
  position: relative;
}
.card__texture {
  animation-duration: 2s;
  animation-timing-function: ease-in-out;
  animation-iteration-count: infinite;
}
.card {
  animation-name: rotate_500;
  background-color: #4158D0;
  background-image: linear-gradient(43deg, #4158D0 0%, #C850C0 46%, #FFCC70 100%);
  width: 300px;
  height: 120px;
  border-radius: 15px;
  cursor: pointer;
}
.card__texture {
      position: absolute;
  animation-name: texture;
  top: 0;
  left: 0;
  width: 200%;
  height: 100%;
}
.card__info {
    display: flex;
    justify-content: center; /* Yatay merkezleme */
    align-items: center; /* Dikey merkezleme */
    width: 100%;
    height: 100%; /* Yükseklik, ekranın tamamı */
    border-radius: 20px; /* İkonu daire yap */
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


# deneme 1 

<div class="visit-counter1">
    <img src="https://visitcount.itsvg.in/api?id=mustafakahsofficial&icon=2&color=5" alt="Visit Count">
    
</div>
<style>
    .visit-counter1 {
            padding: 5px;
        }
.visit-counter1 img {
            margin: 10px;
            border-radius: 20px; /* İkonu daire yap */
            width: 100%; /* İkon boyutu */
            height: 100%;
        }
    </style>