
# Elite Bank Employee Demographics & Salary Analysis
This project analyzes **Elite Bank’s employee demographics and salary structure** using quantitative methods to support fair and effective HR decisions. It explores how demographic and compensation insights can guide better **recruitment**, **promotion**, and **workforce planning**.

**Project Overview**

Organizations depend on accurate HR data to ensure fairness and equity in staffing decisions. This project provides a structured analysis of employee attributes such as:

* Age distribution
* Gender representation
* Job roles
* Salary levels
* Department structure

By combining Python based data analysis with structured reporting, this project aims to uncover trends and insights that HR managers can use to improve decision making.

**Data Sources**

The primary dataset used for this analysis is the "elitebank_db.csv"which contains employee demographic and salary information extracted from Elite Bank’s internal HR system.

**Objectives**

* Identify patterns in employee demographics
* Examine how salary varies across departments and job positions
* Provide insights for improving fairness in recruitment and promotion
* Support data-driven workforce planning
* Present results in clear visual and statistical formats


 **Tools & Technologies**
* **Aiven PostgreSQL** for cloud-based data storage and extraction
* **Python** (Pandas, NumPy, Matplotlib/Seaborn)
* **SciPy and Statsmodels** for conducting inferential statistical tests such as T-tests, ANOVA, and Chi-square analyses.
* **Jupyter Notebook or Python script**
* **PDF Report** summarizing findings
* **GitHub Repository** for project tracking


**Repository Contents**

 File                               Description                                           

`my-elitebank-project.py`      Main Python analysis script    

`EliteBank_Report.pdf`         Full analysis report with visualizations and insights 

`README.md`                     Project documentation (this file)                     


**Exploratory Data Analysis**
In the initial data preparation phase, the following tasks were performed:

1. Which department pays the highest average salary?


   <img width="700" height="360" alt="final 1" src="https://github.com/user-attachments/assets/39559dc1-989f-48df-a653-e87c464b2c28" />

2. What’s the age distribution of employees?

   <img width="700" height="360" alt="final 2" src="https://github.com/user-attachments/assets/1a191de0-9bb8-4c86-aaa7-22dcb0d861d5" />

3. Are widowed employees more common in certain departments?

   <img width="700" height="360" alt="final 3" src="https://github.com/user-attachments/assets/8c405d83-1806-4913-97be-b6b9180133cf" />

4. Does higher education translate to higher pay?

<img width="700" height="360" alt="final 4" src="https://github.com/user-attachments/assets/50725e46-84af-4498-aec2-55296f7b97b4" />

   
5. Which state contributes the most employees?

<img width="700" height="360" alt="final 5" src="https://github.com/user-attachments/assets/8c14eb36-7211-46d7-a37e-a915efd9d5ee" />

   
6. Do male and female employees earn significantly different salaries?

   <img width="1102" height="360" alt="final 6" src="https://github.com/user-attachments/assets/c7872348-4031-485b-a1f2-80b1e9285461" />

7. Is there a significant difference in average salary across departments?
   
<img width="1102" height="360" alt="final 7" src="https://github.com/user-attachments/assets/28269c8d-3f6a-4bb3-8aa7-8f0ffc8aaffe" />

   
8. Is there a relationship between marital status and department allocation?

<img width="1087" height="360" alt="final 8" src="https://github.com/user-attachments/assets/86bed4be-fa7a-4d9a-9cb0-a328f1d7b6af" />

 **Key Insights**

* Distribution of employees across age and gender
* Salary comparisons across job roles
* Department level demographic patterns
* Correlation between employee attributes and compensation


**Recommendations**
Based on the analysis, the following actions are recommended:
- More employees should be hired from regions that are currently underrepresented.
- Development of leadership and mentorship programs to prepare young staff for future roles.
- Salaries in lower paid departments should be reviewed regularly to keep employees motivated. 
- The bank should create strong retention strategies, especially for important departments like IT, HR, and Marketing.


 **How to Run the Script**

1. Download the repository
2. Install required Python libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Run the Python script:

   ```bash
   python my-elitebank-project.py
   ```



 **Contributing**

Contributions, suggestions, and improvements are welcome.


**Contact**

If you have questions or feedback, feel free to reach out via GitHub.
