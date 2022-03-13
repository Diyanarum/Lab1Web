# PEMOGRAMAAN WEB

Diyan Arum Maheswari (312010133)
Teknik Informatika - UNIVERSITAS PELITA BANGSA
______________________________________________

## CARA MEMBUAT PARAGRAF

![menambahkan_paragraf](img/RESULT%20PARAGRAF.png)

Untuk dapat membuat sebuah paragraf seperti gambar diatas dibutuhkan sebuah codingan seperti dibawah ini.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>tag dasar html</title>
</head>
<body>
    <!-- PARAGRAF 1 -->
    <p align="center"> Selamat datang di web program ini. Saya Diyan Arum Maheswari. Mahasiswi jurusan Teknik Informatika - UNIVERSITAS PELITA BANGSA</p>
    

    <!-- PARAGRAF 2 -->
    <P align="left">HTML (Hypertest Markup Language) merupakan bahasa markup yang digunakan untuk membuat sebuah halaman web dan menampilkan berbagai informasi di dalam sebuah browser. HTML berupa kode-kode tag yang menginstruksikan browser untuk menghasilkan tampilan sesuai dengan yang diinginkan. HTML saat ini merupakan standar Internet yang didefinisikan dan dikendalikan penggunaannya oleh World Wide Web Consortium (W3C).</P>

</body>
</html>
```

## CARA MEMBUAT HEADING

Heading adalah sebagai judul dari sebuah artikel web yang dimana (h1) adalah heading atau judul terbesar dan (6) adalah heading terkecil.

![menambahkan_heading](img/RESULT%20HEADING.png)

Dan untuk dapat membuat sebuah heading seperti gambar diatas dibutuhkan sebuah codingan seperti dibawah ini.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>tag dasar html</title>
</head>
<body>
    <!-- Judul Paragraf 1 -->
    <h1>PEMBELAJARAN DASAR HTML</h1>

    <!-- PARAGRAF 1 -->
    <p align="center"> Selamat datang di web program ini. Saya Diyan Arum Maheswari. Mahasiswi jurusan Teknik Informatika UNIVERSITAS PELITA BANGSA</p>
    
<h1>BENTUK PARAGRAF PADA HTML</h1>

    <!-- PARAGRAF 2 -->
    <P align="left">HTML (Hypertest Markup Language) merupakan bahasa markup yang digunakan untuk membuat
        sebuah halaman web dan menampilkan berbagai informasi di dalam sebuah browser. HTML
        berupa kode-kode tag yang menginstruksikan browser untuk menghasilkan tampilan sesuai
        dengan yang diinginkan. HTML saat ini merupakan standar Internet yang didefinisikan dan
        dikendalikan penggunaannya oleh World Wide Web Consortium (W3C).</P>

</body>
</html>
```
## CARA MEMBUAT FORMAT TEXT (italic, background colour, underline, dan bold)

Dalam format text ini ada beberapa fitur yang bisa kalian gunakan seperti contohnya pada gambar dibawah ini, adapun beberapa fitur yang saya gunakan antara lain yaitu : 

### Fitur Italic 

Atau garis miring pada sebuat kalimat yang bisa kalian gunakan dengan (menggunakan perintah <i>)

### Fitur Background Colour

Fitur untuk memblock dengan warna pada kalimat yang kita pilih dengan (menggunakan perintah <style>) setelahnya kalian dapat memilih warna yang tersedia sesuai dengan yang kalian inginkan

### Fitur Underline 

Atau garis bawah pada sebuah kalimat yang bisa kalian gunakan dengan (menggunakan perintah <u>)

### Fitur Bold

Atau penebalan pada suatu huruf yang kita pilih, yang bisa kalian gunakan dengan (menggunakan perintah <b>) 

Berikut contoh hasil dari beberapa Format Text yang saya gunakan.

![menambahkan_formattext](img/RESULT%20FORMAT%20TEXT.png)

Dan untuk dapat membuat sebuah format text seperti gambar diatas dibutuhkan sebuah codingan seperti dibawah ini.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>tag dasar html</title>
</head>
<body>
    <!-- Judul Paragraf 1 -->
    <h1>PEMBELAJARAN DASAR HTML</h1>

    <!-- PARAGRAF 1 -->
    <p align="center"> <span style="background-color: rgb(247, 181, 203);">  Selamat datang di web program ini. Saya Diyan Arum Maheswari, salah satu mahasiswi jurusan <b>Teknik Informatika - UNIVERSITAS PELITA BANGSA</b> </p>
    
    <h1>BENTUK PARAGRAF PADA HTML</h1>

    <!-- PARAGRAF 2 -->
    <P align="left"> <i>(Hypertest Markup Language)</i> merupakan bahasa markup yang digunakan untuk membuat
        sebuah halaman web dan menampilkan berbagai informasi di dalam sebuah browser. HTML itu sendiri
         <u>berupa kode-kode tag yang menginstruksikan browser untuk menghasilkan tampilan sesuai
            dengan yang diinginkan</u>. HTML saat ini merupakan standar Internet yang didefinisikan dan
        dikendalikan penggunaannya oleh World Wide Web Consortium (W3C).</P>

</body>
</html>
```
## CARA MENAMBAHKAN GAMBAR

Untuk memasukan atau menambahkan suatu gambar pada HTML maka kalian bisa menggunakan sebuah tag (img) yang kemudian menyimpan file source pada folder yang sudah dibuat sebelumnya. Berikut hasil dari tag tersebut.

[menambahkan_gambar](img/RESULT%20INPUT%20GAMBAR.png)

Dan untuk dapat menambahkan suatu gambar seperti gambar diatas dibutuhkan sebuah codingan seperti dibawah ini.

```html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>tag dasar html</title>
</head>

<body>
    <!-- Judul Paragraf 1 -->
    <h1>PEMBELAJARAN DASAR HTML</h1>

    <!-- PARAGRAF 1 -->
    <p align="center"> <span style="background-color: rgb(247, 181, 203);"> Selamat datang di web program ini. Saya
            Diyan Arum Maheswari, salah satu mahasiswi jurusan <b>Teknik Informatika - UNIVERSITAS PELITA BANGSA</b>
    </p>

    <h1>BENTUK PARAGRAF PADA HTML</h1>

    <!-- PARAGRAF 2 -->
    <P align="left"> <i>(Hypertest Markup Language)</i> merupakan bahasa markup yang digunakan untuk membuat
        sebuah halaman web dan menampilkan berbagai informasi di dalam sebuah browser. HTML itu sendiri
        <u>berupa kode-kode tag yang menginstruksikan browser untuk menghasilkan tampilan sesuai
            dengan yang diinginkan</u>. HTML saat ini merupakan standar Internet yang didefinisikan dan
        dikendalikan penggunaannya oleh World Wide Web Consortium (W3C).</P>

        <!-- SUB JUDUL GAMBAR -->
        <h1>MENAMBAHKAN GAMBAR</h1>
        <!-- menambahkan gambar pada dokumen -->
        <img src="img/Logo Universitas Pelita Bangsa.png" alt="upb" title="LOGO UNIVERSITAS PELITA BANGSA" width="300px"> 
        
</body>
</html>
```

## CARA MENAMBAHKAN LINK

Untuk dapat menambahkan link pada sebuah web html maka kita perlu menggunakan sebuah tag navigasi untuk membawa kita pada sebuah web tertentu yang mana itu bisa untuk link internal ataupun eksternal. Berikut tampilan dari link pada sebuah web html.

[menambahkan_gambar](img/RESULT%20NAVIGASI%20LINK.png)


Dan untuk dapat menambahkan suatu link seperti gambar diatas dibutuhkan sebuah codingan seperti dibawah ini.

```html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>tag dasar html</title>
</head>

<body>
    <!-- MENAMBAHKAN NAVIGASI -->
    <nav>
        <a href="tag_dasar.html">Dasar HTML</a>
        <a href="halaman2.html">halaman2</a>
        <a href="https://www.instagram.com/diyanarum_/">Halaman web eksternal google</a>
    </nav>
    <hr>

    <!-- Judul Paragraf 1 -->
    <h1>PEMBELAJARAN DASAR HTML</h1>

    <!-- PARAGRAF 1 -->
    <p align="center"> <span style="background-color: rgb(247, 181, 203);"> Selamat datang di web program ini. Saya
            Diyan Arum Maheswari, salah satu mahasiswi jurusan <b>Teknik Informatika - UNIVERSITAS PELITA BANGSA</b>
    </p>

    <h1>BENTUK PARAGRAF PADA HTML</h1>

    <!-- PARAGRAF 2 -->
    <P align="left"> <i>(Hypertest Markup Language)</i> merupakan bahasa markup yang digunakan untuk membuat
        sebuah halaman web dan menampilkan berbagai informasi di dalam sebuah browser. HTML itu sendiri
        <u>berupa kode-kode tag yang menginstruksikan browser untuk menghasilkan tampilan sesuai
            dengan yang diinginkan</u>. HTML saat ini merupakan standar Internet yang didefinisikan dan
        dikendalikan penggunaannya oleh World Wide Web Consortium (W3C).</P>

        <!-- SUB JUDUL GAMBAR -->
        <h1>MENAMBAHKAN GAMBAR</h1>
        <!-- menambahkan gambar pada dokumen -->
        <img src="img/Logo Universitas Pelita Bangsa.png" alt="upb" title="LOGO UNIVERSITAS PELITA BANGSA" width="300px"> 
        
</body>
</html>