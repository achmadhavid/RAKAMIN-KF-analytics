## 📊 Project: Big Data Analytics Internship – Kimia Farma Tbk (RAKAMIN)

Sebagai seorang **Big Data Analytics Intern** di **Kimia Farma**, saya berkontribusi dalam mengevaluasi performa bisnis dari tahun **2020 hingga 2023** melalui berbagai tahapan data engineering dan data analysis.

---

### 🔧 Task Overview

1. 📥 Import Dataset to BigQuery  
2. 📊 Membuat Tabel Analisa  
3. 📈 Dashboard Performance Analytics  

---

### 1️⃣ Import Dataset to BigQuery

Saya mengimpor 4 dataset utama ke dalam BigQuery dengan nama tabel tanpa ekstensi `.csv`:

- `kf_final_transaction.csv`
- `Kf_inventory.csv`
- `Kf_kantor_cabang.csv`
- `Kf_product.csv`

> ✅ Masing-masing dataset diubah menjadi tabel BigQuery dan digunakan untuk proses analisis lanjutan.

---

### 2️⃣ Tabel Analisa

Saya membangun sebuah tabel analitik hasil agregasi dari keempat tabel yang diimpor, dengan kolom-kolom berikut:

| Kolom | Deskripsi |
|-------|-----------|
| `transaction_id` | Kode transaksi |
| `date` | Tanggal transaksi |
| `branch_id` | ID cabang |
| `branch_name` | Nama cabang |
| `kota`, `provinsi` | Lokasi cabang |
| `rating_cabang` | Rating cabang |
| `customer_name` | Nama pelanggan |
| `product_id`, `product_name` | ID dan nama produk |
| `actual_price` | Harga awal produk |
| `discount_percentage` | Diskon yang diberikan |
| `persentase_gross_laba` | Persentase laba berdasarkan harga |
| `nett_sales` | Harga bersih setelah diskon |
| `nett_profit` | Keuntungan bersih |
| `rating_transaksi` | Rating dari pelanggan |

📌 **Skema Persentase Gross Laba:**

| Harga Produk | Persentase Laba |
|--------------|-----------------|
| ≤ Rp50.000 | 10% |
| Rp50.001–100.000 | 15% |
| Rp100.001–300.000 | 20% |
| Rp300.001–500.000 | 25% |
| > Rp500.000 | 30% |

---

### 3️⃣ Dashboard Performance Analytics

📊 **[Lihat Dashboard Looker Studio](https://lookerstudio.google.com/reporting/35c4be1e-d143-480e-bee0-d5ff4cb0dfd8)**

#### ✨ Highlights:

- **Total Transaksi:** 672.458  
- **Total Profit:** Rp98,5 Miliar  
- **Total Penjualan:** Rp347,0 Miliar  
- **Rating Rata-rata:** 4.0 / 5  

#### 🌍 Distribusi Cabang:

- Tersebar di seluruh Indonesia.
- Proporsi terbesar: **Apotek (32,2%)** dari semua jenis cabang.

#### 📈 Perbandingan Laba (2020–2023):

- Kenaikan tertinggi: **Tahun 2021**
- Penurunan: **Tahun 2023**

#### 🏆 Cabang dengan Kinerja Terbaik:

- **Jawa Barat:** Penjualan > Rp150 Miliar  
- **Jawa Timur:** 198.723 transaksi tertinggi  
- Rating cabang rata-rata: **3 dari 5**

---

### 🧠 Insight

Dashboard ini menyajikan **gambaran menyeluruh** tentang performa keuangan dan operasional Kimia Farma dengan fokus pada:

- Profitabilitas
- Distribusi cabang
- Kualitas layanan berdasarkan rating pelanggan

---

