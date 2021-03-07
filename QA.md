## QA
1. Sebutkan 3 Kesalahan besar yang paling sering dilakukan oleh QA lalu berikan solusi agar tidak terjadi atau
terulang kembali?
Jawab:
##### Kesalahan yang sering dilakukan
- Knowledge gap mengenai business flow dan fungsional dari sistem dengan tim produk/analis/product owner/developer
- Tidak mendefinisikan dan mengimplementasikan test plan dengan scenario yang ditentukan, baik fungsional(positif case) dan negative case
- Kurang mengimplementasikan whitebox testing, cenderung dominan blackbox testing

##### Solusi
- Menggali lebih dalam mengenai business flow dan fungsional berdasarkan spesifikasi kebutuhan dan desain sistem yang yang telah ditentukan, independen dan tidak bergantung hanya dengan developer
- Menyusun dan mengeksekusi test plan berdasarkan spesifikasi dan kebutuhan sistem
- Mencari tahu bagaimana flow data dari inputan menjadi output dari logic kode program, sebagai bentuk early detection dari bug

2. Jelaskan point-point terpenting yang harus diperhatikan Dalam menganalisa dan membuat Skenario Test ? Jawab :
- Requirement dan desain sistem, QA harus paham scope dari kebutuhan dan desain sistem
- Coverage test case, test case dapat menguji sistem secara keseluruhan baik dari test yang paling mudah hingga kompleks
- Repeatable, test case harus mempunyai kondisi hasil yang sama di seluruh platform yang sedang dites. Misalnya di Android setelah login, maka akan tampil halaman home maka di ios harus sama juga
- End user oriented, memiliki mindset end user, karena pengguna menginginkan sistem yang berfungsi tanpa gangguan


Buatlah Skenario Test UI, Skenario Test API dan Automation Testing untuk Fitur :
1. Login Organisasi memasukan nama organisasi
2. Login user dan password

UI : https://taskdev.mile.app/login

Untuk Automation menggunakan Katalon :

org_name = testonboard
user password : pakai data asal saja untuk test skenario gagal login.

API : ** inspek di browser dan perhatikan networknya hit ke endpoint mana

Kirim jawaban berupa Link Repositori GIT berisi Jawaban, skenario test dan automation katalon ke email
rifai@paket.id, nelly@paket.id