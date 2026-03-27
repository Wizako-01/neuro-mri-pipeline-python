# Neuroimaging Analysis Pipeline (Python)
An end-to-end Python pipeline for processing 3D MRI data, performing structural analysis, and calculating brain biomarkers using the OASIS dataset.
##  Project Overview
This project demonstrates the application of data science and AI techniques to medical imaging. It focuses on three core stages: preprocessing raw scans, performing comparative morphometry, and validating structural symmetry.
##  Key Features
* **Automated Skull Stripping:** Created a preprocessing workflow to isolate brain tissue from non-brain elements using `Nilearn`.
* **Gray Matter Morphometry:** Developed a comparative analysis to quantify tissue volume and map the effects of aging across different cohorts.
* **Hemispheric Symmetry Checker:** Engineered a 3D-mirroring algorithm using `NumPy` and `Nibabel` to detect structural anomalies between brain hemispheres.
* **Interactive Visualization:** Multi-planar reporting (Axial, Coronal, Sagittal) and difference heatmaps for clinical interpretation.
##  Tech Stack
* **Language:** Python
* **Libraries:** Nilearn, Nibabel, NumPy, Pandas, Matplotlib
* **Environment:** Google Colab / Jupyter Notebook
* **Data Format:** NIfTI (.nii.gz)

##  How to Use
1. Open the `.ipynb` file in Google Colab.
2. Run the cells to download sample data from the OASIS dataset.
3. The script will automatically generate the skull-stripped images and volumetric comparisons.
