# books

A new Flutter project.

## Getting Started

# Wahyu Laksono Saputra || 362358302107

# Soal 1
![alt text](assets/praktikum/soal1.png)

# Soal 2
![alt text](assets/praktikum/soal2.png)

# Soal 3
substring(0, 450) : Mengambil potongan dari string tersebut, mulai dari indeks 0 hingga 450. Ini berarti hanya 450 karakter pertama dari respons yang akan disimpan dalam variabel result. Jika respons memiliki kurang dari 450 karakter, maka akan mengambil seluruh karakter yang ada. Ini sering digunakan untuk membatasi panjang teks yang ditampilkan agar tidak terlalu panjang.

catchError((_) {..}): Ini adalah callback yang akan dijalankan jika terjadi kesalahan saat menjalankan getData().

![alt text](assets/praktikum/soal3.png)

# Soal 4
Langkah 1 :
- Tiga method async yang masing-masing mengembalikan nilai integer (1, 2, 3)
- Setiap method menggunakan Future.delayed() untuk mensimulasikan operasi asinkron yang memakan waktu 3 detik
- await digunakan untuk menunda eksekusi sampai Future selesai
- Setelah penundaan 3 detik, method akan mengembalikan nilai integer yang berbeda

Langkah 2 :
- Method count() adalah method async yang menggabungkan hasil dari tiga method sebelumnya
- total = await returnOneAsync() akan menunggu method pertama selesai dan menyimpan hasilnya (1)
- total += await returnTwoAsync() akan menunggu method kedua selesai dan menambahkan hasilnya (1 + 2 = 3)
- total += await returnThreeAsync() akan menunggu method ketiga selesai dan menambahkan hasilnya (3 + 3 = 6)
- setState() digunakan untuk memperbarui UI dengan nilai total yang telah dihitung
- Hasilnya akan disimpan sebagai string di variabel result

![alt text](assets/praktikum/soal4.png)
