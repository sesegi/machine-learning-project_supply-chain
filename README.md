Machine Learning–Based Supply Chain Delivery Time Prediction and Optimization

This project focuses on predicting delivery lead time in a supply chain context using machine learning techniques, with the goal of improving shipment timeliness and supporting operational decision-making.

The project is based on a real-world logistics and order dataset. Data preprocessing included data cleaning, handling missing values, categorical feature encoding, and correlation analysis to reduce redundancy. Given the high dimensionality and large number of categorical variables, tree-based models were selected as the primary modeling approach. Feature correlation filtering and permutation-based feature importance were applied to reduce dimensionality and improve model stability.

Delivery time was modeled from both regression and multi-class classification perspectives. Regression models were used to predict the exact number of delivery days, while classification models predicted discrete delivery-time categories, which better reflect real business scenarios such as on-time versus delayed delivery. Model hyperparameters were optimized using GridSearchCV, and performance was evaluated using Accuracy, F1-score, and AUROC, with particular attention to class imbalance.

To improve model interpretability and performance, permutation importance was used to identify key drivers of delivery time, such as shipping region, shipping mode, and product category. Low-importance features were removed, and the models were retrained. As a result, the optimized Random Forest model significantly improved performance, increasing on-time delivery prediction accuracy from 82% to 89%, with a micro-average AUROC close to 0.99.

Overall, this project demonstrates a complete machine learning pipeline—from data preprocessing and model training to performance evaluation, feature interpretation, and business-oriented optimization—highlighting how machine learning can enhance supply chain efficiency and decision support.
