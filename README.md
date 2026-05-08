# 🤖 AI Workplace Productivity

Analyzing how AI tool adoption impacts employee productivity and burnout risk using **Python**, **EDA**, and **Machine Learning**.

---

## 📊 Dataset
- **Source:** [Kaggle](https://www.kaggle.com/datasets/vishardmehta/ai-tool-usage-and-workplace-productivity-dataset)
- **4,500 employees** · **6 job roles** · **15 features** · **0 null values**

---

## 🔍 Key Findings

| # | Finding |
|---|---------|
| 1 | High AI users do **54% less manual work** than low AI users |
| 2 | Developers & Writers use AI most · Managers & Designers the least |
| 3 | Very high AI usage correlates with **lower** work-life balance scores |
| 4 | Managers have the **highest burnout risk** across all roles |
| 5 | High deadline pressure raises error rates by **~47%** |

---

## 🤖 ML Models

| Model | Target | Result |
|-------|--------|--------|
| Random Forest Regressor | `productivity_score` | R² = **0.87** |
| Random Forest Classifier | `burnout_risk_level` | Accuracy = **82%** |

---

## ⚙️ Run It

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
jupyter notebook AI_Notebook_Final.ipynb
```
> Run **Kernel → Restart & Run All** to execute all cells in order.

---

## 🛠️ Stack
`Python` · `Pandas` · `Scikit-learn` · `Matplotlib` · `Seaborn` · `Jupyter`

---

**Author: Winnie Nduva**
