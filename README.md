# 🚦 Accident Severity Prediction

## 📌 Description
This project is a machine learning model that predicts the **severity of road accidents** (Low, Medium, High) using real-world Indian road accident data.

The model is built using a single dataset (`Roadaccident.csv`) that includes accident counts by district and year. The project is implemented entirely in **Google Colab** using **pandas** and **scikit-learn**, with a **Decision Tree Classifier** tuned using **GridSearchCV**.

---

## 📁 Files Included

- `Realistic_Roadaccident_model.ipynb` – Google Colab notebook containing data cleaning, preprocessing, severity labeling, model training, tuning, and evaluation.
- `Roadaccident.csv` – Dataset containing district-wise road accident data from 1968 to 2022.

---

## 🚀 How to Run (Google Colab)

1. **Open the Notebook**
   - Use Google Colab to open `Realistic_Roadaccident_model.ipynb`.

2. **Upload the Dataset**
   - Use the Colab file upload to upload `Roadaccident.csv`:
     ```python
     from google.colab import files
     uploaded = files.upload()
     ```

3. **Run All Cells**
   - The notebook will:
     - Clean and group accident data by state and year
     - Create severity levels (Low / Medium / High)
     - Train and tune a Decision Tree model using GridSearchCV
     - Print classification report and accuracy

---

## 🧠 Model Details

- **Input Feature**: Number of Accidents
- **Output Label**: Severity (`Low`, `Medium`, `High`)
- **Algorithm**: Decision Tree Classifier (tuned with GridSearchCV)
- **Libraries Used**: `pandas`, `scikit-learn`, `matplotlib`, `seaborn`

---

## 📈 Output Example (After GridSearchCV Tuning)

🎯 Accuracy: 0.79
📋 Classification Report:
precision recall f1-score support

    High       0.90      0.91      0.91        58
     Low       0.76      0.74      0.75        50
  Medium       0.72      0.72      0.72        57

accuracy                           0.79       165
macro avg 0.79 0.79 0.79 165
weighted avg 0.79 0.79 0.79 165

---

## 👩‍💻 Author

**Cheruku Sri Latha**  
B.E. Artificial Intelligence and Data Science  
Chaitanya Bharathi Institute of Technology (CBIT)  
[LinkedIn](https://www.linkedin.com/in/cheruku-srilatha-4386922ab)

---

## 📜 License

This project is licensed under the **MIT License** – see the `LICENSE` file for details.
