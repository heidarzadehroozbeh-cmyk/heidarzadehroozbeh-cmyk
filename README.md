
<div align="center">

# Roozbeh Heidarzadeh  
### Computational Cancer Genomics • Machine Learning • Transcriptomics  

</div>

---

<div align="center">

![R](https://img.shields.io/badge/R-4.3+-blue?style=for-the-badge&logo=r)
![Python](https://img.shields.io/badge/Python-3.10+-yellow?style=for-the-badge&logo=python)
![Bioconductor](https://img.shields.io/badge/Bioconductor-Transcriptomics-green?style=for-the-badge)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-darkgreen?style=for-the-badge)
![Reproducible](https://img.shields.io/badge/Pipelines-Reproducible-black?style=for-the-badge)

</div>

---

## Research Vision

I develop reproducible computational frameworks to decode cancer transcriptomes using machine learning, systems biology, and network‑based approaches.  
My work focuses on robust biomarker discovery, tumor microenvironment characterization, and cross‑cohort integration of high‑dimensional omics data.

---

# Featured Research Projects

---

## 1. Serous Ovarian Cancer — Cross‑Cohort ML Biomarker Discovery

<p align="center">
<img src="images/ovarian_ml.png" width="800">
</p>

Brief Abstract (Serous ovarian cancer (SOC) remains one of the most lethal gynecological malignancies, with limited robust prognostic biomarkers available for clinical use. In this project, we developed a fully reproducible machine learning framework for cross‑cohort transcriptomic analysis of SOC): A cross‑cohort ML framework integrating harmonized GEO datasets for prognostic biomarker discovery in serous ovarian cancer, with robust feature selection and survival modeling.

**Repository:**  
https://github.com/heidarzadehroozbeh-cmyk/ML-Prognostic_Biomarkers-for-Serous-OvarianCancer  

<details>
<summary><strong>Full Abstract</strong></summary>

Serous ovarian cancer (SOC) remains one of the most lethal gynecological malignancies, with limited robust prognostic biomarkers available for clinical use. In this project, we developed a fully reproducible machine learning framework for cross‑cohort transcriptomic analysis of SOC. Publicly available GEO datasets were curated, pre‑processed, and harmonized using standardized normalization and batch correction procedures. Feature selection pipelines combining univariate filtering, penalized regression, and stability selection were applied to identify robust prognostic gene signatures. Multiple machine learning models, including elastic net, random forest, and gradient boosting, were trained and evaluated under rigorous cross‑validation and cross‑cohort validation schemes. Survival modeling and risk stratification were performed to assess the prognostic value of the derived signatures, while pathway‑level analyses and immune deconvolution were used to contextualize the biological relevance of candidate biomarkers. The framework emphasizes methodological transparency, reproducibility, and multi‑cohort robustness, providing a template for biomarker discovery in other cancers. Manuscript submission is in progress; code and workflows will be fully synchronized with the final published version.

</details>

---

## 2. CRPC — Metastasis‑Associated Co‑expression Modules

<p align="center">
<img src="images/crpc_wgcna.png" width="800">
</p>

Brief Abstract (1–2 lines):  
A WGCNA‑based network analysis identifying metastasis‑linked co‑expression modules and hub genes driving aggressive CRPC progression.

**Repository:**  
https://github.com/heidarzadehroozbeh-cmyk/CRPC-WGCNA-Metastasis  

<details>
<summary><strong>Full Abstract</strong></summary>

Castration‑resistant prostate cancer (CRPC) is characterized by aggressive behavior and a high propensity for metastasis, yet the transcriptional programs that drive metastatic progression remain incompletely understood. In this project, we implemented a weighted gene co‑expression network analysis (WGCNA) workflow to identify metastasis‑associated gene modules in CRPC transcriptomic datasets. After rigorous pre‑processing and normalization, co‑expression networks were constructed and modules were correlated with clinical traits, including metastatic status and disease progression. Hub genes within clinically relevant modules were identified based on intramodular connectivity and eigengene‑based metrics. Functional enrichment analyses linked modules to key biological processes and signaling pathways such as androgen receptor signaling, EMT, and inflammatory pathways. The pipeline is fully scripted in R with an emphasis on reproducibility and interpretability, offering a modular framework extendable to additional cohorts and multi‑omics layers.

</details>

---

## 3. PCOS — Systems‑Level Transcriptomic Networks

<p align="center">
<img src="images/pcos_wgcna.png" width="800">
</p>

Brief Abstract (1–2 lines):  
Systems‑level co‑expression networks identifying endocrine and metabolic modules in PCOS, highlighting inflammatory and ECM‑related regulatory pathways.

**Repository:**  
https://github.com/heidarzadehroozbeh-cmyk/PCOS-WGCNA  

<details>
<summary><strong>Full Abstract</strong></summary>

Polycystic ovary syndrome (PCOS) is a complex endocrine and metabolic disorder with heterogeneous clinical manifestations and poorly defined molecular underpinnings. This project applies a systems biology‑driven co‑expression network approach to transcriptomic datasets derived from PCOS patients and controls. Using WGCNA, we constructed gene co‑expression networks and identified modules associated with key clinical and metabolic traits. Hub genes and driver modules were characterized using network topology metrics and module–trait correlations. Functional enrichment and pathway analyses revealed modules enriched for inflammatory signaling, insulin resistance, steroidogenesis, and extracellular matrix remodeling. This analysis highlights regulatory networks that may contribute to PCOS pathophysiology and provides a reproducible computational pipeline aligned with the Biomedicines 2023 publication.

</details>

---

## 4. EOC — EMT, WNT & TGF‑β Signaling Landscape

<p align="center">
<img src="images/eoc_wnt.png" width="800">
</p>

Brief Abstract (1–2 lines):  
Transcriptomic dissection of EMT programs and WNT/TGF‑β signaling in EOC, integrated with tumor microenvironment–related signatures.

**Repository:**  
https://github.com/heidarzadehroozbeh-cmyk/EOC_WNT_TGFb_EMT_Transcriptomics  

<details>
<summary><strong>Full Abstract</strong></summary>

Epithelial ovarian cancer (EOC) progression and chemoresistance are tightly linked to epithelial‑to‑mesenchymal transition (EMT) programs and dysregulated signaling in pathways such as WNT and TGF‑β. This project systematically characterizes EMT‑related transcriptional signatures and their association with WNT/TGF‑β signaling axes in EOC transcriptomic datasets. Curated datasets were processed using standardized normalization pipelines, followed by differential expression and signature scoring approaches to quantify EMT states. Gene set enrichment, pathway analysis, and module‑level characterization delineated signaling networks associated with mesenchymal‑like phenotypes. Tumor microenvironment–related signals and immune components were incorporated where available to contextualize EMT states within the broader TME. The resulting framework provides a structured, reproducible approach to interrogating EMT, WNT, and TGF‑β signaling in EOC.

</details>

---

## Technical Expertise

| Domain | Tools / Methods |
|--------|-----------------|
| Differential expression | DESeq2, limma, edgeR |
| Network biology | WGCNA, module detection, hub analysis |
| Machine learning | Elastic Net, Random Forest, XGBoost |
| Survival & risk modeling | Cox models, risk scores, cross‑validation |
| Immune & TME profiling | CIBERSORT, ssGSEA, signature scoring |
| Reproducibility | renv, scripted workflows, version‑controlled pipelines |
| Visualization | ggplot2, ComplexHeatmap, publication‑ready figures |

---

## Research Principles

- Cross‑cohort and cross‑platform robustness  
- Fully scripted, reproducible pipelines  
- Transparent reporting of methods and assumptions  
- Emphasis on biological interpretability  
- Alignment with journal‑grade standards  

---

## GitHub Analytics

<div align="center">

![GitHub stats](https://github-readme-stats.vercel.app/api?username=heidarzadehroozbeh-cmyk&show_icons=true&theme=default&hide_border=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=heidarzadehroozbeh-cmyk&layout=compact&hide_border=true)

</div>

---

## Current Focus

Developing integrative ML pipelines for multi‑cohort cancer transcriptomics, survival modeling, and tumor microenvironment characterization.

---

<div align="center">

Computational Oncology • Systems Biology • Translational Bioinformatics  

</div>
