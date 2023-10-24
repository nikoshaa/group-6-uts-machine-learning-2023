# UTS - Machine Learning Course

![screen](screen.png)

## Group 6

- [Wildan Hafidz Mauludin](https://github.com/nikoshaa)
- [Dhayu Intan Nareswari](https://github.com/DhayuIntan)
- [Farhan Dwi Pramana](https://github.com/FarhanDwiPramana)
- [Mochammad Zaky Zamroni](https://github.com/zakyzuf)
- [Ziedny Bisma Mubarok](https://github.com/Ziedny28)

## Segmentasi Gambar dengan Clustering

Segmentasi merupakan salah satu cara untuk membedakan antara objek satu dengan objek lainnya dalam suatu citra. Cara ini dapat dilakukan dengan mengelompokkan nilai pixel citra berdasarkan kedekatan warnanya.

Pada UTS kali ini, Anda diminta untuk melakukan segmentasi citra plat nomor kendaraan di Indonesia. Fungsi segmentasi dalam kasus ini adalah mempermudah pembacaan plat nomor kendaraan sebelum proses selanjutnya, seperti pembacaan karakter pada plat nomor.

## Ketentuan UTS

Berdasarkan pemaparan kasus, Anda diminta untuk,

1. Pilih 5 citra plat nomor untuk setiap anggota kelompok dari dataset yang telah disediakan. [DOWNLOAD](https://storage.googleapis.com/kuliah_mah/dummy.zip)
2. Lakukan segmentasi pada citra plat nomor untuk memperjelas karakter pada plat nomor.
3. Anda dapat menggunakan algortima K-Means seperti yang telah dijelaskan pada praktikum sebelumnya atau menggunakan algoritma klasterisasi yang lain.
4. Anda diperkenankan untuk melakukan pra pengolahan data (preprocessing) pada citra seperti,
   - Merubah color space
   - Reduksi dimensi
   - dsb
5. Tampilkan perbandingan citra antara sebelum dan sesudah di segmentasi

## Open Challange (Opsional)

- Bagaimana cara melakukan evaluasi pada hasil segementasi?
- Terapkan pada kasus ini!

## Catatan:

1. Proses loading citra dicontohkan dengan menggunakan library openCV
2. Secara default, openCV akan memuat citra dalam format BGR

## Kesimpulan dari Berbagai Metode dan Hasil yang didapat

[Wildan Hafidz Mauludin](https://github.com/nikoshaa/group-6-uts-machine-learning-2023/blob/main/UTS_ML_Wildan%20Hafidz%20Mauludin.ipynb)

[Ziedny Bisma Mubarok](https://github.com/nikoshaa/group-6-uts-machine-learning-2023/blob/main/UTS_ML_Mochammad_Zaky_Zamroni.ipynb)

[Mochammad Zaky Zamroni](https://github.com/nikoshaa/group-6-uts-machine-learning-2023/blob/main/UTS_ML_Mochammad_Zaky_Zamroni.ipynb)

[Dhayu Intan Nareswari](https://github.com/nikoshaa/group-6-uts-machine-learning-2023/blob/main/UTS__ML_Dhayu%20Intan%20Nareswari.ipynb)

[Farhan Dwi Pramana](https://github.com/FarhanDwiPramana)

## Kesimpulan

Kesimpulan dari semua metode yang telah dilakukan adalah bahwa hasil dari nomor plat tidak dapat terbaca jika kondisi citra plat rusak atau penyok namun jika kondisi plat tersebut tidak rusak atau penyok hasil dari nomor plat dapat terbaca dengan baik.

## License

MIT License
