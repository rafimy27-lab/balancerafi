CATATAN DUIT - versi 3 (tanpa AI, offline, sinkron ke Google Sheets)

A. PASANG DI INTERNET (sekali saja, gratis)
1. Buka https://app.netlify.com/drop, seret FOLDER "catatan-duit" ini ke halaman itu.
2. Kamu dapat alamat seperti https://nama-acak.netlify.app. Buat akun Netlify gratis
   supaya situsnya jadi milikmu dan tidak dihapus.

B. PASANG DI IPHONE
1. Buka alamat itu di Safari.
2. Tombol Bagikan -> "Tambah ke Layar Utama". Pakai HANYA lewat ikon itu (data Safari dan
   data ikon terpisah di iOS).

C. ISI DATA AWAL (sekali)
Kategori dan budget sudah ada. Data pribadi TIDAK lagi tertanam di kode.
Di app: Pengaturan -> Pulihkan -> pilih catatan-duit-data-awal.json -> Pulihkan.
Atau, kalau kamu sudah menyambungkan Google Sheets yang berisi datamu, cukup Hubungkan
dan semuanya ditarik otomatis.

D. SINKRON GOOGLE SHEETS (opsional)
Ikuti PANDUAN-GOOGLE-SHEETS.txt. Setelah itu: Pengaturan -> Hubungkan Google Sheets.

E. CARA PAKAI
- Kolom bawah: ketik seperti chat. Contoh:
  makan siang 35rb, grab 22rb | kemarin kopi 12k | tgl 3 listrik 100rb | +gaji 3jt
- Periode = tgl 28 s/d 27 (bisa diganti). Harian = jatah makan + Dana sisa makan.
- Tetap rutin Simpan cadangan (Pengaturan), walau sudah pakai Sheets.
- Jatah makan: kalau makan lewat jatah, diambil dari Dana sisa makan. Kalau dana habis, defisitnya dipotong dari jatah besok
  (kalau lebih besar dari jatah sehari, sisanya lanjut ke hari berikutnya). Hemat di hari berikutnya melunasi defisit itu.
- Kategori lain (bukan makan) yang melebihi budget: kelebihannya ditutup dari sisa Jajan dulu, lalu Cadangan Kas.
  Ini hanya tampilan di Per kategori; catatan tetap di kategori aslinya. Label 100% = "Habis", di atas 100% = "Melebihi budget".
- Pemasukan bisa menambah budget: saat membuat atau mengubah catatan pemasukan, pilih "Tambah ke budget kategori" (di ketik cepat: pilihan di baris kedua).
  Budget kategori itu di periode tanggal pemasukan naik sebesar jumlahnya. Pemasukan tanpa kategori (gaji, transfer ibu) tidak mengubah budget.
  Kalau dipilih ke Makan, jatah makan harian ikut naik untuk seluruh periode.
- Lihat uang tiap kategori dipakai untuk apa: di Per kategori (periode maupun harian), ketuk nama kategorinya. Muncul rincian: total, jumlah transaksi,
  yang terbesar, lalu daftar catatan per tanggal atau dikelompokkan Per item (mis. semua "Bensin" dijumlah). Ketuk satu catatan untuk mengubah atau
  menghapusnya; setelah itu kamu kembali ke rincian kategori yang sama.
