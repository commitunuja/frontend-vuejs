# Properti Display

Ada beberapa pengertian dari display :

- Setiap tag pada HTML berada di dalam sebuah kotak. Properti display pada CSS mengatur perilaku dari kotak tersebut
- Setiap tag pada HTML memiliki nilai bawaan untuk properti display. Tetapi kita juga dapat mengubah perilaku dari tag tersebut dengan mengganti nilai-nya.

Nilai dari display :

- inline

  - elemen HTML yang secara default tidak menambahkan baris baru ketika dibuat
  - lebar dan tinggi elemennya sebesar konten yang ada di dalam nya
  - kita tidak dapat mengatur tinggi dan lebar dari elemen inline
  - margin dan padding hanya mempengaruhi elemen secara horizontal, tidak vertikal

Contoh elemen yang memiliki nilai bawaan inline :
b, strong, i, em, a, span, sub, sup, button, input, label, select, textarea

- inline-block

  - Tidak ada elemen yang secara default memiliki properti display: inline-block
  - Kita harus ubah secara manual properti tersebut
  - Perilaku dasarnya sama dengan elemen inline
  - Perbedaannya, elemen inline-block dapat di atur tinggi dan lebar

- block

  - elemen HTML yang secara bawaan menambahkan baris baru ketika dibuat
  - jika tidak diatur lebar-nya, maka lebar bawaan dari elemen block akan memenuhi lebar dari browser/parent-nya.
  - kita dapat mengatur tinggi dan lebar dari elemen block
  - di dalam elemen block, kita dapat menyimpan tag dengan elemen inline, inline-block, atau bahkan elemen block lagi

Contoh elemen yang memiliki nilai bawaan block:
h1-h6, p, ol, ul, li, form, hr, div

- none, nilai ini memang digunakan untuk membuat elemen menjadi dihilangkan. contoh kode : display: none;
