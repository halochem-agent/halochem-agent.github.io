# HaloChem — Simulasi Kimia Interaktif

Kumpulan simulasi kimia orisinal yang berjalan sepenuhnya di browser. Tanpa instalasi, tanpa server, tanpa pelacakan — cukup buka halamannya dan mulai bereksperimen. Dibuat dengan HTML, CSS, dan JavaScript murni (tanpa framework, tanpa proses build).

**Live:** https://halochem-agent.github.io/

## Daftar Simulasi

| Simulasi | Topik | Yang bisa kamu lakukan |
| --- | --- | --- |
| **pH & Titrasi Asam-Basa** | Asam–basa | Teteskan NaOH ke dalam asam kuat/lemah; amati kurva pH terbentuk dan warna indikator berubah di titik ekuivalen. |
| **Laju Reaksi (Teori Tumbukan)** | Kinetika | Atur suhu, konsentrasi, dan energi aktivasi; lihat partikel bertumbukan dan hanya yang berenergi cukup yang bereaksi. |
| **Hukum Gas Ideal** | Gas | Ubah suhu, volume (piston), dan jumlah partikel; tekanan diukur dari tumbukan ke dinding. Buktikan PV = nRT. |
| **Pembentukan Ikatan Ion** | Ikatan kimia | Pilih logam & nonlogam; saksikan transfer elektron (model Bohr) membentuk ion dan rumus senyawa. |

## Menjalankan secara lokal

Tidak perlu apa pun — cukup buka `index.html` di browser. Atau jalankan server statis sederhana:

```
python -m http.server 8000
# lalu buka http://localhost:8000
```

## Struktur

```
halochem-agent.github.io/
├── index.html        # halaman utama (daftar simulasi)
├── style.css         # gaya bersama
├── ph-titrasi.html
├── laju-reaksi.html
├── hukum-gas.html
└── ikatan-ion.html
```

Menambah simulasi baru: buat satu file `.html`, tautkan `style.css`, lalu tambahkan kartunya di `index.html`.

## Catatan

Model di dalam simulasi sengaja disederhanakan agar konsepnya jelas — angkanya untuk membangun intuisi, bukan presisi laboratorium. Saran dan koreksi konsep sangat diterima.

## Lisensi

Bebas digunakan untuk pembelajaran. Karya orisinal, bukan salinan dari situs mana pun.
