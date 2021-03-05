# Kalian sudah tahukah seperti apa Struktur Element di HTML?

Secara garis besar seperti ini :

```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>HyperText Markup Language</title>
  </head>
  <body>
    <p>Contoh Struktur HTML</p>
  </body>
</html>
```

Seperti inilah Struktur Element di HTML, untuk penjelasan mari disimak :

- `!DOCTYPE html`

#### Apa itu `<!DOCTYPE html>` ?

`<!DOCTYPE html>` adalah deklarasi pada dokumen HTML5 yang berfungsi untuk memberikan informasi kepada web browser tentang versi dokumen HTML yang bersangkutan. Dalam hal ini, `<!DOCTYPE html>` menginformasikan bahwa versi dokumen HTML adalah HTML5 (versi terakhir saat ini).

#

- `<html></html>`

#### Element `<html>`

Elemen ini membungkus semua konten di halaman. Terkadang dikenal sebagai elemen root.

#

- `<head></head>`

#### Element `<head>`

Elemen head lah tempat para `Developer` biasanya memasukkan elemen `script, link, style, title, meta,` dll. Tidak seperti body, ketika anda memasukkan teks di body, maka ketika halaman dijalankan, teks yang anda masukkan di dalam body tadi akan ditampilkan di `UI(User Interface)`. Head tidak menggunakan aturan seperti itu, jadi apapun yang anda masukkan ke dalam head tidak akan ditampilkan di `UI(User Interface)` kecuali anda memasukkan teks menggunakan proses javascript atau php.

Dan berikut ini adalah daftar-daftar yang akan kita pelajari kali ini mengenai head :
`title, style, link, meta, script, base.`

##### `<title>`

`<title>` adalah judul dari sebuah dokumen HTML yang ditampilkan pada judul jendela browser, di bagian title inilah biasanya digunakan memberi nama website anda dan deskripsi singkat 1 atau 2 kata mengenai website anda.

##### `<style>`

`<style>` adalah elemen untuk mendefinisikan informasi style untuk dokumen HTML.

##### `<link>`

`<link>` adalah elemen yang digunakan untuk menyertakan file eksternal ke dalam dokumen html.

##### `<meta>`

`<meta>` adalah elemen yang digunakan untuk memberi informasi tentang berbagai aspek baik dari nama penulis, bahasa, judul, kata kunci dari halaman web. element `<meta>` memiliki beberapa atribut, seperti `keywords, description, author, refresh, viewport, robots`, lebih jelas nya klik [disini.](https://www.w3schools.com/tags/tag_meta.asp)

##### `<script>`

`<script>` element digunakan untuk menulis script, atau lebih tepatnya adalah untuk menyisipkan script (seperti JavaScript) pada sisi client, baik itu ditulis secara langsung di dalam element `<script>` , maupun merujuk sumber file eksternal dengan attribute src.

##### `<base>`

`<base>` adalah elemen html yang digunakan untuk mendefinisikan URL dasar/target untuk semua URL relatif dalam dokumen.

#

- `<body></body>`

#### Element `<body>`

Element `<body>` ini berisi semua konten yang ditampilkan di halaman, termasuk teks, gambar, video, game, trek audio yang dapat diputar, atau apapun.

Berikut ini kumpulan tag HTML :

- `<!-- Komentar -->` Digunakan untuk memberi sebuah komentar atau keterangan.
- `<a>` Digunakan untuk mendefinisikan sebuah anchor, intinya untuk menautkan antara satu dokumen HTML ke dokumen HTML lainnya.
- `<abbr>` Digunakan untuk menguraikan satu ungkapan yang disingkat dan Anda dapat memberikan informasi bermanfaat kepada penelusur-penulusur page source(halaman sumber kode) / pembaca layar, sistem terjemahan dan mesin pencari yang berasal dari singkatan yang sudah diuraikan, tetapi saat di browser uraian tersebut tidak akan tampil dan hanya sebagai informasi saja.
- `<acronym>` Mendefinisikan akronim / fungsi tag ini kurang lebih sama dengan tag `<abbr>`
- `<address>` Mendefinisikan informasi kontak untuk penulis/pemilik dokumen
- `<applet>` Digunakan untuk memasukan file java kedalam dokumen HTML
- `<area />` Mendefinisikan daerah yang dapat diklik (link) pada peta gambar
- `<b>` Membuat teks tebal
- `<basefont />` Membuat atribut teks default, seperti warna, ukuran, jenis font untuk semua teks dalam dokumen
- `<bdo>` Digunakan untuk menimpa arah teks
- `<big>` Memperbesar ukuran teks sebesar satu point dari defaultnya
- `<blink>` Membuat teks berkedip
- `<blockquote>` Mendefinisikan sebuah kutipan panjang. Pada saat di browser teks akan tampil menjorok kedalam
- `<br />` Memberi baris baru/pindah baris
- `<button>` Mendefinisikan sebuah tombol diklik
- `<caption>` Membuat caption pada tabel
- `<center>` Untuk perataan tengah terhadap teks atau gambar
- `<cite>` Mendefinisikan kutipan
- `<code>` Mendefinisikan sebuah bagian dari kode komputer
- `<col />` Mendefinisikan nilai atribut dari satu kolom atau lebih dalam sebuah tabel
- `<colgroup>` Menentukan kelompok dari satu kolom atau lebih dalam sebuah tabel untuk performatan
- `<dd>` Mendefinisikan deskripsi dari item dalam daftar definisi
- `<del>` Untuk memberi garis tengah pada teks/mencoret teks
- `<dfn>` Mendefinisikan sebuah istilah definisi
- `<dir>` Mendefinisikan sebuah daftar direktori
- `<div>` Mendefinisikan sebuah section dalam dokumen
- `<dl>` Mendefinisikan sebuah daftar definisi
- `<dt>` Mendefinisikan istilah (item) dalam daftar definisi
- `<em>` Membuat teks miring. Fungsi tag ini sama dengan tag `<i>` tetapi tag `<em>` yang lebih dianjurkan/ditekankan pada penggunaan untuk teks miring
- `<embed>` Digunakan untuk memasukkan file video atau file musik
- `<fieldset>` Untuk mengelompokkan elemen-elemen yang terkait dalam form / membuat seperti frame-box di dalam form
- `<font>` Mendefinisikan jenis font, warna dan ukuran untuk teks
- `<form>` Mendefinisikan sebuah form HTML untuk input form
- `<frame />` Mendefinisikan frame dalam fremeset
- `<frameset>` Mendefinisikan satu set frame
- `<h1>` to `<h6>` Digunakan untuk menunjukkan awal dari suatu header/judul dari dokumen HTML tersebut.
- `<hr />` Membuat garis horisontal
- `<i>` Membuat teks miring
- `<iframe>` Mendefinisikan sebuah inline frame
- `<img />` Berfungsi untuk menampilkan gambar pada dokumen HTML
- `<input />` Mendefinisikan input field pada form
- `<ins>` Membuat teks bergaris bawah
- `<kbd>` Mendefinisikan teks yang di input dari keyboard
- `<label>` Mendefinisikan label untuk sebuah elemen `<input>`
- `<legend>` Mendefinisikan sebuah caption untuk elemen `<fieldset>`
- `<li>` Digunakan untuk menampilkan informasi dalam bentuk item daftar
- `<link />` Mendefinisikan hubungan antara dokumen dan sumber eksternalnya
- `<listing>` Fungsi tag ini sama dengan tag `<pre>` dan dianjurkan menggunakan tag `<pre>` karena tag `<listing>` tidak layak/diprotes
- `<map>` Mendefinisikan client-side peta gambar
- `<marquee>` Membuat teks berjalan secara vertikal atau horisontal
- `<menu>` Mendefinisikan sebuah daftar menu
- `<nobr>` Mencegah ganti baris pada teks atau gambar
- `<noframes>` Jika browser user tidak mendukung frame
- `<noscript>` Jika browser user tidak mendukung client-side scripts
- `<object>` meletakkan embed sebuah objek
- `<ol>` Mendefinisikan daftar dalam format penomoran
- `<optgroup>` Menampilkan beberapa pilihan yang sudah dikelompokkan dalam bentuk sebuah daftar drop-down
- `<option>` Menampilkan beberapa pilihan yang berbentuk dalam sebuah daftar drop-down
- `<p>` Membuat sebuah paragraf
- `<param />` Mendefinisikan sebuah parameter untuk objek
- `<pre>` Membuat teks dengan ukuran huruf yang sama
- `<q>` Mendefinisikan sebuah kutipan singkat
- `<s>` Untuk memberi garis tengah pada teks/mencoret teks, fungsi tag ini sama dengan tag `<del>` tetapi tag `<s>` tidak dianjurkan sebagai gantinya menggunakan tag `<del>`
- `<samp>` Mendefinisikan contoh keluaran dari program komputer
- `<select>` Membuat daftar drop-down
- `<small>` Memperkecil ukuran teks dari ukuran defaultnya
- `<span>` Mendefinisikan sebuah section dalam dokumen
- `<strike>` Untuk memberi garis tengah pada teks/mencoret teks, fungsi tag ini sama dengan tag `<del>`
- `<strong>` Membuat teks tebal, fungsi tag ini sama dengan tag `<b>`
- `<sub>` Memberikan efek subscript pada teks
- `<sup>` Memberikan efek superscript pada teks
- `<table>` Membuat tabel
- `<tbody>` Untuk mengelompokkan isi body di dalam sebuah tabel
- `<td>` Mendefinisikan sel di dalam sebuah tabel
- `<textarea>` Mendefinisikan sebuah kontrol input multiline
- `<tfoot>` Untuk mengelompokkan isi footer di dalam sebuah tabel
- `<th>` Mendefinisikan sel header di dalam sebuah tabel
- `<thead>` Untuk mengelompokkan isi header di dalam sebuah tabel
- `<tr>` Membuat baris di dalam sebuah tabel
- `<tt>` Mendefinisikan teletype text
- `<u>` Membuat teks bergaris bawah, fungsi tag ini sama dengan tag `<ins>` tetapi tag `<u>` tidak dianjurkan untuk kategori HTML text formatting melainkan termasuk kategori HTML Style
- `<ul>` Mendefinisikan daftar dalam format bullet
- `<var>` Mendefinisikan sebuah variabel
- `<xmp>` Mendefinisikan preformatted text, fungsi tag ini sama dengan tag `<pre>`
