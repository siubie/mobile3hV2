### Memanfaatkan SQLLite Pada Flutter
## Mengatur dependencies pada pubspec.yaml
Tambahkan dependency sqlite dan path_provider,selanjutnya download packages yang baru. Untuk nilai Any dapat diisi versi terbaru atau sesuai kebutuhan. Versi

## Membuat model
Buat kelas model kemudia isi dengan attribut. 
Selanjutnya buat getter dan setter untuk masing-masing variabel. Untuk getter dan setter
secara otomatis dapat degenerate menggunakan extension pada vscode dengan nama Dart
Getter and Setters. Jika menggunakan extension tersebut restart VSCode dan klik kanan pada
variabel yang akan degenerate getter dan setternya.
getter akan mengambil nilai yang dimasukkan ke consturctor dan setter ini akan dipakai
untuk mengembalikan nilai yang dimasukkan dari constructor, untuk setiap variable.

## Membuat Db Helper
Membuat fungsi untuk menginisialisasi database. Future adalah “tipe data” yang terpanggil dengan adanya delay atau “keterlambatan”. Tidak seperti method lainnya, sistem akan terus menjalankan method tersebut sampai method itu selesai berjalan.
Didalam flutter ada async dan await.
• async : menggunakan future pada sebuah method, sehingga membuat sistem menunggu
sampai terjadi Blocking. Makanya, method tersebut harus ditandai dengan async.
• await : Jika ada method yang ditandai await, maka artinya sistem harus menunggu sampai
syntax tersebut selesai berjalan.
Pada source code, variable directory akan menunggu sampai method
getApplicationDocumentsDirectory mengerjakan tugasnya. Method
getApplicationDocumentsDirectory() berfungsi untuk mengambil direktori folder aplikasi
untuk menempatkan data yang dibuat pengguna sehingga tidak dapat dibuat ulang oleh
aplikasi tersebut. Setelah itu kita gunakan variable String path, untuk membuat nama
database kita dengan mengambil lokasi directory nya dan menambahkannya dengan nama
database item.db.
## Membuat Entry Form
sesuaikan dengan form yang dibuat