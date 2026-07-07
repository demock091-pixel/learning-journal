# Minggu 5 — Algoritma Keygen (FindLicenseKey)

**Tanggal:** [3 Juli 2026]

## Topik
Menganalisis crackme "FindLicenseKey" yang menggunakan algoritma substitusi tabel berbasis input.

## Apa yang Dipahami
Saya paham bahwa tidak semua crackme punya kunci statis — pada kasus ini, license key 
dihasilkan dari kombinasi indeks posisi dan nilai ASCII karakter username, lalu di-mapping ke 
tabel karakter tetap. Saya berhasil merekonstruksi algoritma ini menjadi program C sendiri 
(keygen) dan memverifikasi hasilnya cocok dengan binary asli lewat gdb.

## Apa yang Masih Bingung
Awalnya saya kesulitan membaca notasi modulo di decompiler (`% 0x3e`) dan menghubungkannya 
dengan panjang tabel karakter — butuh dihitung manual dulu baru paham.
