


# Investigate Hotel Business using Data Visualization
Sangat penting bagi suatu perusahaan untuk selalu menganalisa performa bisnisnya. Pada kesempatan kali ini, kita akan lebih mendalami bisnis dalam bidang perhotelan. Fokus yang kita tuju adalah untuk mengetahui bagaimana perilaku pelanggan kita dalam melakukan pemesanan hotel, dan hubungannya terhadap tingkat pembatalan pemesanan hotel. Hasil dari insight yang kita temukan akan kita sajikan dalam bentuk data visualisasi agar lebih mudah dipahami dan bersifat lebih persuasif.

### Data Preprocessing
- Handling Null Data
- Replacing Inaccurate Values
- Dropping Unnecessary Data
- Clean Data Ready for Hotel Business Analysis


### Monthly Hotel Booking Analysis Based on Hotel Type
![1](https://github.com/cittamudita/Investigate-Hotel-Business-using-Data-Visualization/blob/660637d2dbe206088b33cb8e0f1e27f14624a225/M2-1.jpg)
-   Terdapat peningkatan signifikan dalam pemesanan hotel selama bulan-bulan dengan liburan yang lebih panjang, seperti yang terlihat dari lonjakan pemesanan dari Mei hingga Juli, yang bersamaan dengan liburan Idul Fitri pada bulan Juni dan Juli.
-   Kedua jenis hotel menunjukkan tren kenaikan yang serupa dari Januari hingga Agustus, tetapi hotel resor mengalami peningkatan pada bulan September, sementara hotel di kota mengalami penurunan. Kurangnya pemesanan dari Januari hingga Maret kemungkinan disebabkan oleh komitmen kerja dan sedikitnya liburan.

### Impact Analysis of Stay Duration on Hotel Bookings Cancellation Rates
#### Melihat persebaran data total stay duration
![2](https://github.com/cittamudita/Investigate-Hotel-Business-using-Data-Visualization/blob/660637d2dbe206088b33cb8e0f1e27f14624a225/M2-2.jpg)

- Persebaran data cenderung condong ke sisi kanan, dengan mayoritas data terfokus pada kisaran 0 hingga 5.
-   Plot juga menunjukkan adanya pemesanan dengan durasi menginap lebih dari 10 hari. Agar analisis lebih mudah, kita dapat mengklasifikasikan data ini ke dalam kelompok berdasarkan ambang nilai tersebut.
-   
![3](https://github.com/cittamudita/Investigate-Hotel-Business-using-Data-Visualization/blob/660637d2dbe206088b33cb8e0f1e27f14624a225/M2-3.png)

Persentase pembatalan pada City Hotel lebih tinggi di bandingkan dengan Resort Hotel yang dapat dipengaruhi oleh tujuan pemesanan. Orang yang menginap di City Hotel mungkin memiliki tujuan perjalanan yang lebih beragam, seperti bisnis, acara sosial, atau perjalanan wisata ke kota. Ini berarti bahwa mereka mungkin lebih rentan terhadap perubahan rencana atau pembatalan yang mendadak dibandingkan dengan orang yang menginap di Resort Hotel dengan tujuan rekreasi atau liburan.
Semakin lama periode menginap, semakin banyak faktor yang dapat memengaruhi rencana pelanggan. Dalam jangka waktu yang lebih lama, ada lebih banyak waktu untuk perubahan dalam situasi pribadi atau rencana pelanggan. Misalnya, mereka mungkin mendapatkan kesempatan kerja baru, perubahan kebutuhan perjalanan, atau perubahan rencana liburan.


### Impact Analysis of Lead Time on Hotel Bookings Cancellation Rate
#### Melihat persebaran data total stay duration
![4](https://github.com/cittamudita/Investigate-Hotel-Business-using-Data-Visualization/blob/660637d2dbe206088b33cb8e0f1e27f14624a225/M2-4.png)

-   Berdasarkan distribusi data, terlihat bahwa mayoritas waktu pemesanan berkumpul dalam rentang 0–100 hari, yang menunjukkan condong ke sisi kanan.
-   Plot juga menunjukkan adanya waktu pemesanan pada lebih dari 150 hari.
-   Maka perlu dilakukan pengelompokan data ke dalam kategori per kuartal untuk mempermudah proses analisis.
![5](https://github.com/cittamudita/Investigate-Hotel-Business-using-Data-Visualization/blob/660637d2dbe206088b33cb8e0f1e27f14624a225/M2-5.png)

Semakin lama jarak waktu antara pemesanan dan tanggal kedatangan, semakin besar kemungkinan terjadi perubahan rencana atau keadaan darurat yang mengakibatkan pembatalan.
Hotel resort mungkin menawarkan pengalaman yang lebih terencana atau dijadwalkan dengan baik, sehingga pelanggan cenderung lebih yakin dalam keputusan pemesanannya. Selain itu, pelanggan yang memesan hotel resort mungkin memiliki motivasi atau alasan yang lebih kuat untuk tidak membatalkan.  
Pembatalan pada City Hotel bisa disebabkan oleh faktor-faktor seperti perubahan rencana bisnis, penjadwalan acara kota, atau faktor-faktor lain yang memengaruhi kepastian perjalanan pelanggan.
