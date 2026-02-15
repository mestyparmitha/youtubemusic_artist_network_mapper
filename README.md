# YouTube Music Artist Network Mapper

Project ini menggunakan Python untuk melakukan crawling artis dari YouTube Music dan memvisualisasikannya dalam bentuk jaringan (Network Graph).

## Fitur
- **Level 1 Crawling**: Mengambil artis yang mirip dengan My Chemical Romance.
- **Level 2 Expansion**: Melakukan ekspansi otomatis ke artis terkait lainnya.
- **Interactive Visualization**: Peta jaring-jaring artis yang bisa di-drag dan di-zoom.

## Tech Stack
- **Python**
- **ytmusicapi**: Untuk ekstraksi data dari YouTube Music.
- **Pandas**: Untuk pengolahan data CSV.
- **NetworkX**: Untuk analisis algoritma graf.
- **Pyvis**: Untuk visualisasi interaktif (HTML).

## 📊 Hasil
Jaringan saat ini terdiri dari **46 artis** yang saling terhubung berdasarkan kemiripan genre dan algoritma YouTube Music.
