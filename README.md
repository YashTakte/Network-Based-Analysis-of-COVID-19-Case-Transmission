# Network-Based Analysis of COVID-19 Case Transmission

## Overview
This project applies **network-based visual analytics** to analyze **COVID-19 case transmission** using **graph-based modeling and case flow analysis**. The study aims to identify **major transmission hubs, case movement trends, and superspreader events** using **network visualization techniques**.

## Data Sources
The dataset used in this project is sourced from:
- **[GitHub Repository](https://github.com/laxmanbalaraman/Social-Network-Analysis-on-Global-Spread-of-COVID-19)** – Contains raw **source-target** COVID-19 case transmission data.
- The dataset is named **`covid_df.csv`** and was **preprocessed** to:
  - Remove self-loops and duplicate edges.
  - Compute transmission weights based on **case movement intensity**.
  
## Methodology
### **1. Data Collection & Preprocessing**
- Extracted raw case transmission data from the **GitHub repository**.
- **Preprocessing steps:**
  - Removed **self-loops** and **duplicates**.
  - Computed **transmission weights**.
- The **preprocessed dataset** is included in this repository.

### **2. Network Analysis & Visualization**
- **Tools Used:**
  - **Gephi** – For **node-link graph visualization**.
  - **Power BI** – For **Sankey diagram visualization**.
- **Network Metrics Applied:**
  - **Degree Centrality** – Identifies **high-degree nodes** (major transmission hubs).
  - **Case Flow Analysis** – Tracks **case movement trends and superspreader events**.

## Visualizations
### **1. Node-Link Graph (Gephi)**
- Displays **COVID-19 case transmission pathways**.
- Uses **ForceAtlas2 layout** to highlight **high-degree nodes**.

### **2. Sankey Diagram (Power BI)**
- Illustrates **case flow trends** between regions.
- **Thicker connections** indicate **higher transmission volumes**.

## Deployment & Interpretation
- **Stakeholders** (health officials, policymakers, and the public) can interpret **case movement trends** and **outbreak hubs**.
- **Final Outputs:**
  - **Network Graphs** → Identify **key transmission hubs**.
  - **Sankey Diagrams** → Visualize **case flow between regions**.
- **Data-Driven Decision Making:**
  - Policymakers can use this analysis to implement **targeted containment strategies**.
