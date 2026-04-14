<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>OSINT Services | NetErrror</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background-color: #0a0a0a;
            font-family: 'Segoe UI', 'Courier New', monospace;
            color: #e0e0e0;
            padding: 2rem 1rem;
        }

        .container {
            max-width: 1100px;
            margin: 0 auto;
            background: #111;
            border-radius: 24px;
            padding: 2rem;
            border: 1px solid #2a2a2a;
            box-shadow: 0 15px 35px rgba(0,0,0,0.6);
        }

        h1 {
            font-size: 2.6rem;
            font-weight: 800;
            letter-spacing: -1px;
            background: linear-gradient(135deg, #ffffff, #8c8c8c);
            background-clip: text;
            -webkit-background-clip: text;
            color: transparent;
            text-align: center;
            margin-bottom: 0.5rem;
        }

        .sub {
            text-align: center;
            color: #aaa;
            border-bottom: 1px solid #2a2a2a;
            padding-bottom: 1.5rem;
            margin-bottom: 2rem;
        }

        .price-table {
            width: 100%;
            border-collapse: collapse;
            background: #141414;
            border-radius: 18px;
            overflow: hidden;
            margin-bottom: 1rem;
        }

        .price-table th,
        .price-table td {
            padding: 1rem 1.2rem;
            text-align: left;
            border-bottom: 1px solid #2c2c2c;
        }

        .price-table th {
            background: #1c1c1c;
            color: #fff;
            font-weight: 600;
            text-transform: uppercase;
            font-size: 0.9rem;
            letter-spacing: 1px;
        }

        .price-table tr:last-child td {
            border-bottom: none;
        }

        .price-table tr:hover td {
            background: #1a1a1a;
        }

        .price-col {
            font-weight: 700;
            color: #f0f0f0;
            font-family: monospace;
            font-size: 1.1rem;
        }

        .footer-note {
            text-align: center;
            font-size: 0.75rem;
            color: #5a5a5a;
            margin-top: 2rem;
            padding-top: 1rem;
            border-top: 1px solid #222;
        }

        .badge {
            background: #1a1a1a;
            display: inline-block;
            padding: 4px 10px;
            border-radius: 20px;
            font-size: 0.7rem;
            color: #ccc;
        }

        @media (max-width: 680px) {
            .container {
                padding: 1rem;
            }
            .price-table th, .price-table td {
                padding: 0.7rem;
            }
        }
    </style>
</head>
<body>
<div class="container">
    <h1>🕵️ OSINT<span style="color:#777"> — Belgov Shop</span></h1>
    <div class="sub">Аналитика открытых источников | Конфиденциально | Мгновенный прайс</div>

    <!-- Таблица услуг OSINT (без отдельных кнопок в конце) -->
    <table class="price-table">
        <thead>
            <tr>
                <th>Услуга</th>
                <th>Описание</th>
                <th>Стоимость</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td><strong>🔒 Защита (OSINT-аудит)</strong></td>
                <td>Проверка утечек, анализ цифрового следа, рекомендации по скрытию данных</td>
                <td class="price-col">6 $</td>
            </tr>
            <tr>
                <td><strong>📄 Информационное досье</strong></td>
                <td>Сбор данных по email/никнейму/телефону: соцсети, профили, упоминания</td>
                <td class="price-col">5 $</td>
            </tr>
            <tr>
                <td><strong>⚡ Оперативное досье</strong></td>
                <td>Глубокий поиск + связи, геолокация по фото, WHOIS, архивы интернета</td>
                <td class="price-col">6 $</td>
            </tr>
        </tbody>
    </table>

    <div class="footer-note">
        <span class="badge">⚡ Только таблица прайс-листа</span>&nbsp;&nbsp;|&nbsp;&nbsp;OSINT услуги<br>
        * Кнопки отсутствуют согласно вашему требованию.
    </div>
</div>
</body>
</html>
