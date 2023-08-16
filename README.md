# simple-cashier
Ini merupakan program kasir sederhana dengan menggunakan object, instance, class, method init, dan list. Pada program menu_item memungkinkan pengguna untuk memilih item dari menu yang tersedia dan memasukkan jumlah pesanan. Setelah itu, program akan menghitung total harga berdasarkan item yang dipilih dan jumlah pesanan.

Pertama-tama, program ini mengimpor class MenuItem dari file menu_item. Kemudian, program membuat empat instance dari class MenuItem dengan nama menu_item1, menu_item2, menu_item3, dan menu_item4. Setiap instance mewakili item menu yang berbeda dengan nama dan harga yang berbeda.

Selanjutnya, program membuat list bernama menu_items yang berisi keempat instance MenuItem yang telah dibuat sebelumnya. Program kemudian menampilkan daftar menu dengan menggunakan loop for untuk mengulangi setiap item dalam list menu_items. Dalam setiap iterasi, program mencetak indeks dan informasi tentang item menu yang sedang diulangi.

Setelah menampilkan daftar menu, program meminta pengguna untuk memasukkan nomor menu yang ingin dipesan. Pengguna memasukkan nomor menu sebagai input dan program menyimpan input tersebut dalam variabel bernama order. Program kemudian menggunakan variabel order sebagai indeks untuk mengakses item yang dipilih dari list menu_items dan menyimpannya dalam variabel bernama selected_menu.

Selanjutnya, program meminta pengguna untuk memasukkan jumlah pesanan. Pengguna memasukkan jumlah pesanan sebagai input dan program menyimpan input tersebut dalam variabel bernama count. Program kemudian memanggil method get_total_price pada instance selected_menu dengan memberikan argumen count. Method ini mengembalikan total harga yang kemudian disimpan dalam variabel bernama result.

Terakhir, program mencetak total harga dengan menggunakan variabel result. Total harga dihitung dengan mengalikan harga item yang dipilih dengan jumlah pesanan. Jika jumlah pesanan lebih dari atau sama dengan 3, maka akan diberikan diskon sebesar 10%.


Kode program ini mendefinisikan sebuah class bernama `MenuItem`. Class ini memiliki tiga method: `__init__`, `info`, dan `get_total_price`.

Method `__init__` adalah method khusus yang disebut constructor. Method ini dipanggil secara otomatis saat sebuah instance dari class `MenuItem` dibuat. Method ini menerima dua argumen: `name` dan `price`. Argumen `name` mewakili nama item menu, sedangkan argumen `price` mewakili harga item menu. Dalam method ini, nilai dari argumen `name` dan `price` disimpan sebagai atribut instance dengan nama yang sama.

Method `info` adalah method yang mengembalikan informasi tentang item menu dalam bentuk string. Method ini tidak menerima argumen apa pun. Dalam method ini, atribut instance `name` dan `price` digunakan untuk membuat string yang berisi informasi tentang item menu. String ini kemudian dikembalikan sebagai nilai return dari method.

Method `get_total_price` adalah method yang menghitung total harga berdasarkan jumlah pesanan. Method ini menerima satu argumen bernama `count` yang mewakili jumlah pesanan. Dalam method ini, total harga dihitung dengan mengalikan atribut instance `price` dengan argumen `count`. Jika nilai dari argumen `count` lebih besar dari atau sama dengan 3, maka total harga dikalikan dengan 0.9 untuk memberikan diskon sebesar 10%. Total harga kemudian dibulatkan ke bilangan bulat terdekat menggunakan fungsi `round` dan dikembalikan sebagai nilai return dari method.

Secara keseluruhan, class `MenuItem` ini memungkinkan pembuatan instance yang mewakili item menu dengan nama dan harga tertentu. Instance tersebut dapat memberikan informasi tentang item menu dan menghitung total harga berdasarkan jumlah pesanan.

Berikut output program :

<img width="920" alt="image" src="https://github.com/CharlesD12/simple-cashier/assets/78160523/b2387dd2-32ad-4754-bb37-9bd1069c859d">

