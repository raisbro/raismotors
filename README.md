<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Автосалон</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        header h1 {
            font-size: 2.5em;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #444;
            padding: 15px 0;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 20px;
            font-size: 18px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        section {
            margin-bottom: 40px;
        }
        .card {
            border: 1px solid #ddd;
            border-radius: 8px;
            overflow: hidden;
            margin: 10px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            flex: 1;
            max-width: 300px;
            background-color: #fff;
        }
        .card img {
            width: 100%;
            height: auto;
        }
        .card-content {
            padding: 15px;
            text-align: center;
        }
        .card-content h3 {
            margin: 0;
            font-size: 1.4em;
            color: #333;
        }
        .card-content p {
            color: #777;
            font-size: 1.1em;
            margin-top: 10px;
        }
        .footer {
            text-align: center;
            padding: 15px;
            background: #333;
            color: #fff;
            margin-top: 20px;
        }
        .footer p {
            margin: 0;
        }
        form {
            margin-top: 30px;
            background-color: #f9f9f9;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        form h3 {
            margin-bottom: 20px;
            text-align: center;
        }
        form input, form select, form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-size: 16px;
        }
        form button {
            background-color: #333;
            color: #fff;
            padding: 15px;
            border: none;
            border-radius: 5px;
            width: 100%;
            font-size: 18px;
            cursor: pointer;
        }
        form button:hover {
            background-color: #444;
        }
        @media (max-width: 768px) {
            .card {
                flex: 1 1 100%;
                max-width: 100%;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Добро пожаловать в Раисмоторс</h1>
    </header>
    <nav>
        <a href="#">Главная</a>
        <a href="#cars">Автомобили</a>
        <a href="#about">О нас</a>
        <a href="#contact">Контакты</a>
        <a href="#test-drive">Тест-драйв</a>
    </nav>
    <div class="container">
        <section id="cars">
            <h2>Наши автомобили</h2>
            <div class="card">
                <img src="https://avatars.mds.yandex.net/i?id=04654077537271d15933247da5d853b9_l-10245177-images-thumbs&n=13" alt="Hyundai Sonata LUX">
                <div class="card-content">
                    <h3>Hyundai Sonata</h3>
                    <p>Цена: 14 000 000₸</p>
                </div>
            </div>
            <div class="card">
                <img src="https://paultan.org/image/2021/05/2021-BMW-530i-M-Sport-facelift-Malaysia-launch-1-e1622172651217-1260x841.jpg" alt="BMW I530">
                <div class="card-content">
                    <h3>BMW I530</h3>
                    <p>Цена: 25 800 000₸</p>
                </div>
            </div>
            <div class="card">
                <img src="[https://static.carsguide.com.au/hero/toyota-landcruiser-2025.jpg](https://toyota.com.ua/uploads/fastUpload/landcruiser2.jpg.webp)" alt="Toyota Land Cruiser">
                <div class="card-content">
                    <h3>Toyota Land Cruiser</h3>
                    <p>Цена: 32 000 000₸</p>
                </div>
            </div>
            <div class="card">
                <img src="https://avatars.mds.yandex.net/get-verba/1030388/2a000001609072024cf91b018a617dee8397/456x342" alt="Mercedes-Benz E-Class">
                <div class="card-content">
                    <h3>Mercedes-Benz E-Class</h3>
                    <p>Цена: 22 000 000₸</p>
                </div>
            </div>
            <div class="card">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRave4JO8uOfGdt7CqFaBGE9YFyXGHAV5ITrA&s" alt="Mercedes GLE">
                <div class="card-content">
                    <h3>Mercedes GLE</h3>
                    <p>Цена: 27 500 000₸</p>
                </div>
            </div>
        </section>
        <section id="about">
            <h2>О нас</h2>
            <p>Мы являемся ведущим автосалоном, предлагающим широкий ассортимент автомобилей по выгодным ценам. Мы лучшие в сфере автопродаж не только в Астане, но и по всему миру.</p>
        </section>
        <section id="contact">
            <h2>Контакты</h2>
            <p>Email: info@autosalon.kz</p>
            <p>Телефон: +7 (777) 777-77-77</p>
            <p>Адрес: г. Астана, ул. Туран, 13</p>
        </section>
        <section id="test-drive">
            <h2>Записаться на тест-драйв</h2>
            <form>
                <h3>Заполните форму для записи на тест-драйв</h3>
                <input type="text" placeholder="Ваше имя" required>
                <input type="tel" placeholder="Ваш контактный телефон" required>
                <select required>
                    <option value="">Выберите модель автомобиля</option>
                    <option value="Hyundai Sonata">Hyundai Sonata</option>
                    <option value="BMW I530">BMW I530</option>
                    <option value="Toyota Land Cruiser">Toyota Land Cruiser</option>
                    <option value="Mercedes-Benz E-Class">Mercedes-Benz E-Class</option>
                    <option value="Mercedes GLE">Mercedes GLE</option>
                </select>
                <textarea placeholder="Комментарии или пожелания" rows="4"></textarea>
                <button type="submit">Записаться на тест-драйв</button>
            </form>
        </section>
    </div>
    <footer class="footer">
        <p>&copy; 2025 Автосалон. Все права защищены.</p>
    </footer>
</body>
</html>


