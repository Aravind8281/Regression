1. **Mean Squared Error (MSE):**
   - Calculates the average of the squared differences between predicted and actual values.
   - Larger errors contribute more to the overall error.
   - The formula for MSE is:
     \[ MSE = \frac{1}{n} \sum_{i=1}^{n} (y_i - \hat{y}_i)^2 \]

2. **Mean Absolute Error (MAE):**
   - Calculates the average of the absolute differences between predicted and actual values.
   - Treats all errors equally, regardless of magnitude.
   - The formula for MAE is:
     \[ MAE = \frac{1}{n} \sum_{i=1}^{n} |y_i - \hat{y}_i| \]

3. **Root Mean Squared Error (RMSE):**
   - The square root of the mean squared error.
   - Provides an interpretable scale because it's in the same units as the target variable.
   - The formula for RMSE is:
     \[ RMSE = \sqrt{MSE} \]

4. **R-squared (R2) Score:**
   - Measures the proportion of the variance in the dependent variable that is predictable from the independent variables.
   - Ranges from 0 to 1, where 1 indicates a perfect fit.
   - The formula for R2 is:
     \[ R^2 = 1 - \frac{\sum_{i=1}^{n} (y_i - \hat{y}_i)^2}{\sum_{i=1}^{n} (y_i - \bar{y})^2} \]
     where \(\bar{y}\) is the mean of the target variable.

5. **Mean Squared Logarithmic Error (MSLE):**
   - Measures the average of the logarithmic differences between predicted and actual values.
   - Particularly useful when the target variable spans multiple orders of magnitude.
   - The formula for MSLE is:
     \[ MSLE = \frac{1}{n} \sum_{i=1}^{n} (\log(1 + y_i) - \log(1 + \hat{y}_i))^2 \]

6. **Mean Bias Deviation (MBD):**
   - Measures the average relative difference between predicted and actual values.
   - Positive values indicate overestimation, and negative values indicate underestimation.
   - The formula for MBD is:
     \[ MBD = \frac{1}{n} \sum_{i=1}^{n} \frac{y_i - \hat{y}_i}{y_i} \times 100\% \]

7. **Explained Variance Score:**
   - Measures the proportion to which the model explains the variance of the target variable.
   - Ranges from 0 to 1, where 1 indicates a perfect explanation.
   - The formula for explained variance is:
     \[ \text{Explained Variance} = 1 - \frac{\text{Var}(y - \hat{y})}{\text{Var}(y)} \]
