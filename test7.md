<div class="card">
    <div class="profile-pic">
        <img src="https://i.pinimg.com/564x/ff/e7/b0/ffe7b059b323e66ba56f892cb8f7bc50.jpg" alt="Profil Resmi">
    </div>
    <div class="info">
        <h3>İsminiz</h3>
        <p>İş Unvanınız</p>
    </div>
</div>

<style>
.profile-pic {
    width: 100px;
    height: 100px;
    border-radius: 50%;
    overflow: hidden;
    margin: 0;
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
    background: linear-gradient(to right, rgb(20, 30, 48), rgb(36, 59, 85));
    border-radius: 15px;
    box-shadow: rgb(0, 0, 0, 0.7) 5px 10px 50px, rgb(0, 0, 0, 0.7) -5px 0px 250px;
    display: flex;
    color: white;
    align-items: center; /* Yükseklik hizalaması için */
    padding: 10px; /* İçerik alanını biraz boşlukla ayırma */
}

.info {
    margin-left: 15px; /* Resim ile metin arasında boşluk */
}

.card:hover {
    box-shadow: rgb(0, 0, 0) 5px 10px 50px, rgb(0, 0, 0) -5px 0px 250px;
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
