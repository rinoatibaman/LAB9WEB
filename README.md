# LAB9WEB 
|   RINO ELJON ATIBAMAN   |  TI.20.D.1  |
|     Pemrograman Web    |  Praktikum 9  |

# Lab9Web
Disini saya akan membuat prpgram modular sederhana menggunakan PHP
# Langkah - langkah Praktikum
![1](https://user-images.githubusercontent.com/101688124/171335002-e89a58d5-1e27-46d9-9a47-2da0ea5c489c.png)

## garis XAMPP server

## 1). Buat folder baru dengan nama lab9_php_modular pada docroot webserver

## 2). Buat file baru dengan nama header.php
```![2](https://user-images.githubusercontent.com/101688124/171335060-a9f94cb3-1380-496c-9e0f-4bc2595a7183.png)

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Contoh Modularisasi</title>
<link href="style.css" rel="stylesheet" type="text/stylesheet" media="screen" />
</head>
<body>
    <div class="container">
<header>
    <h1>Modularisasi Menggunakan Require</h1>
</header>
    <nav>
        <a href="home.php">Home</a>
        <a href="about.php">Tentang</a>
        <a href="kontak.php">Kontak</a>
</nav>
```
![3](https://user-images.githubusercontent.com/101688124/171335201-b6c8e9b6-843d-47c3-85d2-343150cd4765.png)


## 3). Buat file baru dengan nama footer.php
```
<footer>
                <p>&copy; 2021, Informatika, Universitas Pelita Bangsa</p>
        </footer>
    </div>
</body>
</html>
```
![4](https://user-images.githubusercontent.com/101688124/171335222-4663fbb9-3f34-4247-8a50-de82be355878.png)


## 4). Buat file baru dengan nama home.php
```
<?php require('header.php'); ?>

<div class="content">
    <h2>Ini Halaman Home</h2>
    <p>Ini adalah bagian content dari halaman.</p>
</div>

<?php require('footer.php'); ?>
```
![5](https://user-images.githubusercontent.com/101688124/171335246-2429253c-cfae-43b7-b058-a77df1c43a65.png)


## 5). Buat file baru dengan nama about.php
```
<?php require('header.php'); ?>

<div class="content">
    <h2>Ini Halaman About</h2>
    <p>Ini adalah bagian content dari halaman.</p>
</div>

<?php require('footer.php'); ?>
```
![6](https://user-images.githubusercontent.com/101688124/171335279-6f506e0c-f1cf-4444-b38b-9b36538f22ea.png)


## 6). Hasil tampilan halaman home pada browser dengan menggunakan modular header dan footer
![7](https://user-images.githubusercontent.com/101688124/171335299-6ffb2042-136e-4967-a72c-66bebd86a914.png)


## 7). Hasil tampilan halaman about pada browser dengan menggunakan modular header dan footer
![8](https://user-images.githubusercontent.com/101688124/171335307-70750cea-699d-4043-84ee-d418cba27aa1.png)


----------------------------------------------------

# Pertanyaan & Tugas
Implementasikan konsep modularisasi pada kode program praktikum 8 tentang
database, sehingga setiap halamannya memiliki template tampilan yang sama.

# Hasil Run
## - Tampilan halaman home
![9](https://user-images.githubusercontent.com/101688124/171335328-fe351756-bc4d-4755-81b7-787acf9b7233.png)


## - Tampilan halaman tambah barang
![10](https://user-images.githubusercontent.com/101688124/171335351-bc9a2162-ae62-44b9-9538-b61214a5b467.png)


# SEKIAN & TERIMA KASIH
