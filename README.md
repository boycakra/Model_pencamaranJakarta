# Model_pencemaranJakarta

Laporan penelitian ini menggunakan data indeks Standar Pencemar Udara di Provinsi DKI Jakarta untuk melakukan Analisis Data dan Prediksi Regresi Logistik dengan beberapa metode dari machine learning, seperti:

## Visualisasi Data

Visualisasi data adalah metode untuk menampilkan data numerik secara grafis dari informasi dan data. Pada laporan penelitian ini, kami melakukan visualisasi data indeks Standar Pencemar Udara di Provinsi DKI Jakarta menggunakan visualisasi data numerik, visualisasi data kategorik, dan Time series data.

## Regresi Logistik

Analisis regresi digunakan untuk menganalisis hubungan dan pengaruh antara variabel bebas dan variabel terikat. Regresi Logistik adalah model regresi non-linear di mana variabel terikat (Y) memiliki skala kategori nominal atau ordinal, sementara variabel bebas (X) memiliki skala pengukuran kontinu atau kategorik. Pada laporan penelitian ini, kami menggunakan Regresi Logistik dengan skala ordinal untuk membuat model data.

## One Hot Encoding

One-Hot Encoding adalah proses manipulasi data untuk membuat kolom baru dari variabel kategorikal, di mana setiap kategori menjadi kolom baru dengan nilai 0 atau 1 (0 mewakili tidak ada dan 1 mewakili ada). Pada laporan penelitian ini, kami melakukan manipulasi data kolom 'lokasi_spku' yang merupakan variabel kategorikal pada dataset untuk mengubahnya menjadi kolom baru dengan nilai 0 dan 1.

Berdasarkan Keputusan Menteri Lingkungan Hidup Republik Indonesia Nomor : KEP 45 / MENLH / 1997 tentang ISPU (Indeks Standar Pencemaran Udara), dikenal batasan-batasan rentang indeks kualitas udara sebagai berikut:

### Tabel 2.1 Rentang indeks kualitas udara

| Rentang | Kategori        | Dampak Kesehatan                                             |
| ------- | --------------- | ------------------------------------------------------------ |
| 0-50    | Baik            | Tidak memberikan dampak bagi kesehatan manusia atau hewan.   |
| 51-100  | Sedang          | Tidak berpengaruh pada kesehatan manusia atau hewan tetapi berpengaruh pada tumbuhan yang peka. |
| 101-199 | Tidak Sehat     | Bersifat merugikan pada manusia atau kelompok hewan yang peka atau dapat menimbulkan kerusakan pada tumbuhan atau nilai estetika. |
| 200-299 | Sangat Tidak Sehat | Kualitas udara yang dapat merugikan kesehatan pada sejumlah segmen populasi yang terpapar. |
| >= 300  | Berbahaya        | Kualitas udara berbahaya yang secara umum dapat merugikan kesehatan yang serius pada populasi (misalnya iritasi mata, batuk, dahak, dan sakit tenggorokan). |
