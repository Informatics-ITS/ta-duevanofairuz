# Model Pembangkit Deskripsi Gambar (BLIP-2)
- Model BLIP-2 yang telah di-finetune pada Tugas Akhir ini dapat diakses di [folder google drive ini](https://drive.google.com/drive/folders/1hn6KjJhxExdbxTnFUQI5qtEtKxSNFDxA?usp=sharing)
- Lakukan pemuatan model seperti yang ada pada section di [notebook ini](https://github.com/Informatics-ITS/ta-duevanofairuz/blob/2763737253a717a8add865c3748712f0fdf51bdf/blip2coba.ipynb), penting untuk melakukan comment pada parameter `cache_dir="./cache-blip2"` di 
```
# Load BASE model hanya sekali
base_model = Blip2ForConditionalGeneration.from_pretrained(
    "ybelkada/blip2-opt-2.7b-fp16-sharded",  # sesuaikan dengan base dari semua peft_model_id kamu
    torch_dtype=torch.float16,
    cache_dir="./cache-blip2"
).to(device)
```
ketika pertama kali memuat model di lokal
- Konfigurasi lengkap semua model yang telah dilatih dapat dilihat di [spreadsheet ini](https://docs.google.com/spreadsheets/d/18gx1c0PSBXS4OUlNdJanU4pXGlMDBLG2g5nmcrDBqss/edit?usp=sharing)
- Tahap pelatihan model ada pada section di [notebook google colab ini](https://colab.research.google.com/drive/10WGnHjLroDEvbytE5F5BzAwHIq6Y2vEt#scrollTo=mbozQy8a1cRG)