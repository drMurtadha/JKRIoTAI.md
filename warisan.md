# 📡 Penyelidikan IoT untuk Pemeliharaan Warisan

**Disampaikan oleh:** Prof. Madya Dr. Mohd Murtadha Mohamad  
**Tarikh:** 1 Oktober 2025  
**Slot 1 | Masa:** 8:30 – 10:30 malam
[📂 Slaid](https://github.com/drMurtadha/JKRIoTAI.md/blob/main/IoT_Pemeliharaan_Warisan.pdf)
---

## 🧩 Kandungan Slot

1. Pengenalan IoT & Warisan  
2. Latar Projek Penyelidikan  
3. Komponen Teknologi  
4. Integrasi AI & Analitik  
5. Cabaran Tempatan  
6. Demo & Kajian Kes  
7. Penutup & Sesi Interaktif

---

## 1️⃣ Pengenalan IoT & Warisan

### ✅ Apa itu IoT?
- IoT = Rangkaian peranti pintar hantar data automatik tanpa manusia
- Digunakan untuk pemantauan digital warisan secara efisien dan responsif

### ⚠️ Isu Warisan Terkini:
- **Pemanasan global:** Ancaman kepada struktur
- **Kelembapan tinggi:** Merosakkan bahan tradisional
- **Kurang pemantauan:** Kekangan tenaga manusia
- **Tiada digitalisasi:** Risiko kehilangan data penting

### 💡 Kenapa Digitalkan Warisan?
- **Keputusan pantas:** Berdasarkan data masa nyata
- **Kos efektif:** Analitik ramalan untuk cegah kerosakan
- **Dasar konservasi:** Lebih mudah dibentuk dan disokong

---

## 2️⃣ Latar Projek Penyelidikan

### 📍 Projek IoT Terdahulu
- Pemantauan kelembapan batu
- Pengimbasan 3D dan sensor getaran
- Pengurusan bangunan bersejarah secara pintar

### 🤝 Kerjasama Strategik
- **Yayasan Warisan Johor:** Tapak & data arkib
- **Komuniti setempat:** Kelulusan dan penyertaan

### 🧠 Permulaan Penyelidikan: Guna SciTe.ai
Untuk memulakan penyelidikan berkaitan IoT dan pemeliharaan warisan, penggunaan **[SciTe.ai](https://scite.ai)** sangat membantu kerana:

- ✅ **Kenal pasti literatur utama** melalui “Smart Citations”
- 🔍 **Jejak logik penyelidikan** (menyokong, mengkritik, atau menggunakan artikel)
- 🧠 **Cadangan automatik** berdasarkan kata kunci carian
- 📥 **Integrasi dengan Zotero & Mendeley** untuk susun rujukan sejak awal

📌 *Contoh carian berkesan di SciTe.ai:*  
```bash
“microclimate monitoring heritage buildings” AND “IoT sensors”
```
Dengan penggunaan awal SciTe.ai, proses **membina kertas cadangan**, mengenal pasti **trend semasa**, dan **mengelak redudansi** dapat dipercepatkan.

---

## 3️⃣ Komponen Teknologi

### 🔧 Sensor Mikroklimat
- Data setiap 5 minit (tidak invasif)
- Sensor: Suhu, kelembapan, CO₂, cahaya, tekanan, kejutan (accelerometer)

### 🔌 Platform IoT
- **NodeMCU & ESP32** – cip Wi-Fi dan Bluetooth yang mesra Arduino IDE
- **MQTT Protocol** – protokol ringan untuk penghantaran data ke cloud

### 🌐 Jaringan LoRaWAN
- Julat sehingga 15 km
- Guna kuasa rendah dan sesuai untuk lokasi terpencil seperti Kampung Naga

### 📊 Dashboard Pemantauan
- Paparan data masa nyata
- Fungsi: carta garis, amaran warna, log peristiwa, muat turun CSV

---

### 🧠 🔍 Cadangan Carian di SciTe.ai (untuk peserta JKR)

📌 *Gunakan kata kunci berikut di [SciTe.ai](https://scite.ai) untuk mendapatkan artikel yang berkaitan dengan teknologi yang digunakan dalam projek IoT warisan:*

```bash
"ESP32 low-power IoT for heritage monitoring"
```
```bash
"LoRaWAN deployment rural environmental monitoring"
```
```bash
"MQTT protocol energy-efficient IoT transmission"
```
```bash
"microclimate sensor node MCU architecture"
```
```bash
"IoT dashboard real-time sensor visualization heritage"
```
---

## 4️⃣ Integrasi AI & Analitik

### 📈 Analisis Data Mikroklimat
- Corak suhu/kelembapan harian
- Zon lembap kritikal (kulat)
- Kesan hujan terhadap kayu

### 🧠 Model Ramalan
- Algoritma: **XGBoost**, **Random Forest**
- Ramalan risiko 7 hari
- Contoh kebarangkalian:
  - Kondensasi: 75%
  - Kayu reput: 40%
  - Simen retak: 20%

### 🔔 Visualisasi & Amaran
- Heatmap zon risiko
- SMS/email amaran automatik
- Kurangkan masa respons sehingga 70%

- ## 🔍 Pembantu AI untuk Analitik & Penyelidikan

Untuk menyokong pembangunan model ramalan dan analisis data, peserta digalakkan menggunakan platform **Perplexity AI** sebagai pembantu pintar.

- **Contoh kegunaan:**
  - Bertanya soalan seperti  
    *“What environmental factors cause wood decay in tropical heritage buildings?”*
  - Menyemak sumber sahih berkaitan kelembapan dan kulat.
  - Menjana idea awal untuk pemboleh ubah ramalan cuaca mikro.
  
- **Kelebihan:**
  - Jawapan ringkas & padat dengan sumber rujukan terus.
  - Sesuai untuk bukan data scientist, mudah difahami.
  
📎 [Pergi ke Perplexity.ai](https://www.perplexity.ai)

---

## 5️⃣ Cabaran Tempatan

### 🚫 Lokasi Tiada Internet
- Contoh: Kampung Naga
- Guna LoRa, solar, data logger lawatan harian

### 💸 Kos & Tenaga Kerja
- RM650/seunit termasuk penyelenggaraan
- Latih sukarelawan komuniti

### 🏛️ Sokongan Agensi
- Kejayaan perlukan:
  - JKR (penyelarasan teknikal)
  - PERZIM, Jabatan Warisan (dasar)

---

## 6️⃣ Demo & Kajian Kes

### 💻 Demo Dashboard
1. Pilih tapak: "Stesen Johor"
2. Klik sensor: DHT22
3. Uji sistem: Aktifkan amaran

### 📱 Peranti & Aplikasi
- ESP32 kalis air + antenna LoRa
- Aplikasi Android: bacaan, notifikasi push, muat turun data

### 🧪 Kajian Kes

#### ✅ Kes Berjaya – Rumah Limas
- Kelembapan 80% dikesan awal → pasang pengalih udara
- Jimat RM12,000

#### ❌ Kes Gagal – Stesen Keretapi
- Amaran diabaikan 3 minggu → kulat merebak
- Kos pembersihan naik 3x

---

## 📑 Impak & Polisi

- **JKR 2024:** 59 projek pemuliharaan siap
- **Dasar Baharu:**
  - Pemantauan IoT wajib untuk Warisan A
  - Daftar Warisan Digital
  - Insentif cukai untuk pemilik bangunan warisan

---

## 7️⃣ Penutup & Interaktif

### ❓ FAQ
- **Penyelenggaraan sensor:** Setiap 6 bulan
- **Hayat bateri:** ≥14 hari (bateri 18650)
- **Ketepatan data:** ±2%

### 💬 Cadangan JKR
- Sensor getaran untuk jambatan besi
- Kamera berkala untuk dokumentasi visual
- Modul latihan IoT untuk kakitangan

---

## 🙏 Terima Kasih

📅 Disampaikan pada: 1 Oktober 2025  
📍 Lokasi: Avillion Port Dickson  
🎓 Oleh: Prof. Madya Dr. Mohd Murtadha Mohamad  
🧠 Disediakan oleh: Kimi AI (2025/08/01)
