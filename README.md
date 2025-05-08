# projectA-sentiment-analysis-coretax
## Deskripsi Proyek

Proyek ini bertujuan untuk melakukan analisis sentimen pada berita yang berkaitan dengan **Coretax** di Indonesia. Data yang digunakan dalam proyek ini dikumpulkan melalui scraping berita online dan diproses untuk analisis sentimen menggunakan teknik **Natural Language Processing** (NLP).

### Tujuan Proyek
- Melakukan scraping berita terkait Coretax
- Melakukan praproses data untuk konten berita dan tanggal
- Melakukan analisis sentimen terhadap berita
- Melakukan **Named Entity Recognition** (NER) dan **Part-of-Speech (POS)** untuk analisis lebih lanjut

## Struktur Direktori

- **data/**: Berisi file data yang digunakan dalam proyek ini.
  - **Kelompok 2 Link Article Coretax.xlsx**: Dataset yang berisi kumpulan link berita Coretax yang telah dikumpulkan.
  - **hasil_praproses.xlsx**: Dataset hasil praproses pada kolom konten.
  - **hasil_preprocessing2.xlsx**: Dataset hasil final preprocessing pada kolom tanggal dan konten berita.
  - **hasil_scrap_berita.xlsx**: Dataset yang berisi berita yang berhasil discraping.
  - **hasildate.xlsx**: Dataset hasil praproses pada kolom tanggal.
  - **hasil_preprocessing3.xlsx**: Dataset hasil final final untuk bisa memulai analisis sentimen.
  - **pos_tag.csv**: Dataset hasil pemrosesan POS Tagging.
  - **entity.csv**: Dataset hasil pemrosesan NER berisi terkait entitas yang muncul dalam artikel.

  
- **notebook/**: Berisi file Jupyter Notebook untuk memproses dan menganalisis data.
  - **1_Scraping_Coretax_News.ipynb**: Notebook untuk melakukan scraping berita dari link.
  - **2_Preprocessing_Coretax.ipynb**: Notebook untuk preprocessing data konten berita.
  - **3_preprocessing_date.ipynb**: Notebook untuk preprocessing kolom tanggal.
  - **4_EDA_POS_NER.ipynb**: Notebook untuk melakukan analisis EDA, POS, dan NER pada data yang telah diproses.
  - **5_Visualization_FeatEngineer.ipynb**: Notebook untuk melakukan analisis sentimen dan tf-idf pada data yang telah diproses.

## Instalasi dan Persiapan

1. **Clone repository**:
   ```bash
   git clone https://github.com/[username]/projectA-sentiment-analysis-coretax.git
   ```
2. **Instalasi Dependensi**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Instalasi Jupyter Notebook**: Untuk membuka dan menjalankan notebook, pastikan sudah menginstal Jupyter:
   ```bash
   pip install jupyter
   ```
4. **Jalankan Notebook**: Jalankan notebook sesuai urutan nomor pada file.
   ```bash
   pip install jupyter
   ```

