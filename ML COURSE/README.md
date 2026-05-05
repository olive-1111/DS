# Machine Learning: From Fundamentals to Ensemble Architectures

This project represents a comprehensive deep-dive into the Machine Learning lifecycle. It documents the transition from understanding core statistical learning theory to deploying complex ensemble models and unsupervised clustering algorithms.

## 🏗️ PROJECT ECOSYSTEM

### **1. Supervised Learning & Regression**
* **House Price Predictor (Refactored):** Originally designed for the Boston dataset, I successfully refactored this project to utilize the **California Housing** dataset. This required adjusting feature engineering and labels to maintain model accuracy within a new data distribution.
* **Linear & Logistic Regression:** Implementing fundamental predictive modeling with a focus on Regularization techniques to prevent overfitting.
* **Stock Price Predictor:** Utilizing time-series logic to forecast market trends.

### **2. Advanced Modeling & Ensembles**
* **Support Vector Machines (SVM):** High-dimensional data classification.
* **Decision Trees & Ensemble Learning:** Implementing robust models through **Boosting** (XGBoost/AdaBoost) and **Stacking** to maximize predictive power.
* **Heart Failure Prediction:** A clinical data project focused on classification accuracy and model evaluation metrics.

### **3. Unsupervised Learning & Dimensionality Reduction**
* **Clustering:** Implementing **K-Means** and **Hierarchical Clustering** to find hidden patterns in unlabeled data.
* **Principal Component Analysis (PCA):** Reducing feature complexity while maintaining data variance.

## THE MIGRATION CHALLENGE

The primary hurdle in this project was the "Time & Version Gap" between the 2021 tutorial and current software libraries:

* **Ethical Data Refactoring:** When `scikit-learn` removed the Boston dataset due to ethical biases, I independently pivoted the "House Price Predictor" project to the California Housing dataset. This involved mapping new features (e.g., `MedInc`, `AveRooms`) and re-validating the model's performance.
* **Environment Resilience:** Navigated performance constraints by optimizing code execution and using AI to troubleshoot specific "ModuleNotFound" or "NotFittedError" roadblocks (specifically with XGBoost).
* **Visualization Logic:** Bridged the gap between legacy syntax and clear data visualizations, including Distribution plots (Normal vs. Log-Transformed), Correlation Heatmaps, and QQ-plots.

## CHALLENGES

* **Syntax Evolution:** Modernizing XGBoost and Seaborn commands that have changed significantly since the tutorial's release.
* **Hardware Limitations:** Managing training times for Ensemble and Boosting models, requiring meticulous code structure to avoid system hangs.
* **Logic Absorption:** Translating high-level math concepts like Regularization, Stacking, and Learning Theory into functional Python scripts.

## SOLUTIONS

* **Dynamic Code Adjustment:** Used AI as a technical consultant to "translate" outdated tutorial prompts into modern, bug-free code.
* **Label Mapping:** Manually adjusted visualization labels and data-dictionary references to align with the California dataset.
* **Persistent Debugging:** Successfully navigated installation issues and fit-sequencing to ensure a fully functional end-to-end pipeline.

## TECHNICAL STACK
* **Languages:** Python
* **Libraries:** Scikit-Learn, XGBoost, Pandas, NumPy, Seaborn, Matplotlib, SciPy
* **Environment:** Jupyter Notebook / Anaconda