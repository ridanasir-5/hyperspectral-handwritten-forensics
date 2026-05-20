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


```

---

# Included Materials

The repository currently includes:

- Dataset indexing notebooks
- Hyperspectral tensor generation pipeline
- Writer-pair generation framework
- CNN-LSTM training implementation
- Evaluation and testing notebooks
- ROC curve generation
- Confusion matrix visualization
- Precision-recall analysis
- Statistical embedding-distance analysis
- Representative metadata examples
- Experimental outputs and performance summaries

---

# Methodology Summary

The proposed framework combines hyperspectral handwriting imaging with deep learning-based sequential feature modeling.

The workflow includes:

1. Hyperspectral handwriting acquisition
2. Tensor generation and preprocessing
3. Pair generation for writer verification
4. Hybrid CNN-LSTM training
5. Evaluation using ROC, precision-recall, confusion matrix, and embedding-distance analysis

The framework is designed for:
- Writer verification
- Ink mismatch detection
- Forensic handwriting analysis

---

# Dataset Availability

The complete hyperspectral handwriting dataset generated during this study consists of approximately 52.2 GB of data, including nearly 51.4 GB of processed tensor representations used during model training and evaluation.

Due to the substantial storage requirements associated with the full dataset, representative subsets, metadata samples, preprocessing examples, and generated outputs are publicly provided within this repository.

The complete dataset and additional research materials are available from the corresponding author upon reasonable academic request.

---

# Reproducibility

All experiments were conducted using consistent preprocessing configurations, fixed training procedures, and controlled evaluation settings to support reproducibility.

Representative notebooks and evaluation scripts are included to facilitate verification of the reported methodology and results.

---

# Code Availability

The repository provides access to:

- Preprocessing pipeline
- Tensor generation framework
- Writer-pair generation methodology
- CNN-LSTM implementation
- Training procedures
- Evaluation scripts
- Statistical analysis notebooks
- Performance visualization scripts

---

# Installation

Recommended environment:

- Python 3.10+
- Jupyter Notebook
- CUDA-enabled GPU (recommended for training)

Install required libraries using:

```bash
pip install numpy pandas matplotlib scikit-learn torch torchvision jupyter opencv-python scipy seaborn tqdm
```

---

# Usage

Typical workflow:

1. Run dataset indexing notebook
2. Generate hyperspectral tensors
3. Create writer pairs
4. Train CNN-LSTM model
5. Perform evaluation and visualization

Suggested execution order:

```text
1_dataset_index.ipynb
↓
2_Sentence_Tensor_Generation.ipynb
↓
3_Pair_Generation.ipynb
↓
4_Model_Training.ipynb
↓
5_evaluation_day3_step4.ipynb
```

---

# Experimental Outputs

The repository includes representative:

- ROC curves
- Precision-recall curves
- Confusion matrices
- Distance distribution analysis
- Performance trade-off visualizations

These outputs support the findings reported in the associated manuscript.

---

# Citation

If you use this repository or associated materials in your research, please cite the corresponding manuscript.

```text
R. Nasir et al.,
"Hyperspectral Handwriting Analysis for Writer Verification and Ink Mismatch Detection Using a Hybrid CNN-LSTM Model,"
Scientific Reports, under review.
```

---

# License

This project is distributed under the MIT License.

---

# Contact

For questions regarding the dataset, experimental materials, or reproducibility resources, please contact the corresponding author.
