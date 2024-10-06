<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kedai Orange Menu</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }
        
        .header {
            background-color: #ff6600;
            padding: 20px;
            text-align: center;
            color: white;
        }
        
        .header h1 {
            margin: 0;
            font-size: 2.5rem;
        }

        .hero {
            background: url('https://pic.52112.com/2019/05/27/JPG-190527_396/TSkENwIRwF_small.jpg') center center no-repeat;
            background-size: cover;
            height: 400px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
        }
        
        .hero h2 {
            font-size: 3rem;
            background-color: rgba(0, 0, 0, 0.5);
            padding: 20px;
            border-radius: 10px;
        }

        .section {
            padding: 50px;
            text-align: center;
        }

        .section h2 {
            color: #ff6600;
            font-size: 2rem;
            margin-bottom: 20px;
        }

        .menu-cards {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 20px;
            justify-items: center;
        }

        .card {
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            text-align: center;
            padding: 20px;
            width: 100%;
        }

        .card h3 {
            font-size: 1.5rem;
            color: #ff6600;
            margin: 10px 0;
        }

        .card p {
            color: #555;
            font-size: 1rem;
            margin: 0;
        }

        .card .price {
            font-size: 1.2rem;
            font-weight: bold;
            color: #ff6600;
            margin-top: 10px;
        }

        .footer {
            background-color: #ff6600;
            color: white;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>
<body>

    <header class="header">
        <h1>Kedai Orange</h1>
    </header>

    <section class="hero">
        <h2>Mulai Hidup Sehat Dengan Minum Jus Tiap hari</h2>
    </section>

    <section class="section">
        <h2>Jus Buah</h2>
        <div class="menu-cards">

            <!-- JUS BUAH -->
            <div class="card">
                <h3>Leci</h3>
                <p class="price">10k</p>
            </div>

            <div class="card">
                <h3>Durian</h3>
                <p class="price">10k</p>
            </div>

            <div class="card">
                <h3>Alpukat</h3>
                <p class="price">9k</p>
            </div>

            <div class="card">
                <h3>Strawberry</h3>
                <p class="price">9k</p>
            </div>

            <div class="card">
                <h3>Anggur</h3>
                <p class="price">9k</p>
            </div>

            <div class="card">
                <h3>Mangga</h3>
                <p class="price">9k</p>
            </div>

            <div class="card">
                <h3>Sirsak</h3>
                <p class="price">9k</p>
            </div>

            <div class="card">
                <h3>Nangka</h3>
                <p class="price">9k</p>
            </div>

            <div class="card">
                <h3>Melon</h3>
                <p class="price">9k</p>
            </div>

            <div class="card">
                <h3>Pisang</h3>
                <p class="price">9k</p>
            </div>

            <div class="card">
                <h3>Jambu</h3>
                <p class="price">8k</p>
            </div>

            <div class="card">
                <h3>Wortel</h3>
                <p class="price">8k</p>
            </div>

            <div class="card">
                <h3>Tomat</h3>
                <p class="price">8k</p>
            </div>

            <div class="card">
                <h3>Buah Naga</h3>
                <p class="price">8k</p>
            </div>

        </div>
    </section>

    <section class="section">
        <h2>Makanan</h2>
        <div class="menu-cards">

            <!-- MAKANAN -->
            <div class="card">
                <h3>Indomie</h3>
                <p class="price">6k</p>
            </div>

            <div class="card">
                <h3>Indomie Telor</h3>
                <p class="price">8k</p>
            </div>

            <div class="card">
                <h3>Indomie Telor Nasi</h3>
                <p class="price">11k</p>
            </div>

            <div class="card">
                <h3>Kentang</h3>
                <p class="price">7k</p>
            </div>

            <div class="card">
                <h3>Sigor</h3>
                <p class="price">7k</p>
            </div>

            <div class="card">
                <h3>Tahu</h3>
                <p class="price">7k</p>
            </div>

            <div class="card">
                <h3>Tempe</h3>
                <p class="price">7k</p>
            </div>

            <div class="card">
                <h3>Jamur</h3>
                <p class="price">10k</p>
            </div>

        </div>
    </section>

    <section class="section">
        <h2>Milkshake</h2>
        <div class="menu-cards">

            <!-- MILKSHAKE -->
            <div class="card">
                <h3>Red Velvet</h3>
                <p class="price">10k</p>
            </div>

            <div class="card">
                <h3>Tiramisu</h3>
                <p class="price">10k</p>
            </div>

            <div class="card">
                <h3>Black Forest</h3>
                <p class="price">10k</p>
            </div>

            <div class="card">
                <h3>Taro</h3>
                <p class="price">10k</p>
            </div>

            <div class="card">
                <h3>Green Tea Matcha</h3>
                <p class="price">10k</p>
            </div>

            <div class="card">
                <h3>Hazelnut</h3>
                <p class="price">10k</p>
            </div>

            <div class="card">
                <h3>Vanilla</h3>
                <p class="price">10k</p>
            </div>

            <div class="card">
                <h3>Blueberry</h3>
                <p class="price">10k</p>
            </div>

            <div class="card">
                <h3>Coklat Karamel</h3>
                <p class="price">10k</p>
            </div>

        </div>
    </section>

    <section class="section">
        <h2>Minuman</h2>
        <div class="menu-cards">

            <!-- MINUMAN -->
            <div class="card">
                <h3>Kopi Susu</h3>
                <p class="price">6k</p>
            </div>

            <div class="card">
                <h3>Kopi Hitam</h3>
                <p class="price">6k</p>
            </div>

            <div class="card">
                <h3>Milo Es/Hot</h3>
                <p class="price">6k</p>
            </div>

            <div class="card">
                <h3>Es Susu</h3>
                <p class="price">6k</p>
            </div>

            <div class="card">
                <h3>Joshua</h3>
                <p class="price">10k</p>
            </div>

            <div class="card">
                <h3>Sosro</h3>
                <p class="price">5k</p>
            </div>

            <div class="card">
                <h3>Teh Es/Hot</h3>
                <p class="price">4k</p>
            </div>

            <div class="card">
                <h3>Lime Es/Hot</h3>
                <p class="price">8k</p>
            </div>

        </div>
    </section>

    <footer class="footer">
        <p>&copy; 2024 Kedai Orange. All rights reserved.</p>
    </footer>

</body>
</html>
