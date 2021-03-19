# box-model

ada beberapa konsep di box-model ini :

- Setiap elemen di halaman berada di dalam sebuah box (kotak)
- Kita bisa mengatur ukuran dan posisi kotak tersebut
- Kita bisa memberi warna/gambar sebagai background kotak tersebut

CSS box-model mendefinisikan 'kotak' yang dihasilkan oleh sebuah elemen, lalu menampilkannya sesuai dengan format visualnya.

CSS box-model terdiri dari margin, border, padding, dan content.

- margin adalah area transparant di sekitar kotak (diluar border)
  Margin ada beberapa lagi, seperti :

```css
  - margin-top
  - margin-bottom
  - margin-left
  - margin-right
  - margin
```

- padding adalah area transparant di dalam kotak (antara content dan border)
  padding ada beberapa, Seperti :

  ```css
  - padding-top
  - padding-bottom
  - padding-left
  - padding-right
  - padding
  ```

- border adalah batas disekeliling content dan padding
  penulisan kode border :

      - border-top
      - border-bottom
      - border-left
      - border-right
      - border: 1px solid black;
      - box-sizing: border-box; // yaitu membuat ukuran beberapapun akan tidak bisa dirubah
      // setelah penulisan kode border, lalu di ikuti lebar(width), tampilan(style), warna(color)
      - style yang bisa di pakai ada beberapa:
        - solid
        - dotted
        - dashed
        - double

- content, adalah konten sebenarnya di dalam box, bisa berupa teks atau gambar

### CSS Reset

CSS reset sangat disarankan digunakan jika baru memulai membuat project. karena agar kita mempunyai kendali penuh kepada semua elemen di HTML.

penulisan kode nya ada beberapa cara :

```css
body {
  margin: 0;
}
```

atau dengan

```css
* {
  margin: 0;
}
```

```
lalu cara terakhir ini dengan copy paste dari website https://meyerweb.com/eric/tools/css/reset/ , disini ada kode yang sudah siapkan dan langsung saja di copy dan di paste kan ke berkas css.
```
