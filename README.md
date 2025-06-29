```
markdown
# 🧠 Ensemble EfficientNet for Image Classification

This project implements an ensemble of EfficientNet models (B3, B4, B5) for improved image classification performance. The ensemble combines the predictions of multiple deep learning models using confidence-based techniques to achieve better generalization and accuracy.

---

## 📌 Key Features

- ✅ Ensemble of EfficientNetB3, B4, and B5
- ✅ Confidence score-based prediction merging
- ✅ PyTorch-based modular implementation
- ✅ Easy to adapt to custom datasets
- ✅ Jupyter Notebook-based workflow for experimentation

---

## 🗂️ Project Structure

```

ensemble\_efficientnet/
├── ensemble\_efficientnet.ipynb     # Main notebook for training and ensemble
├── utils/                          # Helper functions (optional future structure)
├── models/                         # Model setup (optional future structure)
├── output/                         # Output predictions or visualizations
├── requirements.txt                # Python dependencies
└── README.md                       # Project documentation

````

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/UltraSaviour/Ensemble_efficientnet.git
cd Ensemble_efficientnet
````

### 2. Set up a virtual environment (optional but recommended)

```bash
python -m venv my_env
source my_env/bin/activate  # On Windows: my_env\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

Or install individually:

```bash
pip install torch torchvision efficientnet_pytorch matplotlib numpy scikit-learn tqdm seaborn notebook
```

### 4. Launch the notebook

```bash
jupyter notebook ensemble_efficientnet.ipynb
```

---

## 📁 Dataset Format

The project expects datasets in the following structure:

```
data/
├── train/
│   ├── class1/
│   ├── class2/
│   └── ...
└── val/
    ├── class1/
    ├── class2/
    └── ...
```

You can modify the `data_dir` in the notebook to point to your dataset.

---

## 🧠 Model Overview

This project uses:

* `EfficientNetB3`
* `EfficientNetB4`
* `EfficientNetB5`

Each model is trained (or loaded if pre-trained), and predictions are combined using a confidence-aware ensemble strategy.

---



## 🧑‍💻 Author

* **GitHub:** [UltraSaviour](https://github.com/UltraSaviour)
