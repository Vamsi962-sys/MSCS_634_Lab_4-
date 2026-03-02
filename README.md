# MSCS 634 – Lab 4  
## Regression Analysis with Regularization Techniques

## Purpose of the Lab

The purpose of this lab was to explore multiple regression techniques and understand the importance of regularization in machine learning models. 
We implemented **Linear Regression**, **Multiple Regression**, and **Polynomial Regression** models, and enhanced them with **Ridge** and **Lasso** regularization techniques. 
We evaluated each model using performance metrics like MAE, MSE, RMSE, and R² to understand how regularization helps prevent overfitting and improve model accuracy.

## Key Insights

- **Linear Regression**: While simple and intuitive, it showed poor performance due to overfitting, as expected for this type of model.
- **Multiple Regression**: Improved accuracy by using multiple features, but still suffered from overfitting.
- **Polynomial Regression**: Captured non-linear relationships well, but increasing the degree led to overfitting.
- **Ridge and Lasso Regression**: Both regularization techniques helped reduce overfitting. Ridge worked better for preserving all features, while Lasso helped by shrinking some coefficients to zero, effectively performing feature selection.
- **Model Comparison**: Multiple Regression and Ridge/Lasso Regression showed better generalization than Linear and Polynomial Regression models. Ridge and Lasso performed best at moderate regularization strengths (alpha = 1).

## Challenges and Decisions

- **Feature scaling** was critical for performance, especially when working with regularization techniques.
- Regularization parameter tuning (**alpha**) was key to balancing bias and variance. Different alpha values led to varying levels of overfitting or underfitting.
- **Polynomial Regression** had a higher risk of overfitting, but it was essential for modeling complex non-linear relationships.

## Conclusion

Through this lab, we demonstrated the effectiveness of regularization techniques like **Ridge** and **Lasso** for improving regression model performance and preventing overfitting. 
Choosing the right model and regularization strength is essential for achieving optimal performance on real-world datasets.
