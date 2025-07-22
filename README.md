# 🏁 Tugas Akhir (TA) - Undergraduate Thesis

|     |  |
| -------- | ------- |
| **Nama Mahasiswa**  | Duevano Fairuz Pandya    |
| **NRP** | 5025211052     |
| **Judul TA**    | Pembangkitan Deskripsi Gambar _Fashion_ Berbahasa Inggris dengan Metode _Bootstrapping Language-Image Pre-training_    |
| **Dosen Pembimbing**    | Shintami Chusnul Hidayati, S.Kom., M.Sc., Ph.D.    |

---

## 📺 Demo Aplikasi  
Embed video demo di bawah ini:  

[![Demo Aplikasi](https://i.ytimg.com/vi/HQdK63d_Zwo/maxresdefault.jpg)](https://www.youtube.com/watch?v=HQdK63d_Zwo)  
*Klik gambar di atas untuk menonton demo*

---


## 🛠 Panduan Instalasi & Menjalankan Software  

### Prasyarat  
**Core dependencies**
- torch==2.6.0
- transformers==4.50.3
- accelerate>=1.52.0
- datasets>=2.14.4
- peft>=0.14.0
- evaluate>=0.4.5
- rouge_score>=0.1.2
- openai>=1.70.0
- gradio>=5.31.0

**Detectron2**
- git+https://github.com/facebookresearch/detectron2.git

**CUDA/cuDNN compatibility (informational only)**
- CUDA Version: 12.5
- cuDNN Version: 9.2.1 (header-based)

**TensorFlow (optional, if needed)**
- tensorflow==2.18.0

**Runtime environment**
- python>=3.10

### Langkah-langkah  
1. **Clone Repository**  
   ```bash
   git clone https://github.com/Informatics-ITS/TA.git
   ```
2. **Instalasi Dependensi**
   ```bash
   cd [folder-proyek]
   pip install -r requirements.txt  # Contoh untuk Python
   npm install  # Contoh untuk Node.js
   ```
3. **Konfigurasi**
- Salin/rename file .env.example menjadi .env
- Isi variabel lingkungan sesuai kebutuhan (database, API key, dll.)
4. **Jalankan Aplikasi**
   ```bash
   python main.py  # Contoh untuk Python
   npm start      # Contoh untuk Node.js
   ```
5. Buka browser dan kunjungi: `http://localhost:3000` (sesuaikan dengan port proyek Anda)

---

## 📚 Dokumentasi Tambahan

- [Detectron2](https://github.com/facebookresearch/detectron2)
- [BLIP-2](https://huggingface.co/docs/transformers/model_doc/blip-2)
- [OpenAI](https://platform.openai.com/)

---

## ✅ Validasi

Pastikan proyek memenuhi kriteria berikut sebelum submit:
- Source code dapat di-build/run tanpa error
- Video demo jelas menampilkan fitur utama
- README lengkap dan terupdate
- Tidak ada data sensitif (password, API key) yang ter-expose

---

## ⁉️ Pertanyaan?

Hubungi:
- Penulis: duevanofairuz@gmail.com
- Pembimbing Utama: shintami@its.ac.id
