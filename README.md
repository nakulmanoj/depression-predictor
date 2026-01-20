🧠 Depression Predictor — AI-Driven Mental Health Risk Assessment



An end-to-end machine learning system for predicting depression risk using behavioural, academic, lifestyle, and feedback-based indicators.

The project compares multiple classical ML models, ensemble methods, deep learning baselines, and AutoML approaches, with a strong focus on reproducibility, evaluation, and interpretability.

✨ Key Features



&nbsp;   📊 End-to-end ML pipeline: data preprocessing → training → evaluation



&nbsp;   🤖 Multiple models: Logistic Regression, SVM, Decision Trees, Random Forest, Gradient Boosting, XGBoost



&nbsp;   🧠 Deep learning baseline using MLP



&nbsp;   ⚡ AutoML using AutoGluon stacked ensembles



&nbsp;   ⚖️ Handles class imbalance using SMOTE



&nbsp;   🔍 Model interpretability using SHAP



&nbsp;   🧹 Unified preprocessing: scaling, encoding, and feature engineering



&nbsp;   📈 Multiple evaluation metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC



🏗️ Project Structure



depression-predictor/

│

├── notebooks/              # Experiments, EDA, AutoGluon, training notebooks

├── src/                    # Core ML code (models, training, evaluation, utils)

├── data/                   # (Ignored) Datasets used for training/testing

├── artifacts/              # (Ignored) Generated models, outputs, results

├── autogluon\_models/       # (Ignored) AutoGluon trained models

│

├── README.md

├── requirements.txt

└── .gitignore



&nbsp;   ⚠️ Note: data/, artifacts/, and trained models are intentionally not tracked in git to keep the repository lightweight.



🔬 Methodology



&nbsp;   Data Preprocessing



&nbsp;       Missing value handling



&nbsp;       Categorical encoding



&nbsp;       Feature scaling



&nbsp;       Class balancing using SMOTE



&nbsp;   Models Trained



&nbsp;       Logistic Regression



&nbsp;       Support Vector Machine (SVM)



&nbsp;       Decision Tree



&nbsp;       Random Forest



&nbsp;       Gradient Boosting



&nbsp;       XGBoost



&nbsp;       Multi-Layer Perceptron (Neural Network)



&nbsp;       AutoGluon (Stacked Ensembles / AutoML)



&nbsp;   Evaluation



&nbsp;       Train-test split with fixed seeds



&nbsp;       Cross-checked across multiple metrics



&nbsp;       Comparative performance analysis across models



&nbsp;   Explainability



&nbsp;       SHAP used for feature-level importance and explanation of predictions



🛠️ Tech Stack



&nbsp;   Languages: Python



&nbsp;   Libraries:



&nbsp;       NumPy, Pandas, Matplotlib



&nbsp;       scikit-learn



&nbsp;       XGBoost



&nbsp;       TensorFlow / Keras



&nbsp;       AutoGluon



&nbsp;       SHAP



&nbsp;       imbalanced-learn (SMOTE)



🚀 How to Run

1️⃣ Clone the repository



git clone https://github.com/nakulmanoj/depression-predictor.git

cd depression-predictor



2️⃣ Create virtual environment (recommended)



python -m venv venv

venv\\Scripts\\activate   # On Windows



3️⃣ Install dependencies



pip install -r requirements.txt



4️⃣ Add dataset



Place your dataset in:



data/



(e.g., data/train.csv or data/clean\_data.csv)

5️⃣ Run notebooks / scripts



&nbsp;   Use the notebooks in notebooks/ for experiments and AutoGluon training



&nbsp;   Or run scripts from src/ for classical ML experiments



📊 Results (Summary)



&nbsp;   Ensemble methods and AutoGluon stacked models achieved the best overall performance



&nbsp;   Classical models provide strong baselines and better interpretability



&nbsp;   SHAP revealed key behavioural and lifestyle features contributing to depression risk



&nbsp;   Exact numbers depend on dataset and split and are documented in the notebooks.



🧠 Use Cases



&nbsp;   Academic research on mental health prediction



&nbsp;   ML pipeline benchmarking (classical vs ensemble vs AutoML)



&nbsp;   Demonstration project for applied machine learning in healthcare



⚠️ Disclaimer



This project is for educational and research purposes only.

It is not a medical diagnostic tool and should not be used for clinical decisions.

👨‍💻 Author



Nakul Manoj



&nbsp;   GitHub: https://github.com/nakulmanoj



