# LP5DPBO2024C2

## Janji
Saya Jasmine Noor Fawzia [2200598] mengerjakan soal LP5 dalam Mata Kuliah DPBO untuk keberkahan-Nya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan Aamiin

## Desain Program
**1. Kelas Mahasiswa.java**

Kelas ini merepresentasikan entitas mahasiswa dengan atribut NIM, nama, jenis kelamin, dan status mahasiswa. Ini berfungsi sebagai model data untuk informasi mahasiswa, juga terdapat setter dan getter pada setiap atributnya.

**2. Kelas Menu.java**

Kelas ini adalah kelas utama yang mengatur GUI dan logika aplikasi sederhana dalam manajemen data mahasiswa. Mendefinisikan komponen-komponen GUI seperti tabel, label, teks field, button, combo box, dan radio button. Komponen-komponen tersebut berasal dari _Menu.form_ yang telah dibuat sebelumnya. Kemudian terdapat event listeners untuk menangani interaksi pengguna dan menyediakan logika untuk menambahkan, mengubah, dan menghapus data mahasiswa di dalam form khususnya untuk setiap button yang ada. Method _main_ digunakan untuk membuat objek window atau tampilan di aplikasi. Data mahasiswa disimpan dalam list, list mahasiswa ditampung di dalam method _populateList_. Melakukan setting untuk combo box dan radio button. Untuk menggunakan aplikasi (crud data) menggunakan berbagai method _setTable_, _insertData_, _updateData_, _deleteData_, dan _clearForm_.

## Penjelasan Alur
Pada instansiasi GUI, program dimulai dengan membuat instance dari kelas Menu pada metode main(). Di sini, jendela utama (window) ditampilkan dengan ukuran dan tata letak yang telah ditentukan. Kemudian komponen-komponen GUI di dalam kelas menu seperti tabel, label, teks field, button, combo box, dan radio button. Semua komponen ini ditambahkan ke panel utama.

Populasi data untuk mengisi list mahasiswa dengan data awal menggunakan metode populateList(). Data ini digunakan untuk mengisi tabel pada GUI. Mengelompokkan RadioButton untuk status mahasiswa sehingga hanya satu status yang dapat dipilih pada satu waktu. Menampilkan data pada form ketika pengguna mengklik sebuah baris pada tabel, data mahasiswa yang sesuai akan ditampilkan di teks field, combo box, dan radio button pada form.

Event handling dengan action listeners untuk tombol-tombol seperti "Add/Update", "Delete", dan "Cancel". Ketika pengguna berinteraksi dengan tombol-tombol ini, logika aplikasi akan dieksekusi sesuai dengan aksi yang diperlukan. Manipulasi data ketika pengguna menekan tombol "Add/Update", data mahasiswa akan dimasukkan atau diperbarui dalam list mahasiswa sesuai dengan inputan pengguna. Setiap kali data mahasiswa berubah, method setTable() dipanggil untuk memperbarui tampilan tabel dengan data yang terbaru.

Method untuk menambah, mengubah, dan menghapus data menggunakan metode insertData(), updateData(), dan deleteData() untuk menangani operasi-operasi tersebut. Method clearForm() digunakan untuk membersihkan semua inputan dan mengatur kondisi form kembali ke keadaan awal. Metode getStatusMhs() digunakan untuk mengambil status mahasiswa dari radio button yang dipilih. Konfirmasi hapus digunakan sebelum menghapus data mahasiswa, menampilkan prompt konfirmasi untuk memastikan pengguna benar-benar ingin menghapus data.

## Dokumentasi saat Program Dijalankan
1. Tampilan awal
<img width="393" alt="tampilan awal" src="https://github.com/jasminefwz/LP5DPBO2024C2/assets/147362810/dfb60406-cedc-4541-880a-a7c96424fd6c">

2. Proses insert data
<img width="393" alt="1" src="https://github.com/jasminefwz/LP5DPBO2024C2/assets/147362810/3aca8427-2795-4d0d-afe3-a1695c98dba0">
<img width="395" alt="2" src="https://github.com/jasminefwz/LP5DPBO2024C2/assets/147362810/814d4c3c-2a48-4afc-82f6-94071cffb869">
<img width="393" alt="3" src="https://github.com/jasminefwz/LP5DPBO2024C2/assets/147362810/62ffb32e-0cac-4ad8-a1c5-72adefffb026">

3. Proses update data
<img width="393" alt="1" src="https://github.com/jasminefwz/LP5DPBO2024C2/assets/147362810/0c1ce686-f466-4aff-8d84-d1d286a20959">
<img width="393" alt="2" src="https://github.com/jasminefwz/LP5DPBO2024C2/assets/147362810/da783ee5-5b1a-451c-895a-bc8ae648a1c6">
<img width="395" alt="3" src="https://github.com/jasminefwz/LP5DPBO2024C2/assets/147362810/918a12ab-ee26-4ce7-8cfe-97eac495f321">

4. Proses delete data
<img width="393" alt="1" src="https://github.com/jasminefwz/LP5DPBO2024C2/assets/147362810/114a8971-149a-443f-b04c-427d81c08235">
<img width="395" alt="2" src="https://github.com/jasminefwz/LP5DPBO2024C2/assets/147362810/3fb22aac-59d3-45ae-8fe4-0e0f3dce9195">
<img width="395" alt="3" src="https://github.com/jasminefwz/LP5DPBO2024C2/assets/147362810/22b504b1-893a-4047-b4c1-0dd261a6dbd2">

5. Tampilan hasil crud
<img width="271" alt="tampilan hasil crud" src="https://github.com/jasminefwz/LP5DPBO2024C2/assets/147362810/bda0265a-9f87-41e2-91c6-177fc5887cd3">
