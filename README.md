<div align="center"><h1>Navigasi Kinerja Regional AWS</h1></div>
<div align="center"><h2>Analisis Profit Margin Optimal di Pasar Global</h2></div>

## Latar Belakang

### Pertumbuhan Pasar Cloud Computing

Permintaan pasar terhadap layanan komputasi cloud (_cloud computing_) mengalami lonjakan pertumbuhan yang signifikan, khususnya berkat kenaikan permintaan otomatisasi dan pergeseran budaya kerja jarak jauh (_remote work_). Tren ini menjadi salah satu peluang investasi yang sangat menjanjikan bagi raksasa ritel dan TI.

Pada kuartal pertama tahun 2024, <span style="background-color: lightgreen">Amazon Web Service (AWS) memimpin pasar layanan infrastruktur cloud dengan pangsa pasar sebesar 31%</span>. Microsoft Azure mengikuti di posisi kedua dengan pangsa pasar 25%, sementara Google Cloud menyusul dengan pangsa pasar 10%. [(statista.com)](https://www.statista.com/statistics/967365/worldwide-cloud-infrastructure-services-market-share-vendor/)

Bersama-sama, ketiga penyedia cloud terkemuka ini menguasai 66% dari total pasar pada kuartal pertama tahun 2024. [(statista.com)](https://www.statista.com/statistics/967365/worldwide-cloud-infrastructure-services-market-share-vendor/)

Layanan cloud yang ditawarkan terdiri dari beberapa tipe komputasi cloud, yakni _Infrastructure as a Service_ (IaaS), _Platform as a Service_ (PaaS), dan _Software as a Service_ (SaaS). Secara singkat, perbedaan ketiganya adalah:

- IaaS: Memberikan layanan infrastruktur dasar (seperti mesin virtual dan penyimpanan). Sistem operasi dan aplikasinya dikelola oleh pengguna.
- PaaS: Menyediakan platform dan alat pengembangan untuk membangun aplikasi. Pengguna fokus pada pengembangan aplikasi tanpa mengelola infrastruktur.
- <span style="background-color: lightgreen">SaaS: Menyediakan aplikasi perangkat lunak siap pakai. Pengguna hanya menggunakan aplikasi tanpa mengelola infrastruktur atau perangkat lunak, dan berbekal sambungan internet saja.</span>

### Pertumbuhan pasar SaaS
<span style="background-color: lightgreen">Pertumbuhan pasar SaaS diperkirakan akan mengalami kenaikan tahunan sebesar 19% pada 2024</span>, sementara IaaS adalah sekitar 27% dan PaaS  22% . Dari segi skala pasar, segmen-segmen layanan cloud ini diperkirakan mencapai revenue sebesar 232 milyar USD (SaaS), 176 milyar USD (PaaS), and 180 milyar USD (IaaS) pada akhir 2024. [(statista.com)](https://www.statista.com/topics/4418/amazon-web-services/#topicOverview)

### Dominasi AWS di Pasar Layanan Cloud Computing
AWS menghadirkan ekosistem cloud yang komprehensif yang meliputi database, analitik, alat manajemen, keamanan, IoT, aplikasi perusahaan, dan alat pengembangan. Dengan portofolio layanan yang terus dikembangkan, AWS bukan sekedar memenuhi kebutuhan pelanggan yang beragam, tetapi juga mendorong kemajuan standar dan praktik industri. Berkat inovasi berkelanjutan ini, banyak perusahaan global mengandalkan platform cloud publik dan layanan infrastruktur AWS untuk menjalankan aplikasi secara efisien dan scalable. Inilah yang menjadikan AWS sebagai pilihan utama dalam transformasi digital, yang membantu bisnis tetap kompetitif dan adaptif di era teknologi yang terus berkembang di seluruh dunia.
[(statista.com)](https://www.statista.com/topics/4418/amazon-web-services/#topicOverview)

## Permasalahan yang Perlu Dianalisa
Pada paruh pertama tahun 2024 ini, Amazon mengeluarkan 30,5 miliar USD untuk belanja infrastruktur. Pada paruh kedua, <span style="background-color: lightgreen">pengeluaran investasi modal akan lebih banyak diberikan untuk kebutuhan infrastruktur AWS</span> karena permintaan terhadap AI generatif dan non-generatif yang tinggi. [(datacenterdynamics.com)](https://www.datacenterdynamics.com/en/news/aws-revenue-hits-263bn-for-q2-2024-amazon-capex-reaches-305bn/)

Mengingat angka investasi yang sangat tinggi tersebut, <span style="background-color: lightgreen">terdapat kekhawatiran adanya _over-investment_ terhadap AWS</span>. Namun, nyatanya saat ini AWS sudah mencakup 35 wilayah dan 110 zona ketersediaan di seluruh dunia, sehingga AWS memilih untuk menekan resiko logistik dengan cara menyediakan kapasitas yang lebih besar daripada yang dibutuhkan. Dengan begitu, AWS dapat mengantisipasi gangguan layanan karena kekurangan kapasitas.

Untuk memastikan efektivitas investasi terhadap infrastruktur AWS di seluruh wilayah bisnisnya, sebagai data analis, kita dapat mengidentifikasi wilayah bisnis mana yang paling menguntungkan dari segi profit margin dan wilayah mana yang kritis dan butuh peninjauan lebih lanjut. Setelah wilayah kritis teridentifikasi, kita bisa memahami penyebab dari rendahnya profitabilitas dari wilayah tersebut agar solusi yang tepat dapat dibuat. 

Kemudian, kita bisa menelusuri produk tertentu yang memiliki kinerja baik di satu wilayah tetapi kinerjanya buruk di wilayah lain. Dengan begitu, kita bisa mengatur strategi product placement di setiap wilayah bisnis agar efektivitas investasi lebih terjamin.

### Fokus Analisa
Analisa data penjualan SaaS AWS ini difokuskan untuk analisa profitabilitas di wilayah bisnis AWS. Profit margin adalah angka yang menggambarkan profitabilitas suatu bisnis [(accurate.id)](https://accurate.id/akuntansi/pengertian-net-profit-margin-dan-perbedaanya-dengan-gross-profit/). Sehingga, fokus utama analisa ini adalah besaran profit margin dan variabel-variabel yang mempengaruhinya.

Analisa data ini akan menjawab pertanyaan-pertanyaan penelitian bisnis berikut ini:
1.    Bagaimana perbedaan rata-rata profit margin (marjin keuntungan) pada setiap wilayah bisnis AWS? (Wilayah bisnis: EMEA, AMER, dan APJ)
2.    Jika wilayah bisnis kritis sudah diidentifikasi, maka faktor-faktor apa saja kah yang mempengaruhi rendahnya profit margin di wilayah tersebut?
3.    Apakah terdapat produk-produk tertentu yang memiliki profit margin tinggi di satu wilayah, tetapi rendah di wilayah lainnya?

### Kesimpulan:
- Dari analisis yang dilakukan, `wilayah bisnis APJ terbukti menjadi wilayah yang paling kritis dengan profit margin rata-rata yang negatif sebesar -15%`. Meskipun median profit margin menunjukkan nilai positif +0.12, yang artinya 50% transaksi memiliki profit margin di atas 0.12, ada `banyak nilai negatif yang sangat besar hingga menurunkan rata-rata secara signifikan` menjadi -0.15 atau -15%.

- Wilayah `APJ menyumbang profit margin negatif sebesar 39.4% terhadap keseluruhan profit margin` dalam dataset ini, sehingga dibutuhkan penyusunan strategi penjualan baru di sini.

- Faktor utama dari rendahnya profit margin di APJ adalah pemberian diskon yang agresif di beberapa wilayah dengan kuantitas pembelian besar, seperti Jepang dan Australia

- Hanya Australia dan Jepang yang memiliki transaksi dengan diskon 80%, yang jumlahnya sebanyak 300 transaksi. Selain itu, hanya Australia dan Jepang pula yang memiliki transaksi dengan diskon 60% sebanyak 138 transaksi.

- Di wilayah APJ, `tidak ada transaksi yang menghasilkan profit margin positif saat diskon yang diberikan lebih dari 40%.`

- Sayangnya, meskipun diskon diberikan secara besar-besaran, tidak ada korelasi kuat positif antara kuantitas produk terjual dengan besaran diskon. Ini sudah dibuktikan melalui pengujian: 
	- Uji korelasi Spearman Rank baik secara keseluruhan, maupun secara terpisah (per sub grup) untuk mengantisipasi simpson's paradox
	- Uji ANOVA untuk tiga sub grup data, yakni sub data dengan diskon <= 40%, > 40%, dan tanpa diskon

- Lebih lanjut, hasil analisis menunjukkan bahwa `tidak ada korelasi positif yang kuat antara pemberian diskon dan peningkatan penjualan, baik dilihat dari kuantitas, profit, maupun profit margin`. Diskon bahkan memiliki korelasi positif yang sangat lemah dengan kuantitas penjualan (di bawah 0.1), yang membuktikan bahwa diskon bukanlah faktor efektif dalam mendorong penjualan di wilayah APJ.

- `ContactMatcher` adalah produk terlaris, yang konsisten menjadi produk paling banyak terjual di ketiga wilayah. Namun, justru rata-rata profit margin dari penjualan produk ini di APJ sangat rendah (-89%). 

- `SaaS Connector Pack - Gold` adalah produk dengan transaksi tersukses di ketiga wilayah, dan konsisten memberikan profit margin tertinggi di AMER (45%), EMEA (43%), dan bahkan di wilayah kritis APJ (38%).

- `OneView` dan `SaaS Connector Pack` memiliki profit margin baik di AMER dan EMEA, bahkan di atas 25%. Namun, profit margin di APJ justru negatif (-37%)

- Produk `Marketing Suite` memang memiliki profit margin negative juga di APJ, tetapi produk ini memang selalu konsisten bernilai negative di seluruh wilayah

- Namun, analisis menunjukkan bahwa `tanpa diskon wilayah APJ sebenarnya sangat menguntungkan, dengan profit margin rata-rata tertinggi (35%) dibandingkan wilayah lain`. Ini menegaskan bahwa APJ sebenarnya memiliki potensi tinggi yang belum dimanfaatkan sepenuhnya. Misalnya, selain Australia dan Jepang, negara-negara APJ lain memiliki transaksi dengan diskon sangat rendah. Negara-negara seperti Indonesia, India, dan Singapura adalah negara-negara APJ dengan transaksi tanpa diskon. Transaksi di negara-negara lain seperti New Zealand, South Korea, China, dan Taiwan sebagian besar dilakukan tanpa diskon, dan hanya sedikit transaksi dilakukan dengan diskon, itu pun diskonnya sangat rendah (20%-30%). Ini adalah wilayah-wilayah di APJ yang perlu dioptimalkan sebab, mereka tidak sensitif terhadap harga.

### Solusi:

Berdasarkan temuan di atas, beberapa langkah strategis perlu diambil untuk memulihkan dan meningkatkan profitabilitas di wilayah APJ, antara lain:

#### Penghentian Pemberian Diskon Agresif

Mengingat bahwa hasil analisis korelasi dan uji ANOVA menunjukkan bahwa pemberian diskon besar tidak berdampak positif pada penjualan atau profitabilitas, dan justru memperbutuk margin keuntungan, maka langkah pertama yang perlu dilakukan adalah menghentikan strategi diskon agresif di wilayah APJ. Selain itu, diskon -- terlepas dari berapapun besarannya -- tidak mendorong peningkatan kuantitas pembelian.

#### Pengembangan Strategi Promosi Bundling

Berdasarkan hasil analisis keranjang belanja (basket analysis), produk OneView, SaaS Connector Pack, dan ContactMatcher yang berkinerja buruk di APJ ternyata sering dibeli bersama-sama. Fakta ini memberikan peluang besar untuk mengembangkan promosi _bundling_ yang dapat menarik pelanggan tanpa harus memberikan diskon besar. Misalnya, menawarkan `paket OneView, SaaS Connector Pack, dan ContactMatcher dengan potongan harga yang moderat` tetapi tetap menarik.

#### Penguatan Integrasi Produk

Mengembangkan fitur atau paket produk yang meningkatkan `integrasi antara OneView, SaaS Connector Pack, dan ContactMatcher` dapat meningkatkan penjualan bundling secara lebih alami. Dengan peningkatan integrasi, nilai tambah bagi pelanggan akan meningkat, yang bisa mendorong mereka untuk memilih bundling ini tanpa mengharapkan diskon besar.

#### Peningkatan Awareness Produk Berkinerja Tinggi

Produk seperti `SaaS Connector Pack - Gold` yang memiliki profit margin tinggi di semua wilayah, termasuk APJ, harus menjadi fokus utama dalam kampanye pemasaran. Meningkatkan awareness dan edukasi pasar mengenai keunggulan produk ini di APJ bisa menjadi salah satu strategi utama untuk meningkatkan penjualan dengan margin yang baik.

#### Monitoring dan Evaluasi Berkala

Setelah implementasi strategi baru, perlu dilakukan monitoring secara ketat dan berkala terhadap performa penjualan dan profit margin. Penggunaan A/B testing dan metode evaluasi lainnya sangat penting untuk memastikan bahwa strategi yang diterapkan memberikan hasil yang diharapkan. Beberapa indikator kinerja utama (KPI) yang bisa difokuskan dalam monitoring antara lain: peningkatan margin keuntungan, peningkatan jumlah penjualan bundling, dan penurunan proporsi transaksi dengan profit margin negatif.

#### Menggali Potensi APJ yang Belum Dioptimalkan
Mengingat bahwa negara-negara di APJ seperti `Indonesia, India, dan Singapura` dapat efektif bertransaksi tanpa diskon, strategi yang berbeda harus diterapkan di pasar ini. Diskon besar tidak diperlukan dan dapat digantikan dengan strategi nilai tambah lainnya seperti layanan pelanggan yang lebih baik atau penawaran bundling dengan fitur premium. 

Stakeholder AWS dapat fokus kepada negara APJ yang potensial seperti Indonesia, di mana berdasarkan data [(Statista Market Insights)](https://id.techinasia.com/proyeksi-pasar-saas-indonesia-2027#!#:~:text=Berdasarkan%20data%20Statista%20Market%20Insights%2C%20pangsa%20pasar%20sektor,2022%20yang%20sebesar%20US%24326%2C7%20juta%20%28sekitar%20Rp5%2C1%20triliun%29.), pangsa pasar sektor software-as-a-service (SaaS) di Indonesia diproyeksi menembus US$634,5 juta (sekitar Rp9,87 triliun) pada 2027. Jumlah itu meningkat hingga dua kali lipat dibandingkan pada 2022 yang sebesar US$326,7 juta (sekitar Rp5,1 triliun).

Dengan demikian, investasi yang lebih besar dalam pemasaran dan pengembangan produk yang relevan untuk pasar SaaS di Indonesia bisa menjadi strategi yang sangat menguntungkan. Pihak AWS dapat melakukan analisis mendalam untuk memahami preferensi lokal Indonesia dan faktor-faktor yang mendorong penjualan di negara ini. Sehingga, memungkinkan AWS untuk menyesuaikan pendekatan dengan lebih baik di negara potensial ini.

