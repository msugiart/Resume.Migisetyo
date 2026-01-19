<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio - Migi Setyo Sugiarto Adi</title>
    <style>
        :root {
            --primary: #1e293b;
            --secondary: #334155;
            --accent: #2563eb;
            --bg: #f1f5f9;
            --white: #ffffff;
            --text-dark: #0f172a;
            --text-light: #64748b;
        }

        body {
            font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
            background-color: var(--bg);
            color: var(--text-dark);
            line-height: 1.6;
            margin: 0;
            padding: 0;
        }

        .container {
            max-width: 850px;
            margin: 40px auto;
            background: var(--white);
            padding: 50px;
            border-radius: 12px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.05);
            position: relative;
        }

        /* Tombol Download Kanan Atas */
        .download-btn {
            position: absolute;
            top: 40px;
            right: 50px;
            background-color: var(--accent);
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 6px;
            font-weight: 600;
            font-size: 14px;
            transition: 0.3s;
            box-shadow: 0 4px 6px rgba(37, 99, 235, 0.2);
        }

        .download-btn:hover {
            background-color: #1d4ed8;
            transform: translateY(-2px);
        }

        header {
            border-bottom: 2px solid #e2e8f0;
            padding-bottom: 25px;
            margin-bottom: 30px;
        }

        h1 {
            margin: 0;
            font-size: 28px;
            letter-spacing: -0.5px;
        }

        .contact-info {
            color: var(--text-light);
            font-size: 14px;
            margin-top: 8px;
        }

        h2 {
            font-size: 16px;
            text-transform: uppercase;
            letter-spacing: 1.5px;
            color: var(--accent);
            margin-top: 35px;
            border-bottom: 1px solid #e2e8f0;
            padding-bottom: 5px;
        }

        .summary {
            background: #f8fafc;
            padding: 20px;
            border-radius: 8px;
            font-size: 15px;
            color: var(--secondary);
        }

        .exp-item {
            margin-bottom: 25px;
        }

        .exp-header {
            display: flex;
            justify-content: space-between;
            font-weight: bold;
            color: var(--text-dark);
        }

        .company {
            color: var(--secondary);
            font-weight: 600;
            font-style: italic;
        }

        .location {
            font-size: 12px;
            color: var(--text-light);
            margin-bottom: 8px;
        }

        ul {
            padding-left: 20px;
            margin-top: 5px;
        }

        li {
            font-size: 14.5px;
            margin-bottom: 4px;
        }

        /* Desain Visual Skills */
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            gap: 10px;
            margin-top: 15px;
        }

        .skill-tag {
            background: #eff6ff;
            color: #1e40af;
            padding: 10px;
            border-radius: 6px;
            font-size: 13px;
            font-weight: 600;
            text-align: center;
            border: 1px solid #dbeafe;
        }

        footer {
            text-align: center;
            font-size: 12px;
            color: var(--text-light);
            margin-top: 40px;
            padding-bottom: 20px;
        }

        @media (max-width: 600px) {
            .container { padding: 25px; margin: 10px; }
            .download-btn { position: static; display: block; text-align: center; margin-bottom: 20px; }
            .exp-header { flex-direction: column; }
        }
    </style>
</head>
<body>

    <div class="container">
        <a href="Migi Setyo Sugiarto Adi (9).pdf" class="download-btn" download>UNDUH PDF</a>

        <header>
            <h1>MIGI SETYO SUGIARTO ADI</h1>
            <div class="contact-info">
                migisetyosa@gmail.com | 08112683668 | Kota Semarang | Indonesia
            </div>
        </header>

        <section>
            <h2>Summary</h2>
            <div class="summary">
                [cite_start]Profesional Food & Beverage dengan pengalaman lebih dari 5 tahun di bidang operasional restoran, bar, dan manajemen toko[cite: 2]. 
                [cite_start]Memiliki latar belakang sebagai Barista, Bartender, Admin Purchasing, hingga Store Manager[cite: 3]. 
                [cite_start]Terbukti mampu mengelola inventory, menekan biaya operasional, dan menjaga standar layanan pelanggan[cite: 4].
            </div>
        </section>

        <section>
            <h2>Professional Experience</h2>

            <div class="exp-item">
                <div class="exp-header">
                    <span>Bartender</span>
                    <span>Februari 2025 - November 2025</span>
                </div>
                <div class="company">Suji Suan Cai Yu DP Mall Semarang</div>
                <div class="location">Semarang Tengah, Kota Semarang</div>
                <ul>
                    [cite_start]<li>Menyiapkan dan menyajikan minuman non-alkohol sesuai SOP perusahaan[cite: 8].</li>
                    [cite_start]<li>Mengelola stok bahan baku dan berhasil mengurangi waste hingga ±15%[cite: 9].</li>
                    [cite_start]<li>Menjaga kebersihan area bar dengan tingkat kepatuhan SOP 100%[cite: 9].</li>
                </ul>
            </div>

            <div class="exp-item">
                <div class="exp-header">
                    <span>Barista</span>
                    <span>September 2024 - Januari 2025</span>
                </div>
                <div class="company">Cotti Coffee Pollux Paragon Semarang</div>
                <ul>
                    [cite_start]<li>Menyajikan berbagai minuman kopi dan teh serta menjaga kualitas area kerja[cite: 11].</li>
                    [cite_start]<li>Mengelola stok bahan baku dan melakukan pemeliharaan peralatan[cite: 13].</li>
                </ul>
            </div>

            <div class="exp-item">
                <div class="exp-header">
                    <span>Admin Purchasing</span>
                    <span>Juli 2023 - Agustus 2024</span>
                </div>
                <div class="company">TOKO KOPI DJUARA</div>
                <ul>
                    [cite_start]<li>Mengelola proses pembelian, negosiasi dengan pemasok, serta pengawasan inventaris[cite: 14].</li>
                    [cite_start]<li>Membuat laporan pembelian dan stok menggunakan Microsoft Excel[cite: 15].</li>
                </ul>
            </div>

            <div class="exp-item">
                <div class="exp-header">
                    <span>Store Manager</span>
                    <span>Juni 2021 - Agustus 2024</span>
                </div>
                <div class="company">KOPI REJEKI</div>
                <ul>
                    [cite_start]<li>Mengelola operasional harian toko, pengawasan staf, dan pengelolaan inventaris[cite: 20].</li>
                    [cite_start]<li>Menangani keluhan pelanggan dan menjaga kualitas layanan[cite: 21].</li>
                </ul>
            </div>
        </section>

        <section>
            <h2>Skills & Expertise</h2>
            <div class="skills-grid">
                <div class="skill-tag">Cost Control & Inventory</div>
                <div class="skill-tag">Restaurant Operations</div>
                <div class="skill-tag">Purchasing & Supplier</div>
                <div class="skill-tag">Microsoft Excel</div>
                <div class="skill-tag">Food Safety Management</div>
                <div class="skill-tag">Leadership & Teamwork</div>
                <div class="skill-tag">Handle Complaint</div>
                <div class="skill-tag">Problem Solving</div>
            </div>
        </section>

        <section>
            <h2>Education</h2>
            <div class="exp-item">
                <div class="exp-header">
                    <span>Tata Boga</span>
                    <span>2012 - 2015</span>
                </div>
                <div class="company">SMK NEGERI 6 SEMARANG</div>
                <ul>
                    [cite_start]<li>Mempelajari teknik dasar dan lanjutan memasak serta pengolahan bahan makanan[cite: 30].</li>
                    [cite_start]<li>Sertifikat Kompetensi Uji Keterampilan Penyajian Makanan dan Minuman (2015)[cite: 32, 33].</li>
                </ul>
            </div>
        </section>

        <footer>
            &copy; 2026 Migi Setyo Sugiarto Adi - Semarang, Indonesia
        </footer>
    </div>

</body>
</html>
