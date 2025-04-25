
# 🧠 MNIST Handwritten Digit Recognition Report

This repository contains a comprehensive LaTeX report that demonstrates how a **Convolutional Neural Network (CNN)** can be used to classify handwritten digits from the **MNIST dataset**.

---

## 📄 Contents

- `mnist_report.tex` — Full LaTeX report source.
- `output.png` — Training loss plot.
- `output2.png` — Grid of sample MNIST digits with labels.
- `README.md` — This project overview and documentation.

---

## 📊 Project Overview

The MNIST dataset is a collection of 28×28 grayscale images of handwritten digits from 0 to 9. This project trains a CNN to classify these digits accurately.

### 🔧 Steps Covered:
- Data loading and preprocessing
- CNN architecture design
- Model training using categorical cross-entropy
- Visualization of training metrics
- Display of MNIST examples with labels

---

## 🖼️ Sample Visualizations

### 🔹 Training Loss Over Epochs

![Training Loss](output.png)

> As shown above, the model quickly converges with decreasing loss across 10 epochs.

### 🔹 Sample MNIST Digits with Labels

![Sample Digits](output2.png)

> Each image is labeled with its ground truth value. The dataset includes diverse handwriting styles.

---

## 📦 Requirements

To compile the LaTeX report, install any standard LaTeX distribution:
- [TeX Live](https://www.tug.org/texlive/)
- [MiKTeX](https://miktex.org/)

---

## 🛠️ How to Compile

Make sure all files (`mnist_report.tex`, `output.png`, `output2.png`) are in the same directory. Then run:

```bash
pdflatex mnist_report.tex
```

This will generate a PDF with all embedded plots and content.

---

## 👤 Author

**Mahla Entezari**  
*Spring 2024*

---

## 📬 Contact

Feel free to reach out for questions, improvements, or collaborations!

