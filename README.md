<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>rabbit.co | Luxury Gift Boutique</title>

<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;700&family=Inter:wght@300;400;500&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family:'Inter', sans-serif;
    background:#fdf9f7;
    color:#2d2d2d;
}

header{
    padding:25px 8%;
    display:flex;
    justify-content:space-between;
    align-items:center;
    background:#ffffff;
    border-bottom:1px solid #f1e8e4;
}

.logo{
    font-family:'Playfair Display', serif;
    font-size:26px;
    letter-spacing:1px;
}

nav a{
    text-decoration:none;
    color:#555;
    margin-left:30px;
    font-size:14px;
    letter-spacing:1px;
}

.hero{
    height:85vh;
    background:linear-gradient(rgba(0,0,0,0.25), rgba(0,0,0,0.25)),
    url('file:///C:/Users/User/Downloads/download%20(5).jpeg') center/cover;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
    color:white;
    padding:20px;
}

.hero h1{
    font-family:'Playfair Display', serif;
    font-size:52px;
    margin-bottom:20px;
    font-weight:700;
}

.hero p{
    font-size:16px;
    letter-spacing:1px;
}

.hero button{
    margin-top:25px;
    padding:12px 35px;
    border:none;
    background:#e8cfc6;
    color:#2d2d2d;
    font-size:14px;
    letter-spacing:1px;
    cursor:pointer;
}

.section{
    padding:90px 8%;
    background:#fdf9f7;
}

.section h2{
    text-align:center;
    font-family:'Playfair Display', serif;
    font-size:36px;
    margin-bottom:60px;
}

.products{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
    gap:40px;
}

.card{
    background:white;
    border-radius:12px;
    overflow:hidden;
    transition:0.4s;
}

.card:hover{
    transform:translateY(-6px);
}

.card img{
    width:100%;
    height:300px;
    object-fit:cover;
}

.card-content{
    padding:25px;
    text-align:center;
}

.card-content h3{
    font-family:'Playfair Display', serif;
    font-size:20px;
    margin-bottom:10px;
}

.price{
    color:#b68b7a;
    font-weight:500;
    font-size:14px;
}

footer{
    background:#ffffff;
    padding:50px 8%;
    text-align:center;
    border-top:1px solid #f1e8e4;
}

footer p{
    font-size:13px;
    letter-spacing:1px;
    color:#777;
}

@media(max-width:768px){
    .hero h1{
        font-size:34px;
    }
}
</style>
</head>
<body>

<header>
    <div class="logo">rabbit.co</div>
    <nav>
        <a href="#">HOME</a>
        <a href="#">SHOP</a>
        <a href="#">ABOUT</a>
        <a href="#">CONTACT</a>
    </nav>
</header>

<section class="hero">
    <div>
        <h1>Luxury Gifts, Softly Curated</h1>
        <p>Timeless pieces wrapped in elegance.</p>
        <button>DISCOVER</button>
    </div>
</section>

<section class="section">
    <h2>Signature Collection</h2>

    <div class="products">

        <div class="card">
            <img src="https://images.unsplash.com/photo-1607082349566-187342175e2f?auto=format&fit=crop&w=800&q=80">
            <div class="card-content">
                <h3>Velvet Gift Box</h3>
                <p class="price">₹1,899</p>
            </div>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1578898887932-dce23a595ad4?auto=format&fit=crop&w=800&q=80">
            <div class="card-content">
                <h3>Blush Keepsake Set</h3>
                <p class="price">₹1,299</p>
            </div>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1511988617509-a57c8a288659?auto=format&fit=crop&w=800&q=80">
            <div class="card-content">
                <h3>Signature Surprise Box</h3>
                <p class="price">₹2,199</p>
            </div>
        </div>

    </div>
</section>

<footer>
    <p>© 2026 rabbit.co — A Luxury Gift Boutique</p>
</footer>

</body>
</html>
<footer>
    <p>© 2026 rabbit.co — A Luxury Gift Boutique</p>
</footer>

</body>
</html># rabbit.co
