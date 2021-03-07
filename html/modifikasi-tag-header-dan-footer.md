# Modifikasi tag header dan footer

Sebelum versi `HTML5`, para developer umumnya menggunakan tag `<div>` dengan atribut `id` atau `kelas` untuk memisahkan bagian-bagian struktur dalam halaman HTML seperti `header, footer,` dan `sidebar`.

```
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8" />
  <title>Belajar HTML5</title>
</head>

<body>
  <div id="header">
    <h1>Judul Website</h1>
    <img src="logo_website.jpg" />
  </div>

  <div id="menu">
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">About</a></li>
       <li><a href="#">Contact</a></li>
    </ul>
  </div>

  <div id="content">
    <div id="article_1">
      <div id="article_header_1">
        <h1>Judul Artikel 1</h1>
        <h2>Sub Judul Artikel 1</h2>
      </div>
        <p>...Ini adalah isi dari artikel 1...</p>
    </div>
     <div id="article_2">
      <div id="article_header_2">
        <h1>Judul Artikel 2</h1>
        <h2>Sub Judul Artikel 2</h2>
      </div>
        <p>...Ini adalah isi dari artikel 2...</p>
    </div>
  </div>

  <div id="sidebar">
    <h1>Artikel Terbaru</h1>
      <ul>
        <li><a href="#">Link 1</a></li>
        <li><a href="#">Link 2</a></li>
        <li><a href="#">Link 3</a></li>
      </ul>
    </div>

  <div id="footer">
    <p>...Footer - Copyright 2021 ...</p>
  </div>
</body>
</html>
```

Kode diatas sepenuhnya valid dan sangat sering digunakan hingga saat ini. Akan tetapi, `HTML 5` mencoba mengganti semua tag `<div>` menjadi _semantic tag_ yang lebih bermakna.

Berikut adalah pembahasan beberapa tag `HTML5` yang ditujukan untuk membuat struktur halaman:

### Tag `<header>`

Tag `<header>` digunakan untuk bagian halaman web yang merupakan header. kode nya berada dibagian atas di dalam kode `<body>`.

```
<header>
  <h1>Judul Website</h1>
  <img src=”logo_website.png” />
</header>
```

### Tag `<nav>`

Tag `<nav>` digunakan sebagai _container_ dari menu navigasi. Sebaiknya digunakan untuk menu utama yang dirasa penting seperti pada bagian header.

```
<nav>
  <ul>
    <li><a href="#">Home</a></li>
    <li><a href="#">About</a></li>
    <li><a href="#">Contact</a></li>
  </ul>
</nav>
```

### Tag `<section>`

Tag `<section>` digunakan untuk memisahkan bagian-bagian dari struktur web. Tag ini bisa digunakan sebagai container untuk kumpulan artikel, gallery, atau bagian lain dari halaman web yang perlu pemisahan.

```
<section>
  <h1>Judul 1</h1>
   <p>...Kumpulan dari konten...</p>
</section>
<section>
  <h1>Judul 1</h1>
  <p>...Kumpulan dari konten...</p>
</section>
```

### Tag `<main>`

Tag `<main>` cocok digunakan untuk menandakan bagian utama dari sebuah halaman. Berbeda dari tag `<section>`, tag `<main>` umumnya hanya digunakan 1 kali untuk bagian paling penting, yang biasanya berupa konten/artikel utama.

```
<main>
  <h1>Judul Utama</h1>
  <p>...penjelasan...</p>
  <article>
    <h2>Judul Artikel 1</h2>
    <p>...penjelasan artikel 1...</p>
    <p>... </p>
    <p>... </p>
  </article>
  <article>
    <h2>Judul Artikel 2</h2>
    <p>...penjelasan artikel 2...</p>
    <p>... </p>
    <p>... </p>
  </article>
</main>
```

### Tag `<article>`

Tag `<article>` bertujuan untuk menampung konten web. Tag ini cocok sebagai container untuk artikel dalam sebuah blog.

```
<article>
 <h2>Judul Artikel</h2>
 <p>...penjelasan artikel...</p>
 <p>... </p>
 <p>... </p>
</article>
```

### Tag `<aside>`

Tag `<aside>` bertujuan untuk menandai bagian web yang bukan berisi konten utama, tetapi memiliki kaitan dengan artikel yang saat ini ditampilkan. Bagian paling pas untuk tag `<aside>` adalah sidebar. Karena pada sidebar bisa terdiri dari berbagai konten yang tidak langsung berkaitan dengan konten utama seperti ’10 artikel terbaru’, atau ‘5 komentar terbaru’. Selain untuk sidebar, tag `<aside>` juga bisa digunakan di dalam artikel untuk menandai bagian tambahan.

```
<article>
  <h2>Judul Artikel 1</h2>
  <p>...penjelasan artikel 1...</p>
  <p>... </p>
  <p>... </p>
</article>
<aside>
  <p>...penjelasan tambahan...</p>
</aside>
```

### Tag `<footer>`

Tag `<footer>` biasannya digunakan pada bagian bawah halaman, dimana kita menampilkan beberapa informasi mengenai website. Walapun penggunaan paling jelas adalah untuk bagian footer halaman (meletakkan copyright, about us, dll), tag ini juga cocok digunakan pada bagian bawah artikel untuk menampung informasi tambahan seperti ‘tentang penulis‘ maupun link untuk share ke sosial media.

```
<footer>
  <p>...Footer - Copyright 2021 ...</p>
</footer>
```

### Jadi tampilan Kode di HTML5 Seperti ini :

```
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8" />
  <title>Belajar HTML5</title>
</head>

<body>
  <header>
    <h1>Judul Website</h1>
    <img src="logo_website.jpg" />
  </header>

  <nav>
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">About</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
  </nav>

  <section>
    <article>
      <header>
        <h1>Judul Artikel 1</h1>
        <h2>Sub Judul Artikel 1</h2>
      </header>
        <p>...Ini adalah isi dari artikel 1...</p>
    </article>
    <article>
      <header>
        <h1>Judul Artikel 2</h1>
        <h2>Sub Judul Artikel 2</h2>
      </header>
        <p>...Ini adalah isi dari artikel 2...</p>
    </article>
  </section>

  <aside>
    <h1>Artikel Terbaru</h1>
    <ul>
      <li><a href="#">Link 1</a></li>
      <li><a href="#">Link 2</a></li>
      <li><a href="#">Link 3</a></li>
    </ul>
  </aside>

  <footer>
    <p>...Footer - Copyright 2021 ...</p>
  </footer>
</body>
</html>
```

Susunan kode HTML tersebut menjadi lebih mudah dipahami jika anda pernah mendesain layout halaman HTML dengan CSS.Penggunaan semantic tag dari HTML5 juga akan bermanfaat bagi SEO (Search Engine Optimization). Struktur halaman akan lebih jelas, sehingga mesin pencari bisa memprioritaskan bagian mana yang perlu diberikan penekanan (seperti `<header>` atau `<article`>) dan bagian mana yang hanya berupa keterangan (seperti `<aside>` atau `<footer>`).
