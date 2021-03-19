# dimensi-overflow

## Dimensi

Dimensi ada 2, yaitu width untuk mengatur lebar suatu elemen dan height untuk mengatur tinggi dari suatu elemen. Misal :

```
width: 100px;
height: 100px;

```

Ada beberapa nilai satuan, seperti `px, in, cm, mm, pt, pc, %` .

## Overflow

Overflow adalah properti CSS yang akan digunakan untuk mengatur perilaku elemen yang keluar dari `parent` nya.

Ada 4 nilai yang di miliki overflow :

- visible = nilai default , arti dari nilai ini adalah jika ada konten yang keluar dari parent nya, maka akan tetap ditampilkan.
  `overflow: visible;`
- auto, nilai ini akan secara otomatis menambahkan scroll ketika konten nya tidak cukup.
  `overflow: auto;`
- hidden, nilai ini untuk konten jika ingin di sembunyikan.
  `overflow: hidden;`
- scroll, ini mirip seperti auto. tetapi kalau konten nya cukup dengan parent nya, scroll akan tetap ada atau ditampilkan.
  `overflow: scroll`
