# Homework 3: Survival Analysis – Marketing Analytics

**Author**: Zhora Poghosyan  
**Course**: DS223 Marketing Analytics  
**Topic**: Survival Analysis and Customer Lifetime Value (CLV)

---

## 📘 Overview

This notebook applies **Survival Analysis** methods to examine customer retention behaviors, estimate customer lifetime value, and support decision-making in marketing. A range of **parametric and non-parametric models** is explored to understand customer churn patterns, and the models are evaluated for performance and interpretability.

---

## 📊 Key Components

### ✅ Parametric AFT Models
- Models explored: **Weibull**, **Exponential**, **LogNormal**, **LogLogistic**, **Generalized Gamma**, **Spline**, **Piecewise Exponential**, **Mixture Cure**, **BFH**.
- Main tasks:
  - Training and evaluating several survival models.
  - Visualizing survival curves.
  - Conducting feature selection and choosing the most suitable model.

### ✅ Non-Parametric Models
- **Kaplan-Meier Fitter**
- **Nelson-Aalen Fitter**

### ✅ Model Selection
After comparing all parametric models, the **Weibull model** was selected as the final choice due to its strong fit to the data and interpretability.

---

## 💰 Customer Lifetime Value (CLV) Estimation

CLV was calculated for both **male and female** customer groups, using an assumed monthly revenue of **$50**.

- **Female CLV**: $2762.91  
- **Male CLV**: $2757.21  

The analysis indicates that female customers remain subscribed slightly longer on average, resulting in marginally higher lifetime value.

---

## 📌 Conclusion

This notebook demonstrates a full survival analysis workflow—model comparison, retention estimation, and CLV calculation—showing how survival modeling can support marketing strategies and customer management decisions.

---

## ⚙️ Setup and Execution Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/ZhoraPoghosyan/DS223_HW3.git
cd <your-repo-directory>
```

### 2. Create and Activate a Virtual Environment
```bash
python -m venv venv
# On Windows
venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the Jupyter Notebook
```bash
jupyter notebook DS223_HW3.ipynb
```
