# End-to-End Marketing Campaign & Target Audience Analytics

[![Python](https://img.shields.io/badge/Python-38ef7d?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)](https://public.tableau.com/)

---

## 📌 Project Overview
Proyek ini mengevaluasi efisiensi dan efektivitas kampanye iklan digital (*Facebook Ads* & *Instagram Ads*) e-commerce sepanjang tahun 2025. Melalui analisis *conversion funnel*, metrik *unit economics* (CPM, CPC, CPA, ROAS), dan evaluasi kesesuaian target audiens (*demographic matching*), analisis ini mengidentifikasi pemicu utama pemborosan anggaran iklan (*ad waste*) serta merumuskan strategi alokasi anggaran berbasis data.

---

## 🔗 Live Interactive Dashboard
> 🖥️ **[Klik di Sini untuk Mengakses Interactive Tableau Dashboard](PASTE_LINK_TABLEAU_PUBLIC_ANDA_DI_SINI)**

---

## 🎯 Business Problem & Key Objectives
Tim pemasaran menemukan adanya **inkonsistensi profitabilitas antar-kampanye**, di mana beberapa kampanye memakan anggaran besar (*high budget*) namun menghasilkan *Return on Ad Spend* (ROAS) jauh di bawah target.

**Tujuan Utama Analisis:**
1. **Conversion Funnel Analysis:** Mengidentifikasi tingkat penurunan (*drop-off*) audiens dari tahap *Impression* $\rightarrow$ *Click* $\rightarrow$ *Purchase*.
2. **Cost & Revenue Optimization:** Menganalisis tingkat profitabilitas (*ROAS*) dan efisiensi biaya (*CPM, CPC, CPA*) pada level kampanye, platform, serta jenis konten (*Ad Type*).
3. **Target Audience Matching:** Mengukur tingkat pemborosan anggaran akibat ketidaksesuaian kriteria demografi target (Gender & Umur) dengan audiens aktual yang dijangkau.
4. **Actionable Recommendations:** Menyusun alokasi ulang anggaran iklan untuk meningkatkan total margin dan efisiensi konversi.

---

## 📈 Key Performance Indicators (KPIs)
* **Target ROAS:** $> 3.0\text{x}$ *(Minimum profitabilitas ideal)*
* **Target CTR (Click-Through Rate):** $> 15.0\%$
* **Target CVR (Conversion Rate):** $> 5.0\%$
* **Target Audience Match Rate:** $> 80.0\%$

---

## 🔍 Key Findings & Insights

### 1. Performa Kampanye (Top vs Underperformers)
* 🏆 **Top Performer (`Campaign_42_Summer`):**
  * **ROAS Tertinggi (12.17x):** Menghasilkan *revenue* sebesar **Rp 96,3 Juta** hanya dengan *cost* **Rp 7,9 Juta**.
  * **High Engagement:** Mencatatkan **CTR 19.49%** dan volume akuisisi tertinggi (**66 Purchases**).
* 🏆 **Best Conversion Quality (`Campaign_27_Q3`):**
  * Memiliki **Purchase Rate (1.05%)** dan **CVR (7.86%)** tertinggi meskipun jumlah *Impression* tergolong rendah (3.1K), menandakan jangkauan audiens yang sangat relevan (*high-intent*).
* ⚠️ **Underperformer Utama (`Campaign_46_Winter`):**
  * **ROAS Terendah (0.45x / Rugi):** Memakan anggaran terbesar (**~Rp 94 Juta**), tetapi hanya menghasilkan pendapatan **~Rp 42.4 Juta**.

### 2. Evaluasi Platform & Jenis Konten (Ad Type)
* 💡 **Instagram - Video (Paling Efisien):**
  * Memiliki **CPM terendah (Rp 2,235.39)** dan **CPC paling murah (Rp 19.31)**, terbukti sangat ideal untuk menjangkau audiens baru secara ekonomis.
* 💡 **Facebook - Stories (Revenue & Conversion Driver):**
  * Menyumbang **Revenue terbesar (Rp 162.7K)** dengan total **95 Purchases** dan **CTR tertinggi (22.51%)**.
* 🛑 **Instagram - Stories & Carousel (High-Cost Hazard):**
  * Menghasilkan **CPM sangat tinggi (Rp 10.1K – 11.4K)** dan **CPC mahal (Rp 52.00 – 65.54)** dengan tingkat konversi yang relatif rendah dibanding biaya yang dikeluarkan.

---

## 💡 Strategic Recommendations

1. **Re-alokasi Budget ke Formats Berkualitas:** 
   Pindahkan alokasi budget dari kampanye berkinerja buruk (`Campaign_46_Winter`) ke kampanye berefisiensi tinggi (`Campaign_42_Summer` & `Campaign_27_Q3`).
2. **Prioritaskan Video & Stories pada Facebook/Instagram:**
   Alokasikan porsi anggaran terbesar ke format **`Facebook - Stories`** untuk mendorong konversi (*revenue*) dan **`Instagram - Video`** untuk efisiensi biaya jangkauan (*cost-efficient reach*).
3. **Evaluasi/Stop Format High-Cost di Instagram:**
   Kurangi atau re-desain format *Stories* dan *Carousel* di Instagram yang memicu tingginya nilai CPM & CPC.
4. **Perbaiki Targeting Demografi:**
   Pengetatan kriteria targeting iklan untuk mengurangi penayangan iklan pada kelompok demografi yang tidak relevan guna menekan *ad waste*.

---

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Google Colab
* **Business Intelligence:** Tableau Public
