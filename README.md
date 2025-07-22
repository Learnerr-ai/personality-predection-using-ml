# personality-predection-using-ml

# Personality Prediction: Introvert vs. Extrovert

## 📌 Project Overview

This project focuses on predicting whether a person is an **Introvert** or an **Extrovert** using machine learning techniques. Behavioral traits are analyzed using a dataset and trained models to classify personality types. The project is implemented in a Jupyter Notebook (`Personality_predection.ipynb`).

---

## 📂 Project Structure

```
├── Personality_predection.ipynb   # Main Jupyter Notebook for analysis and model
├── model_artifacts/               # Folder to store trained models (.pkl)
├── data/                          # Folder containing raw and processed datasets
├── README.md                      # Project documentation
```

---

## 🧠 ML Workflow

1. **Data Loading & Exploration**  
   Load the personality dataset and perform basic exploratory data analysis.

2. **Data Preprocessing**  
   Clean the data, handle missing values, encode categorical features, and normalize inputs.

3. **Model Training**  
   Train classification models (e.g., Logistic Regression, Random Forest, SVM) to predict personality.

4. **Model Evaluation**  
   Evaluate models using accuracy, precision, recall, F1-score, and confusion matrix.

5. **Prediction**  
   Use the trained model to predict if a new individual is an introvert or extrovert.

---

## 📁 Requirements

Install the following Python libraries before running the notebook:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib
```

---

## ▶️ How to Run

1. Clone this repository or download the `.ipynb` file.
2. Open `Personality_predection.ipynb` in Jupyter Notebook or Google Colab.
3. Run all cells step by step.
4. Use the trained model for prediction at the end.

---

## 📊 Dataset

- **Source**: Kaggle - [Extrovert vs. Introvert Behavior Data](https://www.kaggle.com/datasets/rakeshkapilavai/extrovert-vs-introvert-behavior-data)
- **Attributes**: Behavioral traits like social interaction, energy levels, decision-making preferences, etc.

---

## 🔍 Results

The model successfully classifies individuals as either introverts or extroverts with good accuracy after proper training and tuning.

---

## 📌 Future Improvements

- Integrate with a web or mobile UI for real-time predictions
- Use deep learning for enhanced accuracy
- Add more granular personality traits (e.g., MBTI types)

---

## 📧 Contact

For questions or suggestions, feel free to reach out:

**Author**: Rajdeep  
**Email**: [your-email@example.com]  
**GitHub**: [github.com/yourusername]
