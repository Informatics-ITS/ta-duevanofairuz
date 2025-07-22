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


## 🛠 Panduan Penggunaan

### Prasyarat  
**Core dependencies**
- torch>=2.6.0
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

**CUDA/cuDNN compatibility (Google Colab)**
- CUDA Version: 12.5
- cuDNN Version: 9.2.1

**TensorFlow (optional, if needed)**
- tensorflow==2.18.0

**Runtime environment**
- python>=3.10


---
### Cara Menjalankan
**Seluruh resources Tugas Akhir ini dapat diakses pada [Google Drive ini](https://drive.google.com/drive/folders/1wS4IOzDqAYXSNO2VHnoOLL41g2vcAJvB?usp=sharing)**

**Untuk menjalankan inference model di lokal**, buat sebuah environment python baru (bisa menggunakan python venv atau conda) dengan `CUDA>=11.8` dan `CUDNN>=9.1` **jika menggunakan GPU**,  lalu instal seluruh dependensi di `requirements.txt`, kemudian jalankan notebook berikut ini sesuai dengan kebutuhan: 
- [blip2coba.ipynb](https://youtube.com) merupakan notebook lokal yang digunakan untuk menjalankan inference model pembangkit deskripsi gambar (BLIP-2) saja
- [detectron2coba.ipynb](https://youtube.com) merupakan notebook lokal yang digunakan untuk menjalankan inference model segmentasi (Mask R-CNN) 
- [integrating.ipynb](https://youtube.com) merupakan notebook lokal yang digunakan untuk menjalankan inference model gabungan (segmentasi-captioning-LLM) dan deploy gradio di lokal
- [integrating-per-image.ipynb](https://youtube.com) merupakan notebook lokal yang digunakan untuk menjalankan inference model gabungan (segmentasi-captioning-LLM) untuk memantau kinerja waktu yang dibutuhkan 

Sangat disarankan untuk menjalankan projek ini di Google Colab, berikut ini adalah beberapa Notebook Google Colab yang dapat digunakan secara langsung:<br>
|  📙Notebook   | 🧾Deskripsi  |
| -------- | ------- |
| [Detectron2_maskrcnn_coba.ipynb](https://colab.research.google.com/drive/1GQoPYtM-0r0Y6gBKzBUOruxaz9OOzqIQ?usp=sharing)  | Notebook yang digunakan untuk melatih, inference, dan mengevaluasi model segmentasi objek individu (Mask R-CNN Detectron2)    |
| [Copy of 4_blip2_visual_to_text_USER.ipynb](https://colab.research.google.com/drive/10WGnHjLroDEvbytE5F5BzAwHIq6Y2vEt?usp=sharing)  | Notebook yang digunakan untuk melatih, inference, dan mengevaluasi model pembangkit deskripsi gambar (BLIP-2)    |
| [Demo_BLIP-2_KP Fashion Caption.ipynb](https://colab.research.google.com/drive/1nLuoGidAaTCMDysGaevncZTULXRLFrhS?usp=sharing)  | Notebook yang digunakan untuk inference gambar unggahan ke model pembangkit deskripsi gambar (BLIP-2)    |
| [Detectron2-BLIP2-integrating.ipynb](https://colab.research.google.com/drive/18GINIcIU7IrKrBBspA3nr-oM5CktYphh?usp=sharing)  | Notebook yang digunakan untuk inference & evaluasi Model Akhir (Model Gabungan segmentasi-captioning)    |
| [integrating-cobagradio.ipynb](https://colab.research.google.com/drive/18Qz_n2C-ncds7Q2mDa2nr1FLazkrYXP6?usp=sharing)  | Notebook yang digunakan untuk deploy (di runtime) Model Akhir ke gradio    |

Untuk notebook lain yang ada pada Google Drive di atas merupakan notebook utilitas yang digunakan untuk eksplorasi, pembersihan data, dan uji coba lainnya


---

## 📚 Dokumentasi Tambahan

- [Detectron2](https://github.com/facebookresearch/detectron2)
- [BLIP-2](https://huggingface.co/docs/transformers/model_doc/blip-2)
- [OpenAI](https://platform.openai.com/)

---

## ⁉️ Pertanyaan?

Hubungi:
- Penulis: duevanofairuz@gmail.com
- Pembimbing Utama: shintami@its.ac.id
