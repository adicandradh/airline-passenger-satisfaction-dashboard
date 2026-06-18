# Airline Passenger Satisfaction Dashboard

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
- Pengelompokan (grouping) variabel numerik menjadi variabel kategori

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
- Data cleaning
- Data transformation
- Data modeling
- DAX (Data Analysis Expressions)
- Calculated columns & measures
- Data visualization & dashboard design
- Business analysis

## 🖼️ Preview
Berikut dashboard interaktif yang dikembangkan menggunakan Microsoft Power BI:
<img width="4100" height="2350" alt="airline-passengers-satisfaction" src="https://github.com/user-attachments/assets/209d01f3-fbcd-4317-8542-bd99e4be8ac8" />

## 📊 Insights
- Dashboard menunjukkan terdapat 129,88 ribu passengers, dengan 56,43 ribu (43,45%) berada pada kategori Satisfied dan 73,45 ribu (56,55%) berada pada kategori Neutral or Dissatisfied. Mayoritas merupakan Returning Passengers sebanyak 106,10 ribu (81,69%), sedangkan First-time Passengers berjumlah 23,78 ribu (18,31%). Selain itu, rata-rata Flight Distance tercatat sebesar 1.190 km dengan Average Departure Delay sebesar 14,71 menit.
- Berdasarkan Average Rating by Service Category, In-flight Service memperoleh nilai rata-rata tertinggi sebesar 3,64, diikuti oleh Baggage Handling (3,63) dan Seat Comfort (3,44). Di sisi lain, In-flight WiFi Service memiliki rating terendah sebesar 2,73, disusul Ease of Online Booking (2,76) dan Gate Location (2,98), sehingga ketiga aspek tersebut menjadi area yang paling berpotensi untuk ditingkatkan.
- Distribusi kepuasan menunjukkan bahwa 56,55% penumpang berada pada kategori Neutral or Dissatisfied, sedangkan 43,45% lainnya berada pada kategori Satisfied. Hal ini mengindikasikan bahwa lebih dari separuh penumpang belum memperoleh pengalaman yang sepenuhnya memuaskan selama menggunakan layanan maskapai.
- Jika ditinjau dari Type of Travel, penumpang yang melakukan Business Travel memiliki tingkat kepuasan yang jauh lebih tinggi dengan 58,37% Satisfied dan 41,63% Neutral or Dissatisfied. Sebaliknya, pada Personal Travel, hanya sekitar 10,13% yang merasa puas, sementara 89,87% berada pada kategori Neutral or Dissatisfied.
- Berdasarkan Class, Business Class mencatat tingkat kepuasan tertinggi dengan 69,44% Satisfied, jauh di atas Economy Plus (24,64%) dan Economy (18,77%). Sebaliknya, Economy Class didominasi oleh penumpang yang Neutral or Dissatisfied sebesar 81,23%, menunjukkan adanya perbedaan pengalaman pelanggan yang cukup signifikan antar kelas penerbangan.
- Distribusi tipe penumpang menunjukkan bahwa Returning Passengers mendominasi dengan proporsi 81,69% (106,10 ribu), sedangkan First-time Passengers hanya mencapai 18,31% (23,78 ribu). Komposisi ini mengindikasikan bahwa sebagian besar responden merupakan pelanggan yang telah menggunakan layanan maskapai lebih dari satu kali.
- Komposisi Gender Distribution relatif seimbang, terdiri dari 65,90 ribu Female Passengers (50,74%) dan 63,98 ribu Male Passengers (49,26%), sehingga tidak terdapat perbedaan yang mencolok dalam distribusi penumpang berdasarkan jenis kelamin.
- Berdasarkan Age Group, kelompok usia 46–55 tahun memiliki tingkat kepuasan tertinggi dengan 57,78% Satisfied, diikuti kelompok 36–45 tahun sebesar 52,07%. Sebaliknya, kelompok usia <18 tahun dan 65+ tahun didominasi oleh penumpang yang Neutral or Dissatisfied, masing-masing sebesar 83,27% dan 81,49%, sehingga menjadi segmen dengan tingkat kepuasan paling rendah.
- Jika dilihat dari Departure Delay Group, proporsi penumpang yang merasa puas cenderung menurun seiring meningkatnya keterlambatan keberangkatan. Pada penerbangan On-time, persentase Satisfied mencapai 45,94%, kemudian turun menjadi 43,55% pada keterlambatan 1–15 menit, 38,43% pada 16–30 menit, 36,41% pada 31–60 menit, serta sekitar 35,80% dan 35,95% pada kategori 61–120 menit dan >120 menit. Pola ini menunjukkan bahwa semakin lama keterlambatan keberangkatan, semakin rendah tingkat kepuasan penumpang.
