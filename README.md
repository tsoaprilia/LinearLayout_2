# Activity

Activity adalah komponen yang dapat dilihat oleh pengguna, sehingga mereka dapat berinteraksi dengan aplikasi. Ada dua metode yang pasti dimiliki oleh satu activity yaitu :
1. Metode OnCreate

   Di-method ini Activity sudah dimulai tapi belum terlihat oleh pengguna. Inisialisasi sebagian besar dimulai di sini. 
   Biasanya dipanggil dengan perintah setContentCiew(int) untuk resource yang didefinisikan di layout UI, dengan perintah findViewById(int)  untuk  memanggil  widget  yang  dibutuhkan UI untuk  berinteraksi  dengan aplikasi.
   
2. Metode OnPause
    
   Di method ini ativity sudah akan bersiap-siap meninggalkan layar (masih terlihat) dan sudah tidak berinteraksi dengan pengguna. Metode onPause() digunakan untuk 
   menjeda atau menyesuaikan operasi yang tidak boleh dilanjutkan sementara. Untuk penggunaan dengan Context.StartActivity(), semua kelas activity harus sesuai dengan yang dideklarasikan 
   dalam suatu paket di AndroidManifest.xml. Activity adalah bagian penting dari model aplikasi.
   

# Layout

Layout adalah suatu tampilan tata letak di Android untuk mengatur penempatan teks, gambar, ataupun komponen lainnya sehingga tampilan pada aplikasi yang dibuat terlihat 
rapih dan nyaman untuk dilihat oleh pengguna. [ Baca Selengkapnya...](https://www.codepolitan.com/mempelajari-layout-pada-android-studio)

# View

View adalah komponen pada aplikasi android yang membuat pengguna dapat berinteraksi langsung dengan aplikasi. Contohnya : Button, Text View, Check Box, Image View, Radio Batton.
[ Baca Selengkapnya...](https://gatekno.net/perbedaan-view-dan-viewgroup-android/)

1.	TextView, komponen yang berguna untuk menampilkan teks ke layar.
2.	Button, komponen yang membuat pengguna dapat berinteraksi dengan cara ditekan untuk melakukan sesuatu.
3.	ImageView, Komponen untuk menampilkan gambar.
4.	ListView, komponen untuk menampilkan informasi dalam bentuk list.
5.	GridView, komponen untuk menampilkan informasi dalam bentuk grid.
6.	RadioButton, komponen yang memungkinkan pengguna dapat memilih satu pilihan dari berbagai pilihan yang disediakan.
7.	Checkbox, komponen yang memungkinkan pengguna dapat memilih lebih dari satu dari pilihan yang ada

# ViewGroup

sebuah obyek yang mewadahi obyek-obyek view dan viewgroup itu sendiri sehingga membentuk satu kesatuan tampilan aplikasi yang utuh. 

Contoh komponen viewgroup adalah:
1. LinearLayout 

   LinearLayout merupakan salah satu jenis ViewGroup yang susunan letaknya paling sederhana dan memiliki konsep utama yang menyejajarkan semua anak dalam satu arah, secara vertikal atau horizontal.
   - Linear Layout Vertical (Objek per baris/kesamping)
   - Linear Layout Horizontal (Objek per kolom/kebawah).

2. FrameLayout 

   Frame Layout adalah Layout yang biasanya digunakan untuk membuat objek yang saling bertindihan contohnya yaitu kita membuat button di atas image.

3. RelativeLayout 

   RelativeLayout merupakan layout yang paling mudah kita terapkan, posisi dari masing-masing komponennya saling terkait dengan komponen lainnya. desain tampilan pada aplikasi dengan tata letak komponenya lebih bebas (Relative) sehingga bisa di tata di mana saja.
   Penataannya bisa di sisi kanan, kiri, atas, maupun bawah dari komponen/objek lain. Selain itu penataannya bisa bertumpukan antara komponen/objek satu dengan yang lainnya.
   
   Ada banyak sekali command command untuk mengatur di dalam Relative Layout antara lain yaitu layout_below , allignParrentBottom , allignParrentTop dll.

4. TableLayout 

   Table Layout adalah Layout yang digunakan untuk membangun user interface (tampilan antar muka ) aplikasi android dengan berdasarkan Baris dan Kolom. Tabel layout terdiri dari: row/baris, dan kolom.

5. ConstrainLayout 
   
   ConstrainLayout merupakan salah satu komponen ViewGroup yang dapat kita gunakan untuk menyusun tampilan aplikasi yang kompleks tanpa adanya nested layout.
   ConstraintLayout memiliki kesamaan dengan RelativeLayout. Dalam penggunaan semua view yang berada di dalamnya disusun berhubungan antara parent dan view lainnya. Tapi ConstraintLayout lebih fleksibel dari RelativeLayout dan mudah digunakan dengan dukungan 
   Layout Editor pada Android Studio. 
   
# Linear Layout

![WhatsApp Image 2021-02-09 at 19 49 23](https://user-images.githubusercontent.com/60412314/107367593-14f33a80-6b12-11eb-930a-bb6c64d8ee73.jpeg)

# Relative Layout

![WhatsApp Image 2021-02-09 at 21 04 56](https://user-images.githubusercontent.com/60412314/107374755-846d2800-6b1a-11eb-9e9e-d341e4a33609.jpeg)

# Kesimpulan 1
Activity adalah komponen yang dapat dilihat oleh pengguna, sehingga mereka dapat berinteraksi dengan aplikasi. Ada dua metode yang pasti dimiliki oleh satu activity yaitu metode OnCreate dan metode OnPause.
Metode OnCreate digunakan untuk menginisiasi suatu activity, biasanya dipanggil dengan perintah setContentCiew(int) dan findViewById(int). Sedangkan Metode OnPause digunakan untuk menyatakan ketika user meninggalkan suatu activity, 
untuk penggunaan dengan Context.StartActivity().

# Kesimpulan 2
Jadi Perbedaan dari LinearLayout, RelativeLayout,constrainLayout yaitu terdapat pada susunan-susunan komponen yang ada pada masing-masing layout tersebut dan sifatnya.

Pada ConstrainLayout lebih memanjakan pengguna untuk mengatur layoutnya sendiri secara faksible dan bersifat mudah dibuat.
Pada RelativeLayout pengaturan bersifat sangat relatif yang memungkinkan untuk membuat desain layout yang lebih kompleks dan dapat secara bebas mengatur objek objek yang kita tempatkan, tetapi pada relative layout tampilannya hanya akan terlihat sesuai dengan apa 
yang telah ditetapkan sebelumnya jika ukuran layar berubah bisa saja objek ada yang terpotong atau bahkan tidak terlihat. Sedangkan pada LinearLayout sendiri membuat perubahan pada bentuk layout secara Horizontal dan Vertical, LinearLayout bisa mengikuti ukuran layar handphone yang berbeda-beda tanpa merubah susuan objek.

# Terimakasi :)
