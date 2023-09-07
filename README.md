# Tugas-Akhir
Tugas Akhir dengan topik data mining dengan menggunakan bahasa pemrograman python dan dataset data malware 

Tujuan : Mengetahui apakah Metode Random Forest dapat digunakan dalam dataset Malware Android
Batasan : Bahasa pemrograman Python, menggunakan dataset CIC Android Malware 2017, menggunakan metode Data Minging Random Forest

Penjelasan Singkat  : Dataset menggunakan dataset CICAndMAL2017 dari website CIC (Canadian Institute Cybersecurity). Menggunakan metode Random Forest yang berkonsep memiliki banyak                              decision tree. Menggunakan Malware PornDroid dan benign(malware tidak berbahaya) sebagai bagian sampel. Mengambil 4000 sampel Malware dan 4000 sampel benign.                               Spesifikasi Malware dikatakan sebagai "x" dan Label sebagai "y".
                      Memanggil dataset terlebih dahulu, lalu dilakukan proses EDA untuk mengenali dataset yang digunakan. Preprocessing hanya menghapus data yang terdapat data kosong dan                       duplikat. Setelah dipreprocessing data dibagi menjadi 70:30. 70% untuk data uji dan 30% untuk data uji.
                      Setelah itu melakukan proses Scalling pada data latih untuk membuat rentang sampel menjadi kecil supaya proses perhitungan metode menjadi mudah. 
                      Setelah dilakukan scalling maka data dapat dimasukkan kedalam metode Random Forest dengan memanggil RandomForestClassifier. Dengan menggunakan parameter n_estimator                        = 300 (banyaknya decsion tree maksimal adalah 300). Setelah diproses menggunakan Random Forest maka hasil akan diketahui setelah perhtiungan pada Confusion Matrix.
                      Hasil pada Penelitian ini menghasilkan 80% akurasi yang menandakan **Metode Random Forest dapat digunakan dalam dataset Malware tersebut** 
