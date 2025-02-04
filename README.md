# **California Obesity Data Mapping and Analysis**

## 📊 **Overview**

This project focuses on analyzing and visualizing obesity rates across California using geospatial data. The notebook leverages shapefiles to create thematic maps that highlight obesity distribution, integrating additional population data for comprehensive insights.

## 🚀 **Features**

- Interactive visualization of obesity rates through choropleth maps
- Efficient data processing and cleaning of population statistics
- Merging geospatial and demographic data to calculate detailed obesity-related metrics

## 📂 **Data Sources**

1. **Obesity Data:** Derived from a shapefile (`National_Obesity_By_State.shp`), which includes obesity rates by state.
2. **Population Data:** CSV file (`population_distribution_by_age_number_2015.csv`) containing U.S. population distribution by age and state.

## ⚙️ **Setup Instructions**

1. **Environment Requirements:**

   - Python 3.x
   - Jupyter Notebook
   - Install required libraries:
     ```bash
     pip install geopandas mapclassify mplcursors openpyxl
     ```

2. **Data Download:**

   - The notebook automatically downloads the necessary data files using `wget` commands.

## 📝 **Usage**

1. **Run the Notebook:** Execute each cell sequentially to perform data analysis and visualization.
2. **Key Sections:**
   - **Data Import:** Loads obesity and population datasets.
   - **Data Processing:** Cleans and prepares data for analysis.
   - **Visualization:** Generates interactive maps to display obesity prevalence.

## 🌍 **Visualization Examples**

- **Choropleth Maps:** Displaying obesity rates with color-coded intensity for easy comparison.
- **Merged Data Maps:** Visualizing both population and obesity metrics together for deeper insights.

## 📜 **License**

This project is intended for educational and research purposes. Please provide proper attribution if using the code or data for external projects.

## 👩‍💻 **Author**

Developed as part of a geospatial data analysis project focusing on public health statistics.
