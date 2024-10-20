## Student Dropout Analysis and Academic Prediction
### A data-driven approach to predict and understand student dropout patterns
#### Introduction
This project analyzes key factors that impact student dropout rates using statistical tests and correlation analysis. If you’re looking to understand how student performance, demographics, and financial status influence dropout risk, this repository will guide you through how we uncovered significant patterns using Python, ANOVA, and data visualization.
#### Project Overview
This project analyzes factors influencing student dropout rates and academic outcomes using statistical methods. The study focuses on key variables such as admission grades, first and second-semester grades, age at enrollment, and debtor status to identify students at risk of dropping out, graduating, or remaining enrolled. It combined correlation analysis, hypothesis testing, and ANOVA to answer three critical questions:
* Does Admission Grade affect dropout rates?
*	How do 1st Semester and 2nd Semester Grades influence student success or failure?
*	What demographic factors, like Age at Enrollment or Debtor Status, impact dropout?
#### Dataset
The dataset includes anonymized records of students' academic performance and demographic information. Key features of the dataset are:
*	Admission Grades
*	Curricular Unit Grades (1st and 2nd Semesters)
*	Age at Enrollment
*	Debtor Status
*	Previous Qualification Grades
*	Target (Dropout, Graduate, Enrolled)

#### Methodology
* Data Preprocessing: Cleaning the dataset to remove missing values, outliers, and irrelevant information.
* Correlation Analysis: Discovering relationships between grades, age, debtor status, and dropout rates.
* ANOVA Testing: Running statistical tests to compare the performance of students who drop out, graduate, or remain enrolled.
* Hypothesis Testing: Using p-values to determine which factors significantly impact student outcomes.
* Interpretation: Translating numbers into meaningful insights to inform interventions for at-risk students.
#### User Instructions
Here’s how you can get this project running on your local machine:
1. Clone this repository: git clone [https://github.com/yourusername/student-dropout-risk-analysis.git](https://github.com/TimmyTonyY/STUDENT-DROPOUT-ANALYSIS)
2. Navigate to the project folder: [cd student-dropout-risk-analysis](https://github.com/TimmyTonyY/STUDENT-DROPOUT-ANALYSIS/blob/main/Forecast_Student_Dropout.ipynb)
3. Install dependencies: pip install (Pandas & NumPy, Scipy (Stats), Seaborn & Matplotlib)
4. Open the project in Jupyter Notebook: Jupyter notebook dropout_analysis.ipynb

#### Technologies Used
*	Python: For data analysis, statistical tests, and hypothesis testing.
*	Pandas & NumPy: Data cleaning, preparation, and manipulation.
*	Scipy (Stats): ANOVA testing and hypothesis evaluation.
*	Seaborn & Matplotlib: Data visualization.
*	Jupyter Notebook: Environment for running the analysis.

#### Developer Instructions
This project is built using Python and follows a systematic approach to data analysis:
1. Data Preparation:
* Used Pandas for cleaning and transforming the dataset.
* Removed missing values, handled outliers, and standardized variables.
2. Statistical Analysis:
* Conducted ANOVA tests using SciPy to check for significant differences between student groups (Dropout, Graduate, Enrolled).
* Applied correlation analysis to identify the relationship between dropout risk and other variables like grades and age.
3. Visualization:
* Created graphs and plots using Matplotlib and Seaborn to visualize.

Feel free to explore the code in dropout_analysis.ipynb to see how the analysis flows from data preprocessing to hypothesis testing.
#### Contributor Expectations
Found a bug?
* Open an issue, and let's fix it together!
*	You can also submit a pull request if you have a solution or want to add a new feature.
Want to improve the project?
* Add your insights! Feel free to tweak the analysis, suggest new statistical methods, or improve visualization clarity.
#### Known Issues
* The dataset used only covers a limited student population. Expanding the data could further generalize the results.
* The ANOVA test assumes that groups are normally distributed and have equal variances, which might not be perfect in real-world data.
#### Support the Project
If this project added value to your understanding or research, consider buying me a coffee. Your support will help me continue building meaningful analyses and tools for the data science community.
##### Buy me a coffee!!! ☕ Every cup fuels a new project!

