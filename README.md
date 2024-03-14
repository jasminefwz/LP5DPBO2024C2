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

Populasi data untuk mengisi list mahasiswa dengan data awal menggunakan metode populateList(). Data ini digunakan untuk mengisi tabel pada GUI.

Mengelompokkan RadioButton untuk status mahasiswa sehingga hanya satu status yang dapat dipilih pada satu waktu.

Event handling dengan action listeners untuk tombol-tombol seperti "Add/Update", "Delete", dan "Cancel". Ketika pengguna berinteraksi dengan tombol-tombol ini, logika aplikasi akan dieksekusi sesuai dengan aksi yang diperlukan.

Menampilkan Data pada Form: Ketika pengguna mengklik sebuah baris pada tabel, data mahasiswa yang sesuai akan ditampilkan di teks field, combo box, dan radio button pada form.

Manipulasi Data: Ketika pengguna menekan tombol "Add/Update", data mahasiswa akan dimasukkan atau diperbarui dalam list mahasiswa sesuai dengan inputan pengguna.

Pembaruan Tabel: Setiap kali data mahasiswa berubah, Anda memanggil metode setTable() untuk memperbarui tampilan tabel dengan data yang terbaru.

Konfirmasi Hapus: Sebelum menghapus data mahasiswa, Anda menampilkan prompt konfirmasi untuk memastikan pengguna benar-benar ingin menghapus data.

Metode untuk Menambah, Mengubah, dan Menghapus Data: Anda memiliki metode insertData(), updateData(), dan deleteData() untuk menangani operasi-operasi tersebut.

Clear Form: Metode clearForm() digunakan untuk membersihkan semua inputan dan mengatur kondisi form kembali ke keadaan awal.

Method untuk Mengambil Status Mahasiswa: Metode getStatusMhs() digunakan untuk mengambil status mahasiswa dari radio button yang dipilih.

## Dokumentasi saat Program Dijalankan
