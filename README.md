<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>汽车王 - 专业汽车资讯与改装平台</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: "Microsoft Yahei", sans-serif;
        }
        body {
            background-color: #111;
            color: #eee;
        }
        header {
            background: #0a0a0a;
            padding: 20px 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 2px solid #00cc66;
        }
        .logo {
            font-size: 28px;
            font-weight: bold;
            color: #00cc66;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin-left: 30px;
            font-size: 16px;
            transition: 0.3s;
        }
        nav a:hover {
            color: #00cc66;
        }
        .banner {
            height: 450px;
            background: linear-gradient(rgba(0,0,0,0.6),rgba(0,0,0,0.6)),url("https://img0.baidu.com/it/u=1289678221,3829212323&fm=253&fmt=auto&app=138&f=JPEG?w=1920&h=800") center/cover no-repeat;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
        }
        .banner h1 {
            font-size: 50px;
            margin-bottom: 15px;
            color: #00cc66;
        }
        .banner p {
            font-size: 18px;
            max-width: 700px;
            line-height: 1.8;
        }
        .container {
            width: 90%;
            margin: 60px auto;
        }
        .title-box {
            text-align: center;
            margin-bottom: 40px;
        }
        .title-box h2 {
            font-size: 32px;
            padding-bottom: 10px;
            border-bottom: 3px solid #00cc66;
            display: inline-block;
        }
        .car-list {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px,1fr));
            gap: 30px;
        }
        .car-card {
            background: #1a1a1a;
            border-radius: 10px;
            overflow: hidden;
            transition: transform 0.3s;
        }
        .car-card:hover {
            transform: translateY(-8px);
        }
        .car-card img {
            width: 100%;
            height: 180px;
            object-fit: cover;
        }
        .card-text {
            padding: 20px;
        }
        .card-text h3 {
            font-size: 20px;
            margin-bottom: 10px;
            color: #00cc66;
        }
        .card-text p {
            line-height: 1.7;
            color: #aaa;
        }
        footer {
            text-align: center;
            padding: 30px;
            background: #000;
            margin-top: 80px;
            color: #777;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">汽车王</div>
        <nav>
            <a href="#">首页</a>
            <a href="#">车型大全</a>
            <a href="#">改装方案</a>
            <a href="#">用车评测</a>
            <a href="#">联系我们</a>
        </nav>
    </header>

    <section class="banner">
        <h1>汽车王 · 爱车一站式平台</h1>
        <p>汇聚JDM改装、车型解析、性能评测、养护知识，海量汽车资料随心查阅，改装爱好者聚集地</p>
    </section>

    <div class="container">
        <div class="title-box">
            <h2>热门车型推荐</h2>
        </div>
        <div class="car-list">
            <div class="car-card">
                <img src="https://img1.baidu.com/it/u=268219569,3055412121&fm=253&fmt=auto&app=138&f=JPEG?w=800&h=500" alt="日系性能车">
                <div class="card-text">
                    <h3>日系JDM性能车</h3>
                    <p>经典头文字D同款车型，后置后驱操控拉满，改装潜力巨大。</p>
                </div>
            </div>
            <div class="car-card">
                <img src="https://img2.baidu.com/it/u=3634911512,2067856191&fm=253&fmt=auto&app=120&f=JPEG?w=800&h=500" alt="性能跑车">
                <div class="card-text">
                    <h3>运动跑车系列</h3>
                    <p>大马力后置引擎，极致加速体验，赛道日常两用。</p>
                </div>
            </div>
            <div class="car-card">
                <img src="https://img0.baidu.com/it/u=1997612138,379322518&fm=253&fmt=auto&app=138&f=JPEG?w=800&h=500" alt="家用改装SUV">
                <div class="card-text">
                    <h3>改装SUV</h3>
                    <p>城市



