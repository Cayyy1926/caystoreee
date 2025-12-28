<meta name='viewport' content='width=device-width, initial-scale=1'/><!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CAYSTORE - Celana Levis Pria & Wanita</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #ffffff;
            color: #001f3f;
            line-height: 1.6;
        }
        header {
            background-color: #001f3f;
            color: #ffffff;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2em;
        }
        .btn {
            display: inline-block;
            background-color: #ffffff;
            color: #001f3f;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            margin-top: 10px;
        }
        .btn:hover {
            background-color: #e0e0e0;
        }
        section {
            padding: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .product-card {
            background-color: #f9f9f9;
            border: 1px solid #ddd;
            border-radius: 5px;
            padding: 15px;
            margin: 10px;
            width: 300px;
            text-align: center;
        }
        .product-card h3 {
            margin-top: 0;
        }
        .features {
            background-color: #f0f0f0;
        }
        .features ul {
            list-style: none;
            padding: 0;
        }
        .features li {
            padding: 10px 0;
        }
        .testimonials {
            background-color: #ffffff;
        }
        .testimonial {
            margin: 20px 0;
            padding: 10px;
            border-left: 5px solid #001f3f;
        }
        .cta {
            background-color: #001f3f;
            color: #ffffff;
            text-align: center;
            padding: 40px 20px;
        }
        .cta .btn {
            margin: 10px;
        }
        footer {
            background-color: #001f3f;
            color: #ffffff;
            text-align: center;
            padding: 10px;
        }
        @media (max-width: 768px) {
            .products {
                flex-direction: column;
                align-items: center;
            }
            .product-card {
                width: 90%;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>CAYSTORE</h1>
        <p>Celana Levis Pria & Wanita Berkualitas Tinggi</p>
        <a href="https://shopee.co.id/caystore" class="btn">Beli di Shopee</a>
    </header>

    <section class="products">
        <div class="product-card">
            <h3>Levis Slim Fit</h3>
            <p>Celana jeans slim fit yang nyaman untuk pria dan wanita, cocok untuk gaya kasual sehari-hari.</p>
            <p><strong>Harga mulai: Rp 350.000</strong></p>
            <a href="https://shopee.co.id/caystore/slim-fit" class="btn">Beli di Shopee</a>
        </div>
        <div class="product-card">
            <h3>Levis Straight Fit</h3>
            <p>Celana jeans straight fit klasik dengan bahan tahan lama, ideal untuk pria dan wanita.</p>
            <p><strong>Harga mulai: Rp 400.000</strong></p>
            <a href="https://shopee.co.id/caystore/straight-fit" class="btn">Beli di Shopee</a>
        </div>
        <div class="product-card">
            <h3>Levis Skinny Fit</h3>
            <p>Celana jeans skinny fit modern yang pas di tubuh, tersedia untuk pria dan wanita.</p>
            <p><strong>Harga mulai: Rp 380.000</strong></p>
            <a href="https://shopee.co.id/caystore/skinny-fit" class="btn">Beli di Shopee</a>
        </div>
    </section>

    <section class="features">
        <h2>Keunggulan CAYSTORE</h2>
        <ul>
            <li><strong>Kualitas Terbaik:</strong> Menggunakan bahan denim asli Levis yang tahan lama.</li>
            <li><strong>Harga Terjangkau:</strong> Harga kompetitif dengan diskon menarik di Shopee.</li>
            <li><strong>Pengiriman Cepat:</strong> Kirim ke seluruh Indonesia dengan jasa pengiriman terpercaya.</li>
            <li><strong>Garansi:</strong> Kepuasan pelanggan diutamakan, dengan garansi produk.</li>
        </ul>
    </section>

    <section class="testimonials">
        <h2>Testimoni Pelanggan</h2>
        <div class="testimonial">
            <p>"Celana Levis dari CAYSTORE sangat nyaman dan berkualitas. Sudah beli beberapa kali!" - Andi, Jakarta</p>
        </div>
        <div class="testimonial">
            <p>"Harga murah tapi kualitas top. Pengiriman juga cepat. Recommended!" - Siti, Surabaya</p>
        </div>
        <div class="testimonial">
            <p>"Variasi modelnya banyak, cocok untuk pria dan wanita. Suka banget!" - Budi, Bandung</p>
        </div>
    </section>

    <section class="cta">
        <h2>Siap Membeli Celana Levis Impian Anda?</h2>
        <p>Jangan ragu, beli sekarang di Shopee atau hubungi kami via WhatsApp untuk informasi lebih lanjut!</p>
        <a href="https://shopee.co.id/caystore" class="btn">Beli di Shopee</a>
        <a href="https://wa.me/6281234567890" class="btn">Hubungi WhatsApp</a>
    </section>

    <footer>
        <p>&copy; 2023 CAYSTORE. Semua hak dilindungi.</p>
    </footer>
</body>
</html>
