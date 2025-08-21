# Patient Data Analysis

This project analyzes patient visit data (9,216 rows, 11 columns) from a healthcare facility.  
The focus is on patient demographics, wait times, satisfaction scores, and referral types.

## 📊 Project Goals
- Explore patient demographics and visit patterns  
- Evaluate satisfaction scores and missing ratings  
- Analyze wait times across different groups  
- Study referrals and administrative appointments  
- Build meaningful Power BI dashboards  

## 🛠 Tools & Technologies
- Power BI (Data Modeling, DAX, Visualization)  
- Excel (Initial Dataset)  
- GitHub (Documentation & Sharing)  

## 📑 Dataset Description
- **Date**: Visit date  
- **Patient Info**: ID, Gender, Age, Race, Admin flag  
- **Satisfaction Score**: Scale 1–10 (with missing values)  
- **Wait Time**: Minutes before appointment  
- **Referral Type**: By doctor / walk-in  

## ⚙️ Data Preparation Steps
1. Column profiling & null analysis  
2. Time split into AM/PM (new column `Moment`)  
3. Combine patient first name initial + last name  
4. Create Age Group & Age Bucket classifications  
5. Build separate Date table (Year, Month, Weekday/Weekend)  
6. Add calculated measures using DAX  
7. Highlight min/max values in charts  

## 📈 Key Measures (DAX)
- **Total Patients**  
- **Average Satisfaction Score**  
- **% Not Rated**  
- **Administrative vs Non-Administrative Appointments**  
- **Referred vs Walk-in Patients**  
- **Female/Male/Unknown Visits**  
- **Average Wait Time**  

## 📊 Visualizations
- KPIs (Cards): Total Patients, Average Satisfaction, Average Wait Time  
- Clustered Charts: Age Groups, Referral Types, Gender  
- Line/Area Charts: Patient visits by Year/Month  
- Heatmaps: Satisfaction & Wait Time by Race and Age Bucket  

## 🚀 Insights
- Distribution of patients across weekdays vs weekends  
- Variation in satisfaction by age/race  
- Trends of referrals vs non-referrals  
- Identification of peak & low months  

---

### 📬 Contact
If you're interested in healthcare analytics or data visualization, feel free to connect:  
- [LinkedIn](https://www.linkedin.com/in/fateme-hosseini-183aa2133/)  
- [GitHub](https://github.com/fhProgrammer777)  

