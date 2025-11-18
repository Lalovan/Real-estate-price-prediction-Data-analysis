# Immo Price Prediction: Data Analysis 

# 🚀 Project mission #
Immo Eliza aims to strengthen its position in the Belgian real estate market by improving the speed and accuracy of property value estimation. To support this goal, a machine learning model will be developed to predict property prices across Belgium using the dataset previously collected.

Immo Eliza hires external expertise for the full analytical workflow—from data exploration to model development. This repository documents the second stage of that process (the first stage being data scraping): a preliminary analysis intended for company management.

The objective is to provide early insights into trends and patterns within the Belgian real estate market, and to identify which property features appear most influential in determining price. The analysis lays the groundwork for building a robust predictive model in subsequent phases.

Key guiding questions of the expert are:
- What are the most interesting insights emerging from the current real estate data in Belgium?
- Which variables seem most important for predicting property prices?

# 📝 Description of the deliverable #

This deliverable provides the full first stage of Immo Eliza’s property-price prediction project, using Immoweb data from 2023. It includes a clean, analysis-ready dataset and an exploratory study designed to inform the upcoming modeling phase.

**1. Data Cleaning:** 

The raw dataset was processed to ensure reliability and consistency before any analysis. The following steps were performed:
- Removal of duplicate records
- Standardization of whitespace in all text fields
- Replacement of empty or missing values with NaN
- Correction of incorrectly encoded entries (e.g., text values in numeric columns)

This step ensures that all downstream insights and models are based on trustworthy inputs.

**2. Exploratory Data Analysis (EDA):**

After cleaning, a detailed analysis was conducted to understand the structure of the dataset and the relationships between key features. This analysis addresses:

- Total number of observations and features
- Proportion and distribution of missing values
- Identification of variables to remove and justification
- Detection of outlier-sensitive variables (skeweness analysis) and strategy to tackle the issue
- Distinction between qualitative and quantitative variables, with appropriate visualization strategies
- Correlations between and within features and property price, including interpretation
- Correlations among features themselves and identification of correlated variable groups
- Selection of the most important variables, supported by reasoning
- Comparison of the least and most expensive municipalities in Belgium, Wallonia, and Flanders (price per m², average price, median price)


The analysis is presented in Jupyter notebooks to allow transparent, interactive exploration.


# 🌳 Repo Structure #



# ⚙️ Installation and Execution #

**1. Clone the repository:**

`git clone https://github.com/kristinnuyens/immo-eliza-cats-analysis.git`

**2. Create and activate a virtual environment (optional):**

`python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate`

**3. Install dependencies:**
`pip install -r requirements.txt`

# 🧑‍💻 Constributors #

- Kristin Nuyens
- Nancy Van den Steen
- Bryan Maina
- Anna Lalova

# ⏰ Timeline #

5 working days