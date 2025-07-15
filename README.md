🦠 COVID-19 Indian States Clustering
A data science project that performs clustering on Indian states based on COVID-19 statistics using K-Means clustering algorithm.

📌 Objective
To group Indian states into clusters based on similar patterns in:
- Confirmed COVID-19 cases
- Number of deaths
- Number of recoveries

This helps identify regions with similar severity and spread, which can support planning and health resource allocation.

📁 Dataset

A sample dataset (`covid_19_india.csv`) is included with the following columns:

| State        | Confirmed | Deaths | Recovered |
|--------------|-----------|--------|-----------|
| Maharashtra  | 6600000   | 140000 | 6400000   |
| Kerala       | 5000000   | 50000  | 4800000   |
| ...          | ...       | ...    | ...       |

You can update this dataset with real-time data from official government or health APIs.

🛠️ Technologies Used

- PythoN 
- Pandas
- Matplotlib & Seaborn 
- Scikit-learn (KMeans)
- StandardScaler for data normalization

📊 Clustering Algorithm

The project uses **K-Means clustering** to group the states into `k=3` clusters:
- Cluster 0: Low impact
- Cluster 1: Medium impact
- Cluster 2: High impact

🚀 How to Run

1. Clone the repository:

   git clone https://github.com/Samyuktha162005/COVID19_Indian_States_Clustering.git
   cd COVID19_Indian_States_Clustering

2. Install dependencies:

pip install pandas matplotlib seaborn scikit-learn

3. Run the program:
   
View the output scatter plot to see the clusters.
