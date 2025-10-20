Global Firepower 2025: EDA and Clustering Analysis
This project conducts a comprehensive Exploratory Data Analysis (EDA) on the Global Military Firepower 2025 dataset, which includes 145 countries. The goal is to uncover insights into global military strength, spending, and strategic postures using Python, Pandas, Seaborn, Plotly, and Scikit-learn.

A key component of this project is the use of unsupervised machine learning (KMeans clustering) to segment countries into distinct military profiles based on their assets, budget, and personnel.

Key Analyses & Insights
Machine Learning (Clustering):

Applied KMeans clustering using Scikit-learn to group nations into three distinct military profiles.

Features used for clustering included 'Defense Budget', 'Total Aircraft', 'Tanks', 'Naval Fleet', and 'Active Personnel', which were preprocessed using StandardScaler.

Visualized the resulting clusters (e.g., "High-Tech/High-Budget," "High-Manpower," and "Moderate/Balanced") to identify different national strategies.

Economic & Financial Analysis:

Engineered a new feature, 'Defense % of GDP (PPP)', to identify which countries allocate the largest portion of their economy to defense (e.g., Ukraine, Israel, Paraguay).

Analyzed the correlation between defense spending and economic indicators like GDP, external debt, and oil production using scatter plots and a Seaborn heatmap.

Strategic & Geopolitical Analysis:

Power Projection: Visualized the small number of countries possessing aircraft carriers as an indicator of global power projection.

Asymmetric Warfare: Plotted 'Tanks vs. Attack Helicopters' to identify nations with an apparent focus on asymmetric capabilities (low conventional armor, high air attack).

Bloc Comparison: Aggregated and compared the total military aircraft strength of geopolitical blocs (NATO vs. BRICS).

Logistical & Infrastructural Analysis:

Identified the top 10 countries by logistical capability (serviceable airports and major ports/terminals).

Analyzed the relationship between 'Roadway Coverage' and 'Armored Fighting Vehicles' to assess potential ground mobility.

Advanced Data Visualization:

Created a Plotly choropleth map to visualize the global distribution of 'Total Naval Fleet' assets.

Generated a wide range of plots using Matplotlib and Seaborn, including annotated bar charts (Top 10s), regional pie charts (share of spending), and multi-variable scatter plots (using hue for region).

Technologies Used
Python: Core language for analysis.

Pandas: Data loading, cleaning, manipulation, and feature engineering.

Scikit-learn (sklearn): Preprocessing (StandardScaler) and unsupervised machine learning (KMeans).

Matplotlib & Seaborn: Creating a wide range of static visualizations (bar, scatter, pie, heatmap).

Plotly Express: Generating interactive geospatial (choropleth) maps.

Jupyter Notebook: For iterative analysis and presentation.
