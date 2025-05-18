# Countries-Vaccination-Dataset-Analysis
This project focuses on analyzing the Countries Vaccination Dataset, which provides insights into global vaccination efforts, primarily against COVID-19. The dataset contains crucial information about vaccination trends, population coverage, and vaccine distribution patterns across various countries. Using this dataset, the project aims to uncover insights, visualize trends, and support data-driven policy-making.

the dataset have column like this  country,	iso_code	,date	,total_vaccinations	,people_vaccinated,	people_fully_vaccinated	,daily_vaccinations_raw,	daily_vaccinations	,total_vaccinations_per_hundred,	people_vaccinated_per_hundred	,people_fully_vaccinated_per_hundred	,daily_vaccinations_per_million	vaccines

**Import & Preprocessing:**

Loaded the dataset using pandas.

Inspected the shape and data types.

Checked for and handled duplicate entries.

Dropped irrelevant or redundant columns.

Replaced missing values (NaNs) with appropriate methods (e.g., forward fill, zero).

Removed duplicates based on the vaccine and country columns.

Generated descriptive statistics using data.describe().

 **Visualizations**
 
Type of COVID-19 Vaccines Used Worldwide

Top 10 Countries by Percentage of People Fully Vaccinated

Top 15 Countries by Daily Vaccinations per Million

Percentage of Fully Vaccinated People in ASEAN Countries

Daily Vaccinations per Million in ASEAN Countries

Daily Vaccinations in India

Top 5 Countries by Fully Vaccinated People per Hundred

Total Vaccinations in India Over Time

Total Vaccinations by Country

Daily Vaccinations Over Time (India)

**Machine Learning - Random Forest Regression**

Goal: Predict vaccination metrics.

Model: Random Forest Regressor

Performance:

Achieved R² Score: 0.88

Indicates a strong predictive capability of the model

**Technologies Used**

Python (Pandas, Matplotlib, Seaborn, Scikit-learn)

Jupyter Notebook

Data visualization libraries

Machine Learning (Random Forest

** Conclusion**
This project provided valuable insights into COVID-19 vaccination trends and effectiveness around the globe, with a focus on ASEAN countries and India. The predictive model adds an analytical edge for forecasting vaccination outcomes.

