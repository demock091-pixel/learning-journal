# Minggu 6 — Mengenal Format PE (Windows)

**Tanggal:** [6 Juli 2026]

## Topik
Beralih dari analisis binary ELF (Linux) ke PE (Windows) untuk tugas static-analysis-lab.

## Apa yang Dipahami
Saya paham bahwa PE dan ELF adalah dua format executable yang berbeda platform — PE untuk 
Windows (.exe/.dll), ELF untuk Linux. Saya belajar mengekstrak informasi dasar dari binary PE: 
hash (SHA256/MD5), strings, dan import table (DLL serta fungsi yang dipanggil), menggunakan 
kombinasi PowerShell dan Ghidra.

## Apa yang Masih Bingung
Saya masih belum familiar dengan tools GUI khusus PE seperti PEview/CFF Explorer, jadi lebih 
sering bergantung ke Ghidra untuk membaca import table meskipun sebenarnya ada tools yang lebih 
spesifik untuk itu.
