# AI Audit Case Studies

**Studi Kasus Audit AI Berbasis Dataset Simulasi**

---

## 🇬🇧 English

### About

This repository contains structured AI audit case studies using simulated datasets generated with generative AI assistance.

Each case study follows a full audit report format, from dataset overview to findings, recommendations, and limitations.

> For audit analysis using real-world datasets with NIST AI RMF context, see [ai_audit_applied_analysis](https://github.com/ardisugiarto/ai_audit_applied_analysis)

### Files

| File | Description | Open in Colab |
|---|---|---|
| `Case_Study_1_ENG.ipynb` | Audit of employee transaction log dataset | [Open](https://colab.research.google.com/drive/1QwqbuKTlR3Z760UKRMqamttfKbZkr6Yj?usp=sharing) |
| `Case_Study_2_ENG.ipynb` | Audit of AI-based student scoring system | [Open](https://colab.research.google.com/drive/1hoM16c7-wh3gDM2ebbX8sCqSy5X4PynZ?usp=sharing) |

### Topics Covered

* Anomaly detection with `df.describe()`, `isnull().sum()`, and `np.unique()`
* Input validation gap identification
* Categorical label inconsistency detection
* Fairness analysis across gender groups with `groupby()`
* Structured audit reporting: findings with risk levels, recommendations with responsible stakeholders, and limitations

### Audit Report Structure

Each case study follows this structure:

1. **Overview** - dataset context, structure, and statistical summary
2. **Analysis** - audit checklist with step-by-step solutions
3. **Audit Report** - findings, recommendations, and limitations

### Notes

* Datasets are simulated for practice purposes, findings need to be verified with larger real-world data
* Code style prioritizes readability, written as if explaining to non-technical stakeholders

---

## 🇮🇩 Bahasa Indonesia

### Tentang

Repositori ini berisi studi kasus audit AI menggunakan dataset simulasi yang dibuat dengan bantuan AI generatif.

Setiap studi kasus mengikuti format laporan audit lengkap, dari overview dataset hingga temuan, rekomendasi, dan limitasi.

> Untuk analisis audit menggunakan dataset nyata dengan konteks NIST AI RMF, lihat [ai_audit_applied_analysis](https://github.com/ardisugiarto/ai_audit_applied_analysis)

### File

| File | Deskripsi | Buka di Colab |
|---|---|---|
| `Case_Study_1.ipynb` | Audit dataset log transaksi karyawan | [Buka](https://colab.research.google.com/drive/19dks1Mz5LJ4SOECmg0guiyCf4JtlgY4V?usp=sharing) |
| `Case_Study_2.ipynb` | Audit sistem penilaian siswa berbasis AI | [Buka](https://colab.research.google.com/drive/120r24wO3OlYTLDMZ-irRrm_BTlY1-g4K?usp=sharing) |

### Topik yang Dibahas

* Deteksi anomali dengan `df.describe()`, `isnull().sum()`, dan `np.unique()`
* Identifikasi celah validasi input
* Deteksi inkonsistensi label kategorikal
* Analisis fairness antar kelompok gender dengan `groupby()`
* Penulisan laporan audit terstruktur: temuan dengan tingkat risiko, rekomendasi dengan pemilik tindakan, dan limitasi

### Struktur Laporan Audit

Setiap studi kasus mengikuti struktur berikut:

1. **Overview** - konteks dataset, struktur, dan ringkasan statistik
2. **Analisis** - checklist audit dengan solusi per langkah
3. **Laporan Audit** - temuan, rekomendasi, dan limitasi

### Catatan

* Dataset merupakan simulasi untuk keperluan latihan, temuan perlu diverifikasi dengan data nyata yang lebih besar
* Gaya penulisan kode mengutamakan keterbacaan, ditulis seolah menjelaskan kepada stakeholder non-teknis