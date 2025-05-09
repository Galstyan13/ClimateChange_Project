
# Climate Change Impact on the Economic Sphere and Agricultural Industry

This project analyzes the relationship between climate change and its impact on the global economy, particularly focusing on the agricultural sector. By examining the changes in climate patterns and the corresponding shifts in agricultural industry size, this project aims to shed light on the potential economic consequences of climate change on global food production, agricultural labor markets, and overall economic stability.

## Objectives
- **Analyze the Impact of Climate Change on the Economy**: Evaluate how different climate variables (such as temperature, precipitation, and extreme weather events) influence global economic indicators.
- **Examine the Agricultural Sector**: Assess the size and growth of the agricultural industry, including crop yields and labor force changes, in response to climate variables.
- **Comparison of Economic and Agricultural Data**: Compare the economic impacts with changes in agricultural data to gain insights into how shifts in climate affect both sectors simultaneously.
  
## Tools & Libraries
This project uses a range of Python libraries to handle data analysis, visualization, and geospatial analysis:

- **Pandas**: For data manipulation and analysis of structured datasets.
- **NumPy**: For numerical computations and handling large data arrays.
- **Matplotlib**: For creating static, animated, and interactive visualizations.
- **Geopandas**: For geospatial data analysis, mapping, and visualization.
- **Statistical Techniques**: Various statistical methods (including regression analysis, correlation analysis) are applied to understand trends and relationships between climate and the economy.

## Dataset Overview
The dataset used in this project contains global climate data, agricultural statistics, and economic indicators. Key variables include:

- Temperature anomalies
- Precipitation levels
- Crop yield data (per region and globally)
- GDP and economic output in agricultural and non-agricultural sectors
- Nature impact in the agricultural sector
- Regional data for spatial analysis

## Installation & Setup

To run this project on your local machine, follow these steps:

### Prerequisites:
- Python 3.x+
- Pip (Python package installer)

### Step 1: Clone the repository
```bash
git clone https://github.com/Galstyan13/ClimateChange_Project.git
cd ClimateChange_Project
```

### Step 2: Install Dependencies
Create a virtual environment (optional, but recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows, use venv\Scripts\activate
```

Install required libraries:
```bash
pip install -r requirements.txt
```

### Step 3: Data Preparation
Ensure you have access to the datasets used in the analysis. You may need to download  data files from  sources and place them in the `data/` folder.

### Step 4: Run the Analysis
Once the setup is complete, you can run the main script:
```bash
python main.ipynb
```

This will perform the analysis and generate results in the form of graphs and statistical reports.

## Analysis & Results

After running the project, you’ll obtain the following outputs:

1. **Correlation Analysis**: Relationships between climate factors (temperature, rainfall, etc.) and agricultural productivity and economic growth.
2. **Visualizations**: Graphs comparing the economic output and agricultural sector size over time and under different climate conditions.
3. **Geospatial Maps**: Geographic visualizations showing how climate change impacts regions differently, with a focus on agricultural output.
4. **Statistical Summary**: Statistical summaries and findings highlighting key trends in the data.

## Future Work

- **Enhanced Predictive Modeling**: Incorporating machine learning techniques to forecast future trends in agriculture and economic impacts based on climate scenarios.
- **Incorporate More Variables**: Expanding the dataset to include other socio-economic factors (e.g., healthcare costs, migration patterns).
- **Policy Recommendations**: Based on the analysis, propose actionable insights for policymakers to mitigate climate impacts on the global economy.

## Contributing

Contributions are welcome! If you’d like to improve or expand upon this project, please feel free to fork the repository and submit a pull request. 

## Acknowledgments

- Data sources: Kaggle.com/climate_change.
- Libraries: Python libraries such as Pandas, NumPy, and Matplotlib.
  
