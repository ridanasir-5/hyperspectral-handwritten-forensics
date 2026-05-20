# hyperspectral-handwritten-forensics
Hybrid CNN-LSTM framework for hyperspectral handwriting analysis, writer verification, and ink mismatch detection.

# Hyperspectral Handwriting Analysis for Writer Verification and Ink Mismatch Detection Using a Hybrid CNN-LSTM Model

This repository contains the implementation, preprocessing pipeline, evaluation framework, representative metadata, and experimental materials associated with the research study:

## “Hyperspectral Handwriting Analysis for Writer Verification and Ink Mismatch Detection Using a Hybrid CNN-LSTM Model”

The proposed framework integrates hyperspectral imaging with a hybrid CNN-LSTM architecture for forensic handwriting analysis, writer verification, and ink mismatch detection.

---

# Repository Overview

This repository provides:

- Hyperspectral tensor generation workflow
- Writer-pair generation methodology
- Hybrid CNN-LSTM training notebooks
- Evaluation and statistical analysis scripts
- ROC curves and confusion matrix visualizations
- Representative metadata samples
- Experimental outputs and performance analysis

---

# Repository Structure

```text
hyperspectral-handwritten-forensics/
│
├── code/
│   │
│   ├── figures/
│   │   ├── confusionmatrix.png
│   │   ├── accuracyfold.png
│   │   ├── distance-distribution.png
│   │   ├── performancetradeoff.png
│   │   ├── precisionrecallfold.png
│   │   └── roc.png
│   │
│   ├── metadata/
│   │
│   ├── results/
│   │
│   ├── 1_dataset_index.ipynb
│   ├── 2_Sentence_Tensor_Generation.ipynb
│   ├── 3_Pair_Generation.ipynb
│   ├── 4_Model_Training.ipynb
│   └── 5_evaluation_day3_step4.ipynb
│
├── LICENSE
├── README.md
└── .gitignore
