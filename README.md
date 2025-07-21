# Explaining Deep Learning Predictions for Chronic Kidney Disease Using Neuro-Symbolic AI


## 1 Introduction

Explainability is a critical aspect of AI in medical predictions, where trust and interpretability are essential for clinical
applications. Deep learning models often function as “black boxes,” making it difficult for medical professionals to
understand the reasoning behind their predictions. This lack of transparency poses a significant challenge, as incorrect
or misinterpreted AI predictions can have severe consequences in patient care.
For instance, in chronic kidney disease (CKD) diagnosis, a neural network might predict whether a patient is at risk.
However, if the model cannot explain which features (such as creatinine levels, blood pressure, or proteinuria) contribute
to the decision, doctors may struggle to justify treatments based on the AI’s recommendation. This highlights the need
for an explainable AI framework that combines deep learning with symbolic reasoning to enhance interpretability.

## 2 Project Objectives

This project aims to:

- Develop a deep learning model to classify CKD using a medical dataset.
- Explore the impact of varying neural network architectures and node counts on model performance.
- Apply Neuro-Symbolic AI techniques to improve model explainability.
- Analyze how changes in architecture affect the interpretability of the model’s decisions.

## 3 Methodology

#### 3.1 Dataset and Preprocessing

The CKD dataset will be preprocessed to handle missing values, normalize features, and encode categorical variables
appropriately.

#### 3.2 Deep Learning Model

A neural network will be implemented using TensorFlow/PyTorch. Experiments will be conducted to test different
architectures and configurations, including:

- Number of hidden layers and neurons per layer.
- Activation functions and optimization strategies.
- Regularization techniques to improve generalization.

#### 3.3 Neuro-Symbolic AI for Explainability

To enhance interpretability, symbolic AI methods will be incorporated to extract human-understandable rules from the
trained neural network. This will allow a structured reasoning process for CKD classification decisions.

## 4 Expected Outcomes

- A well-trained deep learning model capable of CKD classification.
- Insights into the relationship between model complexity and explainability.
- A framework integrating Neuro-Symbolic AI to improve interpretability.
- A discussion on the trade-offs between model accuracy and explainability in medical AI.

## 5 Conclusion

This project will contribute to the growing need for explainable AI in healthcare by demonstrating how symbolic reasoning
can be combined with deep learning for enhanced interpretability. The findings could pave the way for more trustworthy
AI models in medical diagnostics, improving their adoption in clinical settings.

### 1


