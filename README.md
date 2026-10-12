# SQL
## 🎓 “CampusConnect – Student Placement and Salary Management System”
Scenairo:
CampusConnect is a college placement management system designed to manage student information, company recruitment activities, job opportunities, placement records, and salary packages.
The college collaborates with multiple companies that visit the campus to recruit eligible students from different departments.
Each company offers different job roles, salary packages, eligibility criteria, and vacancies.

 ## The system maintains information about the following 6 important tables:

● Students

● Companies

● Jobs

● Placements

● Salary Packages 

## 1.👨‍🎓 Students

The college stores personal and academic information for every student to identify eligible candidates for campus recruitment.

 ## The system stores the following information:

● Student ID

● Student Name

● Gender 

● Age 

● Phone 

● Email

● Department 

● Graduation Year 

● CGPA

## 2. 🏢 Companies 

The system stores information about companies that participate in campus recruitment and offer employment opportunities to students.

## The system stores the following information:

● Company ID

● Company Name

● Industry

● Company Location 

● HR Contact Person

● Contact Email

## 3.💼 Jobs

Companies offer different job opportunities to students based on their qualifications, academic performance, and skills.

## The system stores the following information:

● Job ID 

● Company ID 

● Job Role 

● Minimum Required CGPA

● Job Location

● Minimum Salary

● Maximum Salary

● Number of Vacancies

## 4.🎯 Placement Drives

The college organizes placement drives where companies conduct interviews, aptitude tests, technical assessments, and other selection rounds to recruit eligible students.

## The system stores the following information:

● Drive ID 

● Company ID 

● Job ID 

● Drive Date 

● Registration Deadline

● Selection Process

● Drive Status

## 5. 🤝 Placements

The system records the placement details of students who participate in recruitment drives. It tracks whether students are selected, whether they accept their offers, and when they are expected to join the company.

## The system stores the following information:

● Placement ID

● Student ID

● Company ID

● Job ID

● Drive ID

● Selection Date

● Placement Status

● Offer Acceptance Status

● Joining Date

## 3.💰 Salary Packages

The system maintains salary information for students who receive job offers from companies. It helps the college compare salary packages and identify the highest-paying companies and job roles.

## The system stores the following information:

● Salary ID

● Placement ID

● Annual CTC

● Basic Salary

● Bonus

● Joining Bonus

● Offer Year

## 🎯 Project Objectives

 ## 🎓The main objectives of the CampusConnect Student Placement and Salary Management System are:

## 🏢To maintain students' personal and academic information.

## 📋To store company details and job opportunities.

## 🤝To identify students eligible for different job openings based on CGPA.

## ✅To manage placement drives and recruitment activities.

## 💰To track student selection and offer acceptance status.

## 📊To maintain and compare salary packages.

## 📈To identify the highest and average salary packages.

## 🏆To analyze department-wise placement performance.

## 🏆To identify companies offering the highest salaries.

## 📊To generate useful placement reports using SQL queries.



## 🎓 CampusConnect Student Placement & Salary Analytics – SQL Business Analysis Question Bank.



## 👨‍🎓 Student Profile & Academic Performance.


1. Which students have the highest CGPA in each respective department?

2. How many students are registered in the placement portal in total?

3. What is the total number of students belonging to each academic department?

4. Find the total count of students grouped by their graduation year.

5. List all details of students whose age is greater than the average age of all students.

6. Categorize students into 'High' (CGPA \(\ge \) 8.5), 'Medium' (6.5 to 8.4), and 'Low' (Below 6.5) performance tiers using a CASE statement.

7. Find the students who have not received any placement offers using a LEFT JOIN where the placement ID is NULL.


## 🏢 Corporate Partnership & Job Market Insights.


1. Which companies offer the highest total number of vacancies?

2. What is the distribution of companies across different industry sectors?

3. Which job locations (cities) have the highest number of available job roles?

4. Find the specific job roles that offer the absolute highest maximum salary packages.

5. Calculate the average minimum and maximum salary offered within each industry segment.

6. Rank the companies based on the total number of distinct job roles they are offering on campus.

7. Identify the companies that have the highest number of vacancies listed for a single job role.

  
## 📅  Recruitment Drive Efficiency.


1. How many placement drives were organized/performed each month?

2. What is the monthly timeline trend of scheduled recruitment drives?

3. Which placement drives have a status marked as 'Completed' versus 'Pending'?

4. Find the recruitment drives whose registration deadline has already passed based on the current date.

5. Identify drives that select students based on a specific process structure (e.g., 'Aptitude Test + Technical Interview')

6. Find the companies that scheduled a drive but have zero total student vacancies listed under their jobs.


## 💼 Placement Success & Status Tracking.


1. How many students were successfully selected by each participating company?

2. Which students have received multiple distinct job placement offers?

3. What percentage of students participating in placement drives were successfully placed?

4. Which students have accepted their placement offers (where Offer Acceptance Status = 'Accepted')?

5. Find the total number of students placed versus those whose final selection status is still pending.

6. Calculate the average number of days taken between the Selection Date and the formal Joining Date.

7. * Find the company that hired the highest number of female students to analyze diversity hiring trends.
  
  
## 💰Salary Package & Compensation Analytics.

1. What is the highest, lowest, and average annual salary package (Annual CTC) offered to students?

2. Which specific companies offer the highest overall salary packages?

3. Which job roles offer the highest average annual salary across the campus?

4. Which students have received salary packages strictly above the premium threshold of ₹6 LPA?

5. What is the total breakdown of extra compensation (Basic Salary vs. Bonus vs. Joining Bonus) given to placed candidates?

6. Which graduation offer year had the highest average salary package payouts?

7. Which graduation offer year had the highest average salary package payouts?


## 🚀Advanced Placement SQL Operations (Complex Joins & Subqueries)

1. Create a consolidated database view showing complete student profiles, their hired company name, job role, and final annual CTC.

2. Write a subquery placed inside a FROM clause to find the average salary of departments with high placement counts.

3. Demonstrate a CROSS JOIN operation between the Students table and the Companies table to generate a master eligibility matrix.

4. Find the top 3 highest-paid students in each department using ranking window functions (DENSE_RANK).

5. List all jobs where the maximum salary is higher than the average maximum salary across all available campus job postings using a subquery.

6. Identify the "Star Recruiter" company that has selected the highest total number of students across all departments combined.

7. Find the percentage of placed students out of total registered students grouped by gender to analyze placement distributions.


## 🎯 Project Conclusion

The CampusConnect Student Placement & Salary Management System SQL project provides a structured framework to manage and track student profiles, corporate drives, job vacancies, and financial packages.

By linking these six core database tables, the system allows the college to easily monitor recruitment activity trends, track selection milestones, and verify student eligibility criteria.

Using SQL operations like JOINs, GROUP BY aggregations, and subqueries, the project converts raw transactional data into meaningful performance metrics. 
This analytics-driven approach helps the institution easily identify top-paying job roles, evaluate department-wise placement success rates, and discover key corporate trends to systematically improve future campus placement outcomes.


##  🎓 “CampusConnect – Student Placement and Salary Management System”

STUDENT PLACEMENT AND SALARY MANAGEMENT

                    │
                    ▼
                SQL DATABAE
│             
├── Students

├── Companies

├── Jobs

├── Placement Drives

├── Placements

└── Salary Packages

        │
        ▼
        
   DATA VALIDATION
   
        │
        ├── Duplicate Checks
        
        ├── NULL Checks
        
        ├── Primary Key Validation
        
        ├── Foreign Key Validation
        
        ├── CGPA Validation
        
        ├── Salary Amount Validation
        
        └── Date Validation
        
        │
        ▼
        
     SQL ANALYSIS
     
        │
        ├── SELECT / WHERE
        
        ├── DISTINCT / ORDER BY
        
        ├── GROUP BY / HAVING
        
        ├── Aggregate Functions
        
        │   ├── COUNT()
        
        │   ├── SUM()
        
        │   ├── AVG()
        
        │   ├── MAX()
        
        │   └── MIN()
        
        ├── JOINS
        
        │   ├── INNER JOIN
        
        │   └── LEFT JOIN
        
        ├── CASE
        
        ├── SUBQUERIES
        
        ├── WINDOW FUNCTIONS
        
        ├── SELF JOIN
        
        └── VIEWS
        
        │
        ▼
    BUSINESS INSIGHTS
    
        │
        ├── Student Academic Insights
        
        ├── Company Recruitment Insights
        
        ├── Job Vacancy Insights
        
        ├── Department-wise Placement Insights
        
        ├── Salary Package Insights
        
        ├── Placement Success Rate
        
        └── Highest-Paying Company Analysis












  




    








































































   





















 















































