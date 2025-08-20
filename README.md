<h1 align="center">🌸 Machine Learning on Iris Dataset 🌿</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Scikit--learn-ML-orange?logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-yellow?logo=jupyter&logoColor=white" />
  <img src="https://img.shields.io/badge/Status-Completed-success?style=flat-square" />
</p>

---

## 📂 Repository Structure

```bash
iris-ml-classification/
│
├── 📘 Logistic_Regression.ipynb       # Logistic Regression (Binary Classification)
├── 🌳 DecisionTree_PrePruning.ipynb   # Decision Tree with Pre-pruning
├── 🌲 DecisionTree_PostPruning.ipynb  # Decision Tree with Post-pruning
├── 📄 README.md                       # Documentation
└── 📦 requirements.txt                # Dependencies



---

## 📊 Dataset  

The **Iris dataset** 🌸 is a classic dataset with **150 samples** and 4 features:  

- 🌱 Sepal Length  
- 🌱 Sepal Width  
- 🌸 Petal Length  
- 🌸 Petal Width  

**Target Classes:**  
- Setosa 🌼  
- Versicolor 🌿  
- Virginica 🌺  

---

## 🔎 Implementations  

### 1️⃣ Logistic Regression (Binary Classification)  
- **Goal:** Classify 🌿 Versicolor vs 🌺 Virginica (ignoring Setosa).  
- **Steps:**  
  - Data preprocessing (NumPy + Pandas)  
  - Model training with `LogisticRegression()`  
  - Evaluation with **accuracy score & confusion matrix**  
- **Why Logistic?** ➝ Simple yet powerful for binary classification.  

---

### 2️⃣ Decision Tree Classifier 🌳 (Multi-class Classification)  

#### ✂️ Pre-pruning  
- Limit tree growth with:  
  - `max_depth`  
  - `min_samples_split`  
- Controls overfitting early.  

#### 🌲 Post-pruning  
- Grow a **full tree** first.  
- Then prune using **Cost Complexity Pruning (`ccp_alpha`)**.  
- Balances **bias-variance tradeoff** for better generalization.  

---

## 🛠️ Tools & Libraries  

- 🐍 **Python 3.10+**  
- 🔢 **NumPy, Pandas** → Data preprocessing  
- 📊 **Matplotlib, Seaborn** → Visualization  
- 🤖 **Scikit-learn** → ML Models  

---

## 📸 Visualizations  

✅ Feature distribution (pairplots 🌸)  
✅ Decision tree visualization 🌳  
✅ Accuracy metrics 📊  

---

## 🚀 Run Locally  

```bash
# Clone the repository
git clone https://github.com/your-username/iris-ml-classification.git

# Navigate into folder
cd iris-ml-classification

# Launch notebooks
jupyter notebook
