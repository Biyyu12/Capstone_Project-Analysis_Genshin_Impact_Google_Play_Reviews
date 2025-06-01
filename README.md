# 🕹️ Genshin Impact Google Play Review Analysis
Capstone Project Hacktiv8 x IBM Granite

# 📌 Project Overview
Proyek ini bertujuan untuk menganalisis ulasan pengguna aplikasi Genshin Impact di Google Play Store guna mengevaluasi persepsi pemain terhadap berbagai aspek permainan seperti gameplay, karakter, performa teknis, dan lainnya. Dengan bantuan model AI IBM Granite, dilakukan analisis sentimen dan ekstraksi fokus area untuk memperoleh insight yang dapat digunakan oleh developer dalam meningkatkan kualitas game dan pengalaman pengguna secara keseluruhan.

Metodologi yang digunakan mencakup:
- Analisis Sentimen terhadap 50 ulasan acak menggunakan model LLM IBM Granite
- Ekstraksi Fokus Area & Kata Kunci dari tiap ulasan
- Visualisasi Data menggunakan EDA: distribusi sentimen, fokus area, top problem categories, dan wordcloud keyword

# 📂 Raw Dataset
Dataset ulasan pengguna Genshin Impact diambil dari Kaggle dan dapat diakses di tautan berikut:
🔗 [Genshin Impact Google Play Reviews] (https://www.kaggle.com/datasets/supriyoain/genshin-impact-google-play-reviews)

# 🔍 Insights & Findings
## 🎯 Sentimen
- Mayoritas ulasan pengguna bersentimen positif, yang menandakan kepuasan pemain terhadap game.
- Sentimen negatif mencerminkan kritik terhadap aspek teknis seperti storage usage, mobile compatibility, dan registration flow.

## 🔍 Fokus Area
- Topik yang paling sering dibahas mencakup gameplay, overall game, accessibility, dan mobile version.
- Elemen seperti graphics, character design, dan storyline mendominasi ulasan positif.
- Sedangkan storage, performance, dan login system sering muncul dalam konteks keluhan.

## 📈 Visualisasi Tambahan
- Wordcloud menunjukkan bahwa kata seperti “good”, “character”, dan “game” dominan dalam ulasan positif.
- Sebaliknya, kata seperti “storage”, “phone”, dan “registration” sering muncul dalam ulasan negatif.

## 🧠 Rekomendasi untuk Developer
- Optimalkan ukuran aplikasi, terutama untuk perangkat mobile.
- Sederhanakan proses registrasi dan onboarding pemain baru.
- Tingkatkan performa dan aksesibilitas di perangkat dengan spesifikasi menengah ke bawah.
- Lanjutkan inovasi pada karakter, cerita, dan grafis, karena aspek-aspek ini disukai oleh pemain.

# 🤖 AI Support: IBM Granite
Analisis ini didukung oleh model IBM Granite (granite-3.3-8b-instruct) melalui layanan Replicate API, yang digunakan untuk:
- Mendeteksi sentimen (positive, negative, neutral)
- Mengekstrak focus areas dan keywords dari review
- Mengklasifikasi kategori masalah seperti bug, gacha, performance, dan lainnya
- Menyusun ringkasan otomatis dari ulasan

---
Karena keterbatasan token, hanya 50 ulasan yang dianalisis dalam batch dengan struktur prompt terstandarisasi.
