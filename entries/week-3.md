# Minggu 3 — Reverse Engineering Pertama (halftwin)

**Tanggal:** [3 Juli 2026]

## Topik
Mengerjakan crackme pertama "halftwin" menggunakan Ghidra untuk analisis statis.

## Apa yang Dipahami
Saya mulai terbiasa membaca hasil decompile Ghidra meskipun nama variabelnya masih generik 
(`local_3c`, dsb). Saya paham cara menelusuri alur program dari pengecekan argumen (`argc`), 
lalu ke validasi panjang string, sampai ke loop perbandingan karakter. Proses ini melatih saya 
membaca logic program tanpa harus menjalankannya dulu.

## Apa yang Masih Bingung
Saya masih kesulitan kalau ada dua loop yang saling berhubungan — butuh waktu lama untuk 
memahami bagaimana hasil loop pertama mempengaruhi loop kedua.
