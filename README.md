# World Happiness Visualization

This project visualizes and analyzes data on world happiness and various related factors using dimensionality reduction and clustering techniques. It was developed as a course project for Visualization (B.Inf.1240) at the University of Göttingen.

The **analysis** combines multiple datasets:

    World Happiness Report scores and rankings
    Causes of death statistics
    Internet usage
    GDP per capita
    Population
    Temperature change

The data covers 2006-2018 for over 150 countries.


**Methods**

The following key methods were utilized:

    Data Cleaning: Handling missing values, transforming formats, merging datasets
    Dimensionality Reduction: Using UMAP to reduce the dimensionality for visualization
    Clustering: Applying K-means clustering to group countries by happiness and related factors
    Visualization: Creating a 3D interactive plot with Plotly to explore the UMAP projection and clusters
