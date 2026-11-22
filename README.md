
# Campus Event Finder

## Deskripsi
Campus Event Finder merupakan halaman web sederhana untuk mencari informasi kegiatan kampus berdasarkan nama kegiatan atau tanggal pelaksanaannya.

Project ini dibuat untuk memenuhi tugas Web Security & JavaScript DOM Manipulation dengan menerapkan fitur live search menggunakan JavaScript.

## Fitur
- Menampilkan 15 contoh kegiatan kampus.
- Pencarian berdasarkan nama kegiatan.
- Pencarian berdasarkan tanggal, bulan, dan tahun.
- Hasil pencarian diperbarui secara langsung saat pengguna mengetik.
- Menampilkan pesan jika kegiatan tidak ditemukan.
- Tampilan responsif untuk desktop dan mobile.

## Teknologi
- HTML
- CSS
- JavaScript

## Struktur File
```text
Campus_Event_Finder/
├── index.html
├── style.css
└── README.md
```

## Konsep JavaScript yang Digunakan
1. `addEventListener("input")` untuk mendeteksi perubahan pada kolom pencarian.
2. `array.filter()` untuk menyaring data kegiatan sesuai kata kunci.
3. `document.createElement()` untuk membuat elemen HTML secara dinamis.
4. `textContent` untuk menampilkan teks ke dalam elemen.
5. `appendChild()` untuk menambahkan elemen ke halaman.
6. `removeChild()` untuk menghapus hasil pencarian sebelumnya sebelum menampilkan hasil terbaru.

**Catatan:** Project ini tidak menggunakan `innerHTML` sesuai ketentuan tugas.

## Cara Menjalankan
1. Buat folder bernama `Campus_Event_Finder`.
2. Simpan ketiga file di dalam folder tersebut.
3. Pastikan nama file dan penulisannya sesuai.
4. Buka file `index.html` menggunakan browser.
5. Ketik nama kegiatan atau tanggal pada kolom pencarian.
6. Hasil pencarian akan muncul secara otomatis.

## Contoh Pengujian

| Kata Kunci | Hasil |
|---|---|
| seminar | Menampilkan kegiatan seminar |
| workshop | Menampilkan kegiatan workshop |
| 24 November | Menampilkan kegiatan tanggal 24 November |
| desember | Menampilkan kegiatan bulan Desember |
| basket | Menampilkan pesan kegiatan tidak ditemukan |

## Data
Seluruh data kegiatan yang digunakan merupakan data simulasi untuk keperluan praktikum, bukan pengumuman resmi kegiatan kampus.
