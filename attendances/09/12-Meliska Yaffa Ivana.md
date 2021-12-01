### STATEFULL WIDGET DAN MAP

## List
Sebelum masuk pada praktikum akan dijelaskan pengantar tentang List pada Dart. List adalah
collection yang seperti pada bahasa pemrograman yang lain. Pada bahasa pemrograman Dart,
array adalah list of object sehingga disebut juga dengan list.

//contoh list of integer
var list = [1, 2, 3];
//contoh list of string
var list = [ 'Car', 'Boat', 'Plane', ];

List pada Dart mengguna index 0 sebagai nilai awal dan list.length – 1 adalah index nilai
terakhir dari sebuat list.
Untuk membuat list pada saat compile time dapat menggunakan const

## Mulai Dart 2.3 dikenalkan spread operator (…) dan null-aware spread operator (…?)
yang digunakan insert banyak nilai ke collection. Contohnya pada source code di bawah ini,
digunakan untuk memasukkan nilai dari list ke list2.
var list = [1, 2, 3];
var list2 = [0, ...list];
print(list2.length == 4);

## menggunakan null-aware spread operator
Untuk menghindari exception ketika list bernilai null.
var list;
var list2 = [0, ...?list];
print(list2.length == 1);

## collection if dan collection for 
Yang digunakan untuk membuat collection dengan kondisi dan repetisi / perulangan. 




