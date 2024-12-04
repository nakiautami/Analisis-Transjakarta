# Analisis-Transjakarta
## Latar Belakang
TransJakarta adalah salah satu moda transportasi publik utama di DKI Jakarta yang dirancang untuk memberikan solusi perjalanan yang efisien dan terjangkau. Dalam beberapa tahun terakhir, jumlah pengguna TransJakarta terus meningkat, mencerminkan tingginya ketergantungan masyarakat terhadap layanan ini. Namun, tantangan dalam mengelola sistem transportasi massal yang kompleks ini tetap ada, termasuk memastikan efisiensi rute, mengoptimalkan kapasitas, dan meningkatkan pengalaman pengguna.

Pendekatan berbasis data, seperti analisis Origin-Destination (OD), telah menjadi alat penting untuk memahami pola perjalanan penumpang dan mengevaluasi kinerja operasional. Dengan menganalisis data perjalanan, seperti tap in, tap out, demografi pengguna, dan waktu perjalanan, TransJakarta dapat mengidentifikasi pola-pola kritis seperti kepadatan rute, penggunaan halte, dan efisiensi pendapatan. Hal ini tidak hanya membantu meningkatkan layanan, tetapi juga memberikan wawasan strategis untuk pengembangan sistem transportasi publik yang lebih berkelanjutan.

## Pernyataan Masalah

Berdasarkan latar belakang diatas dalam pengoprasian Transjakarta menghadapi berbagai kendala, maka berikut adalah rumusan masalah adalah sebagai berikut :
1. Kepadatan Penumpang: Bagaimana distribusi kepadatan penumpang di halte dan koridor tertentu, serta halte atau koridor mana yang memiliki tingkat kepadatan tertinggi dan terendah?
2. Pola Perjalanan: Bagaimana pola perjalanan berdasarkan arah (Go/Back), jarak rata-rata, dan durasi perjalanan rata-rata per koridor atau waktu tertentu?
3. Demografi Pengguna: Bagaimana karakteristik pengguna TransJakarta berdasarkan jenis kelamin dan usia?
4. Pendapatan: Bagaimana rasio pengguna gratis dan berbayar memengaruhi pendapatan, serta pendapatan rata-rata per koridor atau bank penerbit kartu?
5. Waktu dan Pola Aktivitas: Bagaimana pola aktivitas pengguna TransJakarta berdasarkan jam, waktu sibuk, atau hari tertentu?
6. Efektivitas Koridor: Seberapa efektif koridor dalam mempertahankan penumpang dari titik awal hingga akhir perjalanan?
Untuk memperoleh pemahaman yang lebih mendalam mengenai permasalahan di atas, Analisis **Origin-Destination (OD)** menjadi alat utama. Analisis ini bertujuan untuk memetakan pola perjalanan penumpang antara titik asal dan tujuan dalam sistem transportasi, sehingga memudahkan Transjakarta dalam merancang rute yang lebih efisien. Dengan informasi yang diperoleh dari analisis OD, Transjakarta dapat menyesuaikan kapasitas armada dan mengoptimalkan fasilitas di halte-halte yang memiliki volume penumpang tinggi. Hal ini diharapkan dapat mengurangi waktu tunggu dan meningkatkan kenyamanan penumpang, serta memberikan pengalaman yang lebih baik dalam menggunakan transportasi publik.

## Tujuan 
1. **Analisis Kepadatan Penumpang:**
     Mengidentifikasi rasio penggunaan halte tertentu dan koridor paling sibuk berdasarkan jumlah transaksi.
     Menentukan halte atau koridor dengan tingkat kepadatan tertinggi dan terendah.
2. **Pola Perjalanan:**
     Menganalisis rasio perjalanan arah "Go" dan "Back."
     Menghitung jarak dan durasi perjalanan rata-rata per koridor, halte, atau waktu tertentu.
3. **Demografi Pengguna:**
     Memetakan distribusi jenis kelamin dan usia pengguna TransJakarta untuk memahami karakteristik penumpang.
4. **Pendapatan:**
    Menghitung rasio pengguna gratis versus berbayar, serta pendapatan rata-rata per koridor dan per bank penerbit kartu.
5. **Waktu dan Pola Aktivitas:**
    Menganalisis pola penggunaan TransJakarta berdasarkan waktu (jam, harian, dan mingguan) serta membandingkan perjalanan pagi dan sore.
6. **Efektivitas Koridor:**
    Mengukur efektivitas koridor berdasarkan persentase penumpang yang menyelesaikan rute dari titik awal hingga akhir.
    
Dengan menganalisis data ini, TransJakarta dapat merumuskan kebijakan berbasis data yang mendukung pengembangan layanan transportasi yang lebih baik, efisien, dan berkelanjutan.

**Kesimpulan**
## 1 Berdasarkan Demografi Pengguna
## 1.1 Demografi Berdasarkan Gender
Distribusi pengguna Transjakarta menunjukkan bahwa 
dari total pengguna, 19.429 orang (53,3%) adalah perempuan, sedangkan 17.045 orang (46,7%) adalah laki-laki, artinya perbedaan antara pengguna pria dan wanita relatif seimbang. Proporsi pengguan wanita lebih tinggi hanya sekitar 6.6% dibandingkan pria, ini mengindikasikan bahwa layanan Transjakarta relatif merata digunakan oleh kedua gender tersebut.
## 1.2 Demografi Berdasarkan AgeGroup
Kelompok usia dewasa mendominasi pengguna transportasi publik dengan jumlah tertinggi dibandingkan kelompok lainnya, sementara remaja, anak-anak, dan lansia memiliki jumlah pengguna yang jauh lebih rendah, dengan lansia sebagai kelompok terkecil. Tingginya pengguna dari kelompok dewasa mencerminkan kebutuhan mobilitas mereka yang tinggi, terutama untuk keperluan pekerjaan dan aktivitas harian. Selain itu, perjalanan pulang-pergi harian yang konsisten, seperti menuju tempat kerja atau pusat aktivitas lainnya, turut berkontribusi pada akumulasi jumlah pengguna dari kelompok ini.
## 2 Analisis pola pembayaran pengguna Transjakarta
Berdasarkan distribusi PayCard yang digunakan oleh pengguna Transjakarta, kartu DKI mendominasi dengan lebih dari 18.035 pengguna, jauh melampaui jenis kartu lain seperti E-Money yang berada di posisi kedua dengan sekitar 6.600 pengguna. Popularitas kartu DKI didukung oleh integrasi dengan berbagai layanan publik dan aksesibilitasnya dalam sistem transportasi umum, menjadikannya alat pembayaran serbaguna.

Kartu DKI juga memberikan layanan gratis kepada kelompok tertentu, seperti pegawai negeri sipil (PNS), penyandang disabilitas, dan lansia. Kebijakan ini bertujuan untuk mempermudah akses transportasi umum dan meningkatkan kesejahteraan kelompok rentan, yang sekaligus memperkuat posisi kartu DKI sebagai pilihan utama.

E-Money, dengan lebih dari 6.600 pengguna, menjadi alternatif populer karena didukung oleh perbankan nasional dan dapat digunakan untuk berbagai transaksi, selain transportasi. Kemudahan akses dan fleksibilitas penggunaannya menjadikannya pilihan utama bagi penumpang yang tidak memiliki kartu DKI.

Distribusi yang tidak merata menunjukkan bahwa kebijakan lokal berperan penting dalam menentukan pilihan PayCard. Kartu DKI, dengan desain khusus untuk masyarakat Jakarta, didukung oleh promosi pembayaran non-tunai dan fasilitas gratis, menjadi jauh lebih populer dibandingkan kartu lain yang lebih umum.

## 3 Analisis Pendapatan
Pada bulan April 2023, Transjakarta mencatat total pendapatan sebesar Rp97.636.000, dengan Koridor 1T menyumbang pendapatan tertinggi sebesar Rp7.680.000. Hal ini menunjukkan bahwa Koridor 1T memiliki volume penumpang yang tinggi atau tarif yang lebih mahal dibandingkan koridor lainnya, menjadikannya penyumbang utama pendapatan.

Selain itu, pendapatan dari kartu DKI mencapai Rp43.891.500, yang jauh melampaui metode pembayaran lainnya. Hal ini mencerminkan dominasi kartu DKI sebagai metode pembayaran utama, didorong oleh integrasi kartu ini dengan layanan publik dan kebijakan subsidi bagi kelompok tertentu seperti pelajar, lansia, dan penyandang disabilitas.

## 4. Distribusi Tipe Kendaraan
**Kesimpulan Mengenai Dominasi dan Peran Kendaraan**
Transjakarta mendominasi sistem transportasi publik di Jakarta dengan jumlah armada terbanyak, yakni 18.256 kendaraan. Hal ini disebabkan oleh cakupan yang lebih luas dan jumlah rute yang lebih banyak dibandingkan layanan lainnya. Sementara itu, Jak Lingko memiliki 16.011 kendaraan, memainkan peran penting dalam sistem transportasi terintegrasi, namun masih berada di bawah Transjakarta dalam hal kapasitas dan jangkauan. Royal Trans, dengan cakupan yang lebih terbatas dan armada kecil (1.601 kendaraan), hanya memberikan kontribusi kecil dalam sistem transportasi Jakarta.

**Analisis Gender pada Pengguna Transportasi**
Data menunjukkan bahwa perempuan memiliki jumlah transaksi lebih tinggi dibandingkan laki-laki untuk semua jenis layanan transportasi. Penggunaan tertinggi tercatat pada layanan Transjakarta, diikuti Jak Lingko, dengan Royal Trans berada di posisi terendah. Hal ini mengindikasikan bahwa perempuan adalah pengguna utama layanan transportasi publik, sehingga kebutuhan dan preferensi mereka perlu mendapatkan perhatian lebih, termasuk dalam aspek kenyamanan dan keamanan.

**Transaksi Berdasarkan Kartu Pembayaran dan Tipe Kendaraan**
Transjakarta mendominasi jumlah transaksi untuk semua jenis kartu pembayaran, menunjukkan bahwa layanan ini adalah pilihan utama pengguna dibandingkan Jak Lingko dan Royal Trans. Kartu DKI dan e-money menjadi metode pembayaran paling populer, terutama untuk Transjakarta dan Jak Lingko, sedangkan Flazz dan pembayaran online mencatat transaksi lebih rendah. Layanan Royal Trans memiliki transaksi yang sangat kecil, mengindikasikan bahwa segmen pasarnya lebih terbatas. Preferensi terhadap kartu DKI untuk layanan lokal mencerminkan popularitasnya di kalangan pengguna, sementara kartu lain, seperti BRIZZI dan Flazz, memiliki adopsi yang lebih rendah.
## 5 Analisis Origin Destination
## 5.1 Pola Perjalanan per Hari
Grafik pola perjalanan harian Transjakarta selama April 2023 menunjukkan bahwa puncak tertinggi transaksi terjadi pada 14 April, mendekati 2000 transaksi, kemungkinan dipicu oleh acara atau aktivitas tertentu. Tren mingguan menunjukkan peningkatan jumlah transaksi pada hari kerja (Senin-Jumat), dengan penurunan tajam di akhir pekan, terutama pada hari Minggu. Hal ini mencerminkan pola aktivitas masyarakat yang lebih tinggi selama hari kerja dibandingkan akhir pekan.

Analisis jam puncak transaksi pada hari-hari sibuk (13, 14, 17, 18, dan 19 April) menunjukkan dua periode utama: pagi (sekitar pukul 6 pagi) dan sore (sekitar pukul 5 sore). Puncak pagi menjadi waktu tersibuk dengan lebih dari 1400 transaksi, sementara aktivitas menurun drastis menjelang siang dan kembali meningkat pada sore hari, mencerminkan pola perjalanan rutin masyarakat untuk bekerja atau sekolah.

Berdasarkan pola tersebut, terlihat fluktuasi signifikan dalam jumlah pengguna, dengan lonjakan tertentu yang kemungkinan dipengaruhi oleh faktor seperti hari libur atau event khusus. Jumlah pengguna cenderung lebih tinggi pada hari kerja, sementara permintaan menurun tajam di akhir pekan. Untuk mengakomodasi kebutuhan ini, Transjakarta disarankan menambah armada dan frekuensi keberangkatan pada jam sibuk di hari kerja, terutama Jumat, serta mengurangi operasi di akhir pekan untuk efisiensi sumber daya.
## 5.2 Distribusi Waktu Perjalanan
Berdasarkan data distribusi Tap-In dan Tap-Out per jam, terdapat dua periode jam puncak yang mencerminkan pola perjalanan pengguna Transjakarta: pagi dan sore.

Pada jam puncak pagi (5:00–9:00), aktivitas perjalanan dimulai pada pukul 5 pagi dengan Tap-In sebanyak 3.234, menunjukkan orang mulai berangkat ke tempat kerja atau sekolah. Puncak keberangkatan terjadi pada pukul 6 pagi dengan Tap-In tertinggi mencapai 5.619, sementara puncak kedatangan di tujuan terjadi pada pukul 7 pagi dengan Tap-Out sebanyak 3.894. Hal ini mengindikasikan mayoritas pengguna tiba di tempat tujuan pada jam tersebut.

Sore hari (16:00–21:00) menunjukkan pola serupa. Puncak keberangkatan pulang terjadi pada pukul 5 sore dengan Tap-In mencapai 5.281, mencerminkan orang mulai meninggalkan kantor atau sekolah. Puncak kepulangan ke rumah atau tujuan lain terjadi pada pukul 6 sore, dengan Tap-Out tertinggi sebesar 4.371.

Kesimpulannya, pagi hari didominasi oleh keberangkatan pada pukul 6 pagi dan kedatangan di tujuan pada pukul 7 pagi, sementara sore hari ditandai oleh keberangkatan pulang pada pukul 5 sore dan kepulangan ke rumah pada pukul 6 sore. Pola ini konsisten dengan kebiasaan perjalanan masyarakat untuk bekerja atau bersekolah.
## 5.3 Analisis Koridor Performa Koridor
Pada jam sibuk pagi hari, koridor Kampung Melayu - Tanah Abang via Cikini mendominasi dengan 499 transaksi Tap-In, menunjukkan bahwa rute ini sangat ramai digunakan, terutama untuk akses menuju area perkantoran dan tempat umum di Jakarta. Koridor ini menjadi pilihan utama pengguna karena menghubungkan berbagai pusat kegiatan di Jakarta. Di sisi lain, koridor lainnya memiliki jumlah transaksi yang lebih rendah, seperti Cibubur - Balai Kota (152 transaksi), Kebayoran Lama - Tanah Abang (138 transaksi), Ciputat - CSW (137 transaksi), dan Kampung Rambutan - Pondok Gede (135 transaksi), yang juga melayani rute-rute utama dengan banyak perkantoran dan kawasan pemukiman.

Analisis transaksi Tap-Out pada jam sibuk pagi menunjukkan bahwa Kampung Melayu - Tanah Abang via Cikini kembali mendominasi dengan 403 transaksi, menjadi tujuan utama bagi banyak pengguna. Koridor lainnya, seperti Pasar Minggu - Tanah Abang (119 transaksi), Cibubur - Balai Kota (111 transaksi), Harmoni - Jakarta International Stadium (110 transaksi), dan Kebayoran Lama - Tanah Abang (108 transaksi) mencatatkan jumlah yang jauh lebih kecil.

Dari segi rasio efektivitas, terdapat sekitar 45% penumpang yang melakukan Tap-Out setelah Tap-In, menunjukkan bahwa sebagian besar penumpang tidak menyelesaikan perjalanan hingga halte akhir. Jumlah Tap-In yang lebih tinggi (1.627) dibandingkan Tap-Out (732) mengindikasikan kemungkinan ketidakpatuhan penumpang dalam melakukan Tap-Out, kesalahan teknis pada perangkat, atau penumpang yang turun di halte bukan utama dan lupa melakukan Tap-Out karena terburu-buru.
## 5.4 Analisis Rute
**Rute Paling Sering Digunakan**
Rute dari Rusun Kapuk Muara ke Penjaringan mencatatkan 125 transaksi, jumlah tertinggi. Sebaliknya, rute dari Penjaringan ke Rusun Penjaringan dan Penggilingan ke Rusun Komarudin memiliki transaksi lebih sedikit (masing-masing 68 transaksi). Rute dengan transaksi lebih tinggi mengindikasikan permintaan tinggi, menghubungkan area pemukiman dengan aktivitas ekonomi yang padat, sedangkan rute dengan transaksi lebih rendah menunjukkan kebutuhan transportasi yang lebih rendah atau adanya alternatif yang lebih baik.

**Pemberhentian Utama dalam Transaksi**
Penjaringan sering muncul sebagai titik awal atau tujuan, menandakan bahwa halte ini adalah pusat aktivitas, kemungkinan karena kedekatannya dengan pusat ekonomi atau fasilitas publik. Mengetahui halte dengan aktivitas tinggi membantu memprioritaskan pengembangan infrastruktur atau peningkatan layanan.

**Pola Permintaan**
Rute yang menghubungkan area pemukiman seperti Rusun Kapuk Muara dan Rusun Komarudin menunjukkan pola penggunaan yang tinggi pada jam sibuk. Destinasi seperti BKN juga memiliki transaksi signifikan, mengindikasikan bahwa lokasi ini penting, kemungkinan terkait pekerjaan atau pendidikan.
## 5.5 Analisis Halte
**Penjaringan dan BKN Memimpin dalam Transaksi**
Halte "Penjaringan" berada di peringkat pertama dengan 500 transaksi, sementara "BKN" menyusul di posisi kedua dengan 479 transaksi. Kedua halte ini memiliki volume transaksi yang jauh lebih tinggi dibandingkan dengan halte lainnya, yang mengindikasikan mereka sebagai pusat utama aktivitas. Penjaringan, dengan lokasinya yang strategis di pusat kegiatan ekonomi, dan BKN, yang mungkin memiliki kaitan dengan pekerjaan atau pendidikan, menarik lebih banyak penumpang.

**Halte dengan Transaksi Sedang**
Halte dengan transaksi sedang, seperti "BNN LRT" (260), "Cibubur Junction" (256), dan "Tendean" (253), menunjukkan tingkat penggunaan yang konsisten. Halte-halte ini memiliki jumlah transaksi yang cukup tinggi, menandakan adanya permintaan transportasi yang stabil dan berkelanjutan, meskipun tidak sepadat Penjaringan atau BKN. Lokasi halte-halte ini mungkin melayani area dengan aktivitas yang beragam, meskipun tidak sepadat dua halte teratas.

**Halte dengan Transaksi Lebih Rendah**
Tiga halte terakhir dalam daftar top 10, yaitu "Garuda Taman Mini" (235), "Kejaksaan Agung" (240), dan "Monas" (222), meskipun masih termasuk dalam 10 besar, memiliki jumlah transaksi yang lebih rendah dibandingkan dengan halte-halte lainnya. Hal ini bisa menunjukkan bahwa walaupun halte-halte ini tetap penting dalam sistem transportasi, volume penumpang di sana lebih rendah. Faktor-faktor seperti aksesibilitas, kedekatan dengan area pemukiman atau pusat ekonomi, dan jenis layanan transportasi yang tersedia mungkin mempengaruhi perbedaan jumlah transaksi antara halte-halte ini dengan yang lebih ramai.

**Penjelasan Relevansi**
Analisis ini memberikan wawasan penting bagi perencanaan dan pengelolaan sistem transportasi. Halte-halte dengan volume transaksi tinggi, seperti Penjaringan dan BKN, mungkin memerlukan lebih banyak perhatian dalam hal pengelolaan armada dan peningkatan fasilitas untuk mengakomodasi volume penumpang yang besar. Sementara halte dengan transaksi sedang atau rendah bisa menjadi fokus untuk upaya peningkatan layanan atau promosi agar lebih banyak orang memanfaatkan transportasi di daerah tersebut.

## 5.6 Rasio waktu rata-rata per perjalanan
**Durasi Perjalanan Tertinggi**

Koridor 7B (Keberangkatan) memiliki durasi perjalanan rata-rata tertinggi, yaitu 93,33 menit. Durasi panjang ini disebabkan oleh jumlah pemberhentian yang banyak (45 pemberhentian) dan kondisi lalu lintas yang sering mengalami kemacetan di area yang dilalui oleh koridor ini.
Koridor JAK.12 (Pulang) dan JAK.47 (Keberangkatan) juga mencatatkan durasi perjalanan di atas 90 menit. Hal ini disebabkan oleh banyaknya titik pemberhentian, masing-masing 59 titik pada JAK.12 dan 48 titik pada JAK.47, yang memperpanjang waktu tempuh.

**Durasi Perjalanan Terendah**

Koridor M5 (Pulang) memiliki durasi perjalanan rata-rata terendah, yaitu hanya 33,5 menit. Rute ini menunjukkan efisiensi yang lebih baik, dengan perjalanan yang lebih singkat. Hal ini mungkin disebabkan oleh jalur yang lebih pendek atau kurang padatnya lalu lintas di sepanjang rute.
Rute-rute lainnya seperti 12P (Pulang) dan 7P (Pulang) juga menunjukkan durasi perjalanan yang cukup efisien, dengan waktu tempuh lebih singkat dibandingkan dengan koridor yang memiliki banyak pemberhentian dan rute lebih panjang.

**Perbedaan Antara Keberangkatan dan Pulang**

Secara umum, durasi perjalanan pada arah Keberangkatan sering kali lebih panjang dibandingkan dengan arah Pulang, seperti pada koridor 7B dan JAK.47. Hal ini kemungkinan besar disebabkan oleh pola lalu lintas yang lebih padat di pagi hari, ketika banyak orang berangkat bekerja, dibandingkan dengan perjalanan pulang pada sore hari, yang mungkin tidak sebanyak itu.
Penjelasan Relevansi
Wawasan ini penting untuk mengoptimalkan jadwal dan alokasi armada pada rute-rute Transjakarta. Dengan memahami rute yang memiliki durasi perjalanan lebih panjang, seperti 7B dan JAK.12, pihak pengelola dapat merencanakan untuk meningkatkan efisiensi di rute-rute tersebut, misalnya dengan penambahan armada atau pengaturan ulang pemberhentian yang lebih strategis. Sebaliknya, rute dengan durasi perjalanan lebih pendek, seperti M5, dapat dijadikan contoh untuk merancang rute yang lebih efisien atau memperpendek waktu perjalanan.

Analisis perbedaan antara perjalanan keberangkatan dan pulang juga menunjukkan pentingnya pengaturan jadwal untuk menghindari kemacetan pada jam sibuk di pagi hari dan meningkatkan kenyamanan pengguna transportasi.

## Rekomendasi
Evaluasi ketidakseimbangan kapasitas rute Transjakarta dilakukan dengan menganalisis data jumlah penumpang, kapasitas armada, dan frekuensi layanan pada setiap rute. Tujuan evaluasi ini adalah:
* Mengidentifikasi rute overcapacity, yaitu rute di mana 
  jumlah penumpang melebihi kapasitas armada, yang menyebabkan kepadatan, waktu tunggu yang lama, dan penurunan kenyamanan penumpang.
* Mengidentifikasi rute undercapacity, yaitu rute dengan 
  kapasitas armada yang tidak optimal, sehingga ada kapasitas yang tidak terpakai dan meningkatkan biaya operasional tanpa manfaat yang seimbang.
* Mengevaluasi dampaknya terhadap efisiensi operasional, termasuk waktu tunggu penumpang, kenyamanan, dan biaya operasional.

Data yang dibutuhkan dalam analisis:
1.  Data Rute dan Armada
    * Daftar rute (kode, nama, panjang rute dalam km).
    * Jumlah armada per rute.
    * Kapasitas maksimum per bus (jumlah penumpang). (data ini tidak tersedia di data set)
    * Frekuensi keberangkatan bus per rute per jam.
2. Data Penumpang
    * Volume penumpang per rute per hari/jam.
    * Volume penumpang per halte per rute (untuk analisis 
      waktu tunggu).
3. Indikator Operasional
    * Waktu tunggu rata-rata per halte/rute.
    * Waktu tempuh rata-rata per rute.
    * Tingkat keterlambatan bus.
    
Catatan: Data kapasitas maksimum per bus penting untuk menghitung kapasitas total armada.

Analisis ini dilakukan berdasarkan indikator **Load Factor**, yaitu tingkat pemanfaatan kapasitas armada pada setiap rute.
load factor = Jumlah Penumpang/ (jumlah armada X kapasitas Bus)

Nilai load factor ini yang akan menentukan **overcapacity atau undercapacity**.

Berdasarkan hasil analisis nya dapat dilakukan simulasi strategi yaitu:
* Penyesuaian jummlah armada dapat dilakukan dengna 
  redistribusi armada dari rute undercapacity ke rute overcapacity.
* Tambahkan frekuensi keberangkatan bus pada rute 
  overcapacity untuk mengurangi waktu tunggu penumpang.


Analisis ini dapat memberikan keuntungan strategis dan finansial bagi Transjakarta melalui langkah-langkah berikut:
1. Optimasi Alokasi Sumber Daya
   * Mengurangi pemborosan dengan redistribusi armada  dari rute undercapacity ke overcapacity.
   * Meningkatkan efisiensi operasional melalui pengoperasian armada pada kapasitas optimal.

2. Peningkatan Pengalaman Penumpang
   * Mengurangi waktu tunggu dan kepadatan, meningkatkan kenyamanan perjalanan.
   * Mendorong loyalitas dan retensi penumpang untuk meningkatkan pendapatan.

3. Penurunan Biaya Operasional
   * Menghindari pengeluaran yang tidak perlu seperti bahan bakar, perawatan, dan gaji pengemudi di rute undercapacity.

4. Peningkatan Pendapatan
   * Memaksimalkan kapasitas di rute padat untuk melayani lebih banyak penumpang.
   * Mengidentifikasi potensi restrukturisasi rute untuk meningkatkan profitabilitas.
  
## Analisis Lebih Lanjut 
Berikut analsis lebih lanjut yang dapat dilakukan untuk meningkatkan pelayanan Transjakarta.
## Analisis Pengaruh Ketidakseimbangan Kapasitas Rute terhadap Efisiensi Operasional 
Evaluasi ketidakseimbangan kapasitas rute Transjakarta dilakukan dengan menganalisis data jumlah penumpang, kapasitas armada, dan frekuensi layanan pada setiap rute. Tujuan evaluasi ini adalah:
* Mengidentifikasi rute overcapacity, yaitu rute di mana 
  jumlah penumpang melebihi kapasitas armada, yang menyebabkan kepadatan, waktu tunggu yang lama, dan penurunan kenyamanan penumpang.
* Mengidentifikasi rute undercapacity, yaitu rute dengan 
  kapasitas armada yang tidak optimal, sehingga ada kapasitas yang tidak terpakai dan meningkatkan biaya operasional tanpa manfaat yang seimbang.
* Mengevaluasi dampaknya terhadap efisiensi operasional, termasuk waktu tunggu penumpang, kenyamanan, dan biaya operasional.

Data yang dibutuhkan dalam analisis:
1.  Data Rute dan Armada
    * Daftar rute (kode, nama, panjang rute dalam km).
    * Jumlah armada per rute.
    * Kapasitas maksimum per bus (jumlah penumpang). (data ini tidak tersedia di data set)
    * Frekuensi keberangkatan bus per rute per jam.
2. Data Penumpang
    * Volume penumpang per rute per hari/jam.
    * Volume penumpang per halte per rute (untuk analisis 
      waktu tunggu).
3. Indikator Operasional
    * Waktu tunggu rata-rata per halte/rute.
    * Waktu tempuh rata-rata per rute.
    * Tingkat keterlambatan bus.
    
Catatan: Data kapasitas maksimum per bus penting untuk menghitung kapasitas total armada.

Analisis ini dilakukan berdasarkan indikator **Load Factor**, yaitu tingkat pemanfaatan kapasitas armada pada setiap rute.
load factor = Jumlah Penumpang/ (jumlah armada X kapasitas Bus)

Nilai load factor ini yang akan menentukan **overcapacity atau undercapacity**.

Berdasarkan hasil analisis nya dapat dilakukan simulasi strategi yaitu:
* Penyesuaian jummlah armada dapat dilakukan dengna 
  redistribusi armada dari rute undercapacity ke rute overcapacity.
* Tambahkan frekuensi keberangkatan bus pada rute 
  overcapacity untuk mengurangi waktu tunggu penumpang.


## Analisis Waktu Tunggu 
**Mengidentifikasi penyebab utama waktu tunggu yang lama di beberapa halte Transjakarta, khususnya pada rute sibuk.**

**Tujuan Analisis**
Analisis ini bertujuan untuk mengidentifikasi dan mengatasi faktor-faktor yang mempengaruhi waktu tunggu penumpang di Transjakarta, seperti frekuensi bus, masalah teknis, ketidaksesuaian jadwal, dan ketidakseimbangan kapasitas armada dengan kebutuhan penumpang, terutama pada jam sibuk. Dengan membandingkan waktu tap-in penumpang (tapInHour) dengan waktu kedatangan bus (arrivalTime), Transjakarta dapat merencanakan perbaikan strategi operasional.

**Data yang Digunakan**
1. Waktu Tap-In Penumpang (tapInHour): Menunjukkan waktu saat penumpang tap-in untuk memulai perjalanan.
2. Waktu Kedatangan Bus (arrivalTime): Waktu kedatangan bus di stasiun untuk rute tertentu.
3. Identifikasi Stasiun dan Rute: Data rute dan stasiun yang dilalui bus.
4. Data Frekuensi Bus: Frekuensi bus yang melayani rute tertentu.
5. Data Kapasitas Armada dan Penumpang: Jumlah bus dan kapasitas armada pada rute tertentu.

**Data Kapsitas Armada dan jadwal kedatangan bus disini cukup penting untuk analisis**

**Metode Analisis**
1. Perbandingan Waktu Tap-In dan Kedatangan: Menghitung durasi waktu tunggu dengan membandingkan waktu tap-in dan kedatangan bus.
2. Pencarian Pola Keterlambatan: Mencari pola keterlambatan atau ketidaksesuaian jadwal.
3. Identifikasi Jam Sibuk: Menganalisis waktu tunggu pada jam sibuk untuk merencanakan penambahan armada atau perbaikan jadwal.

**Hasil Analisis**
1. Penurunan Waktu Tunggu: Mengidentifikasi dan memperbaiki ketidaksesuaian jadwal untuk mengurangi waktu tunggu.
2. Peningkatan Kapasitas Armada: Menambah bus jika kapasitas armada tidak mencukupi.
3. Perbaikan Jadwal: Mengoptimalkan jadwal bus agar penumpang tidak menunggu lama.
4. Optimalisasi Rute: Menyesuaikan rute yang memiliki waktu tunggu lebih lama.

**Keuntungan Finansial dan Strategi:** 

Pengurangan Biaya Operasional: Dengan mengoptimalkan frekuensi bus dan penjadwalan, Transjakarta dapat mengurangi biaya operasional yang disebabkan oleh keterlambatan atau kelebihan kapasitas yang tidak efisien.

Peningkatan Kepuasan Pelanggan: Penurunan waktu tunggu dan peningkatan kenyamanan pelanggan dapat meningkatkan kepuasan penumpang, yang pada gilirannya dapat meningkatkan jumlah penumpang yang menggunakan layanan Transjakarta, meningkatkan pendapatan dari tarif.

Efisiensi Sumber Daya: Dengan analisis yang baik mengenai waktu tunggu dan kapasitas armada, Transjakarta dapat lebih efisien dalam mengalokasikan sumber daya seperti bus dan sopir untuk rute yang membutuhkan.

mplementasi Sistem Prediksi Waktu Kedatangan: Transjakarta dapat mengembangkan sistem yang memprediksi waktu kedatangan bus dengan lebih akurat, menggunakan data real-time untuk menginformasikan penumpang mengenai waktu kedatangan yang lebih tepat.
Peningkatan Integrasi Data: Memperkuat integrasi data antara sistem tap-in dan jadwal kedatangan bus untuk memperoleh data yang lebih akurat dan dapat dianalisis dengan lebih baik.


Analisis ini dapat memberikan keuntungan strategis dan finansial bagi Transjakarta melalui langkah-langkah berikut:
1. Optimasi Alokasi Sumber Daya
   * Mengurangi pemborosan dengan redistribusi armada  dari rute undercapacity ke overcapacity.
   * Meningkatkan efisiensi operasional melalui pengoperasian armada pada kapasitas optimal.

2. Peningkatan Pengalaman Penumpang
   * Mengurangi waktu tunggu dan kepadatan, meningkatkan kenyamanan perjalanan.
   * Mendorong loyalitas dan retensi penumpang untuk meningkatkan pendapatan.

3. Penurunan Biaya Operasional
   * Menghindari pengeluaran yang tidak perlu seperti bahan bakar, perawatan, dan gaji pengemudi di rute undercapacity.

4. Peningkatan Pendapatan
   * Memaksimalkan kapasitas di rute padat untuk melayani lebih banyak penumpang.
   * Mengidentifikasi potensi restrukturisasi rute untuk meningkatkan profitabilitas.

link dashboard
[web](https://public.tableau.com/views/Transjakarta_17332353230210/Dashboarke3?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
