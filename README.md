Program ini digunakan untuk mengecek kategori umur seseorang berdasarkan input yang dimasukkan oleh user.
1. Input
Python
umur = int(input("Masukan umur anda: "))
Penjelasan:
Program meminta pengguna memasukkan umur.
int() digunakan untuk mengubah input menjadi angka (integer).
2. Percabangan (If-Else)
Program menggunakan percabangan untuk menentukan kondisi:
a. Jika umur kurang dari 0
Python
if umur < 0:
Artinya:
Jika umur negatif, maka orang tersebut belum lahir.
b. Jika umur kurang dari 18
Python
elif umur < 18:
Artinya:
Jika umur di bawah 18 tahun → belum cukup umur.
c. Jika umur 18 sampai 60
Python
elif umur >= 18 and umur <= 60:
Artinya:
Jika umur antara 18–60 → cukup umur.
d. Jika umur lebih dari 60
Python
else:
Artinya:
Jika umur di atas 60 → masuk kategori lanjut usia (di program ditampilkan pesan khusus).
3. Output
Python
print("Program selesai")
Penjelasan:
Menandakan bahwa program telah selesai dijalankan.
Kesimpulan Singkat
Program ini:
Menerima input umur
Menggunakan percabangan if-elif-else
Mengelompokkan umur menjadi:
Belum lahir,
Belum cukup umur,
Cukup umur,
Lansia. 