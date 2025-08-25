# daffa-dan-fakhri
Jual komputer 
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Fakhri Aristya dan Daffa Zachary R| Toko Online</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>Fakhri Aristya</h1>
    <nav>
      <a href="#">Beranda</a>
      <a href="#">Produk</a>
      <a href="#">Kontak</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Selamat datang di Toko Online Fakhri Aristya</h2>
    <p>Temukan produk terbaik dengan harga terjangkau.</p>
  </section>

  <section class="products">
    <h2>Produk Unggulan</h2>
    <div class="product-list">
      <div class="product">
        <img src="https://via.placeholder.com/200" alt="Produk 1" />
        <h3>Produk 1</h3>
        <p>Rp100.000</p>
        <button onclick="beli('Produk 1')">Beli</button>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/200" alt="Produk 2" />
        <h3>Produk 2</h3>
        <p>Rp150.000</p>
        <button onclick="beli('Produk 2')">Beli</button>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/200" alt="Produk 3" />
        <h3>Produk 3</h3>
        <p>Rp200.000</p>
        <button onclick="beli('Produk 3')">Beli</button>
      </div>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Fakhri Aristya. All rights reserved.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

header {
  background-color: #0f4c75;
  color: white;
  padding: 20px;
  text-align: center;
}

nav a {
  margin: 0 15px;
  color: white;
  text-decoration: none;
}

.hero {
  background-color: #bbe1fa;
  text-align: center;
  padding: 50px 20px;
}

.products {
  padding: 40px 20px;
  text-align: center;
}

.product-list {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 30px;
}

.product {
  border: 1px solid #ccc;
  padding: 15px;
  width: 200px;
  background-color: white;
  border-radius: 5px;
}

.product img {
  max-width: 100%;
}

button {
  background-color: #0f4c75;
  color: white;
  border: none;
  padding: 10px;
  margin-top: 10px;
  cursor: pointer;
}

button:hover {
  background-color: #3282b8;
}

footer {
  background-color: #1b262c;
  color: white;
  text-align: center;
  padding: 15px;
  margin-top: 30px;
}
function beli(Komputer) {
  alert("Anda memilih: "  Komputer + ". Fitur pembelian belum tersedia.");
}
