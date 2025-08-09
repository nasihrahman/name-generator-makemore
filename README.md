# Name Generator — makemore style

A character-level name generator that trains on a dataset of names and generates new, creative names using a neural network. The project is implemented in Python with Jupyter Notebooks and serves as an educational and experimental tool for understanding language models.

---

## 🔎 Overview

This project trains a model to:

* Load and preprocess a dataset of names
* Build and train a character-level neural network
* Generate new names using sampling techniques

It’s designed for readability and easy experimentation.

---

## ⭐ Features

* Fully implemented in Jupyter Notebooks
* Character-level tokenization
* Train/validation/test split for evaluation
* Configurable network parameters
* Sampling with temperature control for creative variation

---

## ⚙️ Requirements

* Python 3.8+
* Jupyter Notebook
* PyTorch
* NumPy
* Matplotlib

Install dependencies:

```bash
pip install torch numpy matplotlib notebook
```

---

## 🚀 How to Run

1. Clone the repo:

```bash
git clone https://github.com/<your-username>/name-generator-makemore.git
cd name-generator-makemore
```

2. Open the notebook in Jupyter:

```bash
jupyter notebook makemore_mlp.ipynb
```

3. Run all cells to train the model and generate names.

---

## 📂 Files in Repo

* `build_makemore_mlp.ipynb` — notebook for building the MLP model
* `makemore1.ipynb` — alternate/trial notebook for experimentation
* `makemore_mlp.ipynb` — main notebook for training and sampling
* `names.txt` — dataset of names
* `README.md` — project documentation

---

## 📊 Example Output

Generated names might look like:

```
Auren
Marla
Zerik
Lyanna
```

---

## 🤝 Contributing

Pull requests are welcome! Please submit issues for bugs or feature requests.

---

