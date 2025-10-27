# Praktikum 6 : Web Framework
### Membuat Bootsrtap 
|                |                    |
| ------------------ | ------------------ |
|      _Nama_    | Dwi Okta Ramadhani |
|      _NIM_     |      312410056     |
|     _Kelas_    |      TI.24.A1      |
|  _Mata Kuliah_ | Bahasa Pemrograman Web 1 |

## Deskripsi
Praktikum ini bertujuan untuk mengenalkan konsep dasar Web Framework dalam pengembangan halaman web modern.
Melalui praktikum ini, saya belajar bagaimana menggunakan Bootstrap sebagai CSS Framework untuk membangun tampilan web yang menarik, responsif, dan terstruktur dengan mudah tanpa menulis banyak kode CSS secara manual.

Selain itu, saya juga mempelajari dasar penggunaan jQuery untuk menambahkan interaksi pada halaman web, seperti menampilkan pesan ketika tombol diklik atau memberikan efek perubahan gaya elemen secara dinamis. 

## Tujuan Praktikum                                                         
|                |                     
| ------------------ | 
| 1.Mengenal dan memahami konsep dasar Web Framework dalam pengembangan halaman web modern.	         |
| 2.Mengembangkan halaman web yang dinamis dengan memanfaatkan kombinasi HTML, CSS, Bootstrap, dan jQuery.|

## Langkah-Langkah Praktikum
**INPUT**
```
index.html : 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Layout Sederhana - Bootstrap</title>
  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Header -->
  <header class="bg-primary text-white text-center py-4 mb-3">
    <h1>Layout Sederhana</h1>
  </header>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark mb-4">
    <div class="container">
      <a class="navbar-brand" href="#">Home</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link active" href="home.html">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="artikel.html">Artikel</a></li>
          <li class="nav-item"><a class="nav-link" href="about.html">About</a></li>
          <li class="nav-item"><a class="nav-link" href="kontak.html">Kontak</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="container text-center my-4">
    <h1>Hello World!</h1>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem elit,
      iaculis in nisl volutpat, malesuada tincidunt arcu.</p>
    <a href="home.html" class="btn btn-primary btn-lg">Learn more &raquo;</a>
  </section>

  <!-- Main Content -->
  <div class="container my-5">
    <div class="row text-center mb-4">
      <div class="col-md-4 mb-3">
        <div class="card h-100">
          <img src="https://dummyimage.com/120/db7d25/fff.png" class="card-img-top rounded-circle mx-auto mt-3" style="width:120px;">
          <div class="card-body">
            <h5 class="card-title">Heading</h5>
            <p class="card-text">Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
            <a href="#" class="btn btn-outline-primary">View detail</a>
          </div>
        </div>
      </div>
      <div class="col-md-4 mb-3">
        <div class="card h-100">
          <img src="https://dummyimage.com/120/3e73e6/fff.png" class="card-img-top rounded-circle mx-auto mt-3" style="width:120px;">
          <div class="card-body">
            <h5 class="card-title">Heading</h5>
            <p class="card-text">Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
            <a href="#" class="btn btn-outline-primary">View detail</a>
          </div>
        </div>
      </div>
      <div class="col-md-4 mb-3">
        <div class="card h-100">
          <img src="https://dummyimage.com/120/71e6d4/fff.png" class="card-img-top rounded-circle mx-auto mt-3" style="width:120px;">
          <div class="card-body">
            <h5 class="card-title">Heading</h5>
            <p class="card-text">Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
            <a href="#" class="btn btn-outline-primary">View detail</a>
          </div>
        </div>
      </div>
    </div>

    <hr>

    <!-- Featurette -->
    <div class="row align-items-center my-5">
      <div class="col-md-7">
        <h2>First featurette heading.</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem elit,
          iaculis in nisl volutpat, malesuada tincidunt arcu.</p>
      </div>
      <div class="col-md-5 text-center">
        <img src="https://dummyimage.com/150/7b8a70/fff.png" class="img-fluid rounded">
      </div>
    </div>

    <hr>

    <div class="row align-items-center my-5 flex-md-row-reverse">
      <div class="col-md-7">
        <h2>Second featurette heading.</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem elit,
          iaculis in nisl volutpat, malesuada tincidunt arcu.</p>
      </div>
      <div class="col-md-5 text-center">
        <img src="https://dummyimage.com/150/7b8a70/fff.png" class="img-fluid rounded">
      </div>
    </div>

    <div class="row">
      <div class="col-md-4">
        <div class="p-3 bg-light rounded shadow-sm">
          <h3>Widget Header</h3>
          <ul class="list-unstyled">
            <li><a href="#">Widget Link</a></li>
            <li><a href="#">Widget Link</a></li>
            <li><a href="#">Widget Link</a></li>
            <li><a href="#">Widget Link</a></li>
            <li><a href="#">Widget Link</a></li>
          </ul>
        </div>
      </div>
      <div class="col-md-8">
        <div class="p-3 bg-light rounded shadow-sm">
          <h3>Widget Text</h3>
          <p>Vestibulum lorem elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla,
            vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc pretium ac.</p>
        </div>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-3 mt-5">
    <p>&copy; 2021 - Universitas Pelita Bangsa</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

style.css:
body {
    font-family: 'Open Sans', sans-serif;
    color: #5a5a5a;
  }
  
  header h1 {
    color: #b5b5b5;
  }
  
  .image-circle {
    border-radius: 50%;
  }
  
  /* Widget Style biar tetep mirip versi lama */
  .widget-box {
    border: 1px solid #eee;
    margin-bottom: 20px;
    border-radius: 8px;
  }
  .widget-box .title {
    padding: 10px 16px;
    background-color: #428bca;
    color: #fff;
    border-radius: 8px 8px 0 0;
  }
  .widget-box li a:hover {
    background-color: #eee;
  }
```

**OUTPUT**

<img width="1920" height="1128" alt="Cuplikan layar 2025-10-27 145935" src="https://github.com/user-attachments/assets/5a3e0b16-5940-42de-b388-e1de3ee0f84b" />


## Terima Kasih

