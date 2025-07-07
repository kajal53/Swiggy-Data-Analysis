# Swiggy Data Analysis Project

## Overview
This project analyzes a dataset from Swiggy, a leading food delivery platform in India, to uncover insights about restaurant performance, customer preferences, and market trends. The analysis is performed using Python for exploratory data analysis (EDA) and visualizations to identify patterns in restaurant ratings, cuisines, delivery times, and other key metrics.

## Dataset
The dataset contains information about restaurants listed on Swiggy across various Indian cities. It is stored in a CSV or Excel file (e.g., `swiggy_data.csv`) and includes columns such as:
- Restaurant ID
- Restaurant Name
- City
- Cuisine Type
- Average Rating
- Delivery Time
- Cost for Two
- Number of Reviews
- Order Details

*Note*: For detailed dataset information, refer to the dataset file or documentation within the repository.

## Objectives
- Perform Exploratory Data Analysis (EDA) to understand distributions and relationships in the dataset.
- Identify trends, such as popular cuisines, top-rated restaurants, or city-wise restaurant distribution.
- Visualize insights using Python-based charts (e.g., bar charts, histograms, heatmaps).
- Provide actionable recommendations for stakeholders, such as restaurant owners or Swiggy's business team.

## Technologies Used
- **Python**: Core programming language for data analysis.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **Matplotlib/Seaborn**: For creating visualizations.
- **Jupyter Notebook**: For interactive analysis and documentation.

## Project Structure

Swiggy-Data-Analysis/
│
├── data/
│   └── swiggy_data.csv       # Dataset file
├── notebooks/
│   └── analysis.ipynb        # Jupyter Notebook with EDA
├── scripts/
│   └── data_processing.py    # Python script for data cleaning
├── visualizations/
│   └── plots/               # Python-generated plots and charts
├── README.md                # Project documentation
└── requirements.txt         # List of Python dependencies


## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/kajal53/Swiggy-Data-Analysis.git
   

2. Navigate to the project directory:
   ```bash
   cd Swiggy-Data-Analysis
 
3. Install the required Python dependencies:
   ```bash
   pip install -r requirements.txt

4. Launch the Jupyter Notebook for EDA:
   ```bash
   jupyter notebook notebooks/analysis.ipynb


## Usage

Open the analysis.ipynb notebook in the notebooks/ folder.
Follow the steps in the notebook to load the dataset, clean the data (e.g., handle missing values, remove duplicates), and perform EDA.
Run the cells to generate visualizations (e.g., bar charts, histograms, heatmaps) and derive insights.
Optionally, use the data_processing.py script for automated data cleaning and preprocessing.

## Example Analysis
Cuisine Popularity: Identify the most popular cuisines (e.g., North Indian, Chinese) based on order counts or restaurant frequency.
Restaurant Ratings: Analyze the distribution of restaurant ratings and identify top-rated restaurants.
City-wise Insights: Explore the number of restaurants per city and average delivery times.

Visualizations:
Bar chart of top 10 cuisines by restaurant count.
Histogram of restaurant ratings.
Heatmap of correlations between cost, ratings, and delivery time.
Results

## The analysis provides insights such as:

North Indian and Chinese cuisines are among the most popular across cities.
Cities like Kolkata, Mumbai, and Chennai have the highest number of listed restaurants.
Relationships between restaurant ratings, cost for two, and delivery times.
Identification of high-performing restaurants based on ratings and reviews.

## Contributing
Contributions are welcome! Please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Commit your changes (git commit -m 'Add new feature').
Push to the branch (git push origin feature-branch).
Create a Pull Request.
   



