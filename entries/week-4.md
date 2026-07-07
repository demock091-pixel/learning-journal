# Minggu 4 — Debugging Dinamis dengan gdb

**Tanggal:** [4 Juli 2026]

## Topik
Belajar dasar gdb untuk melengkapi analisis statis Ghidra, dipraktikkan di crackme "the wired".

## Apa yang Dipahami
Saya paham cara memasang breakpoint di alamat tertentu (`break *alamat`), menjalankan program 
sampai breakpoint (`continue`), lalu membaca isi register (`info registers`) dan memory 
(`x/s $register`). Teknik ini sangat membantu karena saya bisa langsung "mencuri" nilai yang 
sudah di-decode program tanpa perlu menghitung manual algoritma obfuscation-nya.

## Apa yang Masih Bingung
Menghitung alamat breakpoint absolut dari offset Ghidra (perlu dijumlahkan dengan base address 
dari `info proc mappings`) masih sering saya lupa urutan langkahnya.
