# Machine-Learning
---

## 🩸 BloodConnect – Machine Learning Team
---
BloodConnect adalah platform digital yang menghubungkan para pendonor darah dengan mereka yang membutuhkan secara cepat dan efisien. Tim Machine Learning berperan dalam mengembangkan fitur cerdas seperti chatbot FAQ, sistem rekomendasi donor, untuk meningkatkan pengalaman pengguna dan efisiensi sistem.


## 🚀 Tujuan Proyek
---
Mengintegrasikan Machine Learning ke dalam platform BloodConnect melalui:

- Chatbot FAQ berbasis LLM untuk menjawab pertanyaan pengguna secara otomatis.
- Model klasifikasi untuk mendukung fitur tambahan seperti prediksi kebutuhan darah atau rekomendasi pendonor.
- Clustering dengan Unsupervised Learning (Dataset Historis). Hasil clustering ini memungkinkan pemberian segmentasi yang jelas, di mana tiap cluster dapat diberikan strategi komunikasi yang berbeda seperti pengiriman email atau pesan yang disesuaikan dengan pola donor.
- Sistem menampilkan lokasi-lokasi Fasilitas Donor Darah (Dataset Lokasi Fasilitas Donor Darah)
- Prediksi Pendonor Potensial dengan Supervised Classification (Dataset Time Series)
  

## 🧠 Komponen Machine Learning
---
1. Chatbot FAQ
Deskripsi: Chatbot berbasis model LLM yang mampu menjawab pertanyaan-pertanyaan umum pengguna.

Data: Dataset terdiri dari pasangan question-answer yang dikumpulkan dan dibersihkan secara manual.

Model: Dibuat 3 pendekatan:
- TF-IDF + cosine similarity
- Model TinyLlama + RAG
- Model EleutherAi + RAG
  
Tools: Python, scikit-learn, sentence-transformers, HuggingFace, Streamlit.

Deploy to HuggingFace & Streamlit
Model Deployment: Model disimpan dan di-serve melalui HuggingFace.
[Archieve Hugging Face](https://huggingface.co/geraldalivia)


## 📦 Deployment
---
Proyek ini telah berhasil dideploy melalui:
[BloodConnect](bloodconnect.samcode.my.id)

👨‍💻 Tim Pengembang
---
Tim Machine Learning – BloodConnect:

Nama 1 – Geralda Livia - Chatbot

Nama 2 – Mudita Indah

Nama 3 – Valentio Stanley


## 📝 Lisensi
---
Proyek ini berada di bawah lisensi Tim Capstone CC25-CF296.
