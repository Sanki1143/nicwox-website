<Nicwox html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>NICWOX | Sanitary & Home Improvement</title>

<meta name="description"
content="NICWOX - Quality sanitary, bathroom, plumbing and home improvement products.">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family:Arial, sans-serif;
    background:#f5f8fa;
    color:#1d2933;
}

header{
    background:#ffffff;
    padding:18px 6%;
    display:flex;
    justify-content:space-between;
    align-items:center;
    position:sticky;
    top:0;
    z-index:100;
    box-shadow:0 2px 15px rgba(0,0,0,.08);
}

.logo{
    font-size:28px;
    font-weight:900;
    letter-spacing:3px;
    color:#102a43;
}

.logo span{
    color:#00a6a6;
}

nav a{
    text-decoration:none;
    color:#102a43;
    margin-left:20px;
    font-weight:bold;
}

.hero{
    min-height:85vh;
    display:flex;
    align-items:center;
    background:linear-gradient(135deg,#102a43,#087f8c);
    color:white;
    padding:60px 7%;
}

.hero-content{
    max-width:700px;
}

.hero h1{
    font-size:clamp(50px,9vw,90px);
    letter-spacing:5px;
    margin-bottom:15px;
}

.hero h1 span{
    color:#65e6e6;
}

.hero p{
    font-size:20px;
    line-height:1.7;
}

.buttons{
    margin-top:30px;
}

.btn{
    display:inline-block;
    padding:14px 24px;
    border-radius:8px;
    text-decoration:none;
    font-weight:bold;
    margin:5px;
}

.catalog-btn{
    background:white;
    color:#102a43;
}

.whatsapp-btn{
    background:#20bd67;
    color:white;
}

section{
    padding:70px 7%;
}

.section-title{
    text-align:center;
    font-size:38px;
    margin-bottom:15px;
    color:#102a43;
}

.section-text{
    text-align:center;
    max-width:700px;
    margin:0 auto 40px;
    color:#637381;
}

.about{
    max-width:900px;
    margin:auto;
    background:white;
    padding:35px;
    border-radius:15px;
    box-shadow:0 5px 25px rgba(0,0,0,.07);
    text-align:center;
}

.products{
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:22px;
}

.product{
    background:white;
    padding:30px;
    border-radius:15px;
    box-shadow:0 5px 25px rgba(0,0,0,.07);
    text-align:center;
    transition:.3s;
}

.product:hover{
    transform:translateY(-6px);
}

.icon{
    font-size:50px;
    margin-bottom:15px;
}

.product h3{
    color:#102a43;
    margin-bottom:10px;
}

.contact{
    background:#102a43;
    color:white;
    text-align:center;
}

.contact .section-title{
    color:white;
}

.contact p{
    margin:10px;
}

footer{
    background:#081722;
    color:#ccc;
    text-align:center;
    padding:25px;
}

@media(max-width:750px){

    header{
        padding:15px 20px;
    }

    nav{
        display:none;
    }

    .hero{
        padding:60px 25px;
        min-height:80vh;
    }

    .products{
        grid-template-columns:1fr;
    }

    section{
        padding:55px 20px;
    }
}
</style>
</head>

<body>

<header>

<div class="logo">
NIC<span>WOX</span>
</div>

<nav>
<a href="#home">Home</a>
<a href="#about">About</a>
<a href="#catalog">Catalog</a>
<a href="#contact">Contact</a>
</nav>

</header>


<!-- HOME -->

<section class="hero" id="home">

<div class="hero-content">

<h1>NIC<span>WOX</span></h1>

<p>
Quality sanitary, bathroom, plumbing and home improvement
products designed for comfort, durability and everyday use.
</p>

<div class="buttons">

<a href="#catalog" class="btn catalog-btn">
View Catalog
</a>

<a
href="https://wa.me/917982434621?text=Hello%20NICWOX%2C%20I%20want%20to%20know%20about%20your%20products."
class="btn whatsapp-btn"
target="_blank">
WhatsApp Enquiry
</a>

</div>

</div>

</section>


<!-- ABOUT -->

<section id="about">

<h2 class="section-title">
About NICWOX
</h2>

<p class="section-text">
Modern products for modern homes.
</p>

<div class="about">

<h3>Who We Are</h3>

<br>

<p>
NICWOX is a modern brand focused on providing quality
sanitary, bathroom and home improvement products designed
for comfort, durability and everyday use.
</p>

<br>

<p>
Our goal is to bring reliable and stylish products to
customers while maintaining practical quality and value.
</p>

</div>

</section>


<!-- CATALOG -->

<section id="catalog">

<h2 class="section-title">
Our Catalog
</h2>

<p class="section-text">
Explore NICWOX product categories.
</p>


<div class="products">


<div class="product">

<div class="icon">🚿</div>

<h3>Bathroom & Sanitary</h3>

<p>
Modern bathroom and sanitary products for homes
and commercial spaces.
</p>

</div>


<div class="product">

<div class="icon">🚰</div>

<h3>Faucets & Taps</h3>

<p>
Stylish and practical taps and bathroom fittings.
</p>

</div>


<div class="product">

<div class="icon">🔧</div>

<h3>Hardware</h3>

<p>
Useful hardware and fittings for home improvement.
</p>

</div>


<div class="product">

<div class="icon">🪠</div>

<h3>Plumbing</h3>

<p>
Pipes, fittings and plumbing products.
</p>

</div>


<div class="product">

<div class="icon">🔩</div>

<h3>Fasteners</h3>

<p>
Nuts, bolts, screws and fastening products.
</p>

</div>


<div class="product">

<div class="icon">🏠</div>

<h3>Home Improvement</h3>

<p>
Products for everyday home improvement projects.
</p>

</div>


</div>

</section>


<!-- CONTACT -->

<section class="contact" id="contact">

<h2 class="section-title">
Contact NICWOX
</h2>

<p>
For product enquiries, contact us on WhatsApp.
</p>

<p>
<strong>WhatsApp: +91 79824 34621</strong>
</p>

<a
href="https://wa.me/917982434621?text=Hello%20NICWOX%2C%20I%20want%20to%20know%20about%20your%20products."
class="btn whatsapp-btn"
target="_blank">
Chat on WhatsApp
</a>

</section>


<footer>

© 2026 NICWOX. All Rights Reserved.

</footer>

</body>
</html>
