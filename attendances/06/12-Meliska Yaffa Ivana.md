### Basic Aplikasi FLutter

## Struktur Project Flutter

# 1.Struktur folder
Strukturnya terdiri dari .dart_tool, .idea, android, ios, lib, test, .gitignore, .metadata, .packages, .flutter_basic.iml, pubspec.lock, pubspec.yaml, README.md.

# 2. Multi os ios dan android
Perhatikan pada folder project flutter terdapat dua folder yaitu folder ios dan folder
android, dengan menggunakan kedua folder tersebut flutter dapat membuat aplikasi berbasis
ios dan berbasis android dalam satu project.

# 3. Folder android
Folder android berisi file file pendukung untuk mengenerate project android dan akan
dikompilasi menjadi sebuah apk pada folder build. Namun anda jarang atau bahkan tidak
perlu mengedit yang ada di folder android. Anda akan banyak bekerja di folder lib.

# 4. Folder ios
Berisi project ios, folder ini sama dengan folder android, sangat jarang dan bahkan
tidak perlu untuk mengubah apapun pada folder ios. Folder ios dan android dikelola oleh
flutter sdk yang akan dimerge (disatukan) dengan code yang ada di folder lib untuk membuat
aplikasi ios dan android.

# 5. Folder lib 
Folder lib berisi kode program dengan bahasa dart yang berupa widget yang dapat
dibuat sesuai dengan kebutuhan aplikasi anda.

# 6. Folder test
Berisi source code dart yang digunakan untuk melakukan test secara otomatis pada
aplikasi flutter.

# 7. Pubspec.yaml
Pada file ini berisi konfigurasi konfigurasi project flutter yang dibuat dimana anda
dapat mendata asset berupa font, gambar dan lain lain. Pada file ini anda juga dapat
mengkonfigurasi flutter sdk dan konfigurasi yang terkait flutter.