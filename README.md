# spam mail classification

## Technologies & Libraries Used

-Python
-Jupyter Notebook
-Pandas, Numpy
-Scikit-learn (LogisticRegression, train_test_split, accuracy_score)
-Seaborn, Matplotlib (for visualization)
---

### Project Workflow
1. **Import Dependencies** - All required Python libraries are imported
2. **Load Dataset** - Read the 'spam.csv' file
3. **Label Encoding** - Convert spam/ham labels to binary (0 = ham, 1 = spam)
4. **Train_Test_Split** - Split the data into training and testing sets(80/20)
5. **Feature Extraction - Use TF-IDF vectorization for converting text to numeric
6. **Model Training** - Trained with 'LogisticRegression'
7. **Build Predictive System** - Allow user to input text and classify as spam or not
8. **Visualization** - Show spam vs ham distribution using Seaborn and Matplotlib
9. **Model Evaluation**:
     - **Training Accuracy**: '96.7%'
     - **Testing Accuracy**: '96.6%'

---
## Results

- Logistic Regression performed well with high precision and recall.
- Balanced spam/ham distribution ensured a fair model evaluation.

---
Project Files

- 'spam_classifier.ipynb' - Complete Jupyter Notebook with code and results
- 'spam.csv' - Dataset used for training
- 'README.md' -Project documentation

---

