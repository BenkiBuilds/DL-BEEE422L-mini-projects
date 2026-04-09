# 🧠 Deep Learning (BEEE422L) Mini Projects

> A collection of mini-projects developed as part of the **Deep Learning (BEEE422L)** course at VIT. Each project explores a fundamental machine learning or deep learning task, implemented using PyTorch and scikit-learn.

---

## 📁 Repository Structure

```
DL-BEEE422L-mini-projects/
├── Numeral_Recognition_MNIST/
│   ├── numeral_recognition.ipynb
│   └── images/
├── Iris_Classification/
│   ├── iris_classification.ipynb
│   ├── dataset/
│   └── images/
├── Housing_Price_Prediction/
│   ├── house_price_predicition.ipynb
│   ├── dataset/
│   └── images/
└── README.md
```

---

## 📌 Projects Overview

### 1. 🔢 MNIST Digit Classification
A Multi-Layer Perceptron (MLP) trained on the classic MNIST dataset to recognize handwritten digits (0–9). Demonstrates end-to-end training with PyTorch, including loss tracking and confusion matrix analysis.

📂 [`Numeral_Recognition_MNIST/`](./Numeral_Recognition_MNIST/)

---

### 2. 🌸 Iris Flower Classification
A PyTorch MLP classifier trained on the Iris dataset to distinguish between three species of iris flowers based on four morphological features.

📂 [`Iris_Classification/`](./Iris_Classification/)

---

### 3. 🏠 Housing Price Prediction
A regression-based approach to predict house prices using well-engineered features. Includes exploratory data analysis (EDA), correlation analysis, and model evaluation with standard regression metrics.

📂 [`Housing_Price_Prediction/`](./Housing_Price_Prediction/)

---

## 📊 Results Summary

| Project | Model | Metric | Performance |
|---|---|---|---|
| MNIST Digit Classification | MLP (PyTorch) | Test Accuracy | ~97% |
| Iris Flower Classification | MLP (PyTorch) | Test Accuracy | 100% |
| Housing Price Prediction | Linear Regression | R² Score | See project README |
| Housing Price Prediction | Linear Regression | MAE | See project README |

---

## 🛠️ Technologies Used

| Library | Purpose |
|---|---|
| **PyTorch** | Neural network definition, training, and inference |
| **NumPy** | Numerical operations and array handling |
| **Pandas** | Data loading, manipulation, and EDA |
| **Matplotlib / Seaborn** | Data visualization and plotting |
| **scikit-learn** | Regression model, metrics, and preprocessing |

---

## 🖼️ Sample Visualizations

<table>
  <tr>
    <td align="center"><b>MNIST – Confusion Matrix</b></td>
    <td align="center"><b>Iris – Training Accuracy</b></td>
  </tr>
  <tr>
    <td><img src="./Numeral_Recognition_MNIST/images/confusion_matrix.png" width="340"/></td>
    <td><img src="./Iris_Classification/images/accuracy.png" width="340"/></td>
  </tr>
</table>

---

## ▶️ Running the Notebooks

### Prerequisites

Ensure you have Python 3.8+ installed. Install the required packages:

```bash
pip install torch torchvision numpy pandas matplotlib seaborn scikit-learn jupyter
```

### Launch Jupyter

```bash
jupyter notebook
```

Navigate to the respective project folder and open the `.ipynb` file.

---

## 📦 Datasets

| Project | Dataset Source |
|---|---|
| MNIST | Auto-downloaded via `torchvision.datasets.MNIST` (not stored in repo — see note below) |
| Iris | Loaded via `sklearn.datasets.load_iris` (bundled in `dataset/`) |
| Housing Price Prediction | Provided externally in `dataset/` folder |

> **Note:** The MNIST dataset is not included in this repository due to its large size. It is downloaded automatically at runtime via `torchvision`, or can be obtained directly from the [MNIST database](http://yann.lecun.com/exdb/mnist/). For the Iris and Housing projects, datasets are stored in their respective `dataset/` folders.

---

## 👤 Author

**Tejas M**
B.Tech — VIT Vellore
Course: Deep Learning (BEEE422L)

---

*Academic project — for educational purposes only.*
