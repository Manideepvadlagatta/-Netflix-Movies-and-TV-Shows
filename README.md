# -Netflix-Movies-and-TV-Shows
Data cleaning and data preprocessing of  Netflix Movies and TV Shows
## 📖 Overview
This project demonstrates **cleaning and preprocessing** the Netflix Titles dataset using Python and pandas. The dataset contains information about Netflix movies and TV shows, including **titles, directors, cast, country, date added, rating, duration, and type**.

The aim is to make the dataset **consistent, clean, and ready for analysis**, so it can be used for **exploratory data analysis (EDA), visualization, or machine learning projects**.

---

## 🔧 Features / Cleaning Steps

1. **Handling Missing Values**  
   - `director` and `cast` → filled with `"Unknown"`  
   - `country` → filled with `"Not Specified"`  
   - `rating` → filled with `"Not Rated"`  
   - `duration` → filled with `"Not Specified"`  

2. **Date Formatting**  
   - Converted `date_added` from `"Month Day, Year"` → `"MM-DD-YYYY"`  
   - Backfilled missing dates to ensure consistency  

3. **Data Standardization**  
   - Standardized `type` and `country` columns with **title case** and removed extra spaces  

4. **Removing Duplicates**  
   - Dropped duplicate rows to ensure uniqueness
💻 Technologies Used

Python 3.x

pandas

Jupyter Notebook

✅ Outcome

Fully cleaned and preprocessed Netflix Titles dataset

Ready for EDA, visualization, or machine learning

Improves data quality for meaningful insights

👤 Author

Manideep Vadlagatta

B.Tech CSE (AIML Specialization)

Enthusiast in data cleaning, analysis, and machine learning projects
