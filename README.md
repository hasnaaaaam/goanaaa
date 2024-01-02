# Membuat Aplikasi Doa Doa Dengan Canva, HTML,CSS, Javascript, MySQL
Hasna Minatul Mardiah 27 Oktober 2023

# Latar Belakang
Gen Z tumbuh dan berkembang di lingkungan teknologi digital yang berkembang dengan kemajuan intelektual yang semakin beragam. Hal ini menjadi tantangan untuk memanfaatkan peluang teknologi yang ada untuk mengedukasi dan mengajarkan tentang moral dan kebaikan. Salah satukebaikan yang perlu diajarkan, adalah kewajiban untuk berdoa sebagai manusia yang berketuhanan. Sehingga Aplikasi Doa Doa ku ini cocok, aplikasi ini merupakan jenis aplikasi seluler atau perangkat lunak yang dikhususkan untuk menyediakan akses mudah ke berbagai doa, dzikir, ayat suci, dan praktik keagamaan dalam Islam. Aplikasi ini dirancang untuk membantu umat Islam dalam menjalankan ibadah sehari-hari dan untuk memudahkan akses untuk berdoa. 
Aplikasi Doa Doa ku ini pastinya sangat membantu umat Islam dalam menjalankan ibadah sehari-hari dan memahami ajaran agama dengan lebih baik.
# Analysis : Branding
Pada tahap ini kita mengeksplorasi branding dari system yang dibuat. Branding meliputi:

•	Merk: Doa Doa ku

•	Tagline: Berdoa dengan Mudah, Hidup penuh ketenangan

•	Campaign: Aplikasi ini dirancang untuk membantu umat Islam dalam menjalankan ibadah sehari-hari dan untuk memudahkan akses untuk berdoa. 
•	Target user: 
  
  -User semua kelompok usia
  
  -Muslim
  
  -Orang orang yang mau Belajar Agama 
 	
  -Orang orang yang Sedang Menghadapi Tantangan

• User Experience theme :
 
  -Tema visual yang menenangkan 
 
  -Desain Minimalis 
 
  -Jenis Huruf mudah dibaca 
# Analysis: User Story
Pada tahap ini kita mengeksplorasi kebutuhan prioritas dari para pengguna untuk kita
wujudkan sebagai fitur pada sistem atau aplikasi yang akan dibuat. User story memudahkan
kita membuat prioritas fitur-fitur untuk dikerjakan untuk jangka waktu tertentu.

| Sebagai  | Saya ingin bisa |Sehingga | Prioritas |
|-------|--------|-------|---------|
| Pengguna aplikasi | Daftar Doa | Mudah mengakses doa doa dan doa penting lainnya | ⭐⭐⭐⭐ |
| Pengguna aplikasi | Teks Doa dan Terjemahan | Memahami makna doa dalam bahasa arab dan bahasa yang dimengerti | ⭐⭐⭐⭐ |
| Pengguna aplikasi | Audio Doa | Belajar pengucapan doa dengan benar | ⭐⭐⭐ |
| Pengguna aplikasi | Penyusunan Doa Favorit | Menyusun daftar doa favorit dengan mudah | ⭐⭐⭐⭐ | 
| Pengguna aplikasi | Pengingat Doa | Diingatkan untuk berdoa pada waktu yang tepat | ⭐⭐⭐⭐ | 
| Pengguna aplikasi | Kalender Hijriah | Melacak tanggal hari penting dalam islam | ⭐⭐⭐ | 
| Pengguna aplikasi | Tafsir Doa | Memahami makna dan latar belakang doa | ⭐⭐⭐⭐ | 
| Pengguna aplikasi | Doa untuk kategori khusus | Memiliki doa khusus untuk situasi tertentu | ⭐⭐⭐ | 
| Pengguna aplikasi | Pencarian Doa | Mencari doa berdasarkan kata kunci atau tofik | ⭐⭐⭐⭐⭐ | 
| Pengguna aplikasi | Penyimpanan Offline | Mengakses doa dalam mode offline | ⭐⭐⭐⭐ | 
| Pengguna aplikasi | Kustomisasi Tampilan | Menyesuaikan tampilan aplikasi | ⭐⭐ | 
| Pengguna aplikasi | Berbagi Doa | Berbagi doa dengan orang lain | ⭐⭐⭐⭐ | 

# Analysis Struktur Data
<img width="202" alt="image" src="https://github.com/hasnaaaaam/goanaaa/assets/144829887/67096226-f145-45c2-ba69-391ccbc66722">

# Design: Arsitektur Berbasis Client-Server

   <img width="583" alt="Screenshot 2023-12-31 133142" src="https://github.com/hasnaaaaam/goanaaa/assets/144829887/0ba5cb81-af9e-43c0-9c01-0d0be3875f92">

# Code HTML

  HALAMAN AWAL
 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Doa Doa Ku</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      text-align: center;
      padding-top: 100px;
    }
    h1 {
      font-size: 36px;
      color: #333;
    }
    a {
      text-decoration: none;
      color: #007bff;
      display: block;
      margin-top: 20px;
      font-size: 18px;
    }
  </style>
</head>
<body>
  <h1>Doa Doa Ku</h1>
  <a href="doa.html">Lihat Doa</a>
</body>
</html>

  HALAMAN KE 2

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Isi Doa</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      text-align: center;
      padding-top: 50px;
    }
    h1 {
      font-size: 28px;
      color: #333;
    }
    ul {
      list-style: none;
      padding: 0;
      margin-top: 20px;
    }
    li {
      margin-bottom: 10px;
    }
    a {
      text-decoration: none;
      color: #007bff;
      display: block;
      font-size: 16px;
    }
  </style>
</head>
<body>
  <h1>Isi Doa</h1>
  <ul>
    <li><a href="#">Husnul Khatimah - Allahumma jannibnā 'adzāba al-qabri wa 'adzāba an-nār</a></li>
    <li><a href="#">Doa Selamat - Allahumma innī as'aluka al-'āfiyah fi al-dunyā wal-ākhirah</a></li>
    <li><a href="#">Doa Agar Dimudahkan Segala Urusan - Rabbī yassir walā tu'assir</a></li>
    <li><a href="#">Doa untuk Kedua Orang Tua - Rabbir hamhuma kama rabbayānī shaghīrah</a></li>
    <li><a href="#">Doa Taubat - Allahumma innī ṭubtu an dhanbī kullih</a></li>
  </ul>
</body>
</html>






  
# Design: User Experience (UX) Design

![WhatsApp Image 2023-11-08 at 08 20 05_2e364773](https://github.com/hasnaaaaam/goanaaa/assets/144829887/bcf40750-9de3-4fbd-b747-c7d82397243c)




