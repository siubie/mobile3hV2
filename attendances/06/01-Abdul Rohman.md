<H2>STRUKTUR PROJECT FLUTTER</H2><br>
1.	Multi os ios dan android<br>
Perhatikan pada folder project flutter terdapat dua folder yaitu folder ios dan folder<br>
android, dengan menggunakan kedua folder tersebut flutter dapat membuat aplikasi berbasis<br>
ios dan berbasis android dalam satu project.<br>
2.	Folder android<br>
Folder android berisi file file pendukung untuk mengenerate project android dan akan<br>
dikompilasi menjadi sebuah apk pada folder build. Namun anda jarang atau bahkan tidak<br>
perlu mengedit yang ada di folder android. Anda akan banyak bekerja di folder lib.<br>
3.	Folder ios<br>
Berisi project ios, folder ini sama dengan folder android, sangat jarang dan bahkan<br>
tidak perlu untuk mengubah apapun pada folder ios. Folder ios dan android dikelola oleh<br>
flutter sdk yang akan dimerge (disatukan) dengan code yang ada di folder lib untuk membuat<br>
aplikasi ios dan android. <br>
4.	Folder lib <br>
Folder lib berisi kode program dengan bahasa dart yang berupa widget yang dapat <br>
dibuat sesuai dengan kebutuhan aplikasi anda. <br>
5.	Folder test <br>
Berisi source code dart yang digunakan untuk melakukan test secara otomatis pada <br>
aplikasi flutter. <br>
6.	Pubspec.yaml <br>
Pada file ini berisi konfigurasi konfigurasi project flutter yang dibuat dimana anda <br>
dapat mendata asset berupa font, gambar dan lain lain. Pada file ini anda juga dapat <br>
mengkonfigurasi flutter sdk dan konfigurasi yang terkait flutter. <br>
