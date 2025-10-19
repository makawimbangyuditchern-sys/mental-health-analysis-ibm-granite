# 🧠 AI-Powered Mental Health Sentiment Analysis using IBM Granite
### 👩‍💻 Author: Yuditchern Makawimbang  

---

## 🌍 Overview
This project uses **IBM Granite AI** to perform sentiment and emotion analysis on mental health expressions such as burnout, loneliness, anxiety, and grief.  
Proyek ini menggunakan **IBM Granite AI** untuk menganalisis sentimen dan emosi dari curhatan kesehatan mental seperti burnout, kesepian, kecemasan, dan kehilangan.  

The goal is to understand emotional patterns and provide early awareness about mental well-being trends among students and workers.  
Tujuannya adalah memahami pola emosi dan memberikan kesadaran dini tentang tren kesejahteraan mental di kalangan mahasiswa dan pekerja.

---

## 📊 Dataset
📥 **[Download Dataset (mental_health_analysis_results.csv)](https://github.com/makawimbangyuditchern-sys/mental-health-analysis-ibm-granite/raw/main/mental_health_analysis_results.csv)**  

**Columns:**
- `id` — unique identifier  
- `text` — user confession / text input  
- `Sentiment` — Positive / Negative / Neutral  
- `Focus` — main topic (burnout, loneliness, grief, anxiety)  
- `Reason` — short explanation or context  
- `source` — data source (Reddit/Twitter)  
- `created_at` — data creation date  

Dataset bilingual ini berisi curhatan singkat terkait kesehatan mental mahasiswa dan pekerja, digunakan untuk menganalisis pola sentimen dan emosi menggunakan model AI IBM Granite.

---

## ⚙️ Tools & Model
- 🧩 **Model:** IBM Watsonx Granite LLM  
- 💻 **Environment:** Google Colab  
- 📚 **Libraries:** Python (Pandas, Matplotlib)  
- ☁️ **Version Control:** GitHub  

---

## 🚀 How to Run
Langkah cepat untuk menjalankan proyek ini di Google Colab:  

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/makawimbangyuditchern-sys/mental-health-analysis-ibm-granite/blob/main/mental_health_yudit.ipynb)

1. Klik tombol **“Open in Colab”** di atas ☝️  
2. Upload file dataset: `mental_health_analysis_results.csv`  
3. Jalankan semua sel untuk melakukan analisis sentimen  
4. Lihat hasil klasifikasi dan grafik visualisasi di output bawah notebook  

---

## 📈 Example Visualization
Berikut contoh hasil visualisasi dari model analisis sentimen IBM Granite:  

![Sentiment Chart Example](https://github.com/makawimbangyuditchern-sys/mental-health-analysis-ibm-granite/raw/main/sentiment_chart_example.png)  

> Grafik di atas menunjukkan distribusi sentimen:  
> 🔹 **Negative (burnout & anxiety)** → 60%  
> 🔹 **Neutral (reflective)** → 25%  
> 🔹 **Positive (motivational & supportive)** → 15%

Kamu bisa menghasilkan grafik seperti ini secara otomatis setelah menjalankan notebook di Colab.

---

## 💬 Insights
Early sentiment detection can help universities, workplaces, and communities build stronger mental health awareness and empathy.  

Deteksi sentimen sejak dini membantu kampus dan tempat kerja menciptakan lingkungan yang lebih suportif terhadap kesehatan mental.

---

## 🏁 Conclusion
AI-powered sentiment analysis enables large-scale understanding of emotional data and supports data-driven empathy.  
Analisis sentimen berbasis AI membantu memahami kondisi emosional masyarakat dan mendukung empati berbasis data.  

---

## 🎞️ Presentation Slides
📎 **[Download Presentation_Slides_Yuditchern_Makawimbang.pptx](https://github.com/makawimbangyuditchern-sys/mental-health-analysis-ibm-granite/raw/main/Presentation_Slides_Yuditchern_Makawimbang.pptx)**  

*(Pastikan file PPTX dengan nama yang sama sudah diupload ke repo — link ini akan aktif otomatis setelah upload.)*  

---

### 💙 Acknowledgment
Thanks to **IBM SkillsBuild x Hacktiv8** for providing AI tools, mentorship, and the opportunity to explore real-world data projects.  
Terima kasih kepada **IBM SkillsBuild x Hacktiv8** atas dukungan, bimbingan, dan kesempatan untuk mengembangkan proyek AI berbasis data nyata.
