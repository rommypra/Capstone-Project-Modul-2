# Capstone Project Module 2 Data Analysis 
### Background
Sebuah perusahaan bergerak di bidang software dan cloud services ingin melakukan R&D pada satu produk mereka agar selalu menjadi yang terdepan dalam memberikan solusi. Perusahaan ini akan menggunakan capex tahun 2024 sebagai sumber dana pengembangannya, tapi capex tersebut diperkirakan tidak akan cukup untuk melakukan R&D pada semua produk software dan cloud services.

### Problem Statement
Perusahaan ingin tau produk software dan cloud services mana yang layak dilakukan R&D dari sisi bisnis. Di mana biaya R&D harus menghasilkan ROI yang tinggi. Informasi ini akan membantu perusahaan menentukan mana produk software dan cloud services meningkat revenue topline dan profit.

Sebagai seorang data analyst kita akan menjawab pertanyaan berikut:
**Apa rekomendasi produk software dan cloud services yang paling menguntungkan dari parameter bisnis untuk dilakukan R&D?**

### Dataset
Untuk menjawab pertanyaan tersebut kita akan melakukan analisa data dan menggunakan library yang sesuai. Dataset yang digunakan dapat diakses [di sini](https://drive.google.com/drive/folders/1dlpJfgvs8P_IyXqWB4WrNwk91fx0XAzU?usp=sharing).

Dataset berisi informasi penjualan software dan cloud services selama periode 2020-2023. Terdapat 19 kolom dalam dataset SaaS Sales:
1. Row ID: id unik tiap transaksi
2. Order ID: id unik tiap order
3. Order Date: tanggal pemesanan
4. Date Key: nomor yang merepresentasikan tanggal pesanan (DDMMYYYY)
5. Contact Name: identitas pemesan
6. Country: negara asal pemesan
7. City: kota asal pemesan
8. Region: regional asal pemesan
9. Subregion: subregional asal pemesan
10. Customer: nama perusahaan pemesan
11. Customer ID: id unik pemesan
12. Industry: tipe industri perusahaan pemesan
13. Segment: tipe industri perusahaan pemesan (SMB, Strategic, Enterprise, dll)
14. Product: produk yang dipesan
15. License: lisensi produk yang dipesan
16. Sales: total penjualan
17. Quantity: total transaksi
18. Discount: discount dari transaksi
19. Profit: profit dari transaksi
