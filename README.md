# Power BI - Data Professionals Survery
### Overview:
This project demonstrates a complete ETL (Extract, Transform, Load) process and dashboard creation in Microsoft Power BI, using a dataset of data professionals. The analysis focuses on salaries, job satisfaction, education, gender, and programming language preferences among data professionals worldwide.

### Tools & Technologies
- Power BI Desktop – for data transformation and dashboard design
- Power Query Editor – for cleaning and transforming data

### 🗂 Dataset Information
**Source**: https://github.com/AlexTheAnalyst/Power-BI/blob/main/Power%20BI%20-%20Final%20Project.xlsx

### ⚙️ ETL Process
**1️⃣ Extract**
- Imported dataset from GitHub into Power BI Desktop.

**2️⃣ Transform**
Performed several data cleaning and transformation steps in Power Query Editor:
- Adjust Rows as Headers
<img width="1297" height="273" alt="Headers Before" src="https://github.com/user-attachments/assets/57439be2-5346-4531-a0b8-c25b2bdbc5e1" />
<img width="1191" height="248" alt="Headers After" src="https://github.com/user-attachments/assets/76e74a0d-657d-420b-85ee-bade2d944800" />

- Removed unnecessary columns
<img width="1049" height="279" alt="Unwanted Columns" src="https://github.com/user-attachments/assets/d75cd18d-a2ca-444c-96f4-38cb72c1e1d5" />

- Fixed data types (e.g., Date, Time, Numeric, Text)
<img width="1200" height="247" alt="Datatype Before" src="https://github.com/user-attachments/assets/a70c203d-34fb-4f1a-9eb4-8572293b9554" />
<img width="1196" height="247" alt="Datatype After" src="https://github.com/user-attachments/assets/414bb593-d740-4bc1-bce2-5507a32cc689" />

- Split columns where needed (e.g., Other(Please Specify))
<img width="1122" height="354" alt="split columns" src="https://github.com/user-attachments/assets/7222469e-c510-4b4c-8d84-65c0b5004423" />

- Replaced Values
<img width="1024" height="402" alt="Replaced Values Before" src="https://github.com/user-attachments/assets/e60b6a49-2c88-4719-827d-a1325f84c3e5" />
<img width="1029" height="405" alt="Replaced Values After" src="https://github.com/user-attachments/assets/fcf4c89b-042a-4e2d-8922-629753f65c87" />


**3️⃣ Load**
- Loaded the cleaned and transformed dataset into Power BI for visualization.

### 📈 Dashboard Insights
#### Key Insights:
- **Top Countries**: Most survey takers were from the United States and India.
- **Highest Salary**: Data Scientists earn the highest average salary among all roles.
- **Job Difficulty**: ~43% of professionals found it neither easy nor difficult to break into data.
- **Programming Language**: Python is the most preferred programming language.
- **Job Satisfaction**: Average happiness:
  - **Work/Life Balance** – 5.74 / 10
  - **Salary** – 4.27 / 10
- **Total Respondents**: 630
- **Average Age**: 29.87 years

### Dashboard Preview
<img width="1126" height="662" alt="dashboard" src="https://github.com/user-attachments/assets/02538c89-b49b-445f-8fb7-01712f8e9e46" />
