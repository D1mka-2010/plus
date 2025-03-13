<!DOCTYPE html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        /* Основные стили */
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            color: #333;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }

        .container {
            max-width: 800px;
            margin: 20px auto;
            background: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        h1 {
            text-align: center;
            font-size: 2.5em;
            color: #444;
            margin-bottom: 20px;
        }

        h2 {
            font-size: 1.8em;
            color: #555;
            margin-top: 30px;
            margin-bottom: 15px;
            border-bottom: 2px solid #ddd;
            padding-bottom: 5px;
        }

        ul {
            list-style-type: disc;
            margin-left: 20px;
        }

        li {
            margin-bottom: 10px;
        }

        a {
            color: #007BFF;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        .telegram-link {
            text-align: center;
            margin: 20px 0;
        }

        img {
            display: block;
            margin: 20px auto;
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        /* Стили для кнопки */
        .telegram-button {
            display: inline-block;
            background-color: #0088cc;
            color: #fff;
            padding: 10px 20px;
            border-radius: 5px;
            text-decoration: none;
            font-size: 1.2em;
            margin: 20px 0;
        }

        .telegram-button:hover {
            background-color: #006699;
        }

        /* Адаптивность для телефонов */
        @media (max-width: 600px) {
            h1 {
                font-size: 1.8em;
            }

            h2 {
                font-size: 1.4em;
            }

            .container {
                padding: 15px;
            }

            .telegram-button {
                font-size: 1em;
                padding: 8px 16px;
            }

            ul {
                margin-left: 15px;
            }

            li {
                font-size: 0.9em;
            }
        }

        /* Адаптивность для ПК */
        @media (min-width: 601px) {
            h1 {
                font-size: 2.5em;
            }

            h2 {
                font-size: 1.8em;
            }

            .container {
                padding: 20px;
            }

            .telegram-button {
                font-size: 1.2em;
                padding: 10px 20px;
            }

            ul {
                margin-left: 20px;
            }

            li {
                font-size: 1em;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Правила подписки «Антон +»</h1>
        </header>

        <main>
            <!-- Ссылка на Telegram канал -->
            <div class="telegram-link">
                <a href="https://t.me/pravAntonpluseA" class="telegram-button">Перейти в Telegram канал</a>
            </div>

            <!-- Раздел "Точки" -->
            <section>
                <h2>Точки:</h2>
                <ul>
                    <li>При пометке точек можно увидеть их количество подряд. Их должно быть определённое количество: 
                        Одна точка — это просто статус, если две точки, то что-то одно на выбор и так далее. Но только пять точек обозначают всё сразу.</li>
                </ul>
            </section>

            <!-- Раздел "Стоимость" -->
            <section>
                <h2>Стоимость:</h2>
                <ul>
                    <li>При наличии скидок нужно предупреждать заранее перед оплатой. Это должен сделать сразу продавец. 
                        Одна точка будет стоить 1 копейку в месяц. Две точки будут стоить 5 копеек в месяц. Три точки будут стоить 15 копеек в месяц. Четыре точки будут стоить 30 копеек в месяц. Пять точек будут стоить 1 рубль в месяц.</li>
                </ul>
            </section>

            <!-- Раздел "Условные обозначения" -->
            <section>
                <h2>Условные обозначения:</h2>
                <ul>
                    <li>✓ — всё правильно либо же бесплатно.</li>
                    <li>× - есть неуверенность либо же недоверие.</li>
                    <li>Ничего (      ) — это значит, что нет ничего плохого или хорошего.</li>
                </ul>
            </section>

            <!-- Раздел "Примечания" -->
            <section>
                <h2>Примечания:</h2>
                <ul>
                    <li>Продление срока печати будет стоить 80 копеек. Если не подать на печать вовремя, то талон перестанет действовать.</li>
                </ul>
            </section>

            <!-- Раздел "Дополнительная информация" -->
            <section>
                <h2>Дополнительная информация:</h2>
                <ul>
                    <li>Для изменения статуса требуется заплатить 5 копеек (не исключён тот факт, что может выпасть один). Но при этом, чтобы вы сами выбирали, будет стоить 5 рублей.</li>
                    <li>В случае если вы нашли ошибку в том, что было написано продавцом, можно показать и забрать пять точек. Если у вас уже есть пять точек и вы заметили ошибку, то вам достаётся продление подписки. Ну если у вас подписка на всю жизнь, то тогда вам достаётся дополнительная подписка Антон+.</li>
                </ul>
            </section>

            <!-- Картинка -->
            <img src="https://via.placeholder.com/800x400" alt="Изображение Telegram канала">
        </main>

        <footer>
            <div class="telegram-link">
                <a href="https://t.me/pravAntonpluseA" class="telegram-button">Перейти в Telegram канал</a>
            </div>
        </footer>
    </div>
</body>
</html>
