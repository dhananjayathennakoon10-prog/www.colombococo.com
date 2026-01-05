<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Colombo Coco | Pure Coconut Oil</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
}
html{ scroll-behavior:smooth; }

body{
    background: linear-gradient(135deg,#0a0f0f,#1e1e1e);
    color:#fff;
}

/* HEADER */
header{
    position:fixed;
    top:0;
    width:100%;
    padding:20px 50px;
    background:rgba(255,255,255,0.05);
    backdrop-filter:blur(10px);
    display:flex;
    justify-content:space-between;
    align-items:center;
    z-index:1000;
}
header h1{
    color:#00e0a8;
}
nav a{
    margin-left:25px;
    color:#fff;
    opacity:0.85;
    text-decoration:none;
}
nav a:hover{ color:#00e0a8; }

/* SECTIONS */
section{
    padding:100px 50px;
}
.center{
    max-width:1100px;
    margin:auto;
    text-align:center;
}

/* HERO */
.hero{
    height:100vh;
    background:url('https://images.pexels.com/photos/7148527/pexels-photo-7148527.jpeg') center/cover no-repeat;
    display:flex;
    align-items:center;
    justify-content:center;
    position:relative;
}
.hero::after{
    content:"";
    position:absolute;
    inset:0;
    background:rgba(0,0,0,0.6);
}
.hero-content{
    position:relative;
    z-index:2;
}
.hero h2{ font-size:50px; }
.hero p{ margin:20px 0; }

.btn{
    background:#00e0a8;
    padding:15px 30px;
    color:#000;
    font-weight:600;
    border-radius:30px;
    text-decoration:none;
}
.btn:hover{ background:#00b384; }

/* PRODUCTS */
.grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:30px;
    margin-top:40px;
}
.card{
    background:rgba(255,255,255,0.06);
    padding:20px;
    border-radius:20px;
    backdrop-filter:blur(10px);
}
.card img{
    width:100%;
    border-radius:15px;
}
.price{
    color:#00e0a8;
    font-size:20px;
    margin:10px 0;
}

/* LIST */
ul{
    list-style:none;
    line-height:1.8;
    font-size:18px;
}

/* FOOTER */
footer{
    text-align:center;
    padding:30px;
    background:rgba(255,255,255,0.04);
    margin-top:50px;
}

/* MOBILE */
@media(max-width:600px){
    header{flex-direction:column;}
    nav a{margin:10px;}
    .hero h2{font-size:36px;}
}
</style>
</head>

<body>

<header>
    <h1>Colombo Coco</h1>
    <nav>
        <a href="#home">Home</a>
        <a href="#products">Products</a>
        <a href="#export">Export</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<!-- HOME -->
<section id="home" class="hero">
    <div class="hero-content center">
        <h2>Pure Organic Coconut Oil</h2>
        <p>Cold-Pressed | 100% Natural | Sri Lankan Premium Quality</p>
        <a href="#products" class="btn">Shop Now</a>
    </div>
</section>

<!-- PRODUCTS -->
<section id="products">
    <div class="center">
        <h2>Our Products</h2>

        <div class="grid">
            <div class="card">
                <img src="https://tse2.mm.bing.net/th/id/OIP.6X69S8fpzXms4xwV6r5cAwAAAA?pid=ImgDet&w=190&h=285&c=7&o=7&rm=3">
                <h3>500ml Coconut Oil</h3>
                <p class="price">Rs. 999</p>
                <a class="btn" href="https://wa.me/94704845611">Buy Now</a>
            </div>

            <div class="card">
                <img src="https://images.unsplash.com/photo-1615485925600-e146f0d7d76f">
                <h3>1L Coconut Oil</h3>
                <p class="price">Rs. 1800</p>
                <a class="btn" href="https://wa.me/94704845611">Buy Now</a>
            </div>

            <div class="card">
                <img src="https://images.unsplash.com/photo-1556228578-877c94ce3d4f">
                <h3>Cooking Grade Oil</h3>
                <p class="price">Rs. 1500</p>
                <a class="btn" href="https://wa.me/94704845611">Buy Now</a>
            </div>
        </div>
    </div>
</section>

<!-- EXPORT -->
<section id="export">
    <div class="center">
        <h2>🌍 Export Countries</h2>
        <div class="grid">
            <div class="card">USA</div><div class="card">UK</div><div class="card">Australia</div>
            <div class="card">Canada</div><div class="card">UAE</div><div class="card">Germany</div>
            <div class="card">Japan</div><div class="card">India</div>
        </div>

        <h2 style="margin-top:60px;">🏆 Quality</h2>
        <ul>
            <li>✔ 100% Cold-Pressed Virgin Coconut Oil</li>
            <li>✔ No Chemicals or Preservatives</li>
            <li>✔ High Lauric Acid (Up to 52%)</li>
            <li>✔ HACCP, ISO, GMP Certified</li>
        </ul>

        <h2 style="margin-top:60px;">📜 Export Rules</h2>
        <ul>
            <li>✔ Minimum Order: 25kg</li>
            <li>✔ Bulk & Retail Packaging</li>
            <li>✔ Sea & Air Cargo Available</li>
            <li>✔ Worldwide Shipping</li>
        </ul>
    </div>
</section>

<!-- CONTACT -->
<footer id="contact">
    📞 070 484 5611 <br>
    📧 dhananjayathennakoon10@gmail.com <br><br>
    © 2025 Colombo Coco | All Rights Reserved
</footer>

</body>
</html>
