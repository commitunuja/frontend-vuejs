# Memulai dengan CSS

Untuk menambahkan css ada 3 cara :

1. Membuat berkas dengan ekstensi `.css`
2. Menulis kode css langsung di dalam berkas `.html`
3. Menulis kode langsung di `tag` atau `section`

#

#### 1. Membuat berkas dengan ekstensi `.css`

Dengan cara seperti ini, anda dapat merubah tampilan seluruh situs web hanya dengan 1 berkas dan supaya kode nya terlihat rapi dan mudah di baca atau dicari.

cara menambahkan nya yaitu dengan menulis element `<link>` didalam bagian `<head>` pada berkas HTML:

```html
<!DOCTYPE html>
<html>
  <head>
    <!--link file css -->
    <link rel="stylesheet" href="mystyle.css" />
    <!-- di href ini bisa dirubah dengan nama berkas css kalian guys -->
  </head>
  <body>
    <h1>ini judul</h1>
    <p>ini paragraf</p>
  </body>
</html>
```

#

#### 2. Menulis kode css langsung di dalam berkas `.html`

Menggunakan cara seperti ini simple dan digunakan jika satu halaman HTML memiliki kode style yang unik, tetapi tidak disarankan untuk project besar. karena nanti kode nya akan bercampur dengan kode `.html` dan akan bingung jika ingin merubah kode css nya.

cara menuliskan kode css ini yaitu memasukkan element `<style>` didalam bagian `<head>` dan menuliskan kode css di dalam element `<style>`.

```html
<!DOCTYPE html>
<html>
  <head>
    <!-- Start: kode css -->
    <style>
      body {
        background-color: linen;
      }

      h1 {
        color: maroon;
        margin-left: 40px;
      }
    </style>
    <!-- End: kode css -->
  </head>
  <body>
    <h1>Ini judul</h1>
    <p>Ini paragraf</p>
  </body>
</html>
```

#

#### 3. Menulis kode langsung di `tag` atau `section`

Cara seperti ini maksudnya bisa langsung menuliskan kode css nya di tag yang dituju dengan memberikan atribut `style`.

```html
<!DOCTYPE html>
<html>
  <head> </head>
  <body>
    <!-- contoh kode -->
    <h1 style="color:blue;text-align:center;">Ini judul</h1>
    <p style="color:red;">Ini paragraf</p>
  </body>
</html>
```
