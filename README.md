# Program yang saya buat adalah sebuah Rest Server sederhana, dimana pihak lain bisa terhubung dengan database untuk berkomunikasi melalui Rest Server, baik untuk get, tambah,   edit dan hapus data dengan keluaran data JSON.
# Bahan yang saya gunakan adalah sebagai berikut;
  - Bahasa Pemrograman PHP
  - Framework Codeigniter
  - libraries Rest Server dari Chriskacerguis
  - Postman sebagai alat uji.

# Rest Server yang saya buat belum menggunakan autentikasi.
  
# ketika request dengan Get tanpa id, maka respon keluarannya seluruh produk. Sedangkan jika request dengan id, maka respon keluarannya produk berdasarkan id. apabila request     id tidak diketahui, maka respon keluarannya sebuah pesan "id tidak ditemukan".
# ketika request dengan post atau untuk menambahkan data, dianggap data yang diinput sudah benar karena program ini masih belum menggunakan validasi. begitu juga untuk           request dengan put atau untuk mengedit data.
# ketika request dengan delete maka id harus tersedia untuk menghapus produk yang dimaksud, apabila id tidak tersedia maka responnya sebuah pesan 'id tidak ada'.

# database yg digukanan berada pada folder database
# controllers/api/Produk.php controller untuk rest servernya
