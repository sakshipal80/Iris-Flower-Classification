 Iris Flower Classification 

This project uses  **Iris dataset** to build a beginner-friendly machine learning model that can classify flowers into three species:
- Setosa
- Versicolor
- Virginica

It uses the **K-Nearest Neighbors (KNN)** algorithm to predict the species based on:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width
  
 Dataset Information
The Iris dataset contains:
- 150 samples (flowers)
- 4 features per sample
- 3 classes (species)

 Dataset Source: [Iris Dataset (UCI ML Repository)](https://archive.ics.uci.edu/ml/datasets/Iris)

---

 Technologies Used

- Python 
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

 Steps Followed

1. Loaded and explored the dataset
2. Visualized relationships using Seaborn
3. Split data into training and testing sets
4. Trained the model using **KNN**
5. Predicted flower species
6. Evaluated accuracy using `accuracy_score`
7. Made predictions on new flower data

🔮 How to Use
1. Clone the repository
2. Open the notebook (`.ipynb`) in Google Colab or Jupyter
3. Run all cells to train the model and make predictions

---

## 🎯 Sample Output

```python
Predicted species for new data: ['virginica']
Model Accuracy: 96.67%
