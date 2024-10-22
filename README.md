# Evangelina-Tarot
<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Таро від Євангеліни</title>
    <style>
        body {
            font-family: 'Georgia', serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0;
        }

        header {
            text-align: center;
            background: url('https://i.pinimg.com/736x/e3/07/3e/e3073eaaf26be4510fb1f52adeb41cf8.jpg') no-repeat center;
            background-size: cover;
            padding: 60px 0;
            color: white;
        }

        header h1 {
            font-size: 3em;
            margin: 0;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
        }

        h2 {
            font-size: 2em;
            margin-bottom: 10px;
        }

        p {
            font-size: 1.1em;
            line-height: 1.6;
        }

        .price {
            font-weight: bold;
            color: #e67e22;
        }

        .services img {
            width: 100%;
            height: auto;
            border-radius: 10px;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: white;
            margin-top: 40px;
        }

        button {
            background-color: #e67e22;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1em;
        }

        button:hover {
            background-color: #d35400;
        }

        .service-card {
            margin-bottom: 30px;
            border: 1px solid #ddd;
            padding: 20px;
            border-radius: 10px;
            background-color: white;
        }

        .service-card h3 {
            margin-top: 0;
        }

        .service-card img {
            max-width: 100%;
            border-radius: 10px;
        }

        .contact-links a {
            color: #e67e22;
            text-decoration: none;
            font-weight: bold;
        }

        .contact-links a:hover {
            text-decoration: underline;
        }

        .contact-form {
            margin-top: 40px;
            background-color: white;
            padding: 20px;
            border-radius: 10px;
            border: 1px solid #ddd;
        }

        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        .contact-form button {
            width: 100%;
            background-color: #e67e22;
            color: white;
            border: none;
            padding: 10px;
            cursor: pointer;
        }

        .contact-form button:hover {
            background-color: #d35400;
        }
    </style>
</head>
<body>

    <header>
        <h1>Таро від Євангеліни</h1>
        <p>Поринь у магічний світ Таро разом зі мною</p>
    </header>

    <div class="container">
        <section>
            <h2>Послуги</h2>
            <div class="services">
                <div class="service-card">
                    <img src="https://i.pinimg.com/enabled/564x/c9/28/95/c92895dcc5cdfaa8faf410c6c48aaf7c.jpg" alt="Три карти">
                    <h3>Розклад "Три карти"</h3>
                    <p>Короткий, але змістовний аналіз ситуації. Ідеальний для швидкої відповіді на конкретне питання. <span class="price">111 грн</span></p>
                    <button><a href="https://t.me/etartaletka" style="color:white;text-decoration:none;">Замовити через Telegram</a></button>
                </div>

                <div class="service-card">
                    <img src="https://i.pinimg.com/564x/49/0b/8b/490b8bf284ece53ab653c4bf08e6318e.jpg" alt="Шлях майбутнього">
                    <h3>Розклад "Шлях майбутнього"</h3>
                    <p>Дізнайся, що тебе чекає в найближчі місяці, з порадами та підказками. <span class="price">299 грн</span></p>
                    <button><a href="tel:+380636442358" style="color:white;text-decoration:none;">Замовити через Телефон</a></button>
                </div>

                <div class="service-card">
                    <img src="https://i.pinimg.com/enabled/564x/48/99/ae/4899aeb61c6d34153483cc94726efbaf.jpg" alt="Любов та відносини">
                    <h3>Розклад "Любов та відносини"</h3>
                    <p>Відповіді на любовні питання та стосунки. <span class="price">350 грн</span></p>
                    <button><a href="https://t.me/etartaletka" style="color:white;text-decoration:none;">Замовити через Telegram</a></button>
                </div>

                <div class="service-card">
                    <img src="https://i.pinimg.com/564x/4f/74/4a/4f744a4e8acb0fd733f507b7ea005dd6.jpg" alt="Кар'єра та гроші">
                    <h3>Розклад "Кар'єра та гроші"</h3>
                    <p>Відповіді на питання, що стосуються кар'єри та фінансового стану. <span class="price">400 грн</span></p>
                    <button><a href="tel:+380636442358" style="color:white;text-decoration:none;">Замовити через Телефон</a></button>
                </div>

                <div class="service-card">
                    <img src="https://i.pinimg.com/enabled/564x/83/fe/56/83fe56a4e246a47e47e75c3f248b779d.jpg" alt="Індивідуальний розклад">
                    <h3>Індивідуальний розклад</h3>
                    <p>Персональний розклад на будь-яке питання для глибокого аналізу. <span class="price">від 500 грн</span></p>
                    <button><a href="https://t.me/etartaletka" style="color:white;text-decoration:none;">Замовити через Telegram</a></button>
                </div>
            </div>
        </section>

        <section>
            <h2>Про мене</h2>
            <p>Я — Євангеліна, таролог із трирічним досвідом. Моє завдання — допомогти тобі знайти відповіді на важливі питання, прояснити ситуації та отримати напрямок для майбутніх дій. Я працюю з інтуїцією і досвідом, що дозволяє мені створювати глибокі та точні розклади.</p>
        </section>

        <section class="contact-form">
            <h2>Запис на консультацію</h2>
            <form action="mailto:your-email@example.com" method="post" enctype="text/plain">
                <label for="name">Ім'я:</label>
                <input type="text" id="name" name="name" required>

                <label for="phone">Номер телефону:</label>
                <input type="tel" id="phone" name="phone" required>

                <label for="message">Повідомлення або питання:</label>
                <textarea id="message" name="message" rows="4" required></textarea>

                <button type="submit">Відправити</button>
            </form>
        </section>
    </div>

    <footer>
        <p>© 2024 Євангеліна Таро</p>
    </footer>

</body>
</html>
