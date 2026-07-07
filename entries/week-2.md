# Minggu 2 — Operasi Bitwise

**Tanggal:** [3 Juli 2026]

## Topik
Belajar operasi bitwise (`&`, `|`, `^`, `<<`, `>>`) dan kegunaannya di reverse engineering.

## Apa yang Dipahami
Saya paham bahwa `& 1` bisa dipakai untuk mengecek apakah angka genap/ganjil (mengambil bit 
terakhir), dan `>> 1` setara dengan pembagian cepat dengan 2. Ini konsep sederhana tapi ternyata 
sering muncul di logic validasi crackme, jadi penting untuk langsung dikenali saat baca 
decompiler. Saya juga mulai paham operasi XOR (`^`) yang sering dipakai untuk obfuscation string.

## Apa yang Masih Bingung
Masih agak lambat kalau harus menghitung manual hasil XOR antar banyak byte sekaligus, 
terutama kalau melibatkan tabel data yang berulang (modulo).
