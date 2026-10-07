# indonesian Social Media Sentiment Dataset (10K Labeled)

![Language](https://img.shields.io/badge/language-Indonesian-orange)

## Deskripsi Data

10k Dataset Sentimen TikTok Indonesia. Dataset ini berisi **10.000 komentar unik** yang dikumpulkan dari berbagai platform media sosial besar di Indonesia. Setiap data telah melalui proses pembersihan (cleaning) dan pelabelan yang ketat.

1. **Total Data:** 10.000 baris/komentar.
2. **Bahasa:** Bahasa Indonesia (termasuk slang dan bahasa gaul yang umum di media sosial).
3. **Kategori Label:** 
    - **Positif :** Label ini diberikan kepada teks atau komentar yang yang mendukung, menyetujui, memuji, optimis, atau bahagia.
    - **Negatif :** Label ini diberikan kepada teks atau komentar yang menunjukkan emosi, opini, atau sikap yang menolak, mengkritik, kecewa, marah, pesimis, atau membenci.
    - **Netral :** Label ini diberikan kepada teks atau komentar yang bersifat objektif, faktual, bertanya bisa juga berupa kalimat yang ambigu
      
4. **Kualitas Label:** Proses pelabelan dilakukan secara manual dan divalidasi oleh **ahli bahasa Indonesia** untuk memastikan akurasi, konsistensi, dan meminimalkan bias subjektif.
5. **Kegunaan:** Sangat cocok untuk tugas klasifikasi teks, pelatihan model AI/ML (seperti SVM, Naive Bayes, LSTM, atau Transformer/BERT), dan penelitian akademis terkait opini publik.
6. **Periode Pengambilan:** Data dikumpulkan secara **bertahap (incremental) sepanjang tahun 2026**. 

### Struktur Kolom Data
Dataset  `.xlsx` memiliki struktur kolom sebagai berikut:
| Nama Kolom | Tipe Data | Deskripsi |
| :--- | :--- | :--- |
| `uniqueId` | String | ID asli dari platform media sosial. |
| `text` | String | Teks komentar mentah. |
| `sentimen` | String | Label sentimen: `Positif`, `Negatif`, atau `Netral`. |

## Lisensi

Dataset ini disediakan secara gratis untuk memajukan ekosistem riset dan teknologi di Indonesia. Namun, penggunaan dataset ini tunduk pada aturan privasi,
Jika Anda menggunakan dataset ini dalam penelitian atau publikasi Anda, mohon berikan sitasi sebagai bentuk apresiasi:

Copyright (c) 2026 wansobriamin
