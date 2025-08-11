# -Exploratory-Data-Analysis-EDA-
Analysis of the Titanic dataset to find factors affecting passenger survival using data cleaning, EDA, and visualizations.
Got it — you want a **README.md** specifically for **Task 5 (Titanic dataset)** that explains what you did in your project.
##  Project Overview
This project focuses on analyzing the Titanic dataset to understand the factors that influenced passenger survival. Using Python and data analysis libraries, I explored, cleaned, and visualized the data to identify patterns and insights.
##  Dataset
* **Source:** Titanic dataset (Kaggle)
* **Columns include:**
  * PassengerId
  * Survived (Target)
  * Pclass
  * Name
  * Sex
  * Age
  * SibSp
  * Parch
  * Ticket
  * Fare
  * Cabin
  * Embarked
## 🛠 Tools & Technologies Used
* Python
* Pandas – Data cleaning & analysis
* NumPy – Numerical computations
* Matplotlib & Seaborn – Data visualization
* Jupyter Notebook – Development environment
##  Steps Completed
1. **Loaded Dataset** into Pandas DataFrame.
2. **Checked for Missing Values** and handled them appropriately (Age, Cabin, Embarked).
3. **Converted Categorical Data** into numerical format (e.g., Sex, Embarked).
4. **Exploratory Data Analysis (EDA)**:
   * Passenger survival rate by gender.
   * Survival rate by passenger class.
   * Age distribution and survival.
5. **Visualized Data** using Seaborn and Matplotlib.
6. **Correlation Analysis** between features and survival.
7. **Insights Documentation** with key findings.
##  Key Insights

* Female passengers had a much higher survival rate than males.
* Passengers in higher classes (Pclass 1) had better chances of survival.
* Younger passengers had a slightly higher survival rate.

## Sample Visualizations

* Survival rate by gender (Bar plot)
* Age distribution (Histogram)
* Survival rate by passenger class (Bar plot)

## 🚀 How to Run This Project

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/titanic-analysis.git
   ```
2. Install dependencies:

   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Open Jupyter Notebook and run:

   ```bash
   jupyter notebook Titanic_Analysis.ipynb
   ```
