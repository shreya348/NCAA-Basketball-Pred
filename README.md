🏀** NCAA Basketball Tournament Prediction Using Deep Sequence Models
**Project Overview****
This project aims to predict NCAA basketball tournament outcomes by leveraging sequential deep learning models. We systematically apply Long Short-Term Memory (LSTM) networks, Bidirectional LSTM (BiLSTM) architectures, and Temporal Convolutional Networks (TCN) to model the dynamic nature of team performances, player statistics, and matchup histories. Our approach integrates over four decades of historical tournament data (1985–2025) to develop robust and data-driven forecasting systems.

By evaluating multiple models trained with Stochastic Gradient Descent (SGD) and Adam optimizers, we highlight the advantages and limitations of different sequential learning techniques in sports analytics and tournament forecasting.


✨ **Key Features**
Implementation of three deep learning models: LSTM, BiLSTM, and TCN.

Feature engineering incorporating team performance metrics, player stats, seeding information, and venue characteristics.

Dual-optimizer training experiments (SGD and Adam) for assessing model convergence and performance.

Comprehensive evaluation using accuracy, Brier score, and AUC-ROC metrics.

In-depth analysis of model performance, highlighting the superiority of BiLSTM for capturing complex temporal dependencies.

Insights into model generalization for broader sports analytics applications (e.g., football, baseball).

📚 **Technologies Used**
-Python 3.9+
-TensorFlow / PyTorch
-NumPy, Pandas
-Scikit-learn
-Matplotlib, Seaborn
-Google Colab


📁 data/
    - Processed datasets (1985-2025 NCAA tournaments)
📁 models/
    - LSTM_Model.py
    - BiLSTM_Model.py
    - TCN_Model.py
📁 notebooks/
    - EDA.ipynb (Exploratory Data Analysis)
    - Model_Training.ipynb (Training all models)
    - Evaluation.ipynb (Model performance comparison)
📁 utils/
    - preprocessing.py (Data preparation and feature engineering)
    - metrics.py (Custom evaluation metrics)
📄 README.md





