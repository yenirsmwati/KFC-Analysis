# **Sentiment Analysis: KFC vs Competitors** 🍗🍟🥤🍔
## 📌 Project Overview
Project ini bertujuan untuk menganalisis sentimen pelanggan KFC, McDonald's, dan Burger King 
berdasarkan ulasan pelanggan. Hasil analisis digunakan untuk mengidentifikasi kelebihan dan kekurangan masing-masing brand 
serta memberikan rekomendasi perbaikan layanan dan menu untuk KFC agar lebih kompetitif.
## 📊 Dataset & Metode
- **Dataset**: Review pelanggan yang dikumpulkan dari Google Maps Review menggunakan SerpApi.
- **Preprocessing**: Tokenisasi, stopword removal, stemming.
- **Analisis Sentimen**: Label sentimen (Positif, Negatif, Netral) ditentukan menggunakan model Transformers dari Hugging Face.
  [link model hugging face](https://huggingface.co/ayameRushia/bert-base-indonesian-1.5G-sentiment-analysis-smsa)
- **N-Gram Analysis**: Mengidentifikasi pola kata yang sering muncul dalam ulasan negatif dan positif.
- **Visualisasi Data**: Word cloud, bar chart, dan tabel perbandingan sentimen.
## 📂 Project Files
- 📄 [Wordcloud_Sentiment_KFC.ipynb](https://github.com/yenirsmwati/KFC-Analysis/blob/main/Wordcloud_Sentiment_KFC.ipynb) → Script untuk analisis sentimen, N-gram, serta visualisasi wordcloud.
- 📊 [sentiment_transformers.ipynb](https://github.com/yenirsmwati/KFC-Analysis/blob/main/sentiment_transformers.ipynb) → Notebook untuk eksplorasi data dan visualisasi.
- 📑 [review_burgerking_jember.csv](https://github.com/yenirsmwati/KFC-Analysis/blob/main/review_burgerking_jember.csv) → Raw dataset ulasan pelanggan google maps review Burger King.
- 📑 [review_kfc_jember.csv](https://github.com/yenirsmwati/KFC-Analysis/blob/main/review_kfc_jember.csv) → Raw dataset ulasan pelanggan google maps review KFC.
- 📑 [review_mcd_jember.csv](https://github.com/yenirsmwati/KFC-Analysis/blob/main/review_mcd_jember.csv)→ Raw dataset ulasan pelanggan google maps review McDonald's.
## 📌PPT Hasil Analisis
🚀[Klik di sini untuk melihat file PPT lengkap](https://docs.google.com/presentation/d/1cVtpSOUHEJLjyW8g_b7R3jtonIUSi6DC/edit?usp=sharing&ouid=116312443342283854478&rtpof=true&sd=true)
