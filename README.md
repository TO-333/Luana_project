
<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>hair & make Luana</title>
    <link rel="stylesheet" href="css/new-style.css">
    <style>
        body, html {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            font-size: 14px;
        }
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
        }
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 20px;
        }
        .logo {
            font-size: 18px;
            font-weight: bold;
        }
        .logo span {
            font-size: 28px;
            color: #000;
        }
        nav a {
            margin-left: 20px;
            text-decoration: none;
            color: #000;
        }
        .main-image {
            width: 100%;
            height: 500px;
            background-color: #f0f0f0;
            margin-bottom: 20px;
            overflow: hidden;
            position: relative;
        }
        .main-image img {
            width: 100%;
            height: auto;
            display: block;
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            object-fit: cover;
        }
        .news-container {
            border: 1px solid #000;
            margin-bottom: 10px;
        }
        .news-header {
            text-align: center;
            font-weight: bold;
            padding: 5px 0;
            border-bottom: 1px solid #000;
        }
        .news-content {
            padding: 0;
        }
        .news-item {
            padding: 10px;
        }
        .news-item:not(:last-child) {
            border-bottom: 1px solid #000;
        }
        .more-link {
            text-align: center;
            margin-top: 5px;
        }
        .more-link a {
            color: #000;
            text-decoration: none;
        }
        footer {
            margin-top: 20px;
            text-align: center;
            font-size: 12px;
        }
        footer p {
            margin: 5px 0;
        }
        footer span {
            text-decoration: underline;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <div class="logo">hair & make <span>Luana</span></div>
            <nav>
                <a href="#">メニュー</a>
                <a href="#">スタッフ</a>
                <a href="#">ギャラリー</a>
                <a href="#">問合せ</a>
            </nav>
        </header>
        <main>
            <div class="main-image">
                <img src="img/sample4.jpeg" alt="Luana Hair & Make Model">
            </div>
            <div class="news-container">
                <div class="news-header">お知らせ</div>
                <div class="news-content">
                    <div class="news-item">→当社ヘアモデルのCM出演</div>
                    <div class="news-item">→Amazon Prime人気恋愛リアリティー番組ラブトランジット出演カップルにご招待いただきAWコレクションレセプションに出席しました。</div>
                </div>
            </div>
            <div class="more-link">
                <a href="#">→もっと見る</a>
            </div>
        </main>
        <footer>
            <p><span>住所</span>: <span>東京都XXXX-XXX-XXX</span></p>
            <p><span>電話番号</span>: <span>000-0000-0000</span></p>
            <p><span>営業時間</span>: <span>00:00-24:00</span></p>
            <p><span>定休日</span>: <span>火曜日</span></p>
        </footer>
    </div>
</body>
</html>


<style>
body, html {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
    font-size: 14px;
}
.container {
    max-width: 1000px;
    margin: 0 auto;
    padding: 20px;
}
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 20px;
}
.logo {
    font-size: 18px;
    font-weight: bold;
}
.logo span {
    font-size: 28px;
    color: #000;
}
nav a {
    margin-left: 20px;
    text-decoration: none;
    color: #000;
}
.main-image {
    width: 100%;
    height: 500px;
    background-color: #f0f0f0;
    margin-bottom: 20px;
    overflow: hidden;
    position: relative;
}
.main-image img {
    width: 100%;
    height: auto;
    display: block;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    object-fit: cover;
}
.news-container {
    border: 1px solid #000;
    margin-bottom: 10px;
}
.news-header {
    text-align: center;
    font-weight: bold;
    padding: 5px 0;
    border-bottom: 1px solid #000;
}
.news-content {
    padding: 0;
}
.news-item {
    padding: 10px;
}
.news-item:not(:last-child) {
    border-bottom: 1px solid #000;
}
.more-link {
    text-align: center;
    margin-top: 5px;
}
.more-link a {
    color: #000;
    text-decoration: none;
}
footer {
    margin-top: 20px;
    text-align: center;
    font-size: 12px;
}
footer p {
    margin: 5px 0;
}
footer span {
    text-decoration: underline;
    font-weight: bold;
}
</style>
