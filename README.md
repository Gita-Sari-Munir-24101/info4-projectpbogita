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

# Tipe Data Mutable (List)
Tipe data mutable adalah tipe data yang nilainya dapat diubah setelah objek dibuat tanpa harus membuat objek baru. Salah satu contoh tipe data mutable dalam bahasa pemrograman Python adalah list.

# Pengertian List
List merupakan struktur data dalam Python yang digunakan untuk menyimpan sekumpulan data dalam satu variabel. Data yang disimpan di dalam list dapat berupa berbagai tipe data, seperti integer, float, string, maupun tipe data lainnya. List ditulis menggunakan tanda kurung siku [] dan setiap elemen dipisahkan dengan tanda koma.

# Sifat Mutable pada List
List bersifat mutable, artinya elemen di dalam list dapat:

- Diubah nilainya
- Ditambahkan elemen baru
- Dihapus elemennya

# Perubahan tersebut tidak membuat list baru, tetapi langsung mengubah list yang sudah ada.
Contoh List (Tipe Data Mutable)
angka = [1, 2, 3, 4]

# Jika salah satu elemen diubah:

1. angka[2] = 10
print(angka)

# Hasil:
[1, 2, 10, 4]

# Contoh di atas menunjukkan bahwa isi list dapat diubah, sehingga list termasuk tipe data mutable.
Operasi pada List

1. Beberapa operasi yang dapat dilakukan pada list antara lain:
- Menambah elemen menggunakan append()
- Menghapus elemen menggunakan remove() atau pop()
- Mengubah elemen dengan mengakses indeks list
- Mengurutkan data menggunakan sort()

# Contoh Operasi List
- buah = ["apel", "mangga", "jeruk"]
- buah.append("pisang")
- buah.remove("mangga")
- print(buah)

# Hasil:
['apel', 'jeruk', 'pisang']



