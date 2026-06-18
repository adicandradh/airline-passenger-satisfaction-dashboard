# Airline Passenger Satisfaction Dashboard (Power BI)

## 📌 Project Type
Personal Project

## 📊 Overview
Project ini merupakan dashboard interaktif berbasis Microsoft Power BI yang dikembangkan untuk menganalisis tingkat kepuasan penumpang maskapai berdasarkan karakteristik pelanggan, layanan, dan operasional penerbangan.

Fokus utama dari project ini adalah mengolah data penumpang menjadi informasi yang terstruktur, konsisten, dan mudah dianalisis. Proses yang dilakukan mencakup data cleaning, data transformation, pembuatan calculated columns dan measures menggunakan DAX, serta visualisasi data untuk mengidentifikasi faktor-faktor yang memengaruhi kepuasan pelanggan.

## 🎯 Objectives
- Menyajikan ringkasan kondisi penumpang melalui KPI utama
- Menganalisis distribusi kepuasan penumpang
- Mengevaluasi kualitas layanan berdasarkan rata-rata rating setiap service category
- Menganalisis kepuasan berdasarkan tipe perjalanan (Type of Travel)
- Menganalisis kepuasan berdasarkan kelas penerbangan (Class)
- Mengidentifikasi pola kepuasan berdasarkan kelompok usia (Age Group)
- Mengevaluasi hubungan antara departure delay dan tingkat kepuasan penumpang
- Menganalisis distribusi tipe pelanggan dan gender penumpang

## ⚙️ Data Processing
- Data cleaning untuk memastikan konsistensi dan kualitas data
- Penanganan missing values dan validasi data
- Pembuatan calculated columns menggunakan DAX (Age Group dan Departure Delay Group)
- Pembuatan measures menggunakan DAX untuk KPI dan business metrics
- Pengelompokan (grouping) variabel numerik menjadi kategori analitis
- Data transformation untuk mendukung visualisasi dashboard
- Dashboard design dan formatting menggunakan Microsoft Power BI

## 🧠 Business Logic
- Total Passengers dihitung berdasarkan jumlah ID penumpang unik.
- Satisfied Passengers dihitung berdasarkan jumlah penumpang dengan status Satisfied.
- Neutral or Dissatisfied Passengers dihitung berdasarkan jumlah penumpang dengan status Neutral or Dissatisfied.
- Returning Passengers dihitung berdasarkan jumlah penumpang dengan Customer Type = Returning.
- First-time Passengers dihitung berdasarkan jumlah penumpang dengan Customer Type = First-time.
- Gender Distribution dihitung berdasarkan proporsi Male dan Female Passengers terhadap total penumpang.
- Average Flight Distance dihitung menggunakan rata-rata jarak penerbangan seluruh penumpang.
- Average Departure Delay dihitung menggunakan rata-rata waktu keterlambatan keberangkatan.
- Service Category Rating dihitung menggunakan rata-rata skor pada setiap atribut layanan untuk mengidentifikasi aspek layanan dengan performa terbaik dan terendah.
- Age Group dan Departure Delay Group dibentuk melalui calculated columns untuk mempermudah analisis segmentasi dan visualisasi.

## 🛠️ Tools & Skills
- Microsoft Power BI
- DAX (Data Analysis Expressions)
- Data cleaning
- Data transformation
- Data modeling
- Calculated columns & measures
- Data visualization & dashboard design
- Business analysis

## 🖼️ Preview
Berikut dashboard interaktif yang dikembangkan menggunakan Microsoft Power BI:
<img width="4100" height="2350" alt="airline-passengers-satisfaction" src="https://github.com/user-attachments/assets/fb46fa09-3cef-4d35-b116-67aca7c09d77" />

## 📊 Insights
- Dashboard menunjukkan total 129,88 ribu passengers, terdiri dari 56,43 ribu passengers (43,45%) yang satisfied dan 73,45 ribu passengers (56,55%) yang neutral or dissatisfied. Selain itu, mayoritas pelanggan merupakan returning passengers sebanyak 106,10 ribu (81,69%), sedangkan first-time passengers berjumlah 23,78 ribu (18,31%). Distribusi gender relatif seimbang dengan 64 ribu male passengers (49,26%) dan 66 ribu female passengers (50,74%).
- Berdasarkan penilaian layanan, In-flight Service memperoleh rata-rata rating tertinggi sebesar 3,64, diikuti oleh Baggage Handling (3,63) dan Seat Comfort (3,44). Sebaliknya, In-flight WiFi Service mencatat rating terendah sebesar 2,73, diikuti Ease of Online Booking (2,76) dan Gate Location (2,98), sehingga area tersebut menjadi peluang utama untuk peningkatan kualitas layanan.
- Tingkat kepuasan berbeda signifikan berdasarkan Type of Travel. Pada perjalanan Business, 58,37% passengers merasa satisfied, sedangkan pada perjalanan Personal hanya sekitar 10,13% yang satisfied dan 89,87% berada pada kategori neutral or dissatisfied. Hal ini menunjukkan bahwa pengalaman pelanggan pada perjalanan bisnis cenderung lebih baik dibandingkan perjalanan pribadi.
- Berdasarkan Class, Business Class memiliki tingkat kepuasan tertinggi dengan 69,44% satisfied, jauh di atas Economy Plus (24,64%) dan Economy (18,77%). Sebaliknya, Economy Class didominasi oleh 81,23% neutral or dissatisfied passengers, mengindikasikan adanya kesenjangan pengalaman pelanggan antar kelas penerbangan.
- Analisis berdasarkan Age Group menunjukkan bahwa kelompok usia 46–55 tahun memiliki proporsi kepuasan tertinggi dengan 57,78% satisfied, diikuti kelompok 36–45 tahun sebesar 52,07%. Sebaliknya, kelompok usia <18 tahun dan 65+ tahun memiliki tingkat kepuasan terendah, dengan masing-masing hanya 16,73% dan 18,51% yang merasa puas.
- Berdasarkan Departure Delay Group, tingkat kepuasan cenderung menurun seiring meningkatnya keterlambatan keberangkatan. Penumpang On-time memiliki proporsi 45,94% satisfied, sedangkan kategori 61–120 menit hanya mencapai 35,80% satisfied. Meskipun demikian, pada seluruh kategori keterlambatan, proporsi neutral or dissatisfied passengers tetap lebih tinggi dibandingkan satisfied passengers, menunjukkan bahwa faktor selain keterlambatan keberangkatan kemungkinan turut memengaruhi kepuasan pelanggan.
