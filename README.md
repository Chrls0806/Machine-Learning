# Machine Learning Sentiment Analysis Project

**Repository Location:** `Chrls0806/Machine-Learning`  
**Project Type:** Sentiment Analysis using Machine Learning  
**Main Technologies:** Python, scikit-learn, pandas, TF-IDF, Logistic Regression, Linear SVM

## 📁 Repository Overview

This repository contains a comprehensive sentiment analysis project that classifies social media text into positive, negative, and neutral sentiments using two different machine learning approaches.

### 🗂️ Repository Structure

```
Machine-Learning/
├── PROJECT MACHINE LEARNING Final.ipynb    # Main Jupyter notebook with complete analysis
├── sentimentdataset.csv                     # Original dataset (732 samples)
├── oldtonew_data.csv                        # Processed dataset with mapped sentiments
├── README.md                                # This documentation file
└── .gitignore                              # Git ignore configuration
```

## 📊 Dataset Information

- **Original Dataset:** `sentimentdataset.csv` (732 rows, 15 columns)
- **Processed Dataset:** `oldtonew_data.csv` (732 rows, 11 columns)
- **Text Source:** Social media posts from Twitter, Instagram, Facebook
- **Sentiment Categories:** Positive, Negative, Neutral
- **Features:** Text content, user information, platform, engagement metrics, timestamps

## 🚀 Project Components

### Part 1: Logistic Regression Approach
1. **Data Loading & Exploration** - Mount Google Drive and load dataset
2. **Data Analysis** - Count columns and analyze data structure
3. **Sentiment Mapping** - Map complex emotions to positive/negative/neutral
4. **Data Cleaning** - Standardize sentiment labels
5. **Visualization** - Create bar plots and scatter plots
6. **Text Processing** - TF-IDF vectorization of text data
7. **Label Encoding** - Convert categorical labels to numerical
8. **Data Splitting** - Train/test split (80/20)
9. **Model Training** - Train Logistic Regression classifier
10. **Evaluation** - Assess model performance with metrics

### Part 2: Linear SVM Approach
1. **Linear SVM Implementation** - Support Vector Machine classifier
2. **Label Encoding** - Encode sentiment labels
3. **Supervised Learning** - Split dataset for supervised learning
4. **Pipeline Creation** - TF-IDF with bigrams + Linear SVM pipeline
5. **Model Training** - Train the SVM model
6. **Model Evaluation** - Performance assessment and comparison

## 🛠️ Requirements

```python
pandas
numpy
matplotlib
seaborn
scikit-learn
```

## 💻 Usage Instructions

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Chrls0806/Machine-Learning.git
   cd Machine-Learning
   ```

2. **Install Dependencies:**
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

3. **Run the Analysis:**
   - Open `PROJECT MACHINE LEARNING Final.ipynb` in Jupyter Notebook or Google Colab
   - Execute cells sequentially to reproduce the analysis
   - For Google Colab: Update file paths to your Google Drive location

## 📈 Expected Results

- **Logistic Regression Accuracy:** ~61.2%
- **Linear SVM Accuracy:** ~29.9%
- **Best Performing Model:** Logistic Regression with TF-IDF features

## 🎯 Use Cases

This repository is ideal for:
- Learning sentiment analysis techniques
- Comparing different ML algorithms (Logistic Regression vs SVM)
- Understanding text preprocessing and TF-IDF vectorization
- Social media sentiment analysis projects
- Academic research in NLP and machine learning

## 📝 Notes

- The notebook is configured for Google Colab with Google Drive integration
- Modify file paths when running locally
- The dataset contains social media posts with various emotional labels mapped to three main categories

---

**Need Help?** This repository contains everything you need for sentiment analysis machine learning projects. The main notebook provides step-by-step implementation with detailed explanations.
