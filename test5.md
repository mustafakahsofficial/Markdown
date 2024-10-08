<div class="profile-card">
        <div class="profile-pic">
            <img src="https://i.pinimg.com/564x/ff/e7/b0/ffe7b059b323e66ba56f892cb8f7bc50.jpg" alt="Profil Resmi">
        </div>
        <div class="profile-info">
            <h2>Ad Soyad</h2>
            <p>Hakkında kısa bir açıklama burada yer alacak.</p>
            <button class="contact-button">İletişim Kur</button>
        </div>
    </div>

<style>
        .profile-card {
            background: linear-gradient(to right, #4a90e2, #9013fe);
            color: white;
            border-radius: 15px;
            width: 300px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.2);
            overflow: hidden;
            transition: transform 0.3s;
        }

        .profile-card:hover {
            transform: translateY(-10px);
        }

        .profile-pic {
            width: 100%;
            height: 200px;
            overflow: hidden;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .profile-pic img {
            width: 100%;
            height: auto;
            transition: transform 0.3s;
        }

        .profile-card:hover .profile-pic img {
            transform: scale(1.1);
        }

        .profile-info {
            padding: 15px;
        }

        h2 {
            margin: 10px 0;
            font-size: 22px;
        }

        p {
            font-size: 14px;
            margin-bottom: 15px;
        }

        .contact-button {
            background-color: #ffffff;
            color: #4a90e2;
            border: none;
            padding: 10px 15px;
            border-radius: 5px;
            cursor: pointer;
            transition: background 0.3s;
        }

        .contact-button:hover {
            background-color: #4a90e2;
            color: white;
        }
</style>