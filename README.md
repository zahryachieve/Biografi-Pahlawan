# Biografi-Pahlawan
Membuat website biografi pahlawan Menggunakan HTML &amp; CSS
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Beranda - Ir. H. Djuanda Kartawidjaja</title>
    <link rel="stylesheet" href="style.css">
    <style>
        .hero {
            background-image: url('background-beranda.jpg');
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            flex-direction: column;
            text-align: center;
        }

        .hero h1 {
            font-size: 36px;
            margin: 0;
            color: white;
        }

        .hero p {
            max-width: 600px;
            font-size: 18px;
            color: white;
            margin-top: 10px;
        }

        .section {
            padding: 40px;
            max-width: 900px;
            margin: 0 auto;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
            margin-top: 30px;
        }

        .section h2 {
            color: #8b0000;
            font-size: 28px;
            margin-bottom: 20px;
        }

        .section p {
            line-height: 1.6;
            font-size: 18px;
            margin-bottom: 20px;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: #f8f8f8;
            margin-top: 30px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Ir. H. Djuanda Kartawidjaja</h1>
        <nav>
            <ul>
                <li><a href="index.html">Beranda</a></li>
                <li><a href="biografi.html">Biografi</a></li>
                <li><a href="perjuangan.html">Perjuangan</a></li>
                <li><a href="kontak.html">Kontak</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <h1>Selamat Datang</h1>
        <p>Kenali lebih dalam Ir. H. Djuanda Kartawidjaja, tokoh nasional yang berjasa dalam sejarah Indonesia.</p>
    </section>

    <section class="section">
        <h2>Tentang Ir. H. Djuanda</h2>
        <p>Ir. H. Djuanda Kartawidjaja, lahir di Tasikmalaya pada 14 Januari 1911, adalah tokoh nasional yang berperan besar dalam pembangunan dan kebijakan maritim Indonesia. Djuanda dikenal sebagai salah satu Bapak Pembangunan Indonesia, dan nama beliau selalu diingat melalui Deklarasi Djuanda yang mengukuhkan Indonesia sebagai negara kepulauan dengan kedaulatan atas perairan yang mengelilinginya.</p>

        <p>Djuanda menempuh pendidikan di Technische Hoogeschool te Bandoeng (sekarang ITB) dan berhasil meraih gelar insinyur sipil. Pada awal kemerdekaan, beliau diangkat dalam berbagai jabatan penting, termasuk Menteri Perhubungan, Menteri Keuangan, dan Menteri Pertahanan. Beliau juga dipercaya sebagai Perdana Menteri Indonesia pada masa-masa penting yang penuh tantangan politik dan ekonomi.</p>

        <p>Salah satu pencapaian terbesar Djuanda adalah <strong>Deklarasi Djuanda</strong> pada 13 Desember 1957 yang menyatakan bahwa perairan yang mengelilingi pulau-pulau Indonesia merupakan bagian dari wilayah kedaulatan Indonesia. Kebijakan ini menjadi landasan hukum bagi Indonesia untuk mengelola lautnya, yang meliputi lebih dari 17.000 pulau, dan akhirnya diakui oleh dunia internasional.</p>

        <p>Selain itu, Djuanda juga memimpin pembangunan berbagai infrastruktur strategis yang mendukung penyatuan wilayah Indonesia yang luas. Dalam hal diplomasi, beliau memperjuangkan posisi Indonesia di dunia internasional, sehingga Indonesia semakin dihormati sebagai negara yang berdaulat penuh, baik di darat maupun di laut.</p>

        <p>Ir. H. Djuanda wafat pada 7 November 1963, namun jasa-jasanya tetap dikenang, baik dalam pembangunan negara maupun dalam pemikiran-pemikirannya mengenai kemaritiman dan politik luar negeri Indonesia. Nama Djuanda kini diabadikan dalam berbagai infrastruktur, seperti Bandara Internasional Juanda di Surabaya dan Taman Hutan Raya Ir. H. Djuanda di Bandung.</p>
    </section>

    <footer>
        <p>&copy; 2024 Ir. H. Djuanda. All rights reserved.</p>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biografi - Ir. H. Djuanda Kartawidjaja</title>
    <link rel="stylesheet" href="style.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
            color: #333;
        }

        header {
            background-color: #8b0000;
            color: #fff;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 28px;
        }

        nav ul {
            list-style: none;
            padding: 0;
            display: flex;
            justify-content: center;
            gap: 20px;
        }

        nav a {
            color: white;
            text-decoration: none;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .biography-section {
            display: flex;
            flex-direction: row;
            gap: 20px;
            padding: 40px;
            max-width: 900px;
            margin: 0 auto;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }

        .biography-section img {
            max-width: 300px;
            height: auto;
            border-radius: 8px;
            box-shadow: 0px 0px 5px rgba(0, 0, 0, 0.2);
        }

        .biography-content {
            flex: 1;
        }

        .biography-content h2 {
            color: #8b0000;
            margin-bottom: 20px;
            font-size: 26px;
        }

        .biography-content p {
            line-height: 1.6;
            margin-bottom: 10px;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: #f8f8f8;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Ir. H. Djuanda Kartawidjaja</h1>
        <nav>
            <ul>
                <li><a href="index.html">Beranda</a></li>
                <li><a href="biografi.html">Biografi</a></li>
                <li><a href="perjuangan.html">Perjuangan</a></li>
                <li><a href="kontak.html">Kontak</a></li>
            </ul>
        </nav>
    </header>

    <section class="biography-section">
        <img src="images.jpg" alt="Foto Ir. H. Djuanda Kartawidjaja">
        <div class="biography-content">
            <h2>Biografi Ir. H. Djuanda Kartawidjaja</h2>
            <p><strong>Latar Belakang dan Pendidikan:</strong> Lahir pada 14 Januari 1911 di Tasikmalaya, Jawa Barat, Ir. H. Djuanda berasal dari keluarga sederhana. Ia melanjutkan pendidikannya di Technische Hoogeschool te Bandoeng (sekarang ITB) dan meraih gelar insinyur sipil.</p>
            <p><strong>Karier dan Jabatan:</strong> Setelah kemerdekaan Indonesia, Djuanda memegang berbagai jabatan penting seperti Menteri Perhubungan, Menteri Keuangan, dan Perdana Menteri. Selama menjabat, ia berfokus pada pembangunan transportasi dan ekonomi.</p>
            <p><strong>Deklarasi Djuanda:</strong> Pada tahun 1957, Djuanda mengeluarkan Deklarasi Djuanda yang memperluas wilayah laut Indonesia hingga 12 mil dan mengakui perairan di antara pulau-pulau sebagai bagian dari wilayah Indonesia. Deklarasi ini kemudian diakui secara internasional dan menjadi landasan bagi Hukum Laut PBB.</p>
            <p><strong>Kontribusi Infrastruktur:</strong> Djuanda juga berperan dalam membangun jaringan transportasi untuk memperkuat persatuan Indonesia. Proyeknya meliputi pembangunan jalan, jembatan, pelabuhan, dan bandara.</p>
            <p><strong>Akhir Hayat dan Warisan:</strong> Djuanda wafat pada 7 November 1963. Namanya diabadikan dalam Bandara Internasional Juanda dan Taman Hutan Raya Ir. H. Djuanda di Bandung sebagai penghormatan atas jasanya bagi bangsa.</p>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Ir. H. Djuanda Kartawidjaja. All rights reserved.</p>
    </footer>
</body>
</html>


<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Perjuangan Ir. H. Djuanda Kartawidjaja</title>
    <link rel="stylesheet" href="style.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
            color: #333;
        }

        header {
            background-color: #8b0000;
            color: #fff;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 28px;
        }

        nav ul {
            list-style: none;
            padding: 0;
            display: flex;
            justify-content: center;
            gap: 20px;
        }

        nav a {
            color: white;
            text-decoration: none;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .perjuangan-section {
            padding: 40px;
            max-width: 900px;
            margin: 0 auto;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }

        .perjuangan-section img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
            box-shadow: 0px 0px 5px rgba(0, 0, 0, 0.2);
            margin-bottom: 20px;
        }

        .perjuangan-section h2 {
            color: #8b0000;
            margin-bottom: 20px;
            font-size: 26px;
        }

        .perjuangan-section p {
            line-height: 1.6;
            margin-bottom: 15px;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: #f8f8f8;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Ir. H. Djuanda Kartawidjaja</h1>
        <nav>
            <ul>
                <li><a href="index.html">Beranda</a></li>
                <li><a href="biografi.html">Biografi</a></li>
                <li><a href="perjuangan.html">Perjuangan</a></li>
                <li><a href="kontak.html">Kontak</a></li>
            </ul>
        </nav>
    </header>

    <section class="perjuangan-section">
        <img src="607d6b423179b.jpg" alt="Perjuangan Ir. H. Djuanda">
        <h2>Perjuangan Ir. H. Djuanda Kartawidjaja</h2>

        <p><strong>1. Deklarasi Djuanda (1957):</strong> Pada 13 Desember 1957, Ir. H. Djuanda mengeluarkan sebuah pernyataan penting yang dikenal dengan nama **Deklarasi Djuanda**. Deklarasi ini mengubah peta maritim Indonesia dengan menyatakan bahwa seluruh perairan di sekitar, di antara, dan di dalam kepulauan Indonesia merupakan wilayah kedaulatan Indonesia yang tak terpisahkan. Sebelum deklarasi ini, batas laut yang diakui internasional hanya sejauh 3 mil dari garis pantai. Deklarasi ini memperluas batas tersebut hingga 12 mil, sehingga menjadikan Indonesia sebagai negara kepulauan dengan kedaulatan penuh atas lautnya.</p>

        <p><strong>2. Pembangunan Infrastruktur Nasional:</strong> Sebagai Menteri Perhubungan dan Perdana Menteri, Djuanda memfokuskan perhatiannya pada pembangunan infrastruktur yang akan memperkuat konektivitas antarwilayah Indonesia. Pembangunan jalan, jembatan, pelabuhan, dan bandara menjadi prioritas untuk mendukung aktivitas ekonomi dan mempermudah transportasi antar pulau. Dengan demikian, pembangunan infrastruktur menjadi salah satu tonggak penting dalam memajukan negara.</p>

        <p><strong>3. Kepemimpinan dalam Stabilitas Nasional:</strong> Selain dalam hal pembangunan, Djuanda juga memainkan peran yang sangat penting dalam menjaga stabilitas nasional Indonesia, yang pada saat itu masih menghadapi ancaman dari pemberontakan daerah seperti PRRI/Permesta. Dalam situasi yang penuh ketegangan tersebut, Djuanda berhasil meredakan ketegangan politik dengan kebijakan yang bijaksana dan langkah-langkah tegas untuk menjaga keutuhan negara.</p>

        <p><strong>4. Diplomasi dan Perjuangan di Kancah Internasional:</strong> Djuanda juga berjasa dalam diplomasi internasional, khususnya terkait dengan pengakuan terhadap konsep negara kepulauan Indonesia. Deklarasi Djuanda yang memproklamirkan Indonesia sebagai negara kepulauan menjadi dasar bagi pengakuan internasional terhadap kedaulatan Indonesia atas seluruh wilayah laut di sekitarnya. Dalam konteks ini, Djuanda adalah pelopor yang mempengaruhi kebijakan Hukum Laut PBB yang berlaku hingga saat ini.</p>

        <p><strong>5. Perjuangan Mengamankan Kekayaan Alam:</strong> Sebagai bagian dari perjuangan Djuanda dalam menjaga kedaulatan Indonesia, ia juga mengupayakan pengamanan terhadap kekayaan alam Indonesia, terutama sumber daya laut yang kaya akan hasil perikanan dan energi. Kebijakan ini membantu melindungi sumber daya alam Indonesia dari eksploitasi oleh negara asing dan memastikan keberlanjutan pengelolaan sumber daya alam untuk kepentingan rakyat Indonesia.</p>

        <p><strong>Warisan dan Pengaruh:</strong> Ir. H. Djuanda dikenang sebagai seorang pemimpin yang berwawasan jauh ke depan. Usaha dan perjuangannya untuk memperkuat Indonesia sebagai negara yang berdaulat dan mandiri, baik dari sisi maritim maupun infrastruktur, terus memberikan dampak positif bagi generasi-generasi berikutnya. Berbagai fasilitas dan tempat yang dinamai berdasarkan namanya, seperti **Bandara Internasional Juanda** di Surabaya dan **Taman Hutan Raya Ir. H. Djuanda** di Bandung, merupakan simbol penghargaannya atas dedikasi dan pengabdiannya untuk bangsa Indonesia.</p>
    </section>

    <footer>
        <p>&copy; 2024 Ir. H. Djuanda Kartawidjaja. All rights reserved.</p>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kontak - Ir. H. Djuanda Kartawidjaja</title>
    <link rel="stylesheet" href="style.css">
    <style>
        .contact-section {
            background-color: rgba(0, 0, 0, 0.7);
            color: white;
            padding: 40px;
            margin: 40px auto;
            max-width: 600px;
            border-radius: 8px;
        }

        .contact-section h2 {
            color: #f8f8f8;
            font-size: 28px;
            margin-bottom: 20px;
            text-align: center;
        }

        .contact-section form {
            display: flex;
            flex-direction: column;
        }

        .contact-section label {
            margin-bottom: 5px;
            font-size: 16px;
            color: #f8f8f8;
        }

        .contact-section input,
        .contact-section textarea {
            padding: 10px;
            font-size: 16px;
            margin-bottom: 20px;
            border: none;
            border-radius: 4px;
        }

        .contact-section input[type="text"],
        .contact-section input[type="email"] {
            width: 100%;
        }

        .contact-section textarea {
            width: 100%;
            height: 100px;
            resize: vertical;
        }

        .contact-section button {
            padding: 10px 20px;
            font-size: 16px;
            color: white;
            background-color: hsl(202, 75%, 50%);
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }

        .contact-section button:hover {
            background-color: rgb(46, 40, 234);
        }
    </style>
</head>
<body>
    <header>
        <h1>Ir. H. Djuanda Kartawidjaja</h1>
        <nav>
            <ul>
                <li><a href="index.html">Beranda</a></li>
                <li><a href="biografi.html">Biografi</a></li>
                <li><a href="perjuangan.html">Perjuangan</a></li>
                <li><a href="kontak.html">Kontak</a></li>
            </ul>
        </nav>
    </header>

    <section class="contact-section">
        <h2>Kontak Kami</h2>
        <p>Jika Anda memiliki pertanyaan atau ingin memberikan masukan, silakan mengisi formulir di bawah ini.</p>
        <form action="#" method="post">
            <label for="name">Nama</label>
            <input type="text" id="name" name="name" placeholder="Masukkan nama Anda" required>

            <label for="email">Email</label>
            <input type="email" id="email" name="email" placeholder="Masukkan email Anda" required>

            <label for="message">Pesan</label>
            <textarea id="message" name="message" placeholder="Tulis pesan Anda di sini" required></textarea>

            <button type="submit">Kirim</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Ir. H. Djuanda. All rights reserved.</p>
    </footer>
        <p>-Muhammad Rabbani Razaq
            -Siti Nurul Zakiyyah
            -Siti Jahriatussania.</p>
</body>
</html>

