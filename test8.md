
<div class="card">
<div class="profile-pic">
        <img src="https://i.pinimg.com/564x/ff/e7/b0/ffe7b059b323e66ba56f892cb8f7bc50.jpg" alt="Profil Resmi">
    </div>
    <div class="info">
        <h3 class="galaxy-text">MUSTAFAKAHS</h3>
        <p class="galaxy-text">JR DEVELOPER</p>
    </div>
</div>

<style>
.profile-pic {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            overflow: hidden;
            margin: 0 auto;
            box-shadow: inset 4px 4px 10px rgba(255, 255, 255, 0.7),
                        inset -4px -4px 10px rgba(0, 0, 0, 0.2);
            display: flex;
            justify-content: center;
            align-items: center;
            background: linear-gradient(135deg, #4a90e2, #50e3c2);
            border: 4px solid #fff; /* Dış kenar */
        }

        .profile-pic img {
            width: 100%;
            height: auto;
            border-radius: 50%;
            transition: transform 0.3s;
        }
.card {
  width: 280px;
  height: 150px;
  background: rgb(17, 4, 134);
  border-radius: 15px;
  box-shadow: rgb(0,0,0,0.7) 5px 10px 50px ,rgb(0,0,0,0.7) -5px 0px 250px;
  display: flex;
  color: white;
  justify-content: center;
  position: relative;
  flex-direction: column;
  background: linear-gradient(to right, rgb(20, 30, 48), rgb(36, 59, 85));
  cursor: pointer;
  transition: all 0.3s ease-in-out;
  overflow: hidden;
}

.card:hover {
  box-shadow: rgb(0,0,0) 5px 10px 50px ,rgb(0,0,0) -5px 0px 250px;
}

.moon {
  font-size: 20px;
  position: absolute;
  right: 15px;
  top: 15px;
  transition: all 0.3s ease-in-out;
}

.card:hover > .moon {
  font-size: 23px;
}
</style>



