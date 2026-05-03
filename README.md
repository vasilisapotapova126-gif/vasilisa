<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Василиса | Психолог & Сексолог</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Montserrat:wght@300;400;500&display=swap" rel="stylesheet">
    <style>
        :root { --green: #2d4a27; --cream: #fdfcf0; --dark: #1a1a1a; }
        body { margin: 0; font-family: 'Montserrat', sans-serif; background: var(--cream); color: var(--dark); line-height: 1.7; }
        .container { max-width: 900px; margin: 0 auto; padding: 40px 20px; }
        
        /* Шапка с фото */
        header { background: var(--green); color: var(--cream); text-align: center; padding: 60px 20px; }
        .profile-img { width: 200px; height: 200px; border-radius: 50%; object-fit: cover; border: 4px solid var(--cream); margin-bottom: 20px; }
        h1 { font-family: 'Playfair Display', serif; font-size: 3rem; margin: 0; letter-spacing: 3px; text-transform: uppercase; }
        .subtitle { font-size: 1.1rem; max-width: 600px; margin: 20px auto; font-weight: 300; }

        h2 { font-family: 'Playfair Display', serif; text-transform: uppercase; letter-spacing: 2px; border-bottom: 1px solid var(--green); padding-bottom: 10px; margin-top: 50px; }
        
        .grid { display: grid; grid-template-columns: 1fr 1fr; gap: 40px; margin-top: 30px; }
        @media (max-width: 768px) { .grid { grid-template-columns: 1fr; } }

        ul { padding-left: 20px; list-style-type: none; }
        ul li { position: relative; margin-bottom: 10px; }
        ul li::before { content: "—"; position: absolute; left: -20px; color: var(--green); }

        .price-card { background: white; padding: 30px; border-radius: 2px; box-shadow: 0 10px 30px rgba(0,0,0,0.03); margin-bottom: 20px; border-left: 5px solid var(--green); }
        .price-old { text-decoration: line-through; color: #999; font-size: 0.9rem; }
        .benefit { color: var(--green); font-weight: 600; text-transform: uppercase; font-size: 0.8rem; }

        .rules { font-size: 0.9rem; background: #f4f2e6; padding: 25px; border-radius: 5px; }
        
        .diplomas { display: flex; gap: 15px; margin-top: 20px; overflow-x: auto; padding-bottom: 10px; }
        .diploma-img { height: 150px; border: 1px solid #ddd; }

        .cta-block { text-align: center; padding: 60px 0; }
        .btn { display: inline-block; background: var(--green); color: white; padding: 18px 40px; text-decoration: none; font-weight: 500; letter-spacing: 1px; border-radius: 2px; transition: 0.3s; }
        .btn:hover { opacity: 0.9; transform: translateY(-2px); }
        .btn-secondary { background: transparent; color: var(--green); border: 1px solid var(--green); margin-top: 15px; }
    </style>
</head>
<body>

    <header>
        <img src="me.jpg" alt="Василиса" class="profile-img" onerror="this.style.display='none'">
        <h1>Василиса</h1>
        <div class="subtitle">Бережное пространство для твоей честности, глубины и удовольствия [cite: 1, 4-5].</div>
    </header>

    <div class="container">
        
        <div class="grid">
            <div>
                <h2>С чем я работаю</h2>
                <ul>
                    <li>Самооценка и самоценность [cite: 1, 7]</li>
                    <li>Тревожность, страхи, напряжение [cite: 1, 8]</li>
                    <li>Сложности в отношениях (всех видов) [cite: 1, 9]</li>
                    <li>Выгорание и поиск смыслов [cite: 1, 9]</li>
                </ul>
            </div>
            <div>
                <h2>Темы сексуальности</h2>
                <ul>
                    <li>Либидо и желание [cite: 1, 16]</li>
                    <li>Боли, стыд, блоки и телесные зажимы [cite: 1, 17]</li>
                    <li>Вопрос оргазма и удовольствия [cite: 1, 18]</li>
                    <li>Сложности диалога с партнером [cite: 1, 19]</li>
                </ul>
            </div>
        </div>

        <p style="font-style: italic; margin-top: 20px;">Мой подход: без морали и «правильных» ответов. Только поддержка и бережность к твоему темпу[cite: 1, 11].</p>

        <h2>Образование</h2>
        <p><strong>Высшее психологическое:</strong> Диплом Бакалавра с отличием («Красный Диплом») [cite: 1, 56-57].</p>
        <p><strong>Мировой опыт:</strong> Сертификаты Copenhagen Business School (Дания) и University of Chicago (США)[cite: 1, 87, 95].</p>
        
        <div class="diplomas">
            <img src="diploma1.jpg" alt="Диплом 1" class="diploma-img" onerror="this.style.display='none'">
            <img src="diploma2.jpg" alt="Диплом 2" class="diploma-img" onerror="this.style.display='none'">
        </div>

        <h2>Формат и стоимость</h2>
        <div class="grid">
            <div>
                <div class="price-card">
                    <h3>Разовая сессия</h3>
                    <p>60 минут — <strong>3 000 ₽</strong> [cite: 1, 23, 34]</p>
                    <small>Онлайн (Яндекс Телемост) + связь в чате [cite: 1, 21-25]</small>
                </div>
                <div class="price-card">
                    <h3>Пакет из 4 сессий</h3>
                    <p><span class="price-old">12 000 ₽</span> <strong>10 000 ₽</strong> [cite: 1, 40]</p>
                    <span class="benefit">Выгода 2 000 ₽</span>
                </div>
            </div>
            <div class="rules">
                <strong>Правила записи:</strong>
                <ul>
                    <li>Предоплата 100% [cite: 1, 28]</li>
                    <li>Отмена не позже, чем за 24 часа [cite: 1, 30]</li>
                    <li>Опоздание >10 мин = сессия проведена [cite: 1, 31]</li>
                    <li>Частота: не реже 1 раза в 2 недели [cite: 1, 32]</li>
                </ul>
            </div>
        </div>

        <div class="cta-block">
            <a href="https://t.me/vasilisa_potapova" class="btn">ЗАПИСАТЬСЯ НА СЕССИЮ</a><br>
            <a href="https://t.me/vazilissaa" class="btn btn-secondary">МОЙ TELEGRAM-КАНАЛ</a>
        </div>

    </div>

</body>
</html>
