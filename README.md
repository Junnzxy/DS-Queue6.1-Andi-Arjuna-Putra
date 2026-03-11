# DS-Queue6.1-Andi-Arjuna-Putra

Andi Arjuna Putra Bima Akbar Oddang
2086022510024
Data Structure

Definitely not the radical club Problem Description

Tugas Data Structure Week 6 activity 6.1 Queue

Kasus: Penjaga Gerbang Perkumpulan Rahasia
Anda adalah seorang pemikir di sebuah bar eksklusif. Tugas Anda adalah menyaring pengunjung berdasarkan kriteria keanggotaan yang sangat ketat. Anda harus memisahkan mana pengunjung yang valid untuk masuk dan mana yang harus ditolak.

Kriteria Kelayakan
Pengunjung dianggap valid jika memenuhi semua syarat berikut:
- Usia minimal saat ini adalah 28 tahun. Angka ini berasal dari syarat mulai bergabung (minimal 20 tahun) ditambah masa proses rekrutmen (minimal 8 tahun).
- Usia maksimal adalah 118 tahun.
- Input harus berupa angka yang masuk akal.

Aturan Input dan Output
Input: Sebuah deret angka (string) yang dipisahkan oleh koma, mewakili usia setiap orang di antrean.
Output:
Baris 1: Daftar usia yang lolos pengecekan (Lolos).
Baris 2: Daftar usia yang tidak lolos pengecekan (Gagal).

Cara Kompilasi dan Menjalankan Program Persyaratan
- Java Development Kit (JDK) terinstal.
- Terminal atau Command Prompt.
- Step by step

Buka Terminal di folder tempat file .java berada.
- Kompilasi semua file: javac *.java
- Jalankan program: java *.java'
- masukan input kedalam terminal
- dan outpun pun keluar

logika implementasi
kita menggunakan penmdekatan Linear Filtering. Program akan membaca setiap elemen atau satu per satu, memeriksa kondisinya, lalu memasukanannya ke dalam dua wadah (ArrayList) yg berbeda.

Alur Kerja Program
1. Inisialisasi: Siapkan dua list kosong, misalnya list_lolos dan list_gagal.
3. Iterasi: Lakukan perulangan untuk setiap data usia yang masuk.
4. Validasi: Gunakan fungsi logika sederhana.
- Syarat: $28 \le usia \le 118$.
- Angka 28 didapat dari $20 + 8$.
4. Pemisahan:
- Jika syarat terpenuhi, masukkan ke list_lolos.
- Jika tidak, masukkan ke list_gagal.
5. Output: Cetak kedua list tersebut sebagai string.
