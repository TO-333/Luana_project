<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>hair & make Luana</title>
    <style>
        body {
            font-family: 'Hiragino Kaku Gothic Pro', 'Meiryo', sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }
        header {
            background-color: #fff;
            padding: 10px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .logo {
            display: flex;
            align-items: baseline;
        }
        .logo-small {
            font-size: 14px;
            font-weight: normal;
            color: #000;
        }
        .logo-large {
            font-size: 32px;
            font-weight: bold;
            color: #000080;
            margin-left: 5px;
        }
        nav a {
            margin-left: 15px;
            text-decoration: none;
            color: #000;
        }
        .main-image-placeholder {
            width: 100%;
            height: 70vh;
            background-color: #f0f0f0;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 24px;
            color: #888;
        }
        .news {
            margin: 20px auto;
            width: 80%;
            border: 1px solid #ccc;
        }
        .news h2 {
            background-color: #f0f0f0;
            margin: 0;
            padding: 10px;
            font-weight: normal;
        }
        .news-item {
            padding: 10px;
            border-bottom: 1px solid #ccc;
        }
        .news-more {
            text-align: right;
            padding: 10px;
        }
        footer {
            background-color: #f0f0f0;
            padding: 10px 0;
            text-align: center;
            margin-top: auto;
        }
        footer p {
            margin: 5px 0;
            padding: 0;
            line-height: 1.5;
        }
        footer span {
            border-bottom: 1px solid #0000FF;
            display: inline-block;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">
            <span class="logo-small">hair & make</span>
            <span class="logo-large">Luana</span>
        </div>
        <nav>
            <a href="#menu">メニュー</a>
            <a href="#staff">スタッフ</a>
            <a href="#gallery">ギャラリー</a>
            <a href="#contact">問合せ</a>
        </nav>
    </header>
    
    <main>
        <div class="main-image-placeholder">
            <img src="young-buck-salon.png" alt="Stylish man with blonde hair">
        </div>
        
        <div class="news">
            <h2>お知らせ</h2>
            <div class="news-item">
                →当社ヘアモデルのCM出演
            </div>
            <div class="news-item">
                →Amazon Prime人気恋愛リアリティー番組ラブトランジット出演カップルにご招待いただきAWコレクションレセプションに出席しました。
            </div>
            <div class="news-more">
                <a href="#more">→もっと見る</a>
            </div>
        </div>
    </main>

    <footer>
        <p><span>住所: 東京都XXXX-XXX-XXX</span></p>
        <p><span>電話番号: 000-0000-0000</span></p>
        <p><span>営業時間: 00:00-24:00</span></p>
        <p><span>定休日: 火曜日</span></p>
    </footer>
</body>
</html>
