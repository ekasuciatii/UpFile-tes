                                                    # _**CMS Modul Penjadwalan dan Presensi pada Sistem Informasi Sekolah Menengah Pertama (SMP)**_

**Eka Suciati**

_Program Studi Informatika Fakultas Teknologi Industri_

_Universitas Islam Indonesia_

_Jl. Kaliurang km 14 Yogyakarta 55510_

[_16523213@students.uii.ac.id_](mailto:16523213@students.uii.ac.id)

**Nur Wijayaning Rahayu**

_Program Studi Informatika Fakultas Teknologi Industri_

_Universitas Islam Indonesia_

_Jl. Kaliurang km 14 Yogyakarta 55510_

[045230104@uii.ac.id](mailto:045230104@uii.ac.id)

_ **Abstrak** _ **—**** Sebuah sistem informasi sekolah yang fleksibel sangat dibutuhkan bagi banyak instansi pendidikan seperti sekolah menengah pertama. Hal ini dikarenakan kebutuhan dan kebijakan pada setiap sekolah tidak selalu sama. Sehingga pada penelitian ini membahas mengenai pengembangan sebuah sistem yang lebih fleksibel untuk modul penjadwalan dan presensi, serta bagaimana untuk dapat mengetahui tingkat kegunaan/efisiensi dari sistem. Sistem ini dibangun menggunakan CMS. **_** Content Management System **_** (CMS) merupakan suatu sistem yang umum digunakan untuk mengelola suatu konten. Konten akan dikelola secara terpisah dari tampilan yang disajikan. CMS untuk manajemen penjadwalan dan presensi penting dalam lembaga pendidikan. Hal ini berguna dalam mengelola informasi yang terkait dengan siswa, guru, dan berguna untuk memaksimalkan kinerja. Sistem presensi siswa yang dikembangkan pada penelitian dapat **** menganalisis data serta menampilkan data berupa laporan akhir mengenai presensi siswa, dan mencetak laporan untuk periode yang ditentukan. Sedangkan sistem penjadwalan yang dikembangkan pada penelitian dapat mengelola penjadwalan mata pelajaran, guru piket, kelas tambahan, serta kegiatan ekstrakurikuler.**

_ **Kata kunci:** _ _ **SIS, Penjadwalan, Presensi, CMS.** _

1.
# **PENDAHULUAN**

Saat ini, pemanfaatan suatu teknologi informasi merupakan hal yang penting, contohnya seperti pemanfaatan teknologi informasi di lingkungan sekolah yang telah menjadi suatu keharusan. Dalam penerapannya, sistem informasi akademik belum sepenuhnya dapat memenuhi dan sesuai dengan kebutuhan sekolah. Sebelum memulai kegiatan belajar mengajar, tentunya perlu adanya penyusunan atau perencanan yang baik mengenai penjadwalan untuk mata pelajaran setiap kelas, dan jadwalguru [1]. Pada beberapasekolah,jadwalkelas siswaterbagikedalamdua jenis yaitu kelas regular, tambahan dan aktivitas di luar jam KBM. Penjadwalan kelas reguler merupakan sistem penjadwalan untuk setiap kelas yang dilaksanakan pada jam KBM [2]. Penjadwalan kelas tambahan yaitu sistem penjadwalan untuk kegiatan tambahan (les) yang diadakan untuk siswa tingkat akhir. Sedangkan sistem penjadwalan untuk aktivitas di luar jam KBM merupakan jadwal kegiatan ekstrakurikuler [2]. Sedangkan jadwal guru terbagi kedalam jadwal untuk guru mata pelajaran dan guru piket. Tidak hanya itu, beberapa sekolahmembagi lagi jenis jadwal menjadi jadwal prioritas dan khusus. Selain proses penjadwalan **,** di setiap SMP tentunya akan ada proses presensiharianuntuk siswa.

_Content Management System_ (CMS) dapat menjadi solusi yang baik terhadap permasalahan tersebut. CMS merupakan sistemyangdigunakanuntukmemudahkanpengirimanataupenyampaianinformasi. CMS juga termasuk kedalam sistem berbasis web yang umum digunakan untuk mengatur suatu konten informasi secara terpisah dari tampilan informasi yang disajikan [3]. Tujuan dari dikembangkannya CMS ini, karena CMS dapat memudahkan setiap sekolah dalam mengakomodasi kebutuhan untuk dapat melakukan kustomisasi sistem secara komprehensif, dapatmengelola kontendari sistem tersebut dengan mudah, fleksibel, dapat dilakukan secara mandiri, dan dapat menjadi standarsisteminformasiSekolahMenengahPertama(SMP)diSleman dan Yogyakarta[1][4][5]. Selain itu, dikembangkannya sistem ini juga bertujuan untuk dapat memberikan kemudahan yang lebih lagi, sehingga pengguna dapatmengelola informasi khususnya modul penjadwalan dan modul presensi tanpa pengguna harus mengetahui atau menguasai hal-hal yang teknis.

Sistem ini telah dikembangkan sebelumnya, namun masih terdapat kekurangan-kekurangan pada fitur dan teknologi yang digunakan. Pada penelitian sebelumnya yang dilakukan oleh [2][6] telah dikembangkan Sistem Informasi Sekolah khususnya untuk modul penjadwalan dan presensi. Dalam upaya untuk dapat memberikan kemudahan yang lebih kepada sekolah menengah pertama di Sleman dan Yogyakarta, khususnya SMP N 8 Yogyakarta dan SMP Piri yang juga merupakan target pada penelitian ini, maka sistem yang telah ada sebelumnya dikembangkan kembali menjadi suatu CMS Sistem Informasi SMP.

Kebutuhan dan kebijakan setiap sekolah tidak selalu sama. Contohnya seperti kebutuhan sekolah terhadap laporan presensi yang diinginkan berbeda, sistem penyusunan jadwal juga berbeda, terdapat sekolah yang memiliki jadwal prioritas maupun khusus. Sehingga pada penelitian ini, dikembangkan CMS untuk modul penjadwalan dan modul presensi. Dilakukan perubahan mulai dari arsitektur sistem. Pengembangan CMS pada penelitian ini dilakukan dengan menggunakan arsitektur HMVC _(Hierarchical Model-View-Controller)_ yang secara hierarki dan memberikan batas secara jelas untuk setiap modul [7]. CMS dikembangkan untuk dapat membuat sekolah lebih mudah dalam mengakomodasi kebutuhan untuk dapat melakukan kustomisasi terhadap sistem. CMS menjadikan sebuah sistem menajdi lebih adaptif untuk dapat mengakomodasi perkembangan kebutuhan tersebut.

1.
# **KAJIAN PUSTAKA**

  1.
## Sistem Informasi Siswa (SIS)

SIS merupakan suatu sistem informasi yang berguna untuk mengelola administrasi sekolah atau sistem administrasi bagi siswa seperti mendokumentasikan penilaian, pendaftaran, membangun jadwal mata pelajaran siswa, mengontrol kehadiran siswa, dan sebagainya [5]. SIS berguna juga untuk mengintegrasikan antara siswa, orang tua, guru, dan administrasi sekolah.

  1.
## CMS pada Penelitian Lainnya

_Content Management System_ (CMS) merupakan sistem yang bersifat fleksibel untuk menampilkan konten secara online. Selain itu juga mudah untuk digunakan dan dikelola. _Content Management System_ dikatakan pada penelitian [8] memiliki peran yang semakin penting dalam evolusi internet. Sekitar 50% dari seluruh halaman web yang ada, telah mengimplementasikan _Content Management System_ (CMS).

  1.
## Sistem Penjadwalan di Sekolah Lain

Pada penjadwalan dibutuhkan fleksibilitas dan juga efisien. Masalah utama yang berkaitan dengan penjadwalan seperti mata pelajaran di sekolah yang berkaitan dengan kelas, guru, dan mata pelajaran itu sendiri. Pada penelitian yang dilakukan oleh [9] di SMPIT Nurul Fajar Bogor, proses penjadwalan dilakukan dengan menggunakan pemrograman integer taklinear.

  1.
## Sistem Presensi di Sekolah Lain

Berdasarkan penelitian yang dilakukan oleh [10] presensi siswa dilakukan secara harian selama kegiatan belajar mengajar untuk mengetahui siswa yang berhalangan hadir dengan keterangan sakit, ijin, dan alpa. Sistem presensi ini menghasillkan laporan atau hasil rekap presensi yang terdiri dari rekap presensi setiap hari, setiap minggu, setiap bulan, dan juga setiap semester. Sistem Presensi ini berguna untuk monitoring yang tentunya digunakan oleh guru dan juga siswa di sekolah, Perancangan sistem yang diusulkan dapat memudahkan pengguna yaitu guru dalam melakukan monitoring kehadiran siswa setiap harinya. Sistem presensi ini dibangun dengan CMS (_Content Management System_), dimana setiap pengguna memiliki hak akses yang berbeda di sistem tersebut.

  1.
## Sistem Informasi Akademik (SIA)Modul Penjadwalan dan Presensi Sebelumnya

SIA (Sistem Informasi Akademik) pada penelitian ini merupakan kelanjutan dari penelitian yang telah dikembangkan sebelumnya. Penelitian sebelumnya dilakukan oleh beberapa mahasiswa dari Universitas Islam Indonesia. Penelitan dilakukan oleh [1], kemudian dilanjutkan oleh [2] dan [6]. Ketiga penelitian tersebut menggunakan prinsip MVC _(__Model, View,_ _Controller)_. Berdasarkanpenelitiansebelumnya, pengembangan sistem informasi ini telah mencapai tahap analisis, prototype, pengimplementasian kedalam sistem informasi, dan mengintegrasikan antar modul. Khususnya modul penjadwalan telah dapat mengelola jadwal mata pelajaran, baik itu khusus maupun prioritas, dan jadwal untuk guru piket, ekstrakurikuler, serta tambahan belajar. Sistem ini juga sudah berhasil untuk mengaksesinformasijadwalyangdiinputkan [2].Sedangkanuntukpresensi,sudah dapatmenampilkanlaporanpresensisetiapsemester,setiapbulan,danterdapatfitureksporuntuk mengunduh file data presensi [6].

  1.
## Hierarchical Models-Views-Controllers (HMVC)

HMVC merupakan salah satu arsitektur yang terdiri dari lapisan MVC yang diimplementasikan secara hierarki dan memberikan batas secara jelas untuk setiap modul [7]. Menurut [7]arsitektur HMVC memiliki beberapa keunggulan seperti (1) memudahkan dalam penukaran potongan kode (2) memungkinkan setiap modul untuk membuat _model, view, controller_ yang terpisah (3) memudahkan untuk diperluas dengan menambah atau mengganti modul (4) memudahkan kode untuk dapat digunakan digunakan kembali.

  1.
## Content Management System (CMS)

CMS atau _Content Management System_ merupakan suatu sistemyang umum digunakanuntukmemudahkanpengirimanataupenyampaianinformasi. _Content Management System_ termasuk salah satu sistem berbasis web yang digunakan untuk mengatur konten informasi secara terpisah dari tampilan informasi yang disajikan [3]. Prinsip dasar CMS terbagi menjadi dua elemen yaitu (1) CMA _(Content Management Aplication)_ dan CDA _(Content Delivery Application)_[11].

1.
# **METODE PENELITIAN**

  1.
## Validasi Sistem

    1.
### Pengecekan Sistem Sebelumnya

Perbaikan _prototype_ terhadap sistem informasi akademik untuk tingkat sekolah menengah pertama dari sistem yang telah dikembangkan sebelumnya dilakukan dengan menggabungkan modul penjadwalan dan presensi. Kemudian dilakukan pengujian kepada pihak SMP N 8 Yogyakarta dan SMP Piri sebagai sasaran pada studi kasus ini. Selanjutnya dilakukan proses pengecekan untuk mengetahui kekurangan-kekurangan dari sistem sebelumnya, sehingga dapat memudahkan dalam mengembangkan sistem informasi akademik sebelumnya menjadi CMS sistem informasi sekolah untuk SMP.

    1.
### Wawancara

Metode yang dilakukan untuk memperoleh data dari sekolah yaitu dengan wawancara dan observasi. Wawancara dilakukan dengan beberapa pihak di SMPN N 8 Yogyakarta dan SMP Piri, sepertiguru baik itu guru mata pelajaran maupun guru piket, dan juga pihak perwakilan dari kurikulum.

Dengan melakukan tahapan ini, akan dapat :

1. Membantu dalam identifikasi kendala atau kekurangan-kekurangan
2. Mendapatkan informasi lebih detail terkait sistem informasi sekolah saat ini
3. Mengetahui tentang harapan atau kebutuhan dari pihak sekolah terkait dengan pengembangan CMS untuk sistem penjadwalan dan presensi di sekolah, untuk selanjutnya dilakukan perbaikan.

  1.
## Perancangan Ulang Sistem

    1.
### Perbaikan Use Case Diagram

Pada rancangan _use case_ diagram terdapat sedikit perubahan dari sebelumnya. Hal ini dikarenakan proses yang terjadi dengan sistem sebelumnya pada kedua sekolah, khususnya untuk penjadwalan dan presensi tidak jauh berbeda. Jika sebelumnya modul presensi digambarkan dengan DFD, maka dilakukan perubahan dengan menggabungkan modul penjadwalan dan modul presensi dalam bentuk _use case_ diagram. Aktor yang berperan dalam melakukan presensi yaitu admin presensi.

    1.
### Penambahan Basis Data

Pada penelitian ini terdapat penambahan pada basis data, contohnya seperti basis data baru untuk menunjang menu tambah mapel. Penambahan basis data merupakan kebutuhan yang berfungsi untuk menunjang beberapa perubahan proses pada sistem.

    1.
### Perubahan Antarmuka

Perubahan antarmuka pada sistem ini dilakukan di beberapa submodul pada modul penjadwalan dan presensi. Perubahan yang dilakukan antara lain seperti menambah fitur menu untuk pengaturan di beberapa submodul, menambahkan tabel baru, memisahkan satu halaman menjadi dua halaman seperti menggantinya dalam tampilan pop-up, menambahkan fitur tombol edit pada beberapa halaman yang sebelumnya belum tersedia, dan menggabungkan beberapa halaman menjadi satu halaman. Berikut ini beberapa perubahan pada modul penjadwalan dan presensi antara lain:

      1.
#### Rancangan Modul Tambah Mapel

Pada modul Tambah Mapel diberikan penambahan fitur tambah otomatis yang sudah tersedia daftar nama mapel secara default. Jika sebelumnya admin harus menginputkan sendiri semua mata pelajaran secara manual, maka dengan fitur ini admin kurikulum cukup menambahkan mapel yang sesuai dengan masing-masing sekolah. Jika terdapat mata pelajaran yang belum ada pada daftar, admin kurikulum juga dapat menambahkan sendiri mapel tersebut. Nama mata pelajaran yang telah dipilih, otomatis akan hilang dari daftar mapel default dan jika nama mata pelajaran tersebut dihapus dari daftar mata pelajaran pilihan admin, maka jadwal pelajaran tersebut akan kembali muncul pada daftar mata pelajaran tambah otomatis.

      1.
#### Modul Mengelola Ekstrakurikuler

Pada modul Mengelola Ekstrakurikuler terdapat penambahan fitur pengaturan yang pada sistem sebelumnya tidak ada. Pengaturan ini digunakan untuk admin dapat menentukan jenis ekstrakurikuler yang ada pada sekolah masing-masing. Pengguna cukup menghapus ekstrakurikuler yang tidak diperlukan dan dapat menambahkan jenis ekstrakurikuler jika belum ada untuk selanjutkan disusun jadwal ekstrakurikuler pada tabmenu yang lain.

1.
# **HASIL DAN PEMBAHASAN**

Sistem Informasi pada penelitian ini dikembangkan menjadi sebuah CMS. CMS merupakan suatu sistem yang dapat memudahkan penggunanya untuk melakukan pengelolaan dengan mudah terhadap websitenya. Pada pengembangan sistem ini, CMS telah mencapai penerapan di beberapa submodul, seperti submodul Tambah Mapel dan Mengelola Ekstrakurikuler. Berikut ini merupakan hasil dari tahapan-tahapan yang telah dilakukan :

  1.
## Hasil Wawancara

Berdasarkan wawancara yang telah dilakukan dengan pihak SMP N 8 Yogyakarta dan SMP Piri, maka analisis kebutuhan terhadap sistem ini sebagai berikut:

      1.
#### Modul Penjadwalan

Pada rancangan untuk modul penjadwalan yang telah dilakukan oleh peneliti sebelumnya yaitu [2], proses penyusunan jadwal dipegang oleh bagian kurikulum dan dibagi menjadi penjadwalan untuk mata pelajaran, guru piket, tambahan, dan juga ekstrakurikuler. Setelah melakukan wawancara pada kedua SMP didapatkan data yang tidak berbeda dari sebelumnya. Dalam penyusunannya juga masih dengan cara manual dan disusun menggunakan Microsoft Excel atau juga Microsoft Word. Sehingga, berdasarkan Tabel 1 pada nomor 1 sampai 11, penelitian ini akan menambah fitur untuk dapat mengatur sendiri dengan mudah jam belajar di sekolah, dan jadwal pelajaran sesuai dengan masing-masing sekolah menengah pertama, pengaturan untuk mengelola jadwal ekstrakurikuler, tambahan, dan guru piket.

Tabel _1_. Informasi untuk Penjadwalan

| **No** | **Kategori** | **Penjadwalan** |
| --- | --- | --- |
| **SMPN N 8 Yogyakarta** | **SMP Piri** |
| 1 | Jumlah Kelas | Terdapat 10 kelas untuk setiap tingkatnya, dan satu kelas untuk siswa yang mengambil jalur SKS. | Terdapat 4 kelas untuk kelas VII dan VIII. Sedangkan kelas IX terdapat 3 kelas. |
| 2 | Jam Pelajaran |
Satu jam pelajaran terdiri dari 40 menit.
 |
| 3 | Mata Pelajaran | IPS, PPKn, Pendidikan Agama Islam, Pendidikan Agama Kristen, Pendidikan Agama Katolik, Pendidikan Agama Hindu, Bahasa Indonesia, MTK, IPA, PJOK, dan Seni Budaya. | IPS, PKN, PAI, Bahasa Indonesia, Matematika, IPA, PJOK, Seni Budaya, Prakarya, Bahasa Jawa, Bahasa Inggris |
| 4 | Pembimbing Ekstrakurikuler | Pembimbing ekstrakurikuler berasal dari guru sekolah sendiri dan juga dari pihak luar.
 |
| 5 | Jadwal Guru Piket |
Jadwal guru piket dibuat berdasarkan jadwal guru yang paling luang waktunya dalam mengajar. Semua guru berkesempatan bertugas menjadi guru piket, tergantung dari jadwal mengajar masing-masing.
 |
| 6 | Jumlah Guru Piket | Dalam satu hari terdiri dari dua orang guru piket. | Terdapat 12 orang guru yang berkesempatan bertugas menjadi guru piket. |
| 7 | Jadwal Kelas Tambahan | Kelas tambahan dilaksanakan hari Selasa, Rabu, dan Jumat. |
Terdapat mata pelajaran tambahan yaitu Dinul Islam dan Bahasa Inggris Multimedia.Kelas tamabahan dilaksanakan pada hari Selasa, Rabu, Kamis, Sabtu.
 |
| 8 | Jam Kelas Tambahan &amp; Mapel Tambahan | Jam kelas tambahan pagi dilaksanakan pukul 06.15-07.00. Sedangkan jam siang dilaksanakan setelah selesai pelajaran sehingga jumlah jam setiap pelajaran dikurangi 5 menit. Mata pelajaran yang diajarkan adalah mata pelajaran untuk UN. | Jam kelas tambahan (les) dilaksanakan pada jam ke-0 yaitu pukul 06.20-07.40. Mata pelajaran yang diajarkan yaitu Baca Tulis Al-Quran untuk kelas VII dan Mata Pelajaran UN untuk kelas VIII dan IX. |
| 9 | Jenjang Kelas Tambahan | Kelas tambahan diberikan untuk kelas VIII dan IX. | Kelas tambahan diberikan untuk kelas VII, VIII dan IX. |
| 10 | Jenis Ekstrakurikuler | Beberapa ekstrakurikuler terdiri dari ; Karya Ilmiah Remaja, Karawitan, Olimpiade IPA Junior, Olimpiade IPA Senior, Olimpiade Matematika, Pramuka, Olimpiade IPS, Bahasa Inggris, Seni Tari, Orkestra, PMR, Futsal, Pencak Silat, Basket Ball, Volley Ball, Tonti, Badminton, Karate, Paduan Suara. | Beberapa ekstrakurikuler terdiri dari ; Bola Voli, Futsal, Sepak Bola, Badminton, Seni Tari, Musik, Tonti, Multimedia, Renang, Hadroh, Pramuka. |
| 11 | Jadwal Mapel | Jadwal Mengajar dan Mata pelajaran disusun dengan tabel-tabel yang menunjukan nama guru, kelas, dan jam mengajar. |

      1.
#### Modul Presensi

Pada rancangan untuk modul presensi siswa yang telah dilakukan oleh peneliti sebelumnya yaitu [6] proses presensi yang disediakan yaitu presensi harian. Selain itu juga disediakan fitur untuk import file data presensi karena dimungkinkan terdapat kondisi bahwa presensi dilakukan tidak secara langsung dengan sistem. Setelah dilakukan wawancara kepada pihak sekolah terkait, hasil yang didapatkan sama dengan sistem presensi yang ada sebelumnya. Sehingga, berdasarkan Tabel 3.2 pada nomor 1 sampai 3, pengembangan modul presensi akan menambah fitur untuk pengaturan terhadap hak akses dan rekapitulasi presensi yang sesuai dengan masing-masing sekolah.

Tabel _2_. Informasi untuk presensi

| **No** | **Kategori** | **Presensi** |
| --- | --- | --- |
| **SMP N 8 Yogyakarta** | **SMP Piri** |
| 1 | Waktu Presensi | Presensi siswa dilakukan setiap pagi hari. | Presensi dilakukan per hari. |
| 2 | Petugas Presensi | Petugas yang melakukan presensi adalah bagian dari karyawan. | Petugas yang melakukan presensi merupakan petugas Tata Usaha (TU). |
| 3 | Cara Presensi | Presensi dilakukan dengan memasuki setiap kelas di sekolah. |

  1.
## Hasil Rancangan Ulang Sistem

1. _Perubahan Use Case Diagram_

Perubahan dan penggabungan _use case_ diagram presensi dengan penjadwalan diberi tanda dengan kotak berwarna merah seperti pada gambar. Berdasarkan perubahan yang dilakukan, berikut merupakan rancangan _use case_ diagram untuk penelitian ini seperti pada Gambar 1.

![](RackMultipart20200819-4-1a3mlot_html_603dca63f82827c1.gif)

Gambar 1. Rancangan _Use Case_ Diagram

1. _Penambahan Basis Data_

Pada menu tambah mapel diberikan tabel yang berisikan data mata pelajaran yang dapat digunakan oleh kedua sekolah tersebut. Sehingga, ditambahkan tabel pada database dengan nama mapel\_default. Tabel 3 merupakan detail tabel basis data mapel\_default:

Tabel _3_. Struktur Tabel mapel\_default

| No | Nama | TipeData | Keterangan |
| --- | --- | --- | --- |
| 1 | id\_mapel | Integer(10) | _primary key_ |
| 2 | nama\_mapel | Varchar(100) |
 |

  1.
## Hasil Perubahan Antarmuka

1. _Tampilan Tambah Mapel_

Pada submodul Tambah Mapel di modul penjadwalan ditambahkan sejenis pengaturan untuk sekolah dapat dengan mudah menambahkan jenis mata pelajaran yang terdapat di sekolah masing-masing. Daftar nama mata pelajaran yang ditambahkan akan tersimpan di dalam tabel daftar mapel. Selain itu, pengguna dapat menambahkan sendiri mapel yang belum ada di dalam daftar. Disediakan form pada sub modul ini untuk menambahkan mata pelajaran lain. Kode dibawah ini merupakan potongan kode di Controller.

...

public function namamapel($id\_namamapel = &quot;&quot;){

        $data[&#39;nama&#39;] = $this-\&gt;session-\&gt;Nama;

        $data[&#39;foto&#39;] = $this-\&gt;session-\&gt;foto;

        if ($id\_namamapel == &quot;&quot; ) {

            $data[&#39;edit\_mapel&#39;] = null;

            $this-\&gt;load-\&gt;model(&#39;penjadwalan/mod\_namamapel&#39;);

            $data[&#39;tabel\_namamapel&#39;] = $this-\&gt;mod\_namamapel-\&gt;get();

            $this-\&gt;template-\&gt;load(&#39;penjadwalan/kurikulum/dashboard\_kurikulum&#39;,&#39;penjadwalan/kurikulum/namamapel&#39;, $data);

        } else {

            $this-\&gt;load-\&gt;model(&#39;penjadwalan/mod\_namamapel&#39;);

            $data[&#39;edit\_mapel&#39;] = $this-\&gt;mod\_namamapel-\&gt;select($id\_namamapel);

            $data[&#39;tabel\_namamapel&#39;] = $this-\&gt;mod\_namamapel-\&gt;get();

            $this-\&gt;template-\&gt;load(&#39;penjadwalan/kurikulum/dashboard\_kurikulum&#39;,&#39;penjadwalan/kurikulum/namamapel&#39;, $data);

        }   }

...

![](RackMultipart20200819-4-1a3mlot_html_74eb217a415efbe9.png)

Gambar 2. Hasil Tampilan Sub Modul Tambah Mapel

1. _Tampilan Pengaturan Jadwal Ekstrakurikuler_

Pengaturan pada modul Mengelola Ekstrakurikuler berguna untuk pengguna menentukan jenis ekstrakurikuler yang terdapat di sekolah. Selain itu diberikan juga fitur tambah ekstrakurikuler dan mengedit jika terjadi kesalahan. Jenis ekstrakurikuler yang dipilih pada menu pengaturan ini merupakan ekstrakurikuler yang akan muncul pada pilihan daftar ekstrakurikuler saat menambahkan jadwal ekstrakurikuler. Pengguna juga dapat membuat perubahan terhadap jadwal ekstrakurikuler yang telah diinputkan. Berikut ini merupakan potongan kode di Controller dan hasil tampilan dari submodul Mengelola Ekstrakurikuler:

...

public function ekstrakurikuler($id\_jadwal\_ekskul = &quot;&quot;){

        $data[&#39;nama&#39;] = $this-\&gt;session-\&gt;Nama;

        $data[&#39;foto&#39;] = $this-\&gt;session-\&gt;foto;

        if ($id\_jadwal\_ekskul == &quot;&quot; ) {

            $this-\&gt;load-\&gt;model(&#39;penjadwalan/mod\_jadwalekskul&#39;);

            $data[&#39;tabel\_jadwalekskul&#39;] = $this-\&gt;mod\_jadwalekskul-\&gt;get();

            $this-\&gt;load-\&gt;model(&#39;penjadwalan/mod\_jenisklstambahan&#39;);

            $data[&#39;tabel\_jenisklstambahan&#39;] = $this-\&gt;mod\_jenisklstambahan-\&gt;get();

            $this-\&gt;load-\&gt;model(&#39;penjadwalan/mod\_pembimbing&#39;);

            $data[&#39;tabel\_pembimbing&#39;] = $this-\&gt;mod\_pembimbing-\&gt;get();

            $data[&#39;edit\_jadwalekskul&#39;] = null;

            $this-\&gt;template-\&gt;load(&#39;penjadwalan/kurikulum/dashboard\_kurikulum&#39;,&#39;penjadwalan/kurikulum/ekstrakurikuler&#39;, $data);

        } else {

            $this-\&gt;load-\&gt;model(&#39;penjadwalan/mod\_jadwalekskul&#39;);

            $data[&#39;tabel\_jadwalekskul&#39;] = $this-\&gt;mod\_jadwalekskul-\&gt;get();

            $this-\&gt;load-\&gt;model(&#39;penjadwalan/mod\_jenisklstambahan&#39;);

            $data[&#39;tabel\_jenisklstambahan&#39;] = $this-\&gt;mod\_jenisklstambahan-\&gt;get();

            $this-\&gt;load-\&gt;model(&#39;penjadwalan/mod\_pembimbing&#39;);

            $data[&#39;tabel\_pembimbing&#39;] = $this-\&gt;mod\_pembimbing-\&gt;get();

            $data[&#39;tabel\_jadwalekskul&#39;] = $this-\&gt;mod\_jadwalekskul-\&gt;get();

  ![](RackMultipart20200819-4-1a3mlot_html_5794ca7fa1ea3cfe.png)            $data[&#39;edit\_jadwalekskul&#39;] = $this-\&gt;mod\_jadwalekskul-\&gt;select($id\_jadwal\_ekskul);             $this-\&gt;template \&gt;load(&#39;penjadwalan/kurikulum/dashboard\_kurikulum&#39;, &#39;penjadwalan/kurikulum/ekstrakurikuler&#39;, $data);}

Gambar 3. Tampilan Pengaturan Jadwal Ekstrakurikuler

1. _Edit Ekstrakurikuler_

Berikut ini merupakan potongan kode di Controller dan hasil tampilan dari submodul Mengelola Ekstrakurikuler untuk tampilan edit ekstrakurikuler:

...

public function simpanjadwalekskul(){

        $data[&#39;nama&#39;] = $this-\&gt;session-\&gt;Nama;

        $data[&#39;foto&#39;] = $this-\&gt;session-\&gt;foto;

        $this-\&gt;load-\&gt;model(&#39;penjadwalan/mod\_jadwalekskul&#39;);

        $this-\&gt;load-\&gt;model(&#39;penjadwalan/setting\_model&#39;);

        $setting = $this-\&gt;setting\_model-\&gt;getsetting();

        $id\_tahun\_ajaran = $setting-\&gt;id\_tahun\_ajaran;

        $data = array(

            &#39;hari&#39; =\&gt; $this-\&gt;input-\&gt;post(&#39;hari&#39;),

            &#39;jam\_mulai&#39; =\&gt; $this-\&gt;input-\&gt;post(&#39;jam\_mulai&#39;),

            &#39;jam\_selesai&#39; =\&gt; $this-\&gt;input-\&gt;post(&#39;jam\_selesai&#39;),

            &#39;tempat&#39; =\&gt; $this-\&gt;input-\&gt;post(&#39;tempat&#39;),

            &#39;id\_jenis\_kls\_tambahan&#39; =\&gt; $this-\&gt;input-\&gt;post(&#39;id\_jenis\_kls\_tambahan&#39;),

            &#39;id\_pembimbing&#39; =\&gt; $this-\&gt;input-\&gt;post(&#39;id\_pembimbing&#39;),&#39;id\_tahun\_ajaran&#39; =\&gt; $id\_tahun\_ajaran,);

. ![](RackMultipart20200819-4-1a3mlot_html_8f664e7539f3c905.png) ..

Gambar 4. Tampilan Edit Ekstrakurikuler

1.
# **KESIMPULAN**  **DAN SARAN**

  1.
## Kesimpulan

Berdasarkan pembahasan yang telah dilakukan sebelumnya, telah dilakukan pengembangan _Content Management System_ (CMS) berbasis website untuk sistem informasi sekolah menengah pertama pada modul penjadwalan dan presensi dengan menambahkan fitur-fitur yang membuat sistem lebih fleksibel sehingga pengguna dapat melakukan kustomisasi. Hasil yang didapatkan antara lain:

1. Perubahan _use case_ diagram yang meliputi penggabungan antara _use case_ diagram modul penjadwalan dan modul presensi.
2. Memperbaiki rancangan tampilan dari sistem, antara lain submodul tambah mapel sebagai CMS, mengelola ekstrakurikuler dengan menambahkan menu pengaturan sebagai bagian dari CMS, mengelola hari &amp; jam, dan menambahkan fitur pilih jumlah guru sebagai CMS untuk memunculkan tabel pada jam mengajar guru.
3. Menambahkan tabel basis data baru yang berisikan data mapel\_default pada submodul tambah mapel.
4. Mengubah sumber kode untuk keempat sub modul tersebut.

Penelitian ini akan berlanjut hingga tugas akhir terselesaikan dan kemudian akan dilanjutkan dengan melakukan pengujian sistem. Pengujian yang dilakukan yaitu menggunakan metode SUS dengan target pengujian berasal dari SMP N 8 Yogyakarta dan SMP Piri. Pengambangan CMS SI ini dapat membantu banyak sekolah menengah pertama dalam mengelola penjadwalan, presensi dari guru dan juga siswa.

  1.
## Saran

Pengujian yang dilakukan melibatkan aktor-aktor yang terkait. Pengujian dilakukan dengan beberapa cara. Pertama, pengujian dilakukan dengan cara mengujikan langsung sistem tersebut kepada beberapa aktor terpilih sebagai peserta pengujian. Cara ini memiliki tujuan untuk mengetahui sejauh apa tingkat performa dari sistem yang telah dikembangkan berdasarkan dari komentar peserta pengujian setelah menguji cobakan sistem. Kedua, pengujian dilakukan dengan metode SUS yang merupakan kepanjangan dari _System Usability Scale_. Pengujian yang dilakukan merujuk pengujian pada penelitian sebelumnya oleh [2] dan [6]. Metode SUS dilakukan untuk mengetahui kekurangan-kekurangan dan juga kelebihan dari sistem, serta mengetahui tingkat usabilitas dari sistem, apakah telah sesuai dengan fungsi dan tujuannya. Peserta pengujian akan diberikan kuisioner berisi beberapa pertanyaan terkait sistem, kemudian diminta untuk memberikan jawaban pada kuisioner yang tersedia mulai dari sangat tidak setuju hingga sangat setuju atau dengan skala antara 1 sampai 5. Hasil dari isian kuisioner dari setiap peserta pengujian akan dihitung dengan ketentuan sebagai berikut:

1. Skor setiap pertanyaan yang didapatkan di nomor ganjil akan dikurangi 1.
2. Skor akhir pada pertanyaan nomor genap didapatkan dari nilai 5 yang dikurangkan dengan skor pertanyaan dari peserta pengujian.
3. Hasil akhir untuk skor SUS dihiting dengan menjumlahkan skor akhir setiap pertanyaan kemudian dikalikan dengan 2,5.

##### **DAFTAR**** PUSTAKA**

[1] Y. Rahmawati, &quot;Pemodelan Sistem Informasi Sekolah Menengah Pertama Modul Kegiatan Belajar Mengajar (Studi Kasus di Kota Yogyakarta dan Kabupaten Sleman),&quot; 2017.

[2] M. P. Pertiwi, &quot;Sistem Informasi Penjadwalan Kelas Reguler dan Tambahan untuk Sekolah Menengah Pertama ( SMP ) dan Tambahan Untuk Sekolah Menengah,&quot; 2018.

[3] P. Morin _et al._, &quot;Content Management Systems,&quot; vol. 1, no. 12, 2002.

[4] N. Rohilla, &quot;Web Content Management System (WCMS): A Need,&quot; _Int. J. Eng. Comput. Sci._, vol. 6, no. 6, pp. 21729–21731, 2017.

[5] D. Demikrol and C. Seneler, &quot;Evaluation of A Student Information System (SIS) In Terms of User Emotions, Performance and Perceived Usability: A Pilot Study,&quot; pp. 1–8, 2018.

[6] M. H. Siddiq, &quot;Sistem Informasi Penilaian Akademik Sekolah Menengah Pertama Kota Yogyakarta dan Kabupaten Sleman,&quot; p. 105, 2017.

[7] Z. Arifin and D. M. Khairina, &quot;PHP Framework Design With Hierarchical Model-View-Controller Architecture,&quot; pp. 2–7.

[8] J. M. Martinez-Caro, A. J. Aledo-Hernandez, A. Guillen-Perez, R. Sanchez-Iborra, and M. D. Cano, &quot;A Comparative Study of Web Content Management Systems,&quot; _Inf._, vol. 9, no. 2, 2018.

[9] M. Izzuddin, &quot;Penjadwalan Mata Pelajaran di Sekolah: Studi Kasus di SMPIT Nurul Fajar Bogor,&quot; 2015.

[10] C. Kristiawan, &quot;Pembuatan Rapor Digital dan Monitoring Sistem Presesi Berbasis Web di &#39; SMAN 1 DAYEUHKOLOT ,&#39;&quot; vol. 3, no. 3, pp. 1891–1894, 2017.

[11] S. Elinawati, A. Muhammad, and S. Arlis, &quot;Perancangan Content Management System ( CMS ) Dengan Studi Kasus E-Bisnis Pada Toko Alya,&quot; vol. 2, no. 1, 2015.
