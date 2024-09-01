# 122450020_Try-Yani-Rizki-Nur-Rohmah.md
## Nama : Try Yani Rizki Nur Rohmah Kelas : RB
## NIM : 122450020
# VISUALISASI DATA DAN INFORMASI
### Abstrak
Visualisasi data sangat penting dalam dunia bisnis yang didorong oleh data saat ini, yang telah digunakan secara luas untuk membantu pengambilan keputusan yang berhubungan dengan pendapatan utama banyak perusahaan industri. Namun, karena tingginya permintaan pemrosesan data terkait volume, kecepatan, dan kebenaran data, ada kebutuhan yang muncul untuk para ahli basis data untuk membantu dalam visualisasi data yang efisien dan efektif. Artikel ini membahas teknik-teknik yang membuat visualisasi data lebih efisien dan efektif. (1) Spesifikasi visualisasi mendefinisikan bagaimana pengguna dapat menentukan kebutuhan mereka untuk menghasilkan visualisasi. (2) Pendekatan efisien untuk visualisasi data memproses data dan spesifikasi visualisasi yang diberikan, yang kemudian menghasilkan visualisasi dengan target utama untuk efisiensi dan skalabilitas pada kecepatan interaktif. (3) Rekomendasi visualisasi data bertujuan untuk melengkapi spesifikasi yang tidak lengkap, atau menemukan visualisasi yang lebih menarik berdasarkan visualisasi referensi.
### Kata Kunci: Visualisasi data · Bahasa visualisasi · Visualisasi data yang efisien · Rekomendasi visualisasi data
### 1. Pendahuluan
  Dalam era bisnis saat ini, di mana keputusan seringkali didasarkan pada data, visualisasi data menjadi alat yang tak tergantikan untuk memfasilitasi pengambilan keputusan yang strategis. Visualisasi data mengubah data yang bersifat abstrak dan kompleks menjadi format visual yang lebih mudah dipahami, seperti grafik dan diagram. Representasi ini memungkinkan para pengambil keputusan untuk menangkap pola dan wawasan dari data dengan cara yang lebih intuitif. Dengan pertumbuhan eksponensial dalam jumlah data yang tersedia untuk organisasi, peran visualisasi data menjadi semakin krusial untuk memberikan pemahaman menyeluruh dan mendalam mengenai hasil analisis data.
  Kemajuan teknologi dalam visualisasi data telah banyak dipengaruhi oleh kontribusi dari berbagai komunitas. Komunitas grafik komputer, misalnya, telah mengembangkan teknologi rendering canggih yang memungkinkan pembuatan visualisasi yang menarik dan mudah diinterpretasikan. Di sisi lain, komunitas visualisasi telah memperkenalkan berbagai alat seperti D3, Vega-Lite, VizQL, Tableau, dan Microsoft Power BI, yang memudahkan pembuatan dan interaksi dengan visualisasi data. Selain itu, komunitas basis data telah berupaya meningkatkan pengalaman pengguna dalam visualisasi data secara real-time, bahkan untuk dataset yang sangat besar dengan jutaan atau miliaran catatan.
  Visualisasi data, yang mengubah data abstrak menjadi visi fisik (misalnya, panjang, posisi, bentuk, warna, dan sebagainya), adalah cara yang kuat untuk menyajikan cerita data kepada manusia yang lebih berorientasi visual. Saat ini, semua organisasi memiliki lebih banyak data daripada sebelumnya. Akibatnya, semakin banyak organisasi yang menggunakan data dan analitik canggih untuk memandu keputusan strategis dan operasional. Visualisasi data sangat cocok untuk memberikan gambaran umum data yang besar dan memudahkan interpretasi hasil analitik data bagi para ilmuwan data.
### 2. Proses Visualisasi Data
Proses visualisasi data biasanya terdiri dari lima langkah utama yang saling terkait:
1. Pengambilan Data: Langkah ini melibatkan pengumpulan data dari berbagai sumber yang relevan, yang kemudian akan digunakan untuk membuat visualisasi.
2. Persiapan Data: Pada tahap ini, data yang telah diambil dibersihkan dan dipersiapkan untuk visualisasi. Ini termasuk proses seperti normalisasi nilai, perbaikan entri yang salah, dan interpolasi nilai yang hilang.
3. Manipulasi Data: Data yang telah dipersiapkan kemudian dipilih dan dimanipulasi untuk visualisasi. Ini bisa mencakup penyaringan data, penggabungan data dari berbagai sumber, dan pengelompokan data.
4. Pemetaan: Dalam tahap ini, data yang telah dimanipulasi dipetakan ke dalam bentuk geometris seperti titik, garis, atau area, dengan atribut tambahan seperti warna, ukuran, dan posisi.
5. Rendering: Langkah terakhir adalah mengubah data geometris menjadi representasi visual yang dapat dilihat oleh pengguna.
Pipeline ini adalah kerangka kerja dasar dalam proses visualisasi data. Jurnal ini menyoroti tiga area penting untuk meningkatkan efisiensi dan efektivitas visualisasi data,terutama dalam konteks basis data: spesifikasi visualisasi, pendekatan efisien untuk visualisasi data, dan sistem rekomendasi visualisasi.
### 3. Spesifikasi Visualisasi
Spesifikasi visualisasi merujuk pada proses di mana pengguna menentukan bagaimana data mereka harus divisualisasikan. Berbagai penelitian dari komunitas visualisasi dan basis data telah membahas cara spesifikasi ini dilakukan, serta bahasa visualisasi yang digunakan. Secara umum, bahasa visualisasi terdiri dari tiga komponen utama:
#### ● Data: 
Ini mencakup catatan yang akan divisualisasikan serta operasi transformasi yang diterapkan pada data, seperti pengelompokan, pemfilteran, dan pengurutan.
#### ● Tanda:
Ini meliputi elemen-elemen visual yang digunakan untuk mewakili data,
seperti bar, garis, atau titik, serta atribut tambahan seperti ukuran, warna, dan
bentuk.
#### ● Pemetaan:
Ini adalah proses di mana data dipetakan ke tanda visual yang sesuai,
menentukan bagaimana data akan direpresentasikan secara visual.
Bahasa visualisasi dapat dikategorikan berdasarkan tingkat ekspresivitasnya. Bahasa tingkat tinggi, seperti ggplot2 dan Vega-Lite, biasanya menyederhanakan proses dengan menyediakan pengaturan default dan batasan yang mempermudah penggunaan, meskipun mungkin kurang fleksibel. Sebaliknya, bahasa tingkat rendah seperti Prefuse dan Flare memberikan kontrol lebih detail namun memerlukan pengetahuan teknis yang lebih mendalam. Alat berbasis antarmuka grafis pengguna (GUI), seperti Tableau, Qlik, Excel, dan Google Sheets, memungkinkan pengguna non-teknis untuk membuat visualisasi dengan antarmuka yang intuitif, meskipun seringkali kurang fleksibel dibandingkan dengan bahasa visualisasi deklaratif.
### 4. Teknik Efisien untuk Visualisasi Data
Pendekatan efisien dalam visualisasi data berfokus pada bagaimana data diproses dan diterjemahkan menjadi visualisasi yang interaktif dan dapat diskalakan. Ada beberapa pendekatan utama:
 A. Visualisasi yang Tepat
Pendekatan ini berusaha untuk menghasilkan visualisasi dengan cepat dan akurat. Salah satu metode alami adalah dengan menerjemahkan kueri visualisasi menjadi kueri SQL yang dapat dieksekusi oleh sistem basis data. Sistem seperti DeepEye, Polaris, dan SeeDB menggunakan teknik ini untuk memperoleh data dengan cepat. Meskipun pendekatan ini efektif, ia sering menghadapi tantangan terkait optimasi yang tidak konsisten antara server basis data dan alat visualisasi. Untuk mengatasi masalah ini, beberapa penelitian telah menyarankan integrasi antara pengambilan data dan rendering, seperti yang dilakukan oleh sistem Ermac.
B. Perkiraan Visualisasi Data
Ketika ukuran data sangat besar atau kueri terlalu kompleks, menghasilkan visualisasi yang akurat secara instan mungkin tidak praktis. Dalam kasus ini, teknik perkiraan seperti pemrosesan kueri perkiraan (AQP) digunakan untuk memberikan visualisasi yang mendekati akurat dengan cepat. Teknik ini sering melibatkan penggunaan subset data yang representatif untuk menghasilkan visualisasi awal, yang kemudian dapat disempurnakan seiring dengan bertambahnya data.
C. Visualisasi Data Progresif
Teknik visualisasi data progresif memberikan hasil visualisasi secara bertahap. Ini memungkinkan pengguna untuk melihat hasil sementara sambil menunggu visualisasi yang lebih lengkap. Beberapa pendekatan progresif menggunakan agregasi hierarkis, di mana data diorganisasikan dalam struktur hierarkis yang memudahkan eksplorasi data pada berbagai tingkat resolusi. Sistem seperti imMens memungkinkan pengguna untuk melihat data dengan berbagai tingkat detail melalui zoom in dan zoom out.
### 5. Studi Kasus dan Implementasi
Artikel ini juga mengulas dua sistem visualisasi data yang berbeda: Kyrix dan Tableau.
A. Kyrix
Kyrix adalah sistem visualisasi yang dirancang untuk interaktivitas dan skalabilitas, menggabungkan antarmuka spesifikasi deklaratif dengan pemrosesan visualisasi yang efisien. Kyrix memungkinkan pengguna untuk memperbesar dan memperkecil visualisasi dengan lancar, menggunakan dua konsep utama dalam bahasanya: kanvas dan lompatan. Kanvas berisi visualisasi statis, sementara lompatan menentukan sumber dan tujuan kanvas serta jenis transisi saat memperbesar atau memperkecil. Kyrix juga menerapkan teknik granularitas pengambilan dan pengindeksan untuk meningkatkan efisiensi pengambilan data.
B. Tableau
Tableau adalah salah satu alat visualisasi yang paling populer di industri, dikenal karena kemampuannya dalam membuat visualisasi yang efisien. Mesin data Tableau, seperti TDE (Tableau Data Engine) dan Hyper, dirancang untuk mengatasi masalah penyimpanan data berbasis kolom, kompresi, dan perhitungan paralel. TDE mengoptimalkan penyimpanan data dengan menggunakan teknik kompresi untuk mengurangi biaya I/O, sementara Hyper berfungsi sebagai mesin memori utama yang mendukung operasi basis data dengan efisien.
### 6. Sistem Rekomendasi Visualisasi
Sistem rekomendasi visualisasi memainkan peran penting dalam membantu pengguna memilih visualisasi yang paling sesuai dengan data mereka. Sistem ini sering kali menggunakan pendekatan berbasis aturan atau pembelajaran mesin untuk memberikan rekomendasi visualisasi yang relevan. Sistem berbasis aturan, seperti Voyager dan Show Me, menggunakan aturan perseptual yang lebih kaya untuk menilai efektivitas visualisasi. Sistem berbasis pembelajaran mesin, seperti Draco dan DeepEye, melatih model untuk menentukan visualisasi terbaik berdasarkan data pelatihan dan contoh visualisasi.
### 7. Kesimpulan
Visualisasi data adalah bidang yang terus berkembang dengan banyak penelitian baru dan inovasi. Meskipun sistem visualisasi data komersial saat ini cukup baik dalam hal spesifikasi, masih ada tantangan dalam hal efisiensi dan rekomendasi yang perlu diatasi. Peneliti basis data memiliki peluang besar untuk berkontribusi pada pengembangan metode visualisasi yang lebih baik dan lebih efisien, serta untuk mengatasi masalah yang ada dalam praktik visualisasi data.
