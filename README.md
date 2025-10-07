# Housing-Price-Prediction-Multiple-Linear-Regression
            This project applies “Multiple Linear Regression (MLR)” to predict “house prices” based on various factors such as area, location, number of bedrooms, bathrooms, and amenities.  
The objective is to identify the most influential variables driving housing prices and build an interpretable regression model to support “data-driven decision-making” in real estate pricing.
                                          Objectives
                  - Perform “Exploratory Data Analysis (EDA)” to understand housing data distributions and relationships.  
                  - Build a “Multiple Linear Regression model” to predict housing prices.  
                  - Identify and interpret “key predictors” influencing property value.  
                  - Validate the model using statistical metrics such as “R², Adjusted R², RMSE”, and “p-values”.  
                  - Derive “business insights” to assist stakeholders in strategic pricing decisions.
                                          Steps Performed

                  1. “Data Understanding & Cleaning”  
                               - Loaded and explored dataset structure.  
                               - Treated missing values, outliers, and inconsistent entries.  
                               - Renamed columns and standardized numerical/categorical features.  
              
                  2. “Exploratory Data Analysis (EDA)”  
                               - Analyzed distributions of numeric variables (area, price, bedrooms, etc.).  
                               - Studied correlations between independent variables and the target variable.  
                               - Used heatmaps, scatterplots, and pairplots for visualization.
              
                  3. “Feature Engineering”  
                               - Created dummy variables for categorical features.  
                               - Handled multicollinearity using “VIF (Variance Inflation Factor)”.  
                               - Scaled features for consistent model performance.
              
                  4. “Model Building”  
                               - Built the “Multiple Linear Regression model” using `statsmodels` and `scikit-learn`.  
                               - Iteratively refined the model by removing insignificant predictors (based on p-values).  
              
                  5. “Model Evaluation”  
                               - Evaluated model performance using “R², Adjusted R², RMSE”, and “residual analysis”.  
                               - Verified model assumptions (linearity, normality, homoscedasticity, multicollinearity).  
                            
                  6. “Insights & Recommendations”  
                               - Identified top variables impacting housing prices (e.g., area, number of bedrooms, and location).  
                               - Provided actionable insights for “pricing strategy and investment planning”.
                               
                                            Key Insights
                                            
                    - “House area and location” are the most significant predictors of price.  
                    - “Multicollinearity” between certain numerical variables was addressed using VIF.  
                    - The final model explains a substantial portion of price variance (high “Adjusted R²”).  
                    - Residual analysis confirmed good model fit and minimal bias.


                                            Model Performance Summary
                                | Metric |                   Description |                   Value |

                                | R² |                     Variance explained by model |     0.82 |
                                | Adjusted R² |            Adjusted model performance  |     0.80 |
                                | RMSE |                   Root Mean Squared Error     | ~120,000 |
                                | P-values |               Statistical significance    | < 0.05 for key predictors |

