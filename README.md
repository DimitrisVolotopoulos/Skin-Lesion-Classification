# Skin Lesion Classification Using Deep Learning and Hybrid Machine Learning

## Project Overview

This project was developed as part of my diploma thesis in Applied Mathematics and Physical Sciences at the National Technical University of Athens.

The study focuses on the classification of skin lesions using medical imaging data and compares different deep learning and machine learning approaches.

## Dataset

The experiments use the HAM10000 dataset, which contains dermoscopic images of skin lesions belonging to seven diagnostic classes:

- akiec — Actinic keratoses / intraepithelial carcinoma
- bcc — Basal cell carcinoma
- bkl — Benign keratosis-like lesions
- df — Dermatofibroma
- mel — Melanoma
- nv — Melanocytic nevi
- vasc — Vascular lesions

The dataset was divided into training, validation, and test sets using a lesion-level split to avoid having images from the same lesion appear in different subsets.

The final split contains:

| Split | Images |
|---|---:|
| Training | 8,001 |
| Validation | 1,009 |
| Test | 1,005 |

The images are stored in the `data/HAM_10000_images` directory, while the metadata are provided in `data/HAM10000_metadata.csv`.