### Customer Personality Segmentation
# Customer Personality Segmentation
## Business Context

This project applies unsupervised machine learning to segment customers based on their demographics, lifestyle, and purchasing behavior. By understanding the unique traits of each segment, businesses can design personalized marketing strategies, improve customer retention, and allocate resources more effectively.
Understanding customer personality and behavior is pivotal for businesses to enhance satisfaction and increase revenue. Segmentation based on demographics, personality traits, and purchasing behavior allows companies to:

### Project Overview
- Design personalized marketing campaigns

The dataset used contains customer demographic details (age, income, family structure), lifestyle indicators, and purchase data across multiple product categories.
- Improve customer retention

#### The workflow includes:
- Optimize product offerings and resource allocation

Data exploration and cleaning – checking for missing values, outliers, and inconsistent entries.
A leading retail company with a growing customer base seeks deeper insights into customer profiles. By analyzing personality traits, lifestyles, and purchasing habits, the company can move away from generic strategies and sustain a competitive edge through targeted and personalized approaches.

Feature engineering – encoding categorical features, scaling numerical variables, and creating meaningful derived features.
## Objective

Clustering – applying K-Means and determining the optimal number of clusters using evaluation methods such as the elbow method and silhouette score.
The goal of this project is to identify distinct customer segments using unsupervised machine learning. Specifically, the project aims to:

Cluster profiling – analyzing the unique characteristics of each cluster in terms of income, spending habits, product preferences, and preferred purchase channels.
- Develop personalized marketing strategies to increase conversion rates

Visualization – creating plots to make cluster insights more interpretable for business users.
- Design effective retention strategies for high-value customers

#### Repository Structure
- Optimize pricing, promotions, and inventory planning

Learner_Notebook_Full_Code_Version_Customer_Personality_Segmentation.ipynb — full notebook containing EDA, preprocessing, clustering, and insights.
- Provide actionable insights into customer behaviors and preferences

data/ (optional) — place your dataset here.
## Dataset & Data Dictionary

README.md — documentation for the project.
The dataset contains customer demographics, personality traits, purchasing behaviors, and marketing campaign responses.

#### Features
### Customer Information

Exploratory Data Analysis: statistical summaries, visualizations of demographics and purchases.
- ID: Unique customer identifier

Preprocessing: handling missing values, feature scaling, categorical encoding.
- Year_Birth: Year of birth

Clustering: K-Means clustering with evaluation metrics for choosing the optimal K.
- Education: Education level

Profiling: descriptive analysis of clusters to interpret actionable business insights.
- Marital_Status: Marital status

Visualization: plots for demographics, purchase categories, and cluster distributions.
- Income: Household income

#### Installation
- Kidhome: Number of children

Clone this repository and install the required dependencies:
- Teenhome: Number of teenagers

git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
- Dt_Customer: Date joined the company

- Recency: Days since last purchase

If a requirements.txt file is provided:
- Complain: Complaint in the last 2 years (1 = Yes, 0 = No)

pip install -r requirements.txt
### Spending (Last 2 Years)

MntWines, MntFruits, MntMeatProducts, MntFishProducts, MntSweetProducts, MntGoldProds: Amount spent on each product category

Otherwise, install manually:
### Campaigns & Response

pip install pandas numpy matplotlib seaborn scikit-learn jupyter
- NumDealsPurchases: Purchases with discounts

- AcceptedCmp1 to AcceptedCmp5: Response to prior campaigns

- Response: Response to last campaign

### Shopping Behavior

- NumWebPurchases: Purchases via website

- NumCatalogPurchases: Purchases via catalog

- NumStorePurchases: Purchases in stores

- NumWebVisitsMonth: Website visits last month

### Tools & Technologies

- Python (core language)

- Jupyter Notebook (development environment)

- Pandas, NumPy (data cleaning and manipulation)

- Matplotlib, Seaborn (data visualization)

- Scikit-learn (K-Means clustering, scaling, evaluation metrics)

- Git & GitHub (version control, portfolio hosting)

## Workflow

#### Usage
1. Exploratory Data Analysis (EDA):

Open Jupyter Notebook:
- Demographic distributions (age, income, family structure)

jupyter notebook
- Purchase behavior across product categories

- Channel usage (store, catalog, online)

Run the notebook Learner_Notebook_Full_Code_Version_Customer_Personality_Segmentation.ipynb.
2. Data Preprocessing:

Step through each cell to replicate the analysis, clustering, and results.
- Handling missing values and outliers

#### Results
- Feature scaling (StandardScaler)

The clustering analysis produced distinct customer segments that differ in:
- Encoding categorical features

Demographics: age groups, family structures, and income levels.
3. Clustering with K-Means:

Product preferences: spending across categories such as wine, fruits, meat, fish, sweets, and gold.
- Determined optimal k using the elbow method & silhouette score

Shopping behavior: preferred purchasing channels (store, catalog, online).
- Segmented customers into distinct groups

#### Business Implications:
4. Cluster Profiling & Visualization:

High-income, high-spending customers may be targeted with premium product promotions.
- Compared segments across demographics, spending habits, and purchase channels

Younger, digital-savvy customers can be approached with online campaigns.
- Created visual profiles to explain actionable insights

Price-sensitive clusters can be retained through loyalty discounts and catalog promotions.
## Results

- Segmentation revealed 3–5 distinct customer groups with clear differences in income, product preferences, and channel usage.

- High-income clusters spend heavily on wine and gold products → targeted for premium campaigns.

- Mid-income, family-heavy clusters purchase more daily essentials (meat, fruits) → suited for discount offers and loyalty programs.

- Online-focused customers showed higher engagement in digital channels → candidates for email and web campaigns.

## Next Steps

- Apply alternative clustering techniques (DBSCAN, hierarchical clustering) for comparison

- Perform why-analysis to investigate factors behind differences (e.g., why certain segments spend more on specific categories)

- Build a dashboard (e.g., Power BI or Streamlit) for interactive segmentation insights

- Integrate predictive modeling to forecast customer lifetime value (CLV)

## How to Use

#### 1. Clone the repository:

git clone https://github.com/<your-username>/Customer-Personality-Segmentation.git
cd Customer-Personality-Segmentation


#### 2. Install dependencies:

pip install pandas numpy matplotlib seaborn scikit-learn jupyter

### Next Steps

Experiment with other clustering methods (DBSCAN, hierarchical clustering) to validate results.
#### 3. Run the notebook:

Automate the preprocessing and clustering steps into a reusable pipeline.
- jupyter notebook Learner_Notebook_Full_Code_Version_Customer_Personality_Segmentation.ipynb

Build a Streamlit/Flask app or Power BI dashboard to present insights interactively.
#### 4. Step through each section to reproduce the analysis and clustering results.
