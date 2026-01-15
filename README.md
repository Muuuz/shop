<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Example Shop</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        * {
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            margin: 0;
            background: #e08a3a;
        }
        .header {
            background:  #332f2f;
            color: rgb(240, 184, 101);
            text-align: center;
            padding: 20px;
            font-size: 40px;
            font-weight: bold;
        }
        .nav {
            background: rgb(240, 184, 101);
            padding: 10px;
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            gap: 10px;
        }

        .nav button {
            background: rgb(245, 227, 227);
            border: none;
            color: black;
            padding: 10px 20px;
            border-radius: 20px;
            cursor: pointer;
            font-size: 16px;
        }

        .nav input {
            margin-left: auto;
            padding: 8px 15px;
            border-radius: 20px;
            border: none;
            font-size: 16px;
        }
        .content {
            padding: 20px;
        }

        h2 {
            margin-bottom: 20px;
        }

        .section-title {
            font-size: 36px;
            font-weight: bold;
            margin: 30px 0;
        }
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 30px;
        }

        .card {
    background: white;
    border-radius: 24px;
    padding: 15px;
    transition: transform 0.25s ease, box-shadow 0.25s ease;
}
 
.name {
    margin-top: 10px;
    font-size: 17px;
    font-weight: 600;
    text-align: center;
}
        .card {
    transition: transform 0.25s ease, box-shadow 0.25s ease;
}

.card:hover {
    transform: translateY(-8px);
    box-shadow: 0 15px 30px rgba(0,0,0,0.2);
}

.img-box img {
    transition: transform 0.3s ease;
}
.img-box {
    height: 140px;
    border-radius: 20px;
    overflow: hidden;
}

.card:hover .img-box img {
    transform: scale(1.08);
}
.card:hover {
    transform: translateY(-6px);
    box-shadow: 0 18px 35px rgba(0,0,0,0.18);
}


        .img-box {
            background: #00a8e8;
            height: 140px;
            border-radius: 30px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 24px;
        }
        .img-box img {
            width: 100%;
            height: 100%;
            object-fit: cover;      
            border-radius: 30px;
        }

        .name {
            margin-top: 10px;
            font-size: 18px;
        }
        .footer {
            background: #888;
            text-align: center;
            padding: 10px;
            margin-top: 40px;
            color: black;
        }
    </style>
</head>

<body>

    <div class="header">Shop</div>

    <div class="nav">
        <button>Home</button>
        <button>Drink</button>
        <button>Ramen</button>
        <button>Soup</button>
        <button>Snack</button>
        <input type="text" placeholder="search ">
    </div>

    <div class="content">
        <h2>Most popular product</h2>

        <div class="grid">
            <div class="card">
                <div class="img-box">
    <img src="d:\c++\html\shop\image\download.jpg" alt="ramen">
</div>
                <div class="name">Spicy Ramen with sausage </div>
            </div>

            <div class="card">
                <div class="img-box">
    <img src="d:\c++\html\shop\image\frend png.jpg" >
</div>
                <div class="name">Fried Rice</div>
            </div>

            <div class="card">
                <div class="img-box">
    <img src="d:\c++\html\shop\image\Best Keema Samosa Recipe (Patti Samosa) - Cubes N Juliennes (1).jpg" alt="Snack">
</div>
                <div class="name">Patti Samosa</div>
            </div>
        </div>

        <div class="section-title">Eazy take away</div>

        <div class="grid">
            <div class="card">
                <div class="img-box">
    <img src="d:\c++\html\shop\image\_☆save & follow☆_.jpg" >
</div>
                <div class="name">Spicy Ramen with Egg</div>
            </div>

            <div class="card">
                <div class="img-box">
    <img src="d:\c++\html\shop\image\yummm! 😘😘😘😋😋.jpg" >
</div>
                <div class="name">Spicy Ramen with pork cutlet</div>
            </div>

            <div class="card">
                <div class="img-box">
    <img src="d:\c++\html\shop\image\Tom yum kung 🥘🦐.jpg" >
</div>
                <div class="name">Tom yum</div>
            </div>

            <div class="card">
                <div class="img-box">
    <img src="d:\c++\html\shop\image\Veg Spring Rolls (Deep Fried and Air Fried).jpg" >
</div>
                <div class="name">Veg Spring Rolls</div>
            </div>

            <div class="card">
                <div class="img-box">
    <img src="d:\c++\html\shop\image\Starbucks Double Chocolate Chip Frappuccino.jpg" >
</div>
                <div class="name">Chocolate Chip Frappuccino</div>
            </div>

            <div class="card">
                <div class="img-box">
    <img src="d:\c++\html\shop\image\download (2).jpg" >
</div>
                <div class="name">Ice Water</div>
            </div>
        </div>
    </div>

    <div class="footer"> © 2026 Mutestsite. All rights reserved.</div>

</body>
</html>

