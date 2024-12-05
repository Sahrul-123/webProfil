<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website profil mahasiswa</title>
    <link rel="stylesheet" href="style.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f4f8; /* Warna latar belakang */
        }
        header {
            background-color: rgba(255, 255, 255, 0.9); /* Warna latar belakang dengan transparansi */
            padding: 25px;
            text-align: center;
            box-shadow: 0 2px 15px rgba(0, 0, 0, 0.1); /* Bayangan untuk header */
        }
        nav ul {
            list-style-type: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        section {
            margin: 25px;
            background-color: rgba(255, 255, 255, 0.9); /* Warna latar belakang untuk section dengan transparansi */
            padding: 25px;
            border-radius: 8px; /* Sudut membulat */
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1); /* Bayangan untuk section */
        }
        h2 {
            text-align: center;
            color: #00796b; /* Warna judul */
        }
        .profile-photo {
            display: block;
            margin: 0 auto;
            border-radius: 50%; /* Membuat foto menjadi bulat */
            width: 200px; /* Ukuran foto */
            height: 200px; /* Ukuran foto */
            object-fit: cover; /* Memastikan gambar terpotong dengan baik */
        }
        .about, .education, .experience, .skills, .hobbies, .contact {
            margin-top: 35px;
        }
        footer {
            text-align: center;
            padding: 25px;
            background-color: rgba(255, 255, 255, 0.9);
            position: relative;
            bottom: 0;
            width: 100%;
            box-shadow: 0 -5px 10px rgba(0, 0, 0, 0.1); /* Bayangan untuk footer */
        }
    </style>
</head>
<body>
    <header>
        <h1>Profil Website</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="profil.html">Profil</a></li>
                <li><a href="galeri.html">Galeri</a></li>
                <li><a href="kontak.html">Kontak</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>Tentang Saya</h2>
        <img src="image/Sahrul.jpg" alt="Foto Saya" class="profile-photo">
        <p>Saya pernah berpengalaman pekerja dilapangan menjadi Helper Excavator selama 3 bulan,Terampil dalam memecahkan masalah perbaikan dan pemeliharaan berbagai peralatan rekam jejak yang berbukti dalam manajemen Proyek</p>
    </section>
    
    <section id="education" class="education">
        <h2>Pendidikan</h2>
        <ul>
            <li>SMK YP FATAHILLAH 2 CILEGON [ 2020-2023 ]</li>
            <li>MTS ALKHAIRIYAH PAMEKSER [ 2017-2020 ]</li>
            <li>SDN PAMEKSER [ 2014-2017 ]</li>
        </ul>
    </section>
    
    <section id="experience" class="experience">
        <h2>Pengalaman Kerja</h2>
        <ul>
            <li>Aslab (Asisten labtarium fatahillah 2 cilegon ) [ 2023 ]</li>
            <li>Helpe Excavator [ 2023 ]</li>
        </ul>
    </section>
    
    <section id="skills" class="skills">
        <h2>Keahlian</h2>
        <ul>
            <li>Canva</li>
            <li>Excavator</li>
            <li>EXCEL</li>
            <li>Word</li>
        </ul>
