# lab6web

### Nama: M. Rizqy Al Rasyd
### Nim : 312410424
### Kelas : TI.24.A3

## REFACTOR LAYOUT PRAKTIKUM 4
# Code:
```    <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Layout Sederhana (Bootstrap)</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
  <div class="container my-4">
    <!-- Header -->
    <header class="text-center mb-4">
      <h1 class="fw-bold">Layout Sederhana</h1>
    </header>

    <!-- Navigation -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-primary mb-4 rounded">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">Home</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div id="navbarNav" class="collapse navbar-collapse">
          <ul class="navbar-nav me-auto">
            <li class="nav-item"><a href="lab4_layout.html" class="nav-link active">Home</a></li>
            <li class="nav-item"><a href="artikel.html" class="nav-link">Artikel</a></li>
            <li class="nav-item"><a href="about.html" class="nav-link">About</a></li>
            <li class="nav-item"><a href="kontak.html" class="nav-link">Kontak</a></li>
          </ul>
        </div>
      </div>
    </nav>

    <!-- Hero Section -->
    <section class="p-5 mb-4 bg-light rounded-3 text-center">
      <h1 class="display-5 fw-bold">Hello World!</h1>
      <p class="lead">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Placeat provident ut animi enim consectetur.</p>
      <a href="home.html" class="btn btn-primary btn-lg">Learn more &raquo;</a>
    </section>

    <!-- Main Content -->
    <div class="row">
      <main class="col-md-8">
        <!-- 3 Box -->
        <div class="row text-center mb-4">
          <div class="col-md-4 mb-3">
            <div class="card border-0 shadow-sm h-100">
              <img src="https://dummyimage.com/120/db7d25/fff.png" class="rounded-circle mx-auto mt-3" width="120" alt="">
              <div class="card-body">
                <h5 class="card-title">Heading</h5>
                <p class="card-text">Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
                <a href="#" class="btn btn-outline-primary">View Detail</a>
              </div>
            </div>
          </div>
          <div class="col-md-4 mb-3">
            <div class="card border-0 shadow-sm h-100">
              <img src="https://dummyimage.com/120/3e73e6/fff.png" class="rounded-circle mx-auto mt-3" width="120" alt="">
              <div class="card-body">
                <h5 class="card-title">Heading</h5>
                <p class="card-text">Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
                <a href="#" class="btn btn-outline-primary">View Detail</a>
              </div>
            </div>
          </div>
          <div class="col-md-4 mb-3">
            <div class="card border-0 shadow-sm h-100">
              <img src="https://dummyimage.com/120/71e6d4/fff.png" class="rounded-circle mx-auto mt-3" width="120" alt="">
              <div class="card-body">
                <h5 class="card-title">Heading</h5>
                <p class="card-text">Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
                <a href="#" class="btn btn-outline-primary">View Detail</a>
              </div>
            </div>
          </div>
        </div>

        <hr>

        <!-- Artikel 1 -->
        <article class="mb-4">
          <div class="row align-items-center">
            <div class="col-md-4">
              <img src="https://dummyimage.com/150/7b8a70/fff.png" class="img-fluid rounded" alt="">
            </div>
            <div class="col-md-8">
              <h2>First Featurette heading.</h2>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dignissimos odit porro molestiae deleniti perspiciatis veritatis minima ipsum.</p>
            </div>
          </div>
        </article>

        <hr>

        <!-- Artikel 2 -->
        <article class="mb-4">
          <div class="row align-items-center">
            <div class="col-md-8">
              <h2>Second Featurette heading.</h2>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dignissimos odit porro molestiae deleniti perspiciatis veritatis minima ipsum.</p>
            </div>
            <div class="col-md-4">
              <img src="https://dummyimage.com/150/7b8a70/fff.png" class="img-fluid rounded" alt="">
            </div>
          </div>
        </article>
      </main>

      <!-- Sidebar -->
      <aside class="col-md-4">
        <div class="card mb-4">
          <div class="card-header bg-primary text-white">Widget Header</div>
          <ul class="list-group list-group-flush">
            <li class="list-group-item"><a href="#">Widget Link</a></li>
            <li class="list-group-item"><a href="#">Widget Link</a></li>
            <li class="list-group-item"><a href="#">Widget Link</a></li>
            <li class="list-group-item"><a href="#">Widget Link</a></li>
            <li class="list-group-item"><a href="#">Widget Link</a></li>
          </ul>
        </div>

        <div class="card">
          <div class="card-header bg-primary text-white">Widget Text</div>
          <div class="card-body">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Culpa, adipisci. Ab odio nobis mollitia nisi alias sequi ipsum.</p>
          </div>
        </div>
      </aside>
    </div>

    <!-- Footer -->
    <footer class="bg-dark text-white text-center py-3 mt-4 rounded">
      <p class="mb-0">&copy; 2021 - Universitas Pelita Bangsa</p>
    </footer>
  </div>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

# Hasil:
![gambar](layout.png)

## REFACTOR FORM PRAKTIKUM 5 BUTTON
# Code:
``` <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Form Button (Bootstrap)</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <link rel="stylesheet" href="button.css">
  <style>
    body {
      transition: background-color 0.5s, color 0.5s;
    }
  </style>
</head>
<body class="text-center py-5">

  <div class="container">
    <h1 class="mb-4 fw-bold">Form Ubah Warna</h1>

    <div class="card shadow-sm mx-auto" style="max-width: 400px;">
      <div class="card-body">
        <form>
          <div class="d-grid gap-2 mb-3">
            <button type="button" class="btn btn-success" onclick="ubahWarnaLB('green')">Latar Belakang Hijau</button>
            <button type="button" class="btn btn-light border" onclick="ubahWarnaLB('white')">Latar Belakang Putih</button>
            <button type="button" class="btn btn-warning text-dark" onclick="ubahWarnaLD('yellow')">Teks Kuning</button>
            <button type="button" class="btn btn-primary" onclick="ubahWarnaLD('blue')">Teks Biru</button>
          </div>
        </form>
      </div>
    </div>

    <p class="mt-4 text-muted" id="modified"></p>
  </div>

  <script>
    function ubahWarnaLB(warna) {
      document.body.style.backgroundColor = warna;
    }

    function ubahWarnaLD(warna) {
      document.body.style.color = warna;
    }

    document.getElementById("modified").innerText =
      "Dimodifikasi terakhir pada " + document.lastModified;
  </script>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

# Hasil:
![gambar](button.png)

## PORTOFOLIO SEDERHANA
# Code:
``` <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Form Button (Bootstrap)</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <link rel="stylesheet" href="button.css">
  <style>
    body {
      transition: background-color 0.5s, color 0.5s;
    }
  </style>
</head>
<body class="text-center py-5">

  <div class="container">
    <h1 class="mb-4 fw-bold">Form Ubah Warna</h1>

    <div class="card shadow-sm mx-auto" style="max-width: 400px;">
      <div class="card-body">
        <form>
          <div class="d-grid gap-2 mb-3">
            <button type="button" class="btn btn-success" onclick="ubahWarnaLB('green')">Latar Belakang Hijau</button>
            <button type="button" class="btn btn-light border" onclick="ubahWarnaLB('white')">Latar Belakang Putih</button>
            <button type="button" class="btn btn-warning text-dark" onclick="ubahWarnaLD('yellow')">Teks Kuning</button>
            <button type="button" class="btn btn-primary" onclick="ubahWarnaLD('blue')">Teks Biru</button>
          </div>
        </form>
      </div>
    </div>

    <p class="mt-4 text-muted" id="modified"></p>
  </div>

  <script>
    function ubahWarnaLB(warna) {
      document.body.style.backgroundColor = warna;
    }

    function ubahWarnaLD(warna) {
      document.body.style.color = warna;
    }

    document.getElementById("modified").innerText =
      "Dimodifikasi terakhir pada " + document.lastModified;
  </script>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

# Hasil:
![gambar](port.png)
