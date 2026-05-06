# Trastuzumab Drug Repurposing

### In Silico Analysis of Resistance Mechanisms in HER2+ Breast Cancer

---

## Highlights

* Integrated **GEO gene expression datasets** with drug response data (GDSC/DepMap)
* Prioritized **ECM-related resistance biomarkers** (collagen family genes)
* Applied **supervised learning for drug sensitivity analysis (exploratory)**
* Identified **repurposable drug candidates** targeting resistance pathways
* Combined bioinformatics tools with Python-based analysis

---

## Abstract

Trastuzumab resistance remains a major challenge in HER2-positive breast cancer treatment. Understanding the molecular drivers of resistance is essential for identifying alternative therapeutic strategies.

This project presents an **in silico framework** integrating gene expression analysis, pathway enrichment, network biology, and drug sensitivity data to identify candidate therapeutic targets.

The study highlights the role of **extracellular matrix (ECM) remodeling and collagen-associated genes** in mediating resistance and proposes potential repurposable drugs targeting these pathways.

---

## Key Findings

* Identification of **ECM and collagen-related genes** associated with resistance
* Prioritization of **COL15A1 as a key hub gene**
* Enrichment of **ECM organization pathways (Reactome)**
* Discovery of potential drug candidates targeting resistance mechanisms

---

## 🎯 Objectives

* Identify biomarkers associated with trastuzumab resistance
* Perform pathway enrichment analysis (Reactome)
* Prioritize hub genes using network-based approaches
* Integrate drug response data for repurposing analysis
* Explore predictive modeling for drug sensitivity

---

## ⚙️ Methodology

### 1. Data Integration

* Gene expression datasets from GEO (e.g., GSE55005)
* Drug response data from GDSC and DepMap

---

### 2. Differential Expression Analysis

* Identification of DEGs across resistant vs sensitive models
* Overlap analysis across multiple datasets

---

### 3. Pathway Enrichment

* Reactome pathway analysis
* Identification of ECM-related biological processes

---

### 4. Network Analysis

* Protein–protein interaction networks (Cytoscape)
* Hub gene identification (CytoHubba, MCODE)

---

### 5. Drug Repurposing Analysis

* Drug–gene interaction analysis (DGIdb)
* Integration with drug sensitivity datasets

---

### 6. Machine Learning (Exploratory)

* Supervised learning approaches for predicting drug response
* Evaluation based on ECM-related gene expression

---

## 📂 Dataset & Data Availability

This project uses publicly available datasets that are **not included in this repository** due to size and access constraints.

### 🔹 Data Sources

* GEO (Gene Expression Omnibus)
* GDSC (Genomics of Drug Sensitivity in Cancer)
* DepMap (Cancer Dependency Map)

---

### ⚠️ Important Note

Users must manually download the datasets from the respective sources and place them in the `data/` directory.

---

### 📥 Suggested Workflow

1. Download datasets from:

   * GEO: https://www.ncbi.nlm.nih.gov/geo/
   * GDSC: https://www.cancerrxgene.org/
   * DepMap: https://depmap.org/

2. Place files inside:

```bash id="qf83lx"
data/
```

3. Update file paths in the notebook accordingly.

---

### Reproducibility Note

The notebook is designed to work with externally sourced data.
Ensure correct file paths and formats before execution.

---

## 📁 Project Structure

```bash id="c2y9os"
trastuzumab-drug-repurposing/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── notebooks/
│   └── Trastuzumab_DrugRepurpose.ipynb
│
├── data/
├── results/
```

---

## Reproducibility

### Installation

```bash id="j2n9lv"
git clone https://github.com/your-username/trastuzumab-drug-repurposing.git
cd trastuzumab-drug-repurposing
pip install -r requirements.txt
```

---

### Run Analysis

Open and execute:

```bash id="9lq3xt"
notebooks/Trastuzumab_DrugRepurpose.ipynb
```

---

## 📈 Results Summary

* ECM remodeling identified as a major driver of trastuzumab resistance
* Collagen-related genes play a key regulatory role
* Drug repurposing analysis suggests candidate therapeutic compounds
* Machine learning provides preliminary insights into drug sensitivity

---

## Scientific Significance

* Provides insights into **trastuzumab resistance mechanisms**
* Highlights ECM as a **therapeutic vulnerability**
* Demonstrates integration of **bioinformatics and ML approaches**
* Supports **drug repurposing in precision oncology**

---

## ⚠️ Limitations

* Analysis is primarily in silico
* Machine learning component is exploratory
* Requires experimental validation

---

## Future Work

* Expand ML models for robust drug response prediction
* Integrate multi-omics datasets
* Validate findings in independent cohorts
* Experimental validation of candidate drugs

---

## Author

**Vanathi Shanmugam**
Bioinformatics | Genomics | Machine Learning

🔗 LinkedIn: https://www.linkedin.com/in/vanathi-shanmugam-26127928a

---

## License

This project is intended for academic and research purposes.
