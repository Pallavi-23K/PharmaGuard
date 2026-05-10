<div align="center">

# 🧬 PharmaGuard 💊

### AI-Powered Pharmacogenomic Decision Support System

<img src="https://img.shields.io/badge/AI-Random%20Forest-blue?style=for-the-badge" />
<img src="https://img.shields.io/badge/Backend-Flask-black?style=for-the-badge&logo=flask" />
<img src="https://img.shields.io/badge/Frontend-React-blue?style=for-the-badge&logo=react" />
<img src="https://img.shields.io/badge/Python-3.10-yellow?style=for-the-badge&logo=python" />
<img src="https://img.shields.io/badge/Genomics-VCF-success?style=for-the-badge" />

<br><br>

> Personalized Medicine through AI, Pharmacogenomics, and Genomic Intelligence

</div>

---

# 📌 Overview

PharmaGuard is an intelligent pharmacogenomic analysis platform designed to analyze genomic VCF (Variant Call Format) files and identify clinically significant drug-gene interactions.

The system leverages:
- 🧬 Pharmacogenomics
- 🤖 Machine Learning
- 📊 Genomic Variant Analysis
- 💊 Precision Medicine
- 🧠 AI-generated Clinical Insights

to deliver personalized medication recommendations and adverse drug reaction predictions.

---

# 🚀 Core Features

## 🧬 Genomic Analysis Engine
✔️ Upload and parse VCF genomic files  
✔️ Detect pharmacogenomic biomarkers  
✔️ Extract clinically relevant SNPs  
✔️ Variant-to-drug mapping  

---

## 💊 Precision Drug Intelligence
✔️ Personalized dosage recommendations  
✔️ Drug metabolism prediction  
✔️ Gene-drug interaction analysis  
✔️ Therapeutic risk classification  

---

## 🤖 Machine Learning Powered
✔️ Random Forest based prediction engine  
✔️ ADR risk prediction  
✔️ Confidence score generation  
✔️ Phenotype classification  
✔️ Risk categorization (Low / Moderate / High)

---

## 📊 Advanced Dashboard
✔️ Interactive analysis interface  
✔️ Real-time genomic interpretation  
✔️ Variant snapshot tables  
✔️ Clinical recommendation panels  
✔️ AI-powered summaries  

---

# 💊 Supported Pharmacogenomic Drugs

| 💊 Drug | 🧬 Gene | ⚕️ Clinical Relevance |
|------|------|------|
| CODEINE | CYP2D6 | Drug metabolism |
| WARFARIN | VKORC1 | Dosage sensitivity |
| CLOPIDOGREL | CYP2C19 | Drug activation |
| SIMVASTATIN | SLCO1B1 | Myopathy risk |
| AZATHIOPRINE | TPMT | Toxicity prediction |
| FLUOROURACIL | DPYD | Severe toxicity risk |

---

# 🧠 Machine Learning Architecture

<div align="center">

```text
VCF Upload
    ↓
Variant Parsing
    ↓
Pharmacogene Detection
    ↓
Drug-Gene Mapping
    ↓
Random Forest Prediction
    ↓
ADR Risk Classification
    ↓
Clinical Recommendation
    ↓
AI Summary Generation

---

# 🖥️ Technology Stack

## Frontend

* React.js
* JavaScript
* HTML5
* CSS3

## Backend

* Python
* Flask

## Machine Learning

* Scikit-learn
* Random Forest Classifier
* Pandas
* NumPy

## Genomic Processing

* VCF Parsing
* SNP Analysis
* Pharmacogenomic Interpretation

---

# 📂 Project Structure

```bash
PharmaGuard/
│
├── backend/
│   ├── routes/
│   ├── services/
│   ├── utils/
│   ├── tests/
│   ├── data/
│   ├── sample_data/
│   ├── app.py
│   ├── config.py
│   └── requirements.txt
│
├── frontend/
│
├── .env.example
├── .gitignore
├── README.md
└── requirements.txt
```

---

# ⚙️ Installation & Setup

## 1️⃣ Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/PharmaGuard.git
cd PharmaGuard
```

---

## 2️⃣ Create Virtual Environment

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### Linux / Mac

```bash
python3 -m venv venv
source venv/bin/activate
```

---

## 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 4️⃣ Configure Environment Variables

Create a `.env` file in the root directory.

Example:

```env
FLASK_ENV=development
FLASK_DEBUG=False
SECRET_KEY=your-secret-key

ANTHROPIC_API_KEY=your-api-key

FRONTEND_URL=http://localhost:3000
MAX_VCF_FILE_SIZE=5242880
```

---

# ▶️ Running the Application

## Start Backend Server

```bash
cd backend
python app.py
```

Backend server runs on:

```text
http://localhost:5000
```

---

## Start Frontend

```bash
cd frontend
npm install
npm start
```

Frontend runs on:

```text
http://localhost:3000
```

---

# 📄 VCF File Support

PharmaGuard accepts `.vcf` genomic files containing pharmacogenomic variants.

## Supported Variant Types

* SNPs (Single Nucleotide Polymorphisms)
* Drug metabolism variants
* Pharmacogene markers
* ADR-associated variants

---

# 📊 Analysis Output

The system generates:

* Risk Assessment
* Pharmacogenomic Profile
* ADR Prediction
* Dosage Recommendations
* Clinical Guidance
* Drug Safety Analysis
* Variant Confidence Metrics
* AI Clinical Summary

---

# 🔐 Security & Privacy

* `.env` protected using `.gitignore`
* Local genomic analysis supported
* Sensitive credentials excluded from repository
* No permanent genomic data storage

---

# 🎯 Applications

* Precision Medicine
* Personalized Therapeutics
* Clinical Pharmacogenomics
* ADR Prevention
* Genomic Healthcare Research
* AI-assisted Clinical Decision Support

---

# 🧪 Sample Workflow

1. Upload patient VCF file
2. Select medications for analysis
3. Detect pharmacogenomic variants
4. Generate ML-based risk predictions
5. View clinical recommendations
6. Review AI-generated summaries

---

# 📈 Future Enhancements

* Deep Learning integration
* Expanded drug database
* EHR interoperability
* Multi-patient analytics
* Real-time genomic pipelines

---


```
```
