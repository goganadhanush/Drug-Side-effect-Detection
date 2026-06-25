# Drug Side Effects Detection Model

## Project Overview

This project focuses on analyzing a pharmaceutical dataset containing information about drugs, their associated side effects, user reviews, and the medical conditions they are prescribed to treat. The objective was to extract meaningful insights, identify patterns, and explore relationships between drugs, side effects, and medical conditions using data analysis and machine learning techniques.

## Data Preprocessing

### Data Selection

* Removed irrelevant attributes such as **CSA**, **drug_link**, and **medical_condition_url** to improve data quality and reduce redundancy.
* Handled missing values and standardized binary attributes for consistent analysis.

### Data Cleaning

* Tokenized the **medical_condition_description** column using the **NLTK** library.
* Cleaned and processed textual data in the **side_effects** column.
* Performed data transformation and standardization to prepare the dataset for analysis and modeling.

## Exploratory Data Analysis

### Dataset Information

* Final dataset size after preprocessing: **2,931 records** and **14 attributes**.

### Key Findings

* Analyzed the distribution of unique drugs and medical conditions.
* Explored features such as **Rx/OTC status**, **pregnancy category**, **alcohol interaction**, and other drug-related attributes.
* Utilized various visualization techniques including:

  * Bar Charts
  * Pie Charts
  * Line Graphs
  * Scatter Plots
  * Correlation Heatmaps
* Applied the **Apriori Algorithm** to identify associations and relationships among drugs.
* Implemented **Decision Tree Classification** for predictive analysis.
* Performed **Clustering** to group drugs with similar characteristics and side-effect profiles.

## Results and Conclusion

The project successfully demonstrated the application of data preprocessing, exploratory data analysis, association rule mining, classification, and clustering techniques on a pharmaceutical dataset. The analysis provided valuable insights into drug characteristics, side effects, and treatment patterns, helping to better understand relationships within pharmaceutical data and supporting data-driven decision-making.

## Technologies and Libraries Used

* Pandas
* NLTK
* Matplotlib
* Seaborn
* Scikit-learn
