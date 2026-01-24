# Heart-Stroke-Prediction
This project presents a simple yet effective deep learning model for predicting the likelihood of heart stroke based on patient health data. It demonstrates the full machine learning pipeline — from data pre-processing to model training, evaluation, and optimization — with a focus on achieving high predictive accuracy.


Perfect — here’s a **GitHub-ready Markdown section** with all your tables neatly formatted. You can copy-paste this directly into your `README.md` file:

---


##  1. Training & Validation Performance

| Model       | Training Accuracy (%) | Validation Accuracy (%) | Training Loss | Validation Loss |
|-------------|------------------------|--------------------------|---------------|-----------------|
| CNN-LSTM    | 89.42                 | 79.87                   | 0.24          | 0.51            |
| ANN         | 92.15                 | 85.03                   | 0.19          | 0.43            |
| Transformer | 96.60                 | 96.62                   | 0.089         | 0.50            |

---

##  2. Test Set Evaluation  
After completing training, all models were evaluated on the held-out test set (**2,808 samples**).

| Model       | Test Accuracy (%) |
|-------------|-------------------|
| CNN-LSTM    | 76.21             |
| ANN         | 84.78             |
| Transformer | 87.35             |

---

##  3. Classification Metrics  
Precision, Recall, and F1-score were computed for deeper evaluation.

| Model       | Precision (%) | Recall (%) | F1-Score (%) |
|-------------|---------------|------------|--------------|
| CNN-LSTM    | 93.88         | 80.22      | 87.05        |
| ANN         | 96.12         | 88.03      | 92.57        |
| Transformer | 96.41         | 91.87      | 93.64        |

---

##  4. Overall Model Comparison

| Metric          | CNN-LSTM | ANN     | Transformer |
|-----------------|----------|---------|-------------|
| Test Accuracy   | 76.21%   | 84.78%  | 87.35%      |
| F1-Score        | 74.05%   | 91.57%  | 96.64%      |
| AUC             | 0.964    | 0.941   | 0.982       |
| Training Speed  | Medium   | Fastest | Slowest     |
| Generalization  | High     | Moderate| Very High   |
| Overall Rank    | 2nd      | 3rd     | 1st         |

---

