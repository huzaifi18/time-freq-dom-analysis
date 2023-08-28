# Analisis Suara Laki-laki dan Perempuan berdasarkan Time Domain Feature dan Frequency Domain Feature
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/huzaifi18/time-freq-dom-analysis/blob/main/Time_Freq_Analysis.ipynb)<br>
Pada projek ini dilakukan pengolahan suara untuk mendapatkan ciri yang membedakan suara dari laki-laki dan perempuan. Ekstraksi ciri akan dilakukan terhadap kedua jenis suara tersebut. Beberapa metode ektraksi ciri yang digunakan dalam projek ini antara lain, Fast Fourier Transform (FFT), Time Domain Audio Feature meliputi RMSE dan Zero Crossing Rate, dan Frequency Domain Audio Feature meliputi Spectral Centroid dan MFCC. Selain itu juga dilakukan feature selection menggunakan PCA dari MFCC.


TUJUAN:
1. Menganalisis perbedaan suara laki-laki dan perempuan.
2. Mengetahui ciri dari suara laki–laki dan perempuan.
3. Mengetahui jenis ekstraksi fitur yang cocok untuk menunjukkan perbedaan antara suara laki-laki dan perempuan

---
### Analisis Fast Fourier Transform (FFT)


![Gambar](FFT.png)

Dari hasil kedua plotting FFT antara 2 suara yaitu suara laki-laki dan perempuan,
terlihat bahwa sinyal suara laki-laki memiliki peak yang dominan pada rentang 110 - 200 Hz.
Sedangkan untuk suara perempuan memiliki peak pada frekuensi lebih tinggi dan berkisar diantara 275 - 350 Hz.
Hal ini menandakan bahwa suara laki memiliki dominan frekuensi yang lebih rendah dari pada suara perempuan. Selain itu, sinyal suara perempuan memiliki beberapa puncak pada frekuensi yang lebih tinggi setelah puncak tertinggi. Berbeda dengan sinyal suara laki-laki yang memliki bentuk landai pada frekuensi yang lebih tinggi setelah puncak tertingginya.