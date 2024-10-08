# visit card main

[![](https://visitcount.itsvg.in/api?id=mustafakahsofficial&icon=2&color=5)](https://visitcount.itsvg.in)

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


# deneme 2
<div class="visit-counter card">
    <img src="https://visitcount.itsvg.in/api?id=mustafakahsofficial&icon=2&color=5" alt="Visit Count">
    
</div>

<style>
        .visit-counter {
            padding: 5px;
        }
.visit-counter img {
            margin: 10px;
            border-radius: 20px; /* İkonu daire yap */
            width: 100%; /* İkon boyutu */
            height: 100%;
        }
.card {
  width: 250px;
  height: 40px;
  background: #07182E;
  position: relative;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  overflow: hidden;
  border-radius: 15px;
}

.card h2 {
  z-index: 1;
  color: white;
  font-size: 1.5em;
  margin: 10px 0;
}

.card img {
  z-index: 1;
  max-width: 80%;
}

.card::before {
  content: '';
  position: absolute;
  width: 300px;
  background-image: linear-gradient(180deg, rgb(0, 183, 255), rgb(255, 48, 255));
  height: 90%;
  animation: rotBGimg 9s linear infinite;
  transition: all 0.5s linear;
  border-radius: 15px;
}

@keyframes rotBGimg {
  from {
    transform: rotate(0deg);
  }

  to {
    transform: rotate(360deg);
  }
}

.card::after {
  content: '';
  position: absolute;
  background: #07182E;
  inset: 5px;
  border-radius: 15px;
}  
</style>



# deneme 3
<div class="visit-counter2 card2">
    <img src="https://visitcount.itsvg.in/api?id=mustafakahsofficial&icon=2&color=5" alt="Visit Count">
    
</div>

<style>
    .visit-counter2 {
            padding: 10px 3px;
        }
.visit-counter2 img {
            margin: 3px 10px;
            border-radius: 20px; /* İkonu daire yap */
            width: 100%; /* İkon boyutu */
            height: 100%;
        }
.card2 {
  width: 300px;
  height: 100px;
  background-color: #4158D0;
  background-image: linear-gradient(43deg, #4158D0 0%, #C850C0 46%, #FFCC70 100%);
  border-radius: 8px;
  color: white;
  overflow: hidden;
  position: relative;
  transform-style: preserve-3d;
  perspective: 1000px;
  transition: all 0.5s cubic-bezier(0.23, 1, 0.320, 1);
  cursor: pointer;
}
.card2:hover {
  transform: rotateY(10deg) rotateX(10deg) scale(1.05);
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
}

.card2:before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: linear-gradient(transparent, rgba(0, 0, 0, 0.1));
  transition: transform 0.5s cubic-bezier(0.23, 1, 0.320, 1);
  z-index: 1;
}

.card2:hover:before {
  transform: translateX(-100%);
}

.card2:after {
  content: "";
  position: absolute;
  top: 0;
  right: 0;
  width: 100%;
  height: 100%;
  background: linear-gradient(transparent, rgba(0, 0, 0, 0.1));
  transition: transform 0.5s cubic-bezier(0.23, 1, 0.320, 1);
  z-index: 1;
}

.card2:hover:after {
  transform: translateX(100%);
}
</style>