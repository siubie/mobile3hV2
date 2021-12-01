### NAVIGASI DAN RUTE
## Desin APlikasi 
Pembangunan aplikasi bergerak multi halaman. Aplikasi yang dikembangkan berupa kasus daftar barang belanja. Pada aplikasi ini anda akan belajar untuk berpindah halaman dan mengirimkan data ke halaman lainnya.Desain aplikasi menampilkan sebuah ListView widget yang datanya bersumber
dari List. Ketika item ditekan, data akan dikirimkan ke halaman berikutnya.

## Navigator
Perpindahan halaman di Flutter, ditangani oleh Navigator dengan melibatkan konsep
sebagai berikut:
- Navigator: sebuah widget yang mengatur tumpukan (struktur data stack) dari obyek rute
- Route: sebuah obyek yang merepresentasikan tampilan, umumnya diimplementasikan oleh class seperti MaterialPageRoute

Sebuah Route umumnya dimasukkan (push) atau diambil (pop) dari dan ke tumpukan
Navigator. Ketika sebuah halaman dilakukan operasi push, maka halaman tersebut akan
diletakkan di atas halaman yang memanggilnya. Ilustrasi tersebut dapat anda lihat pada
gambar berikut. Dan jika pop dipanggil (tombol back ditekan) maka aplikasi akan
menampilkan halaman sebelumnya. Selain itu Flutter juga mendukung adanya penamaan
Route yang didefinisikan di awal.

## Mendefinisikan route
Mendefinisikan Route untuk penamaan route harus bersifat unique.

## Berpindah Halaman
Sebelum melakukan perpindahan halaman  dibutuhkan proses pemodelan data sesuai dengan desain mockup yang dibuat sebelumnya.

## Pengiriman Data
Untuk melakukan pengiriman data ke halaman berikutnya, cukup menambahkan informasi arguments pada penggunaan Navigator

## Pembacaan Data
Pembacaan nilai yang dikirimkan pada halaman sebelumnya dapat dilakukan
menggunakan ModalRoute. Tambahkan
