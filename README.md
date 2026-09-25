<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>7OCEANS — Premium Drinking Water</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

html{
    scroll-behavior:smooth;
}

body{
    font-family:Arial,Helvetica,sans-serif;
    color:#07364a;
    background:#f2fbff;
}

/* NAVBAR */
nav{
    padding:22px 7%;
    background:white;
    display:flex;
    align-items:center;
    justify-content:space-between;
    position:sticky;
    top:0;
    z-index:100;
    box-shadow:0 2px 15px rgba(0,100,140,.08);
}

.logo{
    font-size:28px;
    font-weight:900;
    letter-spacing:2px;
    color:#087ea5;
}

.logo span{
    color:#0aa9d6;
}

nav a{
    margin-left:25px;
    text-decoration:none;
    color:#345767;
    font-weight:600;
}

/* HERO */
.hero{
    min-height:650px;
    padding:70px 7%;
    display:flex;
    align-items:center;
    justify-content:space-between;
    gap:50px;
    background:linear-gradient(135deg,#e5faff,#ffffff 55%,#dff7ff);
}

.hero-text{
    max-width:600px;
}

.eyebrow{
    font-size:13px;
    font-weight:bold;
    letter-spacing:4px;
    color:#0792b8;
    margin-bottom:18px;
}

.hero h1{
    font-size:clamp(55px,8vw,88px);
    line-height:.92;
    letter-spacing:-4px;
    margin-bottom:25px;
}

.hero p{
    font-size:19px;
    line-height:1.7;
    color:#5c7580;
    max-width:530px;
}

.btn{
    display:inline-block;
    margin-top:25px;
    background:#087ea5;
    color:white;
    padding:16px 28px;
    border-radius:30px;
    text-decoration:none;
    font-weight:bold;
    box-shadow:0 10px 25px rgba(8,126,165,.25);
}

/* BOTTLE */
.bottle-area{
    width:360px;
    height:460px;
    border-radius:45%;
    background:linear-gradient(145deg,#d8f8ff,#b9edff);
    display:flex;
    align-items:center;
    justify-content:center;
    box-shadow:0 30px 70px rgba(8,126,165,.2);
}

.bottle{
    width:170px;
    height:350px;
    border-radius:35px 35px 55px 55px;
    background:linear-gradient(
        90deg,
        #bcefff,
        #ffffff,
        #b5edff
    );
    position:relative;
    box-shadow:
        10px 20px 35px rgba(8,126,165,.18),
        inset -12px 0 25px rgba(70,190,230,.15);
}

.cap{
    position:absolute;
    top:-25px;
    left:40px;
    width:90px;
    height:35px;
    border-radius:10px;
    background:#087ea5;
}

.label{
    position:absolute;
    top:120px;
    left:10px;
    right:10px;
    padding:28px 5px;
    background:#087ea5;
    color:white;
    text-align:center;
    border-radius:8px;
}

.label strong{
    font-size:22px;
    letter-spacing:2px;
}

.label small{
    display:block;
    margin-top:8px;
    letter-spacing:2px;
}

/* SECTIONS */
.section{
    padding:85px 7%;
}

.center{
    text-align:center;
}

.center h2{
    font-size:42px;
    margin-bottom:15px;
}

.muted{
    color:#6b828c;
    line-height:1.7;
}

/* PRODUCTS */
.products{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:28px;
    max-width:900px;
    margin:45px auto 0;
}

.card{
    background:white;
    padding:35px;
    border-radius:28px;
    display:flex;
    justify-content:space-between;
    align-items:center;
    gap:20px;
    border:1px solid #d9eef5;
    box-shadow:0 15px 45px rgba(8,126,165,.10);
}

.card h3{
    font-size:28px;
    margin-bottom:8px;
}

.price{
    font-size:38px;
    font-weight:900;
    color:#087ea5;
}

/* ABOUT */
.about{
    background:#062f40;
    color:white;
    text-align:center;
}

.about .eyebrow{
    color:#55c8e8;
}

.about h2{
    font-size:42px;
    margin-bottom:20px;
}

.about p{
    max-width:750px;
    margin:auto;
    color:#c9e4ec;
    font-size:18px;
    line-height:1.8;
}

/* CONTACT */
.contact h2{
    margin-bottom:15px;
}

/* FOOTER */
footer{
    background:#042530;
    color:#b9d4dc;
    text-align:center;
    padding:30px;
}

/* MOBILE */
@media(max-width:700px){

    nav{
        padding:20px 5%;
    }

    nav a{
        display:none;
    }

    .hero{
        flex-direction:column;
        text-align:center;
        padding:55px 6%;
    }

    .hero p{
        margin:auto;
    }

    .hero h1{
        font-size:60px;
    }

    .bottle-area{
        width:300px;
        height:390px;
    }

    .bottle{
        transform:scale(.9);
    }

    .products{
        grid-template-columns:1fr;
    }

    .card{
        padding:28px;
    }

    .center h2,
    .about h2{
        font-size:34px;
    }
}
</style>
</head>

<body>

<!-- NAVIGATION -->
<nav>

    <div class="logo">
        <span>7</span>OCEANS
    </div>

    <div>
        <a href="#products">Products</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </div>

</nav>


<!-- HERO -->
<header class="hero">

    <div class="hero-text">

        <div class="eyebrow">
            PURE • FRESH • RELIABLE
        </div>

        <h1>
            Water,<br>
            refined.
        </h1>

        <p>
            Premium drinking water made for everyday moments.
            Clean taste, elegant presentation and the
            7OCEANS standard.
        </p>

        <a href="#products" class="btn">
            Explore Products
        </a>

    </div>


    <!-- BOTTLE -->
    <div class="bottle-area">

        <div class="bottle">

            <div class="cap"></div>

            <div class="label">

                <strong>
                    7OCEANS
                </strong>

                <small>
                    PREMIUM WATER
                </small>

            </div>

        </div>

    </div>

</header>


<!-- PRODUCTS -->
<section class="section" id="products">

    <div class="center">

        <div class="eyebrow">
            OUR PRODUCTS
        </div>

        <h2>
            Simple. Pure. Refreshing.
        </h2>

        <p class="muted">
            Choose the size that fits your day.
        </p>

    </div>


    <div class="products">

        <!-- 1 LITRE -->
        <div class="card">

            <div>
                <h3>
                    1 Litre
                </h3>

                <p class="muted">
                    Premium drinking water
                </p>
            </div>

            <div class="price">
                ₹20
            </div>

        </div>


        <!-- 500 ML -->
        <div class="card">

            <div>
                <h3>
                    500 ml
                </h3>

                <p class="muted">
                    Premium drinking water
                </p>
            </div>

            <div class="price">
                ₹10
            </div>

        </div>

    </div>

</section>


<!-- ABOUT -->
<section class="section about" id="about">

    <div class="eyebrow">
        THE 7OCEANS STANDARD
    </div>

    <h2>
        Clean. Fresh. Reliable.
    </h2>

    <p>
        7OCEANS brings a premium feel to everyday drinking water,
        with a focus on freshness, quality and a clean modern identity.
    </p>

</section>


<!-- CONTACT -->
<section class="section center contact" id="contact">

    <div class="eyebrow">
        LET'S CONNECT
    </div>

    <h2>
        Choose 7OCEANS.
    </h2>

    <p class="muted">
        Premium drinking water for everyday life.
    </p>

</section>


<!-- FOOTER -->
<footer>

    © 2026 7OCEANS. All rights reserved.

</footer>

</body>
</html>
