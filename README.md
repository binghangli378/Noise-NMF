# Noise-NMF

## Overview
This project implements different variants of Non-negative Matrix Factorization (NMF) to perform face image reconstruction and clustering on ORL and Extended YaleB datasets. Two NMF methods are provided, namely L1-Norm NMF and L2,1-Norm NMF. The performance of these methods is evaluated using metrics such as Relative Reconstruction Error (RRE), Clustering Accuracy (ACC), and Normalized Mutual Information (NMI) under various noise conditions (block noise and salt-and-pepper noise).
## Dataset
The dataset is not included in this repository. You can download the dataset from [this Google Drive link](https://drive.google.com/drive/folders/1r_Y5UFf30gFQBGjf6ftEAHiH1vSAbm6g?usp=sharing).
## How to run the code
1. Download the dataset
2. Open the codes.ipynb notebook file in Google Colab.
3. Upload the dataset files including ORL and YaleB datasets to the /content/ directory in
Colab. If you are using a different directory, adjust the file paths in the code accordingly.
4. Ensure all files are fully uploaded before running the code.
5. Ensure that all necessary libraries are installed in the Colab environment, such as NumPy,
Pandas, Matplotlib, and Scikit-learn.
6. Execute all cells in the notebook by pressing Ctrl+F9 or selecting Runtime -> Run
all from the Colab menu.
