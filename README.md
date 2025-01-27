# Zeotap Assignment: EDA, Lookalike Model, and Customer Segmentation

This repository contains my solutions for the Zeotap assignment, where I performed Exploratory Data Analysis (EDA), built a Lookalike Model, and conducted Customer Segmentation using customer, product, and transaction data. The aim was to derive insights, recommend similar customers, and segment customers for business strategies.

## Tasks

### Task 1: Exploratory Data Analysis (EDA) and Business Insights
- **EDA** was performed to analyze the provided datasets, which included customer, product, and transaction data.
- Derived **5 business insights** based on the analysis:
  1. **Customer Distribution by Region**: Customers are predominantly located in [Region].
  2. **Product Popularity**: The most popular product category is [Category].
  3. **Purchase Behavior**: High-value customers tend to purchase products from [Category].
  4. **Sales Trends**: Peak transaction periods are observed during [Months/Seasons].
  5. **Customer Retention**: A significant number of customers who signed up in [Year] are still active.

#### Deliverables:
- **EDA Code**: Available in `FirstName_LastName_EDA.ipynb`
- **Business Insights**: Summary available in `FirstName_LastName_EDA.pdf`

### Task 2: Lookalike Model
- Built a **Lookalike Model** to recommend **3 similar customers** for each of the first 20 customers (CustomerID: C0001 - C0020) based on their profile and transaction history.
- The model used both **customer profile information** and **transaction history** to calculate similarity scores between customers.
  
#### Deliverables:
- **Lookalike Recommendations**: Available in `FirstName_LastName_Lookalike.csv` (top 3 lookalikes for each customer).
- **Model Code**: Available in `FirstName_LastName_Lookalike.ipynb`

### Task 3: Customer Segmentation / Clustering
- Performed **customer segmentation** using clustering techniques on both **customer profile** and **transaction data**.
- Chose **K-Means** clustering with [X] clusters for segmentation.
- Calculated the **Davies-Bouldin (DB) Index** and visualized the clusters.
  
#### Deliverables:
- **Clustering Results**: Available in `FirstName_LastName_Clustering.pdf` (DB Index and other clustering metrics).
- **Clustering Code**: Available in `FirstName_LastName_Clustering.ipynb`

## File Naming Convention
All files follow the naming convention as required:
- `FirstName_LastName_EDA.pdf` – Business Insights report for EDA
- `FirstName_LastName_EDA.ipynb` – Jupyter Notebook containing EDA code
- `FirstName_LastName_Lookalike.csv` – CSV file containing lookalike customer recommendations
- `FirstName_LastName_Lookalike.ipynb` – Jupyter Notebook explaining the lookalike model
- `FirstName_LastName_Clustering.pdf` – PDF report on customer clustering results
- `FirstName_LastName_Clustering.ipynb` – Jupyter Notebook for clustering code

## Repository Structure

- **/EDA**: Contains code and analysis related to the EDA task.
- **/Lookalike**: Contains code for building the Lookalike Model and recommendations.
- **/Clustering**: Contains code for customer segmentation and clustering analysis.
- **/Reports**: Contains the PDF reports for EDA and Clustering tasks.


## Submission
The project is submitted as per the guidelines in the repository, containing all the required files with the correct naming convention.

Good luck with the assignment!
