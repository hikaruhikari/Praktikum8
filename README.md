# Praktikum8

Tugas Praktikum

Buat program sederhana dengan mengaplikasikan penggunaan class. Buatlah class untuk menampilkan daftar nilai mahasiswa, dengan ketentuan:

• Method tambah() untuk menambah data

• Method tampilkan() untuk menampilkan data

• Method hapus(nama) untuk menghapus data berdasarkan nama

• Method ubah(nama) untuk mengubah data berdasarkan nama

• Buat diagram class, flowchart dan penjelasan programnya pada README.md.

• Commit dan push repository ke github.


1. Pendahuluan
  
print dan data: Mencetak judul program. Variabel data adalah dictionary kosong yang akan digunakan untuk menyimpan data mahasiswa.

2. Kelas Mahasiswa
  
Kelas ini mendefinisikan struktur dan fungsi untuk mengelola data mahasiswa dan Fungsi: Digunakan untuk mendefinisikan atribut nama, nim, tugas, uts, dan uas saat objek dibuat.

3. Konstruktor (__init__)

Tujuan: Menampilkan semua data mahasiswa yang tersimpan di dictionary data.

Kondisi: Jika data kosong, pesan "Data masih kosong" akan dicetak dan Jika ada data, tabel dengan rincian Nama, NIM, Tugas, UTS, UAS, dan Nilai Akhir akan ditampilkan.

4. Tampilkan
  
Fungsi: Memasukkan data baru ke dictionary data.

Proses: Meminta input dari pengguna untuk atribut nama, nim, tugas, uts, dan uas. Menghitung nilai akhir berdasarkan bobot:

Tugas (30%)

UTS (35%)

UAS (35%)

Menyimpan data mahasiswa dalam format dictionary.

5. Tambah
  
Fungsi: Memperbarui data mahasiswa berdasarkan NIM.

Proses: Meminta NIM dari pengguna dan jika NIM ditemukan di data, program meminta input baru untuk mengganti data lama.

6. Ubah

Fungsi: Menghapus data mahasiswa dari dictionary data berdasarkan NIM.

Kondisi: Jika NIM tidak ditemukan, pesan "Data tidak ditemukan" ditampilkan.

7. Hapus

Fungsi: Mencari dan menampilkan data mahasiswa berdasarkan NIM.

Kondisi: Jika NIM ditemukan, data ditampilkan dan Jika tidak, pesan "NIM tidak ditemukan" muncul.

8. Cari

Fungsi: Mencari dan menampilkan data mahasiswa berdasarkan NIM.

Kondisi: Jika NIM ditemukan, data ditampilkan dan Jika tidak, pesan "NIM tidak ditemukan" muncul.

9. Menu Utama

Tujuan: Memberikan pilihan kepada pengguna untuk melakukan aksi tertentu.

Pilihan:

1: Melihat semua data mahasiswa.

2: Menambahkan data mahasiswa baru.

3: Mengubah data mahasiswa.

4: Menghapus data mahasiswa.

5: Mencari data mahasiswa berdasarkan NIM.

6: Keluar dari program.

Jika pilihan tidak valid, pesan error akan ditampilkan.

10. ini hasilnya

11. ini flowchart yang dibuat

![praktikum6](https://github.com/user-attachments/assets/8d087101-8e45-4dd5-a7df-147060bc15ce)
