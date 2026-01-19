<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Migi Setyo Sugiarto Adi - Portfolio</title>
    <style>
        :root {
            --primary-color: #2c3e50;
            --secondary-color: #34495e;
            --accent-color: #3498db;
            --text-color: #333;
            --bg-color: #f4f7f6;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: var(--text-color);
            background-color: var(--bg-color);
            margin: 0;
            padding: 0;
        }

        .container {
            max-width: 900px;
            margin: 40px auto;
            background: #fff;
            padding: 50px;
            box-shadow: 0 0 20px rgba(0,0,0,0.1);
            position: relative;
        }

        header {
            border-bottom: 2px solid var(--primary-color);
            padding-bottom: 20px;
            margin-bottom: 30px;
        }

        .download-btn {
            position: absolute;
            top: 50px;
            right: 50px;
            background-color: var(--accent-color);
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            transition: background 0.3s;
        }

        .download-btn:hover {
            background-color: #2980b9;
        }

        h1 {
            margin: 0;
            color: var(--primary-color);
            font-size: 2.5em;
            text-transform: uppercase;
        }

        .contact-info {
            margin-top: 10px;
            font-size: 0.9em;
            color: #666;
        }

        h2 {
            color: var(--primary-color);
            border-left: 5px solid var(--accent-color);
            padding-left: 15px;
            margin-top: 40px;
            text-transform: uppercase;
            font-size: 1.3em;
        }

        .job-title {
            font-weight: bold;
            font-size: 1.1em;
            display: flex;
            justify-content: space-between;
        }

        .company-info {
            font-style: italic;
            color: var(--secondary-color);
            margin-bottom: 5px;
        }

        .location {
            font-size: 0.85em;
            color: #7f8c8d;
            margin-bottom: 10px;
        }

        .experience-item {
            margin-bottom: 25px;
        }

        ul {
            padding-left: 20px;
        }

        .skills-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 10px;
        }

        .skill-item {
            background: #ecf0f1;
            padding: 8px 15px;
            border-radius: 4px;
            font-size: 0.9em;
        }

        footer {
            text-align: center;
            margin-top: 50px;
            font-size: 0.8em;
            color: #95a5a6;
        }

        @media (max-width: 768px) {
            .container { padding: 20px; margin: 10px; }
            .download-btn { position: static; display: block; text-align: center; margin-bottom: 20px; }
            .skills-grid { grid-template-columns: 1fr; }
            .job-title { flex-direction: column; }
        }
    </style>
</head>
<body>

    <div class="container">
        <a href="Migi_Setyo_Sugiarto_Adi.pdf" class="download-btn" download>Download PDF CV</a>

        <header>
            <h1>MIGI SETYO SUGIARTO ADI</h1>
            <div class="contact-info">
                migisetyosa@gmail.com | 08112683668 | Kota Semarang | Indonesia
            </div>
        </header>

        <section id="summary">
            <h2>SUMMARY</h2>
            <p>Profesional Food & Beverage dengan pengalaman lebih dari 5 tahun di bidang operasional restoran, bar, dan manajemen toko. Memiliki latar belakang sebagai Barista, Bartender, Admin Purchasing, hingga Store Manager. Terbukti mampu mengelola inventory, menekan biaya operasional, menjaga standar layanan pelanggan, serta bekerja efektif lintas tim. Terbiasa bekerja dengan SOP, target operasional, dan sistem manajemen berbasis data (Microsoft Excel).</p>
        </section>

        <section id="objective">
            <h2>OBJECTIVE</h2>
            <p>Mencari posisi di bidang Food & Beverage Operations / Store Management / Purchasing untuk berkontribusi secara langsung dalam peningkatan efisiensi operasional, kualitas layanan pelanggan, serta pertumbuhan bisnis perusahaan.</p>
        </section>

        <section id="experience">
            <h2>PROFESSIONAL EXPERIENCE</h2>

            <div class="experience-item">
                <div class="job-title"><span>Bartender</span> <span>Februari 2025 - November 2025</span></div>
                <div class="company-info">Suji Suan Cai Yu DP Mall Semarang</div>
                <div class="location">DP Mall Semarang L2.15, Sekayu, Semarang Tengah</div>
                <ul>
                    <li>Menyiapkan dan menyajikan minuman non-alkohol sesuai SOP perusahaan.</li>
                    <li>Mengelola stok bahan baku dan berhasil mengurangi waste hingga ±15%.</li>
                    <li>Menjaga kebersihan area bar dengan tingkat kepatuhan SOP 100%.</li>
                </ul>
            </div>

            <div class="experience-item">
                <div class="job-title"><span>Barista</span> <span>September 2024 - Januari 2025</span></div>
                <div class="company-info">Cotti Coffee Pollux Paragon Semarang</div>
                <div class="location">Jl. Pemuda No.118, Sekayu, Kec. Semarang Tengah</div>
                <ul>
                    <li>Menyajikan berbagai minuman kopi dan teh, menjaga kualitas dan kebersihan area kerja.</li>
                    <li>Mengelola pesanan dengan efisien dan menciptakan suasana ramah.</li>
                    <li>Mengelola stok bahan baku dan pemeliharaan peralatan.</li>
                </ul>
            </div>

            <div class="experience-item">
                <div class="job-title"><span>Admin Purchasing</span> <span>Juli 2023 - Agustus 2024</span></div>
                <div class="company-info">TOKO KOPI DJUARA</div>
                <div class="location">Jl. Pleburan Barat No.10, Semarang Selatan </div>
                <ul>
                    <li>Mengelola proses pembelian, negosiasi dengan pemasok, serta pengawasan inventaris.</li>
                    <li>Membuat laporan pembelian dan stock menggunakan Microsoft Excel.</li>
                    <li>Membantu efisiensi biaya operasional melalui kontrol pembelian rutin.</li>
                </ul>
            </div>

            <div class="experience-item">
                <div class="job-title"><span>Admin Purchasing</span> <span>Januari 2022 - Agustus 2024</span></div>
                <div class="company-info">LAIV.IDN </div>
                <div class="location">Jl. Pleburan Barat No.33, Semarang Selatan </div>
                <ul>
                    <li>Bertanggung jawab untuk pemilihan vendor, negosiasi harga, dan penyusunan kontrak.</li>
                    <li>Memastikan kualitas produk dan ketepatan waktu pengiriman.</li>
                </ul>
            </div>

            <div class="experience-item">
                <div class="job-title"><span>Store Manager</span> <span>Juni 2021 - Agustus 2024</span></div>
                <div class="company-info">KOPI REJEKI </div>
                <div class="location">Jl. Erlangga Barat 7 No.12, Pleburan </div>
                <ul>
                    <li>Mengelola operasional harian toko, pengawasan staf, dan target penjualan.</li>
                    <li>Menangani keluhan pelanggan dan melaksanakan strategi pemasaran.</li>
                </ul>
            </div>

            <div class="experience-item">
                <div class="job-title"><span>Barista</span> <span>Januari 2020 - Juni 2021</span></div>
                [cite_start]<div class="company-info">KOPI KENANGAN </div>
                <div class="location">DP Mall Semarang, Jl. Pemuda No.150 </div>
                <ul>
                    <li>Menyajikan minuman berkualitas tinggi dan mengoperasikan mesin espresso.</li>
                    <li>Mengelola stok bahan baku serta menjaga kebersihan area kerja.</li>
                </ul>
            </div>

            <div class="experience-item">
                <div class="job-title"><span>Captain Waiters</span> <span>Mei 2015 - Agustus 2017</span></div>
                <div class="company-info">KOENO KOENI CAFE & GALERY </div>
                <div class="location">Jl. Tabanan No.4, Tegalsari, Candisari </div>
                <ul>
                    <li>Memimpin tim pelayan untuk pelayanan berkualitas tinggi.</li>
                    <li>Koordinasi pesanan, pengaturan ruang makan, dan menangani keluhan pelanggan.</li>
                </ul>
            </div>
        </section>

        <section id="education">
            <h2>EDUCATION</h2>
            <div class="experience-item">
                <div class="job-title"><span>Tata Boga</span> <span>2012 - 2015</span></div>
                <div class="company-info">SMK NEGERI 6 SEMARANG </div>
                <p>Mempelajari teknik dasar dan lanjutan dalam memasak, pengolahan bahan makanan, serta presentasi hidangan. Praktik langsung dalam persiapan menu dan pengembangan resep.</p>
            </div>
        </section>

        <section id="certificates">
            <h2>COURSES AND CERTIFICATES</h2>
            <div class="experience-item">
                <div class="job-title"><span>Certificate of Competency Serving Food & Beverages</span> <span>2015</span></div>
                <div class="company-info">SMK 6 Semarang x Crown Plaza Hotel </div>
                <p>Memperoleh pengetahuan mendalam tentang praktik penyajian makanan dan standar kebersihan industri F&B.</p>
            </div>
        </section>

        <section id="skills">
            <h2>SKILLS</h2>
            <div class="skills-grid">
                <div class="skill-item">Cost Control & Inventory Management</div>
                <div class="skill-item">Restaurant & Store Operations</div>
                <div class="skill-item">Purchasing & Supplier Coordination</div>
                <div class="skill-item">Food Safety Management System</div>
                <div class="skill-item">Microsoft Excel (Reporting)</div>
                <div class="skill-item">Leadership & Teamwork</div>
                <div class="skill-item">Handle Complaint</div>
                <div class="skill-item">Problem Solving</div>
            </div>
        </section>

        <section id="languages">
            <h2>LANGUAGES</h2>
            <p><strong>Indonesia</strong> </p>
        </section>

        <footer>
            &copy; 2026 Migi Setyo Sugiarto Adi - Semarang, Indonesia
        </footer>
    </div>

</body>
</html>
