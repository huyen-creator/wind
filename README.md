<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Wind</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial,sans-serif;
}

body{
    background:#fff0f5;
}

header{
    background:#ffb6c1;
    padding:20px;
    text-align:center;
}

header h1{
    color:white;
    font-size:40px;
}

nav{
    margin-top:10px;
}

nav a{
    text-decoration:none;
    color:white;
    margin:0 10px;
    font-weight:bold;
}

.hero{
    text-align:center;
    padding:60px 20px;
}

.hero h2{
    color:#ff69b4;
    margin-bottom:10px;
}

.search{
    margin-top:20px;
}

.search input{
    width:300px;
    max-width:90%;
    padding:10px;
    border:none;
    border-radius:20px;
}

.books{
    padding:40px;
}

.books h2{
    color:#ff69b4;
    margin-bottom:20px;
}

.book-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
    gap:20px;
}

.book{
    background:white;
    border-radius:15px;
    padding:20px;
    text-align:center;
    box-shadow:0 0 10px rgba(0,0,0,.1);
}

.book img{
    width:100%;
    border-radius:10px;
}

footer{
    text-align:center;
    padding:20px;
    background:#ffb6c1;
    color:white;
}
</style>
</head>

<body>

<header>
<h1>🌸 WIND 🌸</h1>

<nav>
<a href="#">Trang chủ</a>
<a href="#">Truyện</a>
<a href="#">Đăng truyện</a>
<a href="#">Đăng nhập</a>
</nav>
</header>

<section class="hero">
<h2>Thế giới truyện của bạn</h2>
<p>Đọc truyện miễn phí hoặc đăng tải tác phẩm của riêng mình.</p>

<div class="search">
<input type="text" placeholder="Tìm truyện...">
</div>
</section>

<section class="books">
<h2>📚 Truyện nổi bật</h2>

<div class="book-grid">

<div class="book">
<h3>Truyện 1</h3>
<p>Fantasy</p>
</div>

<div class="book">
<h3>Truyện 2</h3>
<p>Ngôn tình</p>
</div>

<div class="book">
<h3>Truyện 3</h3>
<p>Kinh dị</p>
</div>

</div>
</section>

<footer>
© 2026 Wind - Nền tảng đọc và đăng truyện
</footer>

</body>
</html>
