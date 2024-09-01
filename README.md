# HR ANALYTICS-DASHBOARD

### Dashboard Link : https://drive.google.com/file/d/1VG5hPCIq7rs2UHAUpbqXQ5Fls0x_fogY/view?usp=sharing

## Problem Statement

This HR Analytics Dashboard helps the organization better understand its employees' performance and identify areas where improvement is needed. By analyzing key metrics like employee satisfaction, productivity, and attrition rates, the dashboard allows the company to address factors leading to employee turnover. It highlights specific areas where performance is lagging and provides insights into what may be causing employee dissatisfaction or disengagement.

Through this dashboard, the organization can implement targeted strategies to boost employee morale, enhance productivity, and ultimately reduce attrition. Since a high percentage of employees may be showing early signs of disengagement, the company can use this data to foster a more supportive and motivating work environment, ensuring better retention and growth in employee performance.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for ~1400 rows so I need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present except column named "EmpID".
- Step 5 : For calculating average delay time, null values were not taken into account as only less than 1% values are null in this column(i.e column named "EmpID") 
- Step 6 : In the report view, under the view tab, theme was selected.
- Step 7 : Since the data contains various ratings, thus in order to represent ratings, a new visual was added using the three ellipses in the visualizations pane in report view. 
- Step 8 : Visual filters (Slicers) were added for fields named "Gender".
- Step 9 : Six card visuals were added i.e KPI's into the canvas, one representing total no of employee next representing attrition after that attrition rate, average salary, average age and  average year.
           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into average calculation.
           
           Although, by default, while calculating average, blank values are ignored.
- Step 10 : some bar charts was also added to the report design area representing the number of Attritions. While creating this visual, field named "Depart" was also added to the  bucket, thus number of employees are also seggregated according the department.
- Step 11 : The overall indicators of visuals are listed below,

  (a) Count of Employee

  (b) Attrition
  
  (c) Attrition Rate
  
  (d) Avg Age
  
  (e) Avg Salary
  
  (f) Avg Years 

  (g) Attrition by Education
  
  (h) Attrition by Age
  
  (i) Job Satisfaction by Rating
  
  (j)Attrition by Salary
  
  (k) Attrition Rate Based on Years of Service
  
  (l)Attrition by Job Role
  
  (m) Attrition Ratio
  
- Step 12 : In the report view, under the Attrition by Education tab, the details of employees education are listed.

![Screenshot (21)](https://github.com/user-attachments/assets/482ed44e-b48c-4c0a-8de8-a0bd4c0dc839)


- Step 13 : Attrition by age stacked column was created in which, employees were grouped into various age groups.


![Screenshot (22)](https://github.com/user-attachments/assets/5d74b33f-0f1e-48ec-9222-f59ac7948c37)
        
- Step 14 : New measure was created to check in how many year of services a employee is leaving the company, based on this  area chart is created.


![Screenshot (28)](https://github.com/user-attachments/assets/5b4f9521-0cc0-4b31-b008-bdb23554183a)

       
 - Step 15 : New measure was created to see the rating of employees of different departments to measure how much they like to work in the company (rating starts from 1 to 4).

 ![Screenshot (29)](https://github.com/user-attachments/assets/660e6d7d-8637-4558-81fb-aa59ece84bb7)

 
 
 - Step 16 : New measure was created to check the attrition numbers according to the job role of the employees.

 
![Screenshot (30)](https://github.com/user-attachments/assets/3bf47258-2140-4dfd-bf6f-ce5b59ece03c)


A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

### Total Number of Employees = 1470

   Number of Male Employees = 882

   Number of Female Employees = 588

   Number of Attritions = 237
  
  ### Attrition by salary 
  
     The data is showing that whose salaries were upto 5k they were more in numbers.

 ### Age Group
     While according to age employees whose age were in between 26 to 35 were the maximum ones.
