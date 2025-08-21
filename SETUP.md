# Project Setup Guide

## Getting Started with the Machine Learning Sentiment Analysis Project

### Quick Start

**Repository URL:** https://github.com/Chrls0806/Machine-Learning

### Method 1: Clone Locally
```bash
# Clone the repository
git clone https://github.com/Chrls0806/Machine-Learning.git

# Navigate to project directory
cd Machine-Learning

# Install required packages
pip install pandas numpy matplotlib seaborn scikit-learn jupyter

# Start Jupyter Notebook
jupyter notebook "PROJECT MACHINE LEARNING Final.ipynb"
```

### Method 2: Use Google Colab (Recommended)
1. Go to [Google Colab](https://colab.research.google.com/)
2. Click "File" → "Open notebook" → "GitHub"
3. Enter: `Chrls0806/Machine-Learning`
4. Select: `PROJECT MACHINE LEARNING Final.ipynb`
5. Upload the CSV files when prompted or connect your Google Drive

### Prerequisites
```python
# Required Python packages
pandas>=1.0.0
numpy>=1.18.0
matplotlib>=3.1.0
seaborn>=0.10.0
scikit-learn>=0.22.0
jupyter>=1.0.0
```

### File Structure After Clone
```
Machine-Learning/
├── PROJECT MACHINE LEARNING Final.ipynb  # 📓 Main notebook
├── sentimentdataset.csv                   # 📊 Original data
├── oldtonew_data.csv                      # 📊 Processed data
├── README.md                              # 📖 Main documentation
├── REPOSITORY_INFO.md                     # ℹ️ Quick reference
└── SETUP.md                               # 🚀 This file
```

### Running the Project

1. **Open the notebook** in Jupyter or Google Colab
2. **Execute cells sequentially** from top to bottom
3. **Adjust file paths** if running locally (instead of Google Drive paths)
4. **Wait for training** to complete (may take a few minutes)
5. **Review results** and model performance metrics

### Expected Outputs
- Data analysis and visualizations
- Sentiment mapping results
- TF-IDF feature matrices
- Model training progress
- Performance metrics (accuracy, classification reports)
- Confusion matrices

### Troubleshooting

**If you can't find the repository:**
- URL: https://github.com/Chrls0806/Machine-Learning
- Make sure you're logged into GitHub
- Check if the repository is public

**If packages are missing:**
```bash
pip install --upgrade pandas numpy matplotlib seaborn scikit-learn
```

**If Google Colab can't find files:**
- Upload CSV files manually to Colab session
- Or connect Google Drive and upload files there

### Next Steps
After running the notebook successfully:
1. Experiment with different parameters
2. Try other machine learning algorithms
3. Use your own dataset
4. Modify the sentiment mapping function
5. Add more visualizations

---
**You now have everything you need to run the sentiment analysis project!** 🎉