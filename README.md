# Air-Quality-Index-analysis-Data-Analysis

## Project Overview 🌍

Delhi’s severe air pollution, particularly in winter, necessitates accurate Air Quality Index (AQI) predictions. AQI ranges from 0 to 500, with higher values indicating greater health risks. This project uses machine learning to predict AQI levels, offering timely alerts and preventative actions.

### Key Features:

- **Data Processing**: Cleaning and normalizing AQI datasets from major Indian cities such as Delhi, Bangalore, Kolkata, and Hyderabad.
- **Predictive Modeling**: Training machine learning models (Random Forest, Gradient Boosting, etc.) to forecast AQI levels.
- **Imbalance Handling**: Using SMOTE to address class imbalances in AQI_Bucket values.
- **Evaluation**: Evaluating models using accuracy, precision, recall, and confusion matrices.

The project aims to provide accurate AQI predictions to help authorities and communities take timely action to combat air pollution.

---

## Project Structure 📁

```bash
.
├── data/                 # Datasets for AQI data
├── notebooks/            # Jupyter notebooks for data analysis and experimentation
├── src/                  # Source code for the project
│   ├── data_processing.py
│   ├── model_training.py
├── README.md             # Project documentation
└── CONTRIBUTING.md       # Contribution guidelines
```
