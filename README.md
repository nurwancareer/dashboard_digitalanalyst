# Duo Bahlul Content Performance Dashboard

Studi kasus **Digital Analyst** untuk Mahaka Radio Integra — analisis performa konten YouTube channel *Duo Bahlul* (51 video, Jun 2025–Jul 2026), mencakup tren pencarian, korelasi search interest terhadap views, performa per kategori topik, dan comment/sentiment analysis.

🔗 **Live Dashboard:**  https://nurwancareer.github.io/dashboard_digitalanalyst/
📄 **Case Study Deck:** [`docs/Duo Bahlul Analysis.pdf`]

## Struktur Proyek

```
├── index.html                          # Dashboard interaktif (HTML + Chart.js)
├── docs/
│   └── Duo_Bahlul_Content_Analysis.pdf # Deck studi kasus (landscape, sentiment, key findings, rekomendasi)
└── data/
    └── processed/
        ├── duo_bahlul_videos.csv       # Data 51 video: views, likes, comments, durasi, kategori topik
        └── duo_bahlul_categories.csv   # Ringkasan performa per kategori topik
```

## Ringkasan Studi Kasus

1. **Duo Bahlul Landscape** — breakout pencarian >5.000% sepanjang 2026, didorong amplifikasi personal host dan ekosistem media sosial (TikTok, Instagram Reels).
2. **Content Context** — pemetaan kalender konten terhadap musim pencarian (mis. klaster Ramadan).
3. **Comment & Sentiment Analysis** — analisis sentimen komentar penonton.
4. **Key Findings (Data POV)** — insight berbasis data dari korelasi search interest vs performa video.
5. **Actionable Recommendations** — rekomendasi strategi konten.

Detail lengkap ada di deck PDF pada folder `docs/`.

## Tools

- **Analisis & pengolahan data:** Python / Excel
- **Dashboard:** HTML, CSS, Chart.js
- **Presentasi:** disusun sebagai slide deck, diekspor ke PDF untuk portofolio

## Catatan

Dataset merupakan hasil analisis pribadi atas data publik YouTube channel Duo Bahlul, disusun sebagai bagian dari proses rekrutmen Digital Analyst di Mahaka Radio Integra.
