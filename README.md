# 🚢 Titanic: Machine Learning from Disaster

**Predicting passenger survival using machine learning | 82.72% accuracy**

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python)
![Kaggle](https://img.shields.io/badge/Kaggle-Competition-20BEFF)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📊 Project Overview

Analyzed 2,224 passenger records from the Titanic disaster to predict survival outcomes using machine learning. Built and compared multiple classification models to identify the key factors that determined who survived.

**Best Model: Decision Tree - 82.72% Accuracy**

## 🎯 Key Insights

| Factor | Impact | Finding |
|--------|--------|---------|
| Gender | 🔴 Critical | Women: 74% survival vs Men: 19% |
| Class | 🔴 Critical | 1st Class: 63% vs 3rd Class: 24% |
| Age | 🟠 Important | Children had higher survival rates |

## 🛠️ Models Tested

- Logistic Regression: 80.13% accuracy
- **Decision Tree: 82.72% accuracy** ⭐

## 📚 Tech Stack

Python • Pandas • NumPy • Scikit-learn • Matplotlib • Seaborn

## 🚀 Quick Start

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GutoOliva/Titanic-Machine_Learning_from_Disaster/blob/main/Titanic_Machine_Learning_from_Disaster.ipynb)

Or run locally:
```bash
pip install -r requirements.txt
jupyter notebook Titanic_Machine_Learning_from_Disaster.ipynb
```

## 💡 Key Learnings

- ✅ Women and children were prioritized in lifeboats
- ✅ Socioeconomic status (class) heavily influenced survival
- ✅ Decision Trees provided better insights than Logistic Regression
- ✅ Model predictions validated against historical outcomes

## 📂 Files

- `Titanic_Machine_Learning_from_Disaster.ipynb` - Main analysis
- `train.csv` - Training data (891 passengers)
- `test.csv` - Test data (418 passengers)
- `requirements.txt` - Dependencies

## 🤝 Contributing

Contributions welcome! Feel free to fork, open issues, or submit PRs.

## 📄 License

MIT License - See LICENSE file for details

---

**Predicting survival: Women & 1st class = higher chances | Men & 3rd class = lower chances**
