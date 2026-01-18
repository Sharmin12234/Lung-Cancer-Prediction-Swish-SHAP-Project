
# Interpretable Lung Cancer Prediction using Swish-optimized NN 🫁

Official implementation of the research paper: **"An Interpretable Deep Learning Framework for Lung Cancer Prediction using Swish-optimized Neural Networks and SHAP Explanations"**.

## 📑 Status
- **Status:** Submitted to **IEEE** for publication.
- **Methodology:** Leverages Swish activation functions and SHAP for reliable medical diagnostics.

## 🚀 Project Highlights
- **Swish Optimization:** Utilizes the Swish activation function for better gradient flow and higher accuracy in lung cancer detection.
- **Explainability (XAI):** Uses **SHAP KernelExplainer** to visualize how each clinical symptom (like fatigue, coughing, etc.) impacts the model's prediction.
- **Robustness:** Implemented EarlyStopping and Learning Rate Reduction to prevent overfitting.



## 📊 Methodology
1. **Data Augmentation:** SMOTE was used to handle class imbalance.
2. **Model:** A multi-layered Feed-forward Neural Network (FNN).
3. **Interpretability:** Local Waterfall plots and Global Summary plots to explain individual patient cases.

## 🛠 Installation
```bash
pip install tensorflow shap pandas scikit-learn matplotlib