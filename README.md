# Tugas-Akhir
Tugas Akhir dengan topik data mining dengan menggunakan bahasa pemrograman python dan dataset data malware 

Tujuan : Mengetahui apakah Metode Random Forest dapat digunakan dalam dataset Malware Android
Batasan : Bahasa pemrograman Python, menggunakan dataset CIC Android Malware 2017

Penjelasan Singkat  : Dataset menggunakan dataset CICAndMAL2017 dari website CIC (Canadian Institute Cybersecurity). Menggunakan Malware PornDroid dan benign sebagai bagian sampel. Mengambil 4000 sampel Malware dan 4000 sampel benign.
                      Memanggil dataset terlebih dahulu, lalu dilakukan proses EDA untuk mengenali ini dataset yang digunakan. Preprocessing hanya menghapus data yang terdapat data kosong dan duplikat. Setelah di preprocessing data dibagi menjadi 70:30. 70% untuk data uji.
                      Setelah itu melakukan proses Scalling pada data latih untuk membuat rentang sampel menjadi kecil supaya proses perhitungan metode menjadi mudah. 
                      Setelah dilakukan scalling maka data dapat dimasukkan kedalam metode Random Forest dengan memanggil RandomForestClassifier. Setelah diproses menggunakan Random Forest maka hasil akan diketahui setelah perhtiungan pada Confusion MAtrix.
                      Hasil pada Penelitian ini menghasilkan 80% akurasi yang menandakan **Metode Random Forest dapat digunakan dalam dataset Malware tersebut**
