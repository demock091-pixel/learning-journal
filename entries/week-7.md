# Minggu 7 — Membandingkan Dua Compiler Berbeda (VB6 vs GCC)

**Tanggal:** [6 Juli 2026]

## Topik
Menganalisis dua binary PE dengan asal compiler berbeda: Visual Basic 6 dan GCC/MinGW-w64.

## Apa yang Dipahami
Saya paham bahwa binary hasil compiler berbeda punya "sidik jari" yang berbeda juga — binary 
VB6 bergantung penuh ke `MSVBVM60.DLL` dan pakai fungsi `__vba*`, sedangkan binary GCC/MinGW 
bergantung ke banyak DLL kecil `api-ms-win-crt-*` (Universal CRT). Ini membantu saya mengenali 
asal-usul binary hanya dari import table dan string yang tertanam, tanpa perlu tahu source code 
aslinya.

## Apa yang Masih Bingung
Saya masih belum paham detail kenapa binary VB6 menggunakan operasi trigonometri (`cos`, `tan`) 
untuk validasi serial — sepertinya ini teknik obfuscation matematis yang levelnya lebih tinggi 
dari yang pernah saya temui sebelumnya.
