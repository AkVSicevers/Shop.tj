<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SHOP.TJ - Товары из Китая</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@700&display=swap');

        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        
        /* Кастомный заголовок SHOP.TJ */
        .shop-title {
            background: linear-gradient(135deg, #ff4500, #ff7300);
            color: white;
            text-align: center;
            font-size: 40px;
            font-weight: bold;
            padding: 20px 10px;
            font-family: 'Montserrat', sans-serif;
            letter-spacing: 3px;
            text-transform: uppercase;
            text-shadow: 3px 3px 10px rgba(0, 0, 0, 0.3);
            animation: fadeIn 1.5s ease-in-out;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .container {
            width: 90%;
            margin: 30px auto;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }

        .card {
            background: white;
            width: 300px;
            margin: 15px;
            padding: 15px;
            border-radius: 10px;
            box-shadow: 0px 5px 10px rgba(0, 0, 0, 0.2);
            text-align: center;
            transition: transform 0.3s;
        }

        .card:hover {
            transform: scale(1.05);
        }

        .card img {
            width: 100%;
            border-radius: 5px;
        }

        .card h3 {
            margin: 15px 0;
            color: #333;
        }

        .card p {
            font-size: 14px;
            color: gray;
            margin-bottom: 10px;
        }

        .card button {
            background: #ff4500;
            color: white;
            padding: 10px 15px;
            border: none;
            cursor: pointer;
            border-radius: 5px;
            transition: background 0.3s;
        }

        .card button:hover {
            background: #e03e00;
        }

        /* Блок контактов */
        .contact {
            background: #222;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }

        .contact a {
            color: #ff7300;
            text-decoration: none;
            font-size: 18px;
            font-weight: bold;
        }

        .contact a:hover {
            text-decoration: underline;
        }

    </style>
</head>
<body>

<div class="shop-title">SHOP.TJ</div>

<div class="container">
    <div class="card">
        <img src="https://source.unsplash.com/300x200/?electronics" alt="Гаджеты">
        <h3>Гаджеты</h3>
        <p>Современные китайские гаджеты по низким ценам.</p>
        <button>Купить</button>
    </div>

    <div class="card">
        <img src="https://source.unsplash.com/300x200/?clothes" alt="Одежда">
        <h3>Одежда</h3>
        <p>Стильная и недорогая одежда прямо из Китая.</p>
        <button>Купить</button>
    </div>

    <div class="card">
        <img src="https://source.unsplash.com/300x200/?shoes" alt="Обувь">
        <h3>Обувь</h3>
        <p>Качественная обувь для любого сезона.</p>
        <button>Купить</button>
    </div>
</div>

<div class="contact">
    <p>Свяжитесь с нами через WhatsApp:</p>
    <a href="https://wa.me/992009772799" target="_blank">+992 009772799</a>
</div>

</body>
</html>
