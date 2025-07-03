# Analisis Faktor yang Mempengaruhi Engagement Tren Media Sosial

## Repository Outline
1. description.md - Penjelasan gambaran umum project
2. h8dsft_Milestone1_iriel_aureleo.ipynb - Notebook yang berisi pengolahan dan analisis data dengan phyton
3. Viral_Social_Media_Trends.csv - file dataset yang digunakan untuk pengolahan dan analisis data

## Problem Background
Media sosial menjadi platform utama bagi kreator, brand, dan individu untuk menjangkau audiens. Namun, tidak semua konten mendapatkan engagement tinggi. Analisis ini menganalisis faktor-faktor seperti platform, jenis konten, dan lokasi wilayah yang memengaruhi viralitas tren media sosial. Hasilnya dapat membantu kreator konten merancang strategi yang lebih efektif.Analisis bertujuan untuk mengidentifikasi faktor yang paling berpengaruh terhadap engagement tren media sosial yang diharapkan dapat membantu kreator konten dalam merancang strategi konten yang lebih efektif untuk meningkatkan keterlibatan audiens dan jangkauan secara optimal.

## Project Output
Output dari project ini merupakan dasboard berupa Data Visualization dan Statistical Analysis

## Data
Dataset yang digunakan dalam analisis ini berjudul "Viral Social Media Trends and Engagement Analysis", yang diperoleh dari Kaggle. Dataset ini berisi informasi mengenai tren viral di berbagai platform media sosial, mencakup detail seperti hashtag, jenis konten, wilayah, dan berbagai metrik keterlibatan pengguna.

Karakteristik Data:

    Jumlah Baris: 5.000

    Jumlah Kolom: 10 (tidak termasuk kolom yang dihitung sendiri dalam analisis)

    Tidak terdapat missing values dalam dataset

    Kolom yang tersedia:

        Post_ID: Identifikasi unik setiap postingan.

        Platform: Platform media sosial tempat tren terjadi.

        Hashtag: Hashtag yang digunakan dalam postingan.

        Content_Type: Jenis konten (misalnya gambar, video, teks, dll.).

        Region: Wilayah atau lokasi audiens utama.

        Views: Jumlah tampilan dari postingan.

        Likes: Jumlah suka yang diterima.

        Shares: Jumlah kali postingan dibagikan.

        Comments: Jumlah komentar pada postingan.

        Engagement_Level: Kategori tingkat keterlibatan (Low, Medium, High).


## Method
Digunakan analisis eksplorasi data (EDA) dan statistik untuk memahami faktor yang memengaruhi engagement di berbagai platform media sosial. Statistik deskriptif diterapkan untuk melihat variasi engagement (standard deviation & IQR). Selain itu, uji ANOVA digunakan untuk menentukan apakah terdapat perbedaan signifikan dalam engagement antar platform. Hasil analisis juga dilakukan visualisasi.

## Stacks
Analisis ini dilakukan menggunakan Python dengan berbagai library untuk pemrosesan data, analisis statistik, dan visualisasi, serta Tableau untuk pembuatan dashboard interaktif. Berikut adalah tools dan library yang digunakan:

    pandas → Untuk manipulasi dan analisis data.

    plotly.express → Untuk visualisasi data interaktif.

    statsmodels & scipy.stats → Untuk analisis statistik, termasuk uji ANOVA.

    Tableau → Untuk membuat dashboard interaktif guna menampilkan hasil analisis secara visual.

Tools ini digunakan secara kombinatif untuk mengeksplorasi pola engagement dan memberikan insight berbasis data.

## Reference
Link Dashboard Tableau : https://public.tableau.com/views/Milestones1_17423934921470/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link 

---
