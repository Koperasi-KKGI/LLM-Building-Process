# LLM-Building-Process
## Learn to build - training - fine tuning- quantifying - AI LLM Models - Machine Learning

Membangun AI trained model dengan bahasa dan pengetahuan yang sangat spesifik dan untuk ditujukan/digunakan sebagai tools yang mempermudah para ahli di suatu bidang (__misal__ : coder spesialis yang sudah spesifik berbasis platform tertentu)

### Bagian 1: Pengantar Dunia AI dan LLM

#### 1. Selamat Datang di Era Bahasa Buatan: Memahami Large Language Model (LLM)

* Apa itu LLM dan bagaimana cara kerjanya? 
* Konsep "Text Completion" sebagai fondasi LLM. 
* Peran ChatML dalam interaksi LLM. 
* Mekanisme LLM berhenti menghasilkan output.
  
#### 2. Membongkar Otak LLM: Arsitektur Transformer dan Pelatihan Generatif

* Di balik kesederhanaan LLM: Kompleksitas arsitektur Transformer. 
* Proses pelatihan LLM: "Next Token Predictor". 
* Skala data pelatihan LLM: Triliunan token yang mengagumkan. 

### Bagian 2: Kustomisasi LLM: Fine-Tuning dan Efisiensi
#### 3.  Personalisasi LLM: Mengapa Fine-Tuning adalah Kunci

* Definisi fine-tuning dan tujuannya. 
* Studi kasus penggunaan fine-tuning: Chatbot layanan pelanggan khusus. 
* Peran fine-tuning dalam menyesuaikan pengetahuan LLM. 


#### 4. Fine-Tuning yang Efisien: Memanfaatkan Lora (Low-Rank Adaptation)

* Lora sebagai metode fine-tuning yang populer. 
* Prinsip kerja Lora: Modifikasi parsial untuk efisiensi. 
* Manfaat Lora: Mengurangi kebutuhan sumber daya komputasi. 

#### 5. Unsloth: Revolusi Fine-Tuning LLM yang Cepat dan Mudah

* Keunggulan Unsloth: Kecepatan dan efisiensi memori GPU. 
* Kemudahan penggunaan Unsloth: Template dan integrasi Hugging Face. 
* Parameter kunci dalam fine-tuning dengan Unsloth: Max Sequence Length, Model Name, dan R Value. 
* Dukungan arsitektur model di Unsloth (Mistral, Llama, Gemma, dll.). 

#### 6. Memasukkan Data ke dalam LLM: Proses Dataset Loading dan Formatting

* Pemuatan dataset dari Hugging Face. 
* Pentingnya format dataset yang sesuai (contoh: Alpaca Prompt). 
* Konsep "Epochs" dan "Steps" dalam proses fine-tuning. 
* Memahami "Overfit" dan bagaimana menghindarinya.

#### 7. Dari Fine-Tuning ke Implementasi: Menggunakan Model LLM yang Dikustomisasi

* Penyimpanan dan pengunggahan hasil fine-tuning. 
* Konsep "Quantization" dan format GGUF untuk efisiensi model. 
* Platform untuk menjalankan model GGUF (LM Studio, Ollama, Faraday, GPT for All). 
* Antarmuka pengguna untuk interaksi langsung dengan LLM. 

### Bagian 3: Membangun Mesin AI: PC Workstation untuk AI Training
#### 8. Membangun Fondasi Kekuatan Komputasi: Perakitan PC Workstation Spesialis
* Tujuan spesifik PC workstation ini: AI Training. 
* Casing InWin R400 Series 01n: Desain dan fitur untuk server/workstation. 
* Manajemen pendinginan casing: Fan depan dan belakang. 
* Dukungan penyimpanan dan GPU holder. 
* Kompatibilitas motherboard dan dukungan dual PSU. 

#### 9. Jantung Sistem: Power Supply, Storage, dan Pendinginan

* NZXT C1500: Power supply 1500W dengan sertifikasi Platinum dan 12VHPWR. 
* Pentingnya jumlah kabel PCIE Express dan EPS untuk motherboard workstation. 
* Penyimpanan super cepat: 4x 4TB T-Force Cardea GE PRO Gen 5 NVMe SSD. 
* Solusi pendinginan prosesor: Arctic Freezer 4U (air cooling vs. liquid cooling). 
* Fan exhaust tambahan untuk sirkulasi udara optimal. 

#### 10. Otak dan Jaringan Syaraf: Prosesor, Memori, dan GPU Unggulan

* AMD Ryzen Threadripper Pro 7965WX: Prosesor 24 core/48 thread untuk workstation. 
* Perbedaan dengan Threadripper biasa: Dukungan 8-channel memory. 
* ASUS Pro WS WRX90E-SAGE SE: Motherboard dengan chipset AMD WRX90, 8-channel memory, dan 7 PCIe Gen 5 slot. 
* Memori G.Skill Zeta R5 Neo DDR5 RDM 192GB. 
* GPU Ganda untuk AI Training: 2x NVIDIA RTX A6000 48GB. 

#### 11. Proses Perakitan (Hardware) dan Tantangan (Studi Kasus)

* Langkah-langkah perakitan prosesor Threadripper ke socket TR5. 
* Pemasangan pendingin prosesor Arctic Freezer 4U. 
* Running test di luar casing dan kendala pemasangan power supply (pentingnya manual). 
* Waktu booting yang lama pada sistem memori besar dan indikator LED. 
* Pengujian performa (Cinebench R23, CPU Throttling Test, CrystalDiskMark) dan suhu komponen. 
* Hasil akhir dan biaya keseluruhan: Mesin AI Training seharga 500 juta Rupiah. 


# Youtube ref
* https://www.youtube.com/watch?v=5-N2vbFgNKo __(Tutorial Mengerti Large Language Model (LLM) dari Nol: Pasti Paham!)__
* https://www.youtube.com/watch?v=_O_XYuS6f4g __(Rakit PC 450 Juta-an buat AI Training | Harga PC Setara Harga Mobil Innova | RTX 6000 ADA)__
* https://www.youtube.com/watch?v=4htQb1trFAw __(12 Juta udah Cukup Kok | NgeRakit PC buat Bikin AI Canggih !, disclaim: bukan u/ proses training)__
* https://www.youtube.com/watch?v=vRYbhohxTWo __(Bagaimana saya membuat LLM dari nol 😎)__
* https://www.youtube.com/watch?v=n9mDHL5kSlI __(Gaperlu pake punya OpenAI, LLM open-source juga bisa bahasa Indonesia loh 😎)__
* https://www.youtube.com/watch?v=AttGNMSy4dg __(Tips dan panduan menggunakan LLM dan tools AI sebagai software engineer dan coders 🧑‍💻)__
* https://www.youtube.com/watch?v=wE71qcNa2Ts __(Tutorial Finetune LLM (Large Language Model) GRATIS via Google Collab)__
* https://www.youtube.com/watch?v=8u2hucF6ZBM __(Cara Menjalankan LLM di PC Lokal Untuk Pemula ~ Pasti Bisa 👌)__
* https://www.youtube.com/watch?v=QRzS6aJWGkA __(Optimizer Lomo dan AdaLomo: Solusi Training LLM Minim GPU Memory 🤗)__
* https://www.youtube.com/watch?v=-tqSFXO6bMw __(Trend LLM 2024: Software 3.0, potensi dan realita 🤔)__
* https://www.youtube.com/watch?v=-yG3w57Dcvw __(Tiga Tools Berguna Saat Fine-Tuning LLM ~ Bisa Dapat Uang Juga 💵💵💵)__
* https://www.youtube.com/watch?v=PX9J1Cfi-LI __(Tierlist dan Panduan Memilih LLM Yang Tersedia di Publik 🤖)__
* https://www.youtube.com/watch?v=A2ssQQMUXNA __(Penjelasan ORPO (Odds Ratio Preference Optimization): Alignment LLM singkat sekali jalan 🏃‍♂️)__
* https://www.youtube.com/watch?v=r9293xJHNAI __(Cara Saya Jalanin Program (mirip) ChatGPT di Laptop Sendiri)__
* https://www.youtube.com/watch?v=fZxTHLunRQw __(ICLR: Bukti kalau LLM mampu melakukan online learning 😱)__
* https://www.youtube.com/watch?v=ZASgQFhKLdg __(Quantization dan BitNet: Large Language Model untuk semua)__
* https://www.youtube.com/watch?v=1t_j6ZBlYwo __(Kuliah Gratis Lengkap Tentang DeepSeek R1: Semuanya dibahas 🐳)__
* https://www.youtube.com/watch?v=ZZZrZnH1Exc __(Cara Upload Dataset ke HuggingFace Hub Untuk Pemula 🤗)__
* https://www.youtube.com/watch?v=Nle_987GyvE __(Tips Membaca Paper dan Riset Machine Learning Terkini 🤖)__
