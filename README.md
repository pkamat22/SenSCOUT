# Single-cell morphology encodes functional subtypes of senescence in aging human dermal fibroblasts [SenScout]

---
Paper: [https://www.biorxiv.org/content/10.1101/2023.05.17.541204v1](https://www.biorxiv.org/content/10.1101/2024.05.10.593637v2)

**Use Guide**:
1. **Manuscript and Figures Folder** 
   1. Contains paper and associated figures
2. **Notebooks Folder**
   1. Contains example workflow 
   2. *Preprocessing* delineates log normalization and standard scaling of morphological data
   3. Senescence UMAP_KMEANS* describes 2D dimensionality reduction and identification of KMEANS clusters
   4. *Biomarker Imputation Platform* describes imputation platform using morphology to predict un-stained biomarker expression
   5. *Recombat* describes reComBat batch correction for biomarkers between biorepeats
   6. *Time Series KMEANS* describes time series kmeans for cell morphological trajectories
   7. *Senotherapy Response Dendrogram* describes hierachal clustering to identify the 4 response modalities for single cell responses.
   8. *Xception Data Creator* workflow to get single cell image instances for Xception senescence model
   9. *Xception Training Model and Applier* workflow to train Xception senescence model and applying to new dataset
3. **Data Availability**
   1. Please contact authors for data availability 
   
---
**Python Library Dependencies**\
tensorflow-gpu==2.5.0\
scipy==1.7.1\
sklearn==1.1.1\
pandas==1.4.3\
matplotlib==3.4.2\
seaborn==0.12.0\
plotly==5.10.0\
trackpy==0.5.0\
umap-learn==0.5.3\
numpy==1.22.4
