# Graph Neural networks for synthetic fiber production

## Overview
The GNN_FIBER notebook presents a comprehensive analysis focused on the fiber industry, leveraging a combination of data manipulation, graph theory, community detection, and visualization techniques. This document serves as a detailed guide to understanding the structure, methodology, and insights derived from the notebook's analysis.

## Dataset Description
The analysis begins with fetching data from an external API. The dataset includes various metrics such as product groups, quantities, and values over multiple fiscal years. The data spans several columns, each representing different aspects of the fiber products and their market performance across years.

## Preprocessing Steps
- **Data Fetching**: The notebook initiates by fetching the dataset using the `requests` library and checks for a successful response from the API.
- **Data Loading**: Upon a successful fetch, the data is loaded into a Pandas DataFrame for ease of manipulation and analysis.
- **Initial Display and Saving**: The DataFrame is displayed for an initial review, and the data is saved to a CSV file for potential offline analysis.

## Analysis Overview
The notebook employs various Python libraries such as Pandas for data manipulation, NetworkX for graph analysis, Matplotlib for visualization, and community detection algorithms for clustering.

### Graph-Based Modeling
- **Supply Chain and Correlation Graphs**: Constructs graphs to model relationships between products, including supply chains and product correlations.
- **Community Detection**: Applies algorithms to detect communities within graphs, aiming to uncover groups of products that share significant relationships.

### Visualization
- **Graph Visualizations**: Includes visualizations of the constructed graphs, utilizing layouts that best represent the underlying data structure and relationships.
- **Growth Rate Analysis**: Visualizes the growth rates of products over the years, highlighting trends and product performance.

### Analytical Insights
- **Community Evolution**: Analyzes how product communities evolve over time, offering insights into market dynamics and product relationships.
- **Product Growth Trends**: Assesses the growth rates of products, identifying trends that could influence strategic business decisions.

## Key Findings and Insights
- **Market Structure Insights**: The community detection and analysis reveal the underlying market structure, showing how products are interconnected and how these connections evolve over time.
- **Product Performance and Trends**: Growth rate analysis provides a quantitative measure of product market trends, identifying products with increasing or decreasing demand.

## Conclusion
The GNN_FIBER notebook exemplifies the application of advanced analytics in industry-specific data analysis. Through its structured approach combining data visualization, graph theory, and statistical measures, it offers actionable insights into the fiber industry's dynamics. This analysis is invaluable for stakeholders seeking to understand market trends, product synergies, or competitive dynamics, guiding informed decision-making.

## Libraries and Dependencies
- Python 3.x
- Pandas
- NetworkX
- Matplotlib
- Requests
- Community Detection Libraries (e.g., `python-louvain`)

Ensure all dependencies are installed using pip or conda to replicate the analysis environment successfully.

## How to Use
1. **Data Preparation**: Ensure the dataset URL is up-to-date and accessible.
2. **Execution**: Run each cell sequentially, from data fetching to final analysis.
3. **Customization**: Adjust parameters such as value thresholds in community detection or graph layouts as per specific analysis needs.

## Future Work
- **Data Expansion**: Incorporate additional datasets for a more comprehensive analysis.
- **Model Refinement**: Explore advanced graph algorithms and community detection methods.
- **Real-Time Analysis**: Adapt the notebook for real-time data fetching and analysis for up-to-date insights.
