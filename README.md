# Country_Clusters
This project involves exploratory data analysis and clustering of countries around the world based on different socio-economic factors. The aim of the project is to identify patterns and correlations that may exist among countries and to explore how these countries cluster together based on these factors.

Key features of the dataset include a variety of economic indicators, geographical data, and demographic statistics such as GDP per capita, population density, literacy rates, and more. This data was processed, explored, and visualized using Python libraries including pandas, seaborn, matplotlib, and plotly.

The project primarily employs the KMeans algorithm from scikit-learn, one of the most common clustering methods in data science. To decide on the optimal number of clusters, the project utilizes the Elbow method, which involves plotting the explained variation as a function of the number of clusters and picking the "elbow" of the curve as the number of clusters to use.

Finally, the results are visualized using a geographical choropleth map, highlighting the clustering of countries. The clusters appear to differentiate mainly along the lines of wealth, providing an interesting perspective on the global distribution of socio-economic conditions.

This project demonstrates the application of data preprocessing, exploratory data analysis, clustering, and data visualization in a real-world context. It provides a basis for further exploration and refinement, such as using different clustering algorithms, incorporating more features, or applying predictive modeling techniques.
