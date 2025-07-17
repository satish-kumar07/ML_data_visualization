# 🎌 Anime Popularity Classification using Random Forest

A machine learning project that predicts anime score categories — **Low**, **Medium**, or **High** — based on various metadata like genre, episodes, rating, and popularity stats.

## 📂 Dataset

**Source**: [Popular Anime Dataset on Kaggle](https://www.kaggle.com/datasets/tanishksharma9905/top-popular-anime)  
**Records**: 10,000+ anime entries  
**Features**:
- `title`, `genre`, `episodes`, `members`, `rating`, `score`, `rank`, `popularity`, `status`, `type`, etc.

## 🎯 Objective

Build a classification model to **predict the popularity score category** of an anime:
- `Low`: score < 5
- `Medium`: 5 ≤ score < 7
- `High`: score ≥ 7

## 🛠️ Tech Stack

- **Python 3**
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn` (RandomForestClassifier, train_test_split, metrics)

## 🔬 Workflow

1. **Data Cleaning**: Missing value handling, type checking
2. **EDA**: Visualizations, correlation heatmaps, distribution plots
3. **Feature Engineering**: Encoding categorical variables
4. **Model Training**: Train/test split, Random Forest
5. **Evaluation**:
   - Accuracy Score
   - Confusion Matrix

## 🧪 Results

*Your results here — e.g.,*
- Accuracy: 1.0

