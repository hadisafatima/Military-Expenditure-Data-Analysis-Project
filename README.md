# Military_Expenditure_Data_Analysis_Project_Documentation

### Project: 
Military Expenditure Analysis (1960 - 2018)

---

### Author:
Hadisa Fatima Syed (Role: Data Analysis Enthusiast and BE Software Student)

---

### Project Start Date:                                        ### Project End Date:
26th-June-2025                                                 Xx-xxxx-xxxx

---

### Project Overview:

---

### Objective/Problem Statement:

---

### Dataset Info:
- The cleaned dataset has 109 rows and 59 columns.
- This Dataset has 4 types Geographic Locations.

---

### Questions:
1. Which country has the highest and lowest total military expenditure so far?
2. Which country has the highest and loweset average military expenditure so far?
3.  Which type of countries has the highest expenditure?
4. which year had the highest global military spending?
6. Which country has had the most increase in spending in the last 10 years?
7. What is the trend of global spending across decades?
8. What is the total of top 5 spenders as a % of global spend?

--- 

### Tools and Technologies:
1. Google Sheets (for storing the Original and Cleaned Dataset and for performing Data Cleaning Process)
2. Google Docx (For Creating Scope of Work document and Analytical Report).
3. Tabulae (For creating Visualizations).
4. GitHub (For Doucmenting the entire project in this README.md file, documenting the growth of the project day by day by creating and managing Changelog.md file and for Uploading all the Deliverables).

---

### Data Preprocessing/Cleaning Process:
1. Calculated the Missing Values percentage per Row. If the percentage was less than or equal to 20% then those countries were kept in the dataset else were dropped.
2. Used Conditional Formatting to highlight the cells with missing value % greater than 20 and dropped the corresponded rows, i.e 154 rows out of 265.
3. Dropped 2 more rows, as they contained ‘0’ as their military expenditure for all the years. With this, there are 109 total rows left in the dataset.
4. Missing value cells were filled out using the average of known Expenditure values for each country.
5. Placed each coutries Average Expenditure values in their corresponded empty cells and that change was reflected in the Missing cells % Column.
7. After the all average values were placed, all the values in the Missing value cells % column became '0.005', therefore tht column along with Average Expenditure column was dropped.
8. The Dataset had no Duplicated Values.
9. Dropping 'Indicator Name' Column as it is just reflects the currency type which is same for all the countries, i.e USD, and this is reflected from the a specific Expenditure value of the country.

---

### EDA Summary:


---

### Visualizations:

---

### Limitations:
- Dataset was outdated
- All the countries were not included
- It had a lot of missing values

---

### Conclusion:

---

### Key Takeaways:


