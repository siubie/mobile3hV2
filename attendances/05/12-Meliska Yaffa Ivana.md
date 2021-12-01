## Flutter

## Apa itu FLutter
Flutter adalah sebuah framework open source yang dibuat oleh Google. Google membuat
flutter dengan tujuan membangun sebuah framework untuk membuat UI yang modern, native
dan reactive yang dapat berjalan di sistem operasi iOS maupun Android. Tidak hanya pada
smartphone google juga membuat flutter untuk desktop, web dan embedded device.

## Widget dan Element pada Flutter
Widget adalah sebuah konsep dimana UI dapat dianggap sebagai sebuah balok LEGO, sebuah
bentuk baru dapat disusun dari beberapa balok dan masing masing kumpulan balok dapat
dikombinasikan dengan kumpulan balok lain sehingga membentuk sebuah bentuk baru yang
lebih kompleks. Flutter menggunakan widget ini sebagai balok dasar pembangunan aplikasi.
Widget dapat disusun dan dikombinasikan dalam satu layar, sama halnya dengan xml
pada pemrograman android native, widget dapat disusun dalam bentuk tree dimana satu widget
menjadi parent dan widget lain menjadi child. Masing masing widget dapat diberikan
konfigurasi sesuai dengan kebutuhan aplikasi.
Flutter memiliki dua jenis widget yaitu StatelessWidget dan StatefullWidget. Stateless
widget digunakan ketika value (state /konfigurasi) dari widget tersebut tidak pernah berubah,
dan StatefullWidget digunakan ketika value (state / konfigurasi) dari widget dapat berubah.
Baik StatelessWidget maupun StatefullWidget sama sama memiliki sebuah method bernama
“build” yang memiliki BuildContext untuk mengatur posisi widget didalam widget tree detail
mengenai widget dan bagaimana membuatnya akan dibahas pada bab selanjutnya.