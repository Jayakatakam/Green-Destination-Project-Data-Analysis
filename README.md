# Green-Destination-Project-Data-Analysis
* Project Goal: To understand the employee attrition rate and identify key factors (Age, Years at Company, Monthly Income) that influence whether employees leave the company.
 * Data Source: Employee dataset (greendestination (1) (1).csv.xlsx -   Sheet1.csv). 

* Purpose of Report: To present the findings from the data analysis and provide insights into employee attrition.
<img width="1984" height="213" alt="image" src="https://github.com/user-attachments/assets/e62aa19b-25a9-47a9-a249-a5980dcc87a7" />
 * Dataset Description: Briefly mention the type of data (employee records) and key columns (e.g., Attrition, Age, MonthlyIncome, YearsAtCompany).
<img width="2610" height="81" alt="image" src="https://github.com/user-attachments/assets/46e0cb0c-8654-458b-9bae-393fc18a05e9" />
 * Preprocessing Steps: 

  * Loading the CSV file into a Pandas DataFrame. 
  * Handling the 'ï»¿Age' column name issue (renaming to 'Age’). 
  * Converting the 'Attrition' column ('Yes'/'No') into a numerical format (1/0) for easier calculation.   
* Ensuring 'Age', 'YearsAtCompany', and 'MonthlyIncome' columns are treated as numeric types.  
 * Handling any missing values (e.g., by dropping rows with NaN for the analyzed factors).
<img width="1798" height="422" alt="image" src="https://github.com/user-attachments/assets/6211dbff-4bb7-424a-b07a-98ed2dee4f68" />
 3.1 Overall Attrition Rate
 * Finding: The overall attrition rate is 16.12\%.
 * Interpretation: This means that out of all the employees in this dataset, approximately 16.12\% have left   the company. This figure serves as a baseline for further analysis.

3.2 Impact of Age on Attrition 
* Average Age of Attrited Employees: 33.61 years * Average Age of Staying Employees: 37.56 years
<img width="2488" height="316" alt="image" src="https://github.com/user-attachments/assets/ebe0e90d-c1f8-4762-bb55-ff6ae4392f9e" />
* Analysis:  
 * Employees who leave the company tend to be younger on average. 
  * The distribution (as seen in the KDE plot for Age) shows a higher concentration of attrition among employees in their late 20s and early 30s. 
  * Implication: Younger employees might be seeking different opportunities, experiencing early career challenges, or less committed to long-term tenure.3.3 Impact of Years at Company on Attrition 
* Average Years at Company for Attrited Employees: 5.13 years
 * Average Years at Company for Staying Employees: 7.37 years
<img width="3268" height="365" alt="image" src="https://github.com/user-attachments/assets/09603ca4-6fad-426c-a701-db5be559e529" />
* Employees with shorter tenures are more prone to attrition. 
  * A significant portion of employees leaving have been with the company for 0-5 years. 
 * Implication: The early years at the company are critical for retention. This could be due to onboarding issues, lack of career progression clarity, or initial job dissatisfaction.
<img width="2879" height="184" alt="image" src="https://github.com/user-attachments/assets/93de3cad-5c83-46a2-853f-6dd46764952d" />
3.4 Impact of Monthly Income on Attrition 
* Average Monthly Income for Attrited Employees: \$4787.09
 * Average Monthly Income for Staying Employees: \$6832.74 
* Analysis:  
 * Employees with lower monthly incomes are more likely to attrite. 
  * The distribution for those who left is heavily concentrated in the lower income brackets.   * Implication: Compensation plays a significant role in employee retention, with lower-paid employees being more susceptible to leaving.
<img width="3788" height="365" alt="image" src="https://github.com/user-attachments/assets/224aa15f-0850-42f8-8c4a-de768548e203" />
 Plot 1: Distribution of Age by Attrition

<img width="746" height="81" alt="image" src="https://github.com/user-attachments/assets/9bbe9e10-e2e0-4279-83fe-832d7348b4c0" />
Plot 2: Distribution of YearsAtCompany by Attrition
<img width="953" height="81" alt="image" src="https://github.com/user-attachments/assets/1591ba61-0ea9-47ad-bdd0-c519681a14ba" />
Plot 3: Distribution of MonthlyIncome by Attrition
<img width="929" height="81" alt="image" src="https://github.com/user-attachments/assets/f70c47ce-a364-40b5-b799-c654f3f05818" />
* Summary of Key Findings: Reiterate that attrition is 16.12\% and that younger employees, those with shorter tenures, and those with lower monthly incomes are more likely to leave.
* Potential Recommendations (Based on findings):   
* For Younger Employees: Implement mentorship programs, clear career development paths, and opportunities for skill enhancement to foster engagement and growth.   

* For Newer Employees: Enhance onboarding processes, provide early feedback and support, and ensure job role clarity to improve initial satisfaction and commitment. 

  * For Lower-Income Employees: Review compensation structures, explore opportunities for salary adjustments, or offer non-monetary benefits and recognition programs to improve satisfaction and reduce financial motivations for leaving. 
 
 * Consider conducting exit interviews to gather qualitative data on specific reasons for attrition. 
      * Regularly monitor these key metrics to track the effectiveness of retention        strategies. 

<img width="3706" height="623" alt="image" src="https://github.com/user-attachments/assets/790e25cd-c2de-4aa0-a8ac-8c86c03f2c85" />
