# Strength Data DistilBERT Model Implementations

This repository hosts Jupyter Notebook implementations of DistilBERT models, built on a **strengthened dataset** (fill in your specific task here: e.g., text classification/regression for strength-related data) — focusing on exploring different feature fusion strategies.


## File Details
| Notebook Filename                          | Core Functionality                                                                 |
|--------------------------------------------|-------------------------------------------------------------------------------------|
| `strength_data_DistilBERT.ipynb`           | Baseline model: Initial DistilBERT implementation on the strengthened dataset (no extra feature fusion) |
| `strength_data_TF-skkf_DistilBERT_noAIM.ipynb` | Feature fusion v1: DistilBERT integrated with **global max + global mean features** |
| `strength_data_TF-skkf_DistilBERT_noTFIDF.ipynb` | Feature fusion v2: DistilBERT integrated with **TFIDF features** |
| `Strength Data TF-skkf DistilBERT.ipynb`   | Full fusion model: DistilBERT combining both global statistical features and TFIDF |


## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/LY-ILY/MDPI_DATA
