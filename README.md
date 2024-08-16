<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>hair & make Luana</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 0;
        }
        .logo {
            font-weight: bold;
            white-space: nowrap;
        }
        .logo-small {
            font-size: 16px;
        }
        .logo-large {
            font-size: 32px;
            margin-left: 5px;
        }
        nav ul {
            list-style-type: none;
            display: flex;
            margin: 0;
            padding: 0;
        }
        nav ul li {
            margin-left: 20px;
        }
        .main-image {
            width: 100%;
            height: 600px;
            overflow: hidden;
            position: relative;
        }
        .main-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            object-position: center 30%;
        }
        .announcements {
            margin-top: 20px;
            border: 1px solid #ccc;
        }
        .announcement-item {
            padding: 10px 20px;
            border-bottom: 1px solid #ccc;
            margin: 0;
        }
        .announcement-item:last-child {
            border-bottom: none;
        }
        .more-link {
            text-align: right;
            padding: 10px 20px;
        }
        footer {
            margin-top: 40px;
            background-color: #f0f0f0;
            text-align: center;
            padding: 20px 0;
        }
        .footer-item {
            margin: 5px 0;
        }
        .underline {
            border-bottom: 1px solid blue;
            display: inline-block;
            padding-bottom: 2px;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <div class="logo">
                <span class="logo-small">hair & make</span>
                <span class="logo-large">Luana</span>
            </div>
            <nav>
                <ul>
                    <li>メニュー</li>
                    <li>スタッフ</li>
                    <li>ギャラリー</li>
                    <li>問合せ</li>
                </ul>
            </nav>
        </header>
        
        <main>
            <div class="main-image">
                <img src="young-buck-salon.png" alt="Stylish man with blonde hair">
            </div>
            
            <div class="announcements">
                <h2 class="announcement-item">お知らせ</h2>
                <p class="announcement-item">→当社ヘアモデルのCM出演</p>
                <p class="announcement-item">→Amazon Prime人気恋愛リアリティー番組ラブトランジット出演カップルにご協力いただきAWコレクションレセプションに出席しました。</p>
                <p class="more-link">→もっと見る</p>
            </div>
        </main>
        
        <footer>
            <p class="footer-item"><span class="underline">住所 東京都XXXX-XXX-XXX</span></p>
            <p class="footer-item"><span class="underline">電話番号 000-0000-0000</span></p>
            <p class="footer-item"><span class="underline">営業時間 00:00-24:00</span></p>
            <p class="footer-item"><span class="underline">定休日 火曜日</span></p>
        </footer>
    </div>
</body>
</html>
