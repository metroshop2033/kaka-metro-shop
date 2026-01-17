<!DOCTYPE html>
<html lang="uk">
<head>
<meta charset="UTF-8">
<title>KAKA METRO SHOP</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: white;
    text-align: center;
}

header {
    padding: 30px;
}

header img {
    width: 280px;
    height: 280px;
    border-radius: 50%;
    animation: pulse 3s infinite;
}

@keyframes pulse {
    0% { transform: scale(1); }
    50% { transform: scale(1.05); }
    100% { transform: scale(1); }
}

h1 {
    font-size: 36px;
}

.items {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 25px;
    padding: 30px;
    max-width: 1000px;
    margin: auto;
}

.item {
    border: 2px solid #ddd;
    border-radius: 15px;
    padding: 15px;
    transition: transform 0.3s, box-shadow 0.3s;
}

.item:hover {
    transform: translateY(-10px);
    box-shadow: 0 10px 25px rgba(0,0,0,0.2);
}

.item img {
    width: 100%;
    max-height: 180px;
    object-fit: contain;
}

.price {
    font-size: 22px;
    font-weight: bold;
    margin: 10px 0;
}

.buy {
    display: inline-block;
    padding: 10px 20px;
    background: #0088cc;
    color: white;
    text-decoration: none;
    border-radius: 25px;
    font-size: 16px;
}

.buy:hover {
    background: #006fa3;
}
</style>
</head>

<body>

<header>
<img src="banner.jpg">
<h1>KAKA METRO SHOP</h1>
<p>Продаж предметів Metro • Швидко • Надійно</p>
</header>

<section class="items">

<div class="item">
<img src="item1.jpg">
<p>Зброя</p>
<div class="price">150 грн</div>
<a class="buy" href="https://t.me/ТВІЙ_КАНАЛ">Купити</a>
</div>

<div class="item">
<img src="item2.jpg">
<p>Броня</p>
<div class="price">200 грн</div>
<a class="buy" href="https://t.me/ТВІЙ_КАНАЛ">Купити</a>
</div>

<div class="item">
<img src="item3.jpg">
<p>Шолом</p>
<div class="price">120 грн</div>
<a class="buy" href="https://t.me/ТВІЙ_КАНАЛ">Купити</a>
</div>

<div class="item">
<img src="item4.jpg">
<p>Рюкзак</p>
<div class="price">180 грн</div>
<a class="buy" href="https://t.me/ТВІЙ_КАНАЛ">Купити</a>
</div>

</section>

</body>
</html>
