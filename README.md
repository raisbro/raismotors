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
            padding: 10px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #444;
            padding: 10px 0;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
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
        .card {
            border: 1px solid #ddd;
            border-radius: 8px;
            overflow: hidden;
            margin: 10px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .card img {
            width: 100%;
            height: auto;
        }
        .card-content {
            padding: 15px;
        }
        .card-content h3 {
            margin: 0;
            font-size: 1.2em;
        }
        .card-content p {
            color: #555;
            margin: 10px 0;
        }
        .footer {
            text-align: center;
            padding: 10px;
            background: #333;
            color: #fff;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Добро пожаловать в Автосалон</h1>
    </header>
    <nav>
        <a href="#">Главная</a>
        <a href="#cars">Автомобили</a>
        <a href="#about">О нас</a>
        <a href="#contact">Контакты</a>
    </nav>
    <div class="container">
        <section id="cars">
            <h2>Наши автомобили</h2>
            <div class="card">
                <img src="car1.jpg" alt="Автомобиль 1">
                <div class="card-content">
                    <h3>Автомобиль 1</h3>
                    <p>Цена: 2 000 000₸</p>
                </div>
            </div>
            <div class="card">
                <img src="car2.jpg" alt="Автомобиль 2">
                <div class="card-content">
                    <h3>Автомобиль 2</h3>
                    <p>Цена: 3 500 000₸</p>
                </div>
            </div>
            <!-- Добавьте больше карточек автомобилей по мере необходимости -->
        </section>
        <section id="about">
            <h2>О нас</h2>
            <p>Мы являемся ведущим автосалоном, предлагающим широкий ассортимент автомобилей по выгодным ценам.</p>
        </section>
        <section id="contact">
            <h2>Контакты</h2>
            <p>Email: info@autosalon.kz</p>
            <p>Телефон: +7 (701) 123-45-67</p>
            <p>Адрес: г. Алматы, ул. Центральная, 123</p>
        </section>
    </div>
    <footer class="footer">
        <p>&copy; 2025 Автосалон. Все права защищены.</p>
    </footer>
</body>
</html>
