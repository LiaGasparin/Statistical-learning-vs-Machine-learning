### Statistical Learning vs Machine Learning :

- __Overview__ 🔎 :
  
In the field of econometrics and machine learning, the question of automatic variable selection arises, particularly when dealing with datasets containing numerous potential predictors. Procedures can be artificially distinguished between those involving inference (statistical learning) and those without (machine learning). In the context of this dissertation, we have studied different variable selection methods falling under statistical learning (forward, backward, stepwise selection) and machine learning (LASSO, LARS, ELASTICNET). This README outlines a project aimed at evaluating the performance of these methods using simulated data and considering various stopping criteria (AIC, BIC, CV, etc.).

- __Project Description__ 💻:
  
This article focuses on assessing the effectiveness of various variable selection techniques across four distinct data scenarios. 

For this study, we employed algorithms generating four types of data under different assumptions (H0: data independence and H1: data dependence), created through Monte Carlo simulations. The true model was defined as comprising an intercept with all variables ranging from X1 to X5. Simultaneously, we calculated performance metrics to evaluate each method's ability to identify the correct model. These metrics encompass perfect fit (matching the true model), overfit (obtaining the true model with additional variables), underfit (failure to include all true model variables), and fail (incorrect selection of additional variables, leading to an incomplete true model representation).

- __Keywords__ 🔑:

Statistical learning,
Machine learning,
Forward / backward / Stepwise selection,
Forward Stagewise / LARS / LASSO / ELASTICNET,
AIC / AICc / BIC / K-fold cross-validation / PRESS,
SAS: proc glmselect, proc iml, proc freq

- __Instructions__ 📋:
  
To replicate or build upon this project, follow the steps outlined in the project documentation. Ensure that all dependencies are installed and configured correctly. For any questions or issues, please refer to the documentation or contact the project contributors.

- __Contributors__ 👩‍🎓:
  
Lia GASPARIN-GRANGER,
Samanta LAMOUR,
Nora AANKOUD
