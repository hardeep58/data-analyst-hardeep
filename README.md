# data-analyst-hardeep

# Portfolio Projects

# Council Voting Records: Data Analysis and AWS Integration

**Project Description:**  
This project involves analyzing the Council Voting Records dataset for the City of Vancouver for the years 2023 and 2024. The goal is to manage and analyze the voting patterns and decisions made by council members, ensuring data integrity, security, and generating insights through automated processes using AWS.

## Objective:  
The primary aim is to analyze voting patterns, participation rates, and decision outcomes using the dataset. Data was ingested, protected, and processed using AWS services, with key insights visualized through dashboards.

## Dataset:  
- **Columns:** Meeting Type, Vote Date, Voter Number, Agenda Description, Vote Start Date, Time, Vote Decision, and Vote Details ID.
- The dataset includes voting records for 2023 (7032 rows) and 2024 (3908 rows).

## Methodology:  
1. **Data Ingestion:**  
   The dataset was extracted from the City of Vancouver portal and uploaded to AWS S3 for storage.
   
2. **Data Protection:**  
   AWS Glue and AWS KMS were used for encrypting data at rest and managing access. IAM roles provided controlled access, ensuring only authorized personnel could access the dataset.

3. **Data Cleaning and Structuring:**  
   AWS Glue DataBrew was employed to clean and structure the dataset, filling in missing values, and transforming the data into a consistent format for analysis.

4. **Data Analysis:**  
   SQL queries were run using AWS Athena to analyze participation rates, decision trends, and voting outcomes for various agenda items.  

5. **Data Visualization:**  
   Dashboards were created in Amazon QuickSight to visualize:
   - Voting participation trends over time.
   - Voting outcomes ("In Favour" vs. "Against") across different agenda items and meetings.
   - Analysis of council members' voting behavior.

## Tools & Technologies:  
- AWS S3, AWS Glue, AWS KMS, AWS Athena, AWS QuickSight, Python.

## Deliverables:  
- Cleaned and structured Council Voting Records dataset stored in AWS S3.
- Dashboards visualizing voting trends, participation rates, and decision-making patterns.
- Automated ETL pipeline for continuous data processing and analysis.

---

## Surviving the Titanic: An Exploratory Data Analysis
**Project Description:**  
Perform an Exploratory Data Analysis (EDA) on the Titanic dataset to uncover patterns and insights related to passenger survival, analyzing various features such as age, gender, class, and fare.

**Objective:**  
Understand the factors that influenced survival during the Titanic disaster by performing statistical analysis and data visualizations.

**Dataset:**  
- Passenger ID, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Embarked

**Methodology:**  
- Data cleaning and preprocessing using Python (Pandas, NumPy)
- Descriptive statistics
- Visualizations (Histograms, Bar Charts, Heatmaps)
- Survival analysis based on gender, class, and age group

**Tools & Technologies:**  
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook

**Deliverables:**  
- Jupyter Notebook with analysis
- Presentation summarizing key insights

---

