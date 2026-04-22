<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PT. Pilar Cakrawala Samudera - Logistics & Export Import</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Poppins', sans-serif; }
        .hero-section {
            background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('https://images.unsplash.com/photo-1586528116311-ad8dd3c8310d?auto=format&fit=crop&q=80&w=2000');
            background-size: cover;
            background-position: center;
            color: white;
            padding: 150px 0;
            text-align: center;
        }
        .navbar { background-color: #004a99; }
        .section-title { color: #004a99; font-weight: 700; margin-bottom: 30px; }
        .card { border: none; box-shadow: 0 4px 15px rgba(0,0,0,0.1); transition: 0.3s; }
        .card:hover { transform: translateY(-10px); }
        footer { background: #333; color: white; padding: 40px 0; }
    </style>
</head>
<body>

    <nav class="navbar navbar-expand-lg navbar-dark sticky-top">
        <div class="container">
            <a class="navbar-brand fw-bold" href="#">PT. PILAR</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#about">Tentang Kami</a></li>
                    <li class="nav-item"><a class="nav-link" href="#services">Layanan</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Kontak</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <header class="hero-section">
        <div class="container">
            <h1 class="display-3 fw-bold">Connecting the World</h1>
            <p class="lead">Moving Your Business Across Borders</p>
            <a href="#about" class="btn btn-primary btn-lg mt-3">Pelajari Lebih Lanjut</a>
        </div>
    </header>

    <section id="about" class="py-5">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-md-6">
                    <h2 class="section-title">Tentang Perusahaan</h2>
                    <p>PT. Pilar Cakrawala Samudera adalah perusahaan Ekspor Impor yang dinamis dan inovatif, berkomitmen untuk memberikan layanan berkualitas internasional.</p>
                    <p>Kami menyediakan solusi logistik komprehensif melalui transportasi udara, laut, dan darat dengan rekam jejak yang terbukti.</p>
                </div>
                <div class="col-md-6 text-center">
                    <div class="p-4 bg-light rounded shadow-sm">
                        <h4 class="text-primary">Visi Kami</h4>
                        <p>Menjadi perusahaan logistik terdepan di Asia Tenggara yang dikenal karena inovasi dan efisiensi.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="services" class="py-5 bg-light">
        <div class="container text-center">
            <h2 class="section-title">Layanan Kami</h2>
            <div class="row g-4 mt-2">
                <div class="col-md-4">
                    <div class="card h-100 p-4">
                        <h3>Air Freight</h3>
                        <p>Transportasi udara super cepat dan andal untuk kargo bernilai tinggi.</p>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card h-100 p-4">
                        <h3>Sea Freight</h3>
                        <p>Pengiriman jumlah besar antarpulau atau antarnegara melalui jalur laut.</p>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card h-100 p-4">
                        <h3>Land Trucking</h3>
                        <p>Layanan angkutan darat yang menjangkau jalur lintas tetangga.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="py-5">
        <div class="container">
            <h2 class="section-title text-center">Kontak Kami</h2>
            <div class="row mt-4">
                <div class="col-md-6">
                    <h5>Head Office (Batam)</h5>
                    <p>Grand Permata Bandara Blok B No 17</p>
                    <p>Email: pilarpcs79@gmail.com</p>
                </div>
                <div class="col-md-6">
                    <div class="card p-4">
                        <form>
                            <div class="mb-3">
                                <input type="text" class="form-control" placeholder="Nama Anda">
                            </div>
                            <div class="mb-3">
                                <textarea class="form-control" rows="3" placeholder="Pesan"></textarea>
                            </div>
                            <button type="submit" class="btn btn-primary w-100">Kirim Pesan</button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <footer>
        <div class="container text-center">
            <p>&copy; 2026 PT. Pilar Cakrawala Samudera. All Rights Reserved.</p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
