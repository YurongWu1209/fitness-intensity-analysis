# Exercise Biometrics Analysis 🏃‍♂️📊

This is a mini data science project focused on exploring the relationship between exercise duration, personal physical attributes (Age, Weight, Sex), and physiological responses (Heart Rate).

## Repository Structure
* `analysis.ipynb`: The core Kaggle Notebook containing data visualization and correlation analysis.
* `test.csv`: The dataset utilized for this analysis.
* `README.md`: Project overview and key summaries.

## Technologies Used
* **Python 3**
* **Pandas**: For data manipulation and summary metrics.
* **Seaborn & Matplotlib**: For statistical data visualization (`lmplot` and `heatmap`).

## Key Findings & Conclusion
* **Strong Positive Correlation**: A prominent correlation coefficient of **0.88** was observed between exercise duration and heart rate, demonstrating that workout length is the primary driver of heart rate acceleration.
* **Negligible Biological Impact**: Personal biological factors such as `Age` (0.017) and `Weight` (-0.0042) showed near-zero correlation with working heart rate.
* **Gender Consistency**: The upward trajectory of heart rate over time remains highly consistent across both male and female groups.
