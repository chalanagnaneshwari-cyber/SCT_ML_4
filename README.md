# SkillCraft Technology – Machine Learning Internship

## Task 4: Hand Gesture Recognition Using SVM

### Project Overview
This project classifies hand-gesture images representing letters of the American Sign Language (ASL) alphabet using the Sign Language MNIST dataset. The workflow uses image features, Principal Component Analysis (PCA), and a Support Vector Machine (SVM) classifier.

### Objective
- Load and explore the hand-gesture dataset.
- Preprocess pixel data for machine learning.
- Train a model to classify gesture labels.
- Evaluate classification performance.
- Visualize predictions and model results.

### Dataset
**Dataset:** Sign Language MNIST

**Source:** https://www.kaggle.com/datasets/datamunge/sign-language-mnist

The CSV files typically include a `label` column and pixel columns representing 28 × 28 grayscale images. The labels correspond to ASL alphabet letters, excluding J and Z because those letters require motion.

Expected files:
```text
SCT_ML_4/
├── sign_mnist_train.csv
└── sign_mnist_test.csv
```

### Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook

### Workflow
1. Load the training and testing CSV files.
2. Separate labels from pixel features.
3. Normalize pixel values.
4. Display sample gesture images.
5. Apply PCA for dimensionality reduction.
6. Train an SVM classifier.
7. Predict labels for the test data.
8. Evaluate the model using accuracy, a classification report, and a confusion matrix.
9. Save the trained model and result files.

### Algorithms
**Principal Component Analysis (PCA):** Reduces the number of pixel features while retaining important information.

**Support Vector Machine (SVM):** Learns to classify gesture images into the dataset's label categories.

### Evaluation
The notebook evaluates the model using:
- Accuracy
- Precision, recall, and F1-score
- Confusion matrix

Add the actual test accuracy and key findings from your notebook here. Do not report a metric until you have confirmed it from your run.

### Project Structure
```text
SCT_ML_4/
├── README.md
├── SCT_ML_Task4_Hand_Gesture.ipynb
├── sign_mnist_train.csv
├── sign_mnist_test.csv
├── results/
└── artifacts/
```

Adjust the structure to match your repository. If you prefer not to include the dataset CSVs in GitHub, add them to `.gitignore` and explain how to download them in the Dataset section.

### How to Run
1. Download the Sign Language MNIST dataset from Kaggle.
2. Place the CSV files in the project folder, or update the paths in the notebook.
3. Install the dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn joblib jupyter
   ```
4. Open the notebook:
   ```bash
   jupyter notebook SCT_ML_Task4_Hand_Gesture.ipynb
   ```
5. Run the notebook cells in order.

### Learning Outcomes
- Loading and preparing image data stored in CSV files.
- Normalizing pixel values.
- Applying PCA for dimensionality reduction.
- Training an SVM image classifier.
- Evaluating multi-class classification performance.
- Visualizing gesture predictions.

### Conclusion
This project demonstrates a hand-gesture image classification workflow using the Sign Language MNIST dataset, PCA, and SVM. The model predicts dataset labels representing ASL alphabet letters.

### Internship Details
- **Organization:** SkillCraft Technology
- **Domain:** Machine Learning
- **Task:** Task 4
