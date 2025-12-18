# info4-projectpbogita
percabangan/percabangan bersarang

Program Percabangan If–Elif–Else pada Python
# Deskripsi
Program ini dibuat menggunakan bahasa pemrograman Python untuk menerapkan konsep percabangan (conditional statement) menggunakan struktur if, elif, dan else.
Program bertujuan untuk menentukan kategori nilai serta status seseorang berdasarkan kondisi tertentu.

# Contoh 1: Penentuan Nilai Akademik
# Penjelasan Program
- Variabel nilai berisi angka 75.
- Program akan mengecek nilai tersebut menggunakan struktur if–elif–else.
- Setiap kondisi memiliki rentang nilai tertentu untuk menentukan kategori nilai.

# Ketentuan Penilaian
- Nilai ≥ 90 → Nilai A
- Nilai ≥ 75 → Nilai B
- Nilai ≥ 60 → Nilai C
- Nilai < 60 → Nilai D

# Hasil
Karena nilai adalah 75, maka program menampilkan:
Nilai B

# Contoh 2: Percabangan Bersarang (Nested If)
# Penjelasan Program
- Variabel umur diisi dengan nilai 20.
- Variabel status diisi dengan teks "mahasiswa".
- Program menggunakan percabangan bersarang (if di dalam if) untuk menentukan status seseorang.

# Alur Logika Program
1. Program mengecek apakah umur ≥ 18.
2. Jika benar, program akan mengecek status:
- Jika status adalah mahasiswa → menampilkan pesan dewasa dan mahasiswa
- Jika bukan mahasiswa → menampilkan pesan dewasa tapi bukan mahasiswa
3. Jika umur < 18, program menampilkan pesan belum dewasa.

# Hasil
Karena umur ≥ 18 dan status adalah mahasiswa, maka program menampilkan:
Anda dewasa dan seorang mahasiswa
