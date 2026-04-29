# Smart Loan Recovery System

[![Streamlit App](https://img.shields.io/badge/Streamlit-Deployed-green)](https://smart-loan-recovery-system-rkyw6xkw6anbygkdocw7gn.streamlit.app/)

[Demo Video](https://drive.google.com/file/d/1V1e6W5M5Apzpa1MhbAM591mqCHDllKUM/view?usp=sharing)

## 📌 Project Overview
The **Smart Loan Recovery System** is a machine learning-based solution designed to predict loan recovery outcomes and recommend strategies for minimizing default risks. It analyzes borrower details like **income, loan amount, and repayment history** to assess their risk levels.

---

## ✨ Features
- **Loan Recovery Prediction**: Predicts the likelihood of loan repayment.
- **Borrower Segmentation**: Uses **K-Means Clustering** to classify borrowers into risk categories.
- **Risk Scoring**: Assigns risk scores based on financial behavior.
- **Action Recommendation**: Suggests recovery strategies for high-risk borrowers.
- **Interactive Dashboard**: Built with **Streamlit** for easy visualization.

---

## 🧠 Tech Stack
- **Programming Language**: Python  
- **Libraries**:
  - `Pandas` – Data manipulation
  - `Scikit-learn` – Machine Learning models
  - `Plotly` – Interactive charts
- **Model**:
  - **Random Forest Classifier** for risk prediction
  - **K-Means Clustering** for borrower segmentation
- **Deployment**: Streamlit

---

## 🔍 Methodology
1. **Data Collection** – Borrower information including income, loan size, and repayment history.
2. **EDA (Exploratory Data Analysis)** – Detect patterns and anomalies.
3. **Feature Engineering** – Create meaningful features like `Days_Past_Due`, `Num_Missed_Payments`.
4. **Clustering (K-Means)** – Segment borrowers into risk groups.
5. **Model Training** – Use **Random Forest Classifier** for risk scoring.
6. **Action Recommendation** – Suggest strategies for recovery based on risk level.
7. **Deployment** – Built an interactive dashboard using Streamlit.

---

## 🚀 Live Demo
🔗 **[Click Here to View Deployed App](https://smart-loan-recovery-system-rkyw6xkw6anbygkdocw7gn.streamlit.app/)**

---

## 📊 Sample Visualizations
- Risk Score Distribution
- Borrower Segmentation (Clusters)
- Recommended Recovery Actions

---

## 🛠 Installation Guide
To run the project locally:

### 1️⃣ Clone the Repository

git clone https://github.com/shinewithsachin/Smart-Loan-Recovery-System.git
cd Smart-Loan-Recovery-System

### 2️⃣ Create Virtual Environment & Install Dependencies
pip install -r requirements.txt

### 3️⃣ Run the Streamlit App
streamlit run app.py

## 📂 Project Structure
Smart-Loan-Recovery-System/
│

├── data/
│   └── sample_dataset.csv

├── app.py

├── model/
│   └── loan_model.pkl

├── requirements.txt

└── README.md

## 🖼 Screenshots

![Input-Output](https://github.com/shinewithsachin/Smart-Loan-Recovery-System/blob/main/Screenshot%202025-08-21%20235917.png)
![Input-Output](https://github.com/shinewithsachin/Smart-Loan-Recovery-System/blob/main/Screenshot%202025-08-21%20235932.png).
![Input-Output](https://github.com/shinewithsachin/Smart-Loan-Recovery-System/blob/main/Screenshot%202025-08-21%20235945.png)
![Input-Output](https://github.com/shinewithsachin/Smart-Loan-Recovery-System/blob/main/Screenshot%202025-08-21%20235959.png).

## 📬 Contact

For any queries, reach out:

Author: Sachin Kumar

GitHub: shinewithsachin


## ⭐ Contribute

Feel free to fork this repo and submit pull requests for improvements!

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


