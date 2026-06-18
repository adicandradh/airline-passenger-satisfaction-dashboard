# Airline Passenger Satisfaction Dashboard (Power BI)

## 📌 Project Type
Personal Project

## 📊 Overview
Project ini merupakan dashboard interaktif berbasis Microsoft Power BI yang dikembangkan untuk menganalisis tingkat kepuasan penumpang maskapai berdasarkan karakteristik pelanggan, layanan, dan operasional penerbangan.

Fokus utama dari project ini adalah mengolah data penumpang menjadi informasi yang terstruktur, konsisten, dan mudah dianalisis. Proses yang dilakukan mencakup data cleaning, data transformation, pembuatan calculated columns dan measures menggunakan DAX, serta visualisasi data untuk mengidentifikasi faktor-faktor yang memengaruhi kepuasan pelanggan.

## 🎯 Objectives
- Menyajikan ringkasan kondisi penumpang melalui KPI utama, meliputi Total Passengers, Satisfied Passengers, Neutral or Dissatisfied Passengers, Returning Passengers, Average Flight Distance, dan Average Departure Delay.
- Mengevaluasi kualitas layanan berdasarkan Average Rating by Service Category untuk mengidentifikasi aspek layanan dengan performa terbaik dan terendah.
- Menganalisis distribusi tingkat kepuasan penumpang melalui Passenger Satisfaction Distribution.
- Membandingkan tingkat kepuasan berdasarkan Type of Travel.
- Membandingkan tingkat kepuasan berdasarkan Class penerbangan.
- Menganalisis distribusi tipe pelanggan melalui Passenger Type Distribution.
- Menganalisis distribusi penumpang berdasarkan Gender Distribution.
- Mengidentifikasi pola kepuasan berdasarkan Age Group.
- Mengevaluasi hubungan antara Departure Delay Group dan tingkat kepuasan penumpang.

## ⚙️ Data Processing
- Data cleaning untuk memastikan konsistensi dan kualitas data
- Penanganan missing values dan validasi data
- Pembuatan calculated columns menggunakan DAX
- Pembuatan measures menggunakan DAX untuk KPI dan business metrics
- Pengelompokan (grouping) variabel numerik menjadi kategori

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
<img width="4100" height="2350" alt="airline-passengers-satisfaction" src="https://github.com/user-attachments/assets/209d01f3-fbcd-4317-8542-bd99e4be8ac8" />

## 📊 Insights
- Dashboard menunjukkan terdapat 129,88 ribu passengers, dengan 56,43 ribu passengers (43,45%) yang satisfied dan 73,45 ribu passengers (56,55%) yang neutral or dissatisfied. Selain itu, mayoritas merupakan returning passengers sebanyak 106,10 ribu (81,69%), sedangkan first-time passengers berjumlah 23,78 ribu (18,31%). Rata-rata flight distance tercatat sebesar 1.190 km dengan average departure delay sebesar 14,71 menit.
- In-flight Service menjadi kategori layanan dengan rata-rata rating tertinggi sebesar 3,64, diikuti oleh Baggage Handling (3,63) dan Seat Comfort (3,44). Sebaliknya, In-flight WiFi Service memperoleh rating terendah sebesar 2,73, diikuti Ease of Online Booking (2,76) dan Gate Location (2,98), sehingga aspek layanan digital menjadi peluang utama untuk ditingkatkan.
- Distribusi kepuasan menunjukkan bahwa 56,55% penumpang berada pada kategori neutral or dissatisfied, sedangkan 43,45% lainnya merasa satisfied. Kondisi ini mengindikasikan bahwa masih terdapat ruang yang cukup besar untuk meningkatkan pengalaman pelanggan secara keseluruhan.
- Jika ditinjau berdasarkan Type of Travel, penumpang yang melakukan Business Travel memiliki tingkat kepuasan yang jauh lebih tinggi, dengan 58,37% berada pada kategori satisfied. Sebaliknya, pada Personal Travel, sekitar 89,87% penumpang berada pada kategori neutral or dissatisfied.
- Analisis berdasarkan Class memperlihatkan bahwa Business Class memiliki tingkat kepuasan tertinggi dengan 69,44% satisfied, sedangkan Economy Plus dan Economy masing-masing hanya mencapai 24,64% dan 18,77% satisfied. Hal ini menunjukkan adanya perbedaan pengalaman yang cukup signifikan antar kelas penerbangan.
- Dari sisi Passenger Type, returning passengers mendominasi dengan proporsi 81,69%, sementara first-time passengers hanya 18,31%. Sementara itu, distribusi berdasarkan gender relatif seimbang, dengan 50,74% female passengers dan 49,26% male passengers.
- Kelompok usia 46–55 tahun memiliki tingkat kepuasan tertinggi dengan 57,78% satisfied, diikuti kelompok usia 36–45 tahun sebesar 52,07%. Sebaliknya, kelompok usia <18 tahun dan 65+ tahun menunjukkan proporsi kepuasan terendah, masing-masing hanya 16,73% dan 18,51%.
- Tingkat kepuasan juga cenderung menurun seiring meningkatnya departure delay. Penumpang dengan penerbangan On-time memiliki proporsi 45,94% satisfied, sedangkan pada kategori keterlambatan 61–120 menit hanya 35,80% yang satisfied, menunjukkan bahwa ketepatan waktu keberangkatan berkontribusi terhadap pengalaman penumpang.
