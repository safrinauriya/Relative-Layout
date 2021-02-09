# Relative-Layout
Relative Layout adalah jenis layout yang memiliki karakteristik dalam menempatkan view secara relative. Penataan layout pada Relative Layout dengan menempatkan widget-widget didalamnya seperti layer, sehingga sebuah widget dapat berada di atas/ di bawah widget lainnya atau penataannya lebih bebas (Relative) sehingga bisa di tata dimana saja. Desain tampilan Relative Layout pada aplikasi dengan tata letak objek atau komponen secara bebas tanpa aturan sesuai orientasi (horizontal atau vertical) seperti yang diterapkan pada Linear Layout. Jika tidak di tetapkan, maka objek dapat menumpuk antara satu objek dengan objek yang lain.

# Linear-Layout
LinearLayout merupakan susunan tata letak yang paling sederhana dapat digunakan para developer android. Kesederhanaan tersebut membuat penggunaan menjadi lebih mudah namun pada akhirnya harus membatasi fleksibilitas penataan tata letak tampilan. Linear Layout ialah jenis layout dimana user menempatkan 1 objek per baris atau kolom secara sejajar. Di dalam setiap baris atau kolom hanya ada 1 objek yang bisa ditempatkan Linear Layout ada dua jenis yaitu:
-	Linear Layout Vertical (Objek per baris/ kesamping)
-	Linear Layout Horizontal (Objek per kolom/kebawah)

# Constraint Layout
Constarint Layout memungkinkan kita membuat tata letak yang besar dan kompleks dengan tampilan datar. Contstraint Layout merupakan pengembangan dari Relative Layout karena semua tampilan ditata berdasarkan hubungan antara satu objek dengan yang lain, tetapi lebih fleksibel daripada RelativeLayout. Layout ini pula didesain untuk lebih mudah menempatkan objek dengan cara diseret dan dilepaskan pada editor Layout, Android Studio.

# Perbedaan 
- Linear Layout: mengikuti ukuran layer handphone yang berbeda-beda tanpa merubah susunan objek
- Relative Layout: hanya akan terlihat sesuai dengan apa yang telah ditetapkan sebelumnya jika ukuran layar berubah bisa saja objek ada yang terpotong atau bahkan tidak terlihat
- Constraint Layout: lebih flexible dan mudah bagi pengguna untuk membuat desain layout yang lebih kompleks

# onCreate
onCreate() adalah kondisi awal saat Activity baru diciptakan, biasanya dilakukan untuk menginisialisasi suatu activity. onCreate dipanggil dengan perintah setContentView(int) untuk resource yang didefinisikan di layout UI, dengan perintah findViewById(int) untuk memanggil widget yang dibutuhkan UI untuk berinteraksi dengan aplikasi. Ketika sebuah activity dibuat, pada method inilah kita melakukan inisialisasi seperti create, view, list data, dan lain-lain. Method onCreate() selalu diikuti oleh onStart().
# onPause
onPause untuk menyatakan ketika user meninggalkan suatu activity. onPause() akan dipanggil saat ada Activity lain yang terbuka. Untuk penggunaannya dengan Context.StartActivity(), semua kelas activity harus sesuai dengan dideklarasikan dalam suatu paket di AndroidManisfest.xml. Ketika sebuah activity lainnya dipanggil atau dimulai, method ini digunakan ketika data tidak harus disimpan kedalam system secara permanen, method ini diikuti onResume() atau onStop(). Activity sudah akan bersiap-siap meninggalkan layar (masih terlihat) dan sudah tidak berinteraksi dengan pengguna. Biasanya bila perlu melakukan undo untuk pekerjaan yang dilakukan di onResume() kita lakukan di sini.

![image](https://user-images.githubusercontent.com/60589670/107395756-afae4200-6b2f-11eb-9150-565f49a1fb3a.png)
