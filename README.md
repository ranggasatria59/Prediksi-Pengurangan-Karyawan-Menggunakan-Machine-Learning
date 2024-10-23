Deskripsi
Proyek ini bertujuan untuk menganalisis dan memprediksi potensi pengunduran diri (attrition) karyawan di perusahaan. Dengan memanfaatkan model klasifikasi seperti Logistic Regression dan Decision Tree, kami dapat menentukan faktor-faktor yang berkontribusi pada pengunduran diri karyawan, seperti usia, kepuasan kerja, gaji, dan jam kerja.

Dataset
Dataset terdiri dari beberapa fitur berikut:

EmployeeID: ID Karyawan
Age: Usia Karyawan
Job Satisfaction: Tingkat Kepuasan Kerja (1 hingga 5)
Salary: Gaji Tahunan
Working Hours: Jumlah Jam Kerja per Minggu
Attrition: Status Pengunduran Diri (0 = Tidak Mengundurkan Diri, 1 = Mengundurkan Diri)
Contoh data:

EmployeeID	Age	JobSatisfaction	Salary	WorkingHours	Attrition
1	34	4	70000	40	0
2	29	2	45000	45	1
3	42	5	90000	50	0
...	...	...	...	...	...
Teknologi & Tools
Python
Pandas untuk pemrosesan data
Matplotlib untuk visualisasi data
Scikit-learn untuk membangun model klasifikasi
Proses
Preprocessing Data: Mengubah variabel kategorikal menjadi numerik dan membersihkan data.
Modeling: Menggunakan model Logistic Regression dan Decision Tree untuk memprediksi pengunduran diri karyawan.
Evaluasi Model: Mengukur akurasi model dan melihat metrik evaluasi seperti precision, recall, dan F1-score.
Hasil
Model yang dibangun dapat membantu perusahaan dalam memahami faktor-faktor yang menyebabkan karyawan mengundurkan diri, dengan akurasi model mencapai 78%. Ini memberikan wawasan penting dalam pengambilan keputusan strategis terkait retensi karyawan.

Kesimpulan
Dengan model ini, perusahaan dapat lebih proaktif dalam mengidentifikasi karyawan yang berpotensi mengundurkan diri dan mengambil langkah-langkah untuk mempertahankan mereka melalui peningkatan kepuasan kerja, penyesuaian gaji, atau perubahan pada jam kerja.



Hasil Grafik

![grafik distribusti turnover](https://github.com/user-attachments/assets/ac7dc104-3e9f-41fd-a2bd-6708ac7f0822)
![Grafik Perbandingan Gaji dengan Turnover](https://github.com/user-attachments/assets/4a3eba5b-a5d6-4571-b34f-035720e5531a)
![Grafik Perbandingan Logistic Regression dan Decision Tree](https://github.com/user-attachments/assets/0973025e-9041-4935-bba9-f65abf359619)
