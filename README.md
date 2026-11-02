LPJ DIGITAL – School Financial Management System

Solusi Terpadu Pengelolaan Keuangan, Pembukuan, Pajak, dan Laporan Pertanggungjawaban Sekolah.

📌 Deskripsi Aplikasi

LPJ DIGITAL adalah sistem administrasi dan pembukuan keuangan digital sekolah yang dirancang khusus untuk mengelola seluruh administrasi bantuan pemerintah (seperti Dana Revitalisasi Sekolah, BOS, BPOPP, dan sumber dana sekolah lainnya).

Aplikasi ini mengusung prinsip Satu Kali Input (Integrated Transaction Center): bendahara cukup menginput 1 transaksi pengeluaran atau penerimaan, dan sistem akan otomatis memperbarui seluruh buku pembukuan, rekapitulasi pajak, serta menghasilkan Bukti Kas Pengeluaran (Voucher) secara akurat dan real-time.

🚀 Modul Utama Pembukuan

Dashboard Utama & Analistik: Ringkasan saldo bank, kas tunai, total penerimaan, pengeluaran, utang/setoran pajak, dan grafik visual arus kas.

Pusat Input Transaksi Terpadu: Formulir tunggal dengan penomoran otomatis, perhitungan PPN/PPh, breakdown rincian item belanja, dan dukungan pemindahbukuan (mutasi bank ke kas tunai).

Buku Kas Umum (BKU): Tabel format dual-side (Penerimaan & Pengeluaran berdampingan) lengkap dengan sub-baris rincian belanja.

Buku Kas Tunai (BKT): Pembukuan khusus mutasi tunai lengkap dengan teks paragraf penutupan buku kas resmi di akhir bulan.

Buku Pembantu Bank: Pencatatan mutasi kredit/debit rekening bank sekolah.

Buku Rekapitulasi Pajak: Rekap otomatis pemungutan PPN (11%) & PPh (1,5%), penyetoran ke kas negara, dan saldo sisa pajak.

Bukti Kas Pengeluaran (Voucher): Pembuatan dokumen resmi kwitansi pengeluaran lengkap dengan kalimat terbilang otomatis dalam bahasa Indonesia.

Pusat Laporan LPJ & Cetak: Pratinjau dan cetak seluruh modul dengan mode cetak bersih (clean print).

📦 PWA (Progressive Web App) & Akses Offline

Aplikasi ini dapat dijalankan 100% Offline (tanpa koneksi internet) dan dapat diinstal langsung ke Desktop (Windows/Mac/Linux) maupun Smartphone (Android/iOS) sebagai aplikasi native PWA.

Cara Menginstal Ke Desktop:

Buka aplikasi di browser Chrome / Microsoft Edge.

Klik tombol "Install Aplikasi PWA" yang muncul di bar navigasi atas.

Aplikasi akan terpasang di desktop dan menu Start laptop/komputer Anda.

💻 Petunjuk Instalasi & Penggunaan Lokal

Metode 1: Buka Langsung (Tanpa Web Server)

Cukup unduh file index.html dan klik ganda (double click) file tersebut di browser (Google Chrome, MS Edge, Firefox, Opera, atau Safari).

Metode 2: Jalankan Menggunakan Python (HTTP Server)

Jika ingin menjalankan aplikasi secara lokal dengan alamat port:

Buka Terminal / Command Prompt pada direktori tempat file berada.

Jalankan perintah:

python -m http.server 8080


Buka browser dan kunjungi:

http://localhost:8080


Metode 3: Jalankan di XAMPP / Laragon

Salin file index.html ke folder htdocs (XAMPP) atau www (Laragon).

Buka browser dan akses: http://localhost/index.html.

🗄️ Database & Penyimpanan Data

Local Persistence: Menggunakan localStorage browser. Data transaksi dan pengaturan identitas sekolah tetap aman tersimpan meskipun browser ditutup atau komputer dimatikan.

Backup & Restore (JSON): Menyediakan fitur ekspor file cadangan .json dan pemulihan data (restore) kapan saja melalui menu Backup / Restore di navbar atas.

Ekspor CSV / Excel: Data transaksi dapat diekspor ke file .csv untuk diolah kembali menggunakan Microsoft Excel.

🖨️ Pengaturan Cetak Dokumen

Seluruh dokumen yang dicetak (BKU, BKT, Buku Bank, Rekap Pajak, dan Bukti Kas) telah dikonfigurasi menggunakan stylesheet @media print khusus:

Ukuran Kertas: A4 / F4 (Landscape untuk pembukuan, Portrait untuk Bukti Kas).

Format Bersih: Menyembunyikan seluruh tombol aplikasi, navbar, sidebar, dan filter saat dicetak.

Tabel Resmi: Header tabel otomatis berulang (repeat header) jika dokumen terdiri dari beberapa halaman.

📋 Data Demo Awal (Master Data)

Aplikasi sudah dilengkapi dengan data awal untuk pengujian:

Nama Sekolah: SMK PGRI 1 KOTAAGUNG

Kabupaten/Provinsi: Tanggamus / Lampung

Program Kegiatan: Bantuan Pemerintah Revitalisasi Sekolah Tahun Anggaran 2026

Catatan: Anda dapat mengubah seluruh identitas dan data demo ini melalui menu Identitas & Anggaran atau melakukan reset melalui menu Backup / Restore.
