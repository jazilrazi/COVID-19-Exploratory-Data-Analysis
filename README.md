🦠 COVID-19 Exploratory Data Analysis

Exploratory Data Analysis (EDA) project analyzing global COVID-19 data to understand the spread of the pandemic, cases, deaths, testing, vaccination progress, and differences between countries and continents.

📌 About the Project

This project performs Exploratory Data Analysis (EDA) on the Our World in Data (OWID) COVID-19 dataset.

The dataset contains daily COVID-19 information for countries around the world, including:

COVID-19 cases
COVID-19 deaths
Testing
Vaccination
Population
Demographic information
Health-related indicators
Government response indicators
Excess mortality

The main goal of this project is to identify patterns, trends, relationships, and unusual values in the COVID-19 data.

📊 Dataset

Dataset: owid-covid-data.csv

The dataset contains country-level daily observations.

Main Information Included
🌍 Country and continent
📅 Date
🦠 Total and new COVID-19 cases
⚰️ Total and new deaths
🧪 Testing information
💉 Vaccination information
📈 Reproduction rate
🏥 Hospital and healthcare indicators
👥 Population information
💰 GDP per capita
🧓 Age-related demographic information
❤️ Health indicators
📊 Human Development Index
📉 Excess mortality
🎯 Project Objectives
Understand the structure of the COVID-19 dataset
Clean and preprocess the data
Handle missing values
Remove duplicate records
Convert the date column into the correct format
Analyze COVID-19 cases and deaths
Compare countries and continents
Analyze vaccination progress
Identify unusual values and patterns
Study COVID-19 trends over time
Explore relationships between different variables
Create meaningful visualizations
Extract useful insights from the data
🧹 Data Cleaning

The following data-cleaning steps were performed:

Checked dataset shape and structure
Checked missing values
Filled missing values in:
total_cases
new_cases
total_deaths
new_deaths
Removed columns with a high percentage of missing values related to ICU and hospital admissions
Filled country-level information using values from the same country
Converted date from text to datetime format
Cleaned column names
Checked for duplicate rows
Removed duplicate records
🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
🔍 EDA Process
Data Loading
      ↓
Data Inspection
      ↓
Missing Value Analysis
      ↓
Data Cleaning
      ↓
Duplicate Analysis
      ↓
Data Type Conversion
      ↓
Descriptive Statistics
      ↓
Univariate Analysis
      ↓
Bivariate Analysis
      ↓
Outlier / Unusual Value Analysis
      ↓
Correlation Analysis
      ↓
Data Visualization
      ↓
Insights & Findings
📈 Analysis & Visualizations

The project explores:

COVID-19 case trends
Death trends
Cases and deaths by continent
Cases and deaths by country
Vaccination progress
Testing statistics
Population-related comparisons
COVID-19 trends over time
Distribution of numerical variables
Relationships between COVID-19 indicators
Correlation between selected variables
Unusual and extreme values
📁 Project Structure
covid-19-eda/
│
├── COVID-19 Vaccine Efficacy.ipynb
├── owid-covid-data.csv
└── README.md

If the dataset is not included in the repository because of file size or distribution restrictions, you can provide the dataset source instead.

🚀 How to Run
1. Clone the Repository
git clone https://github.com/yourusername/covid-19-eda.git
2. Open the Project
cd covid-19-eda
3. Install Required Libraries
pip install pandas numpy matplotlib seaborn jupyter
4. Start Jupyter Notebook
jupyter notebook

Open the project notebook and run the cells.

💡 Key Areas Explored
🦠 COVID-19 Cases

Analysis of total cases, new cases, and cases per population.

⚰️ COVID-19 Deaths

Analysis of total deaths, new deaths, and death-related indicators.

💉 Vaccination

Exploration of vaccination progress, fully vaccinated people, boosters, and vaccination rates.

🧪 Testing

Analysis of total tests, new tests, testing rates, and positive rates.

🌍 Country & Continent Analysis

Comparison of COVID-19 statistics across different countries and continents.

📅 Time-Series Analysis

Analysis of how COVID-19 cases, deaths, and vaccinations changed over time.

📊 Health & Demographic Analysis

Exploration of relationships between COVID-19 data and population, age, GDP, life expectancy, healthcare facilities, and other indicators.

📌 Project Goal

The main goal of this project is to use Exploratory Data Analysis to understand global COVID-19 patterns and discover meaningful trends and relationships within the dataset.

👨‍💻 Author

Jazil

Data Science | Python | SQL | Machine Learning | Data Analytics

⭐ If you find this project useful, consider giving the repository a star!
