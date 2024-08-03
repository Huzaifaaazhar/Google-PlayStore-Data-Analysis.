# Google PlayStore Data Analysis.

## Overview

This repository provides a detailed analysis of Google Play Store data, utilizing both a Jupyter Notebook for data exploration and a Power BI file for interactive visualization. The analysis covers various aspects of app performance, including ratings, reviews, and categories.

## Repository Structure

```
google-play-store-data-analysis/
│
├── Google_Play_Store_Analysis.ipynb  # Jupyter Notebook for data analysis
│
└── Google_Play_Store_Dashboard.pbix  # Power BI file for interactive dashboard
```

## Data

The dataset used for this analysis includes information about Google Play Store apps. Key attributes include:

- **App**: Name of the app.
- **Category**: Category to which the app belongs.
- **Rating**: Average rating of the app.
- **Reviews**: Number of reviews the app has received.
- **Size**: Size of the app.
- **Installs**: Number of installs.
- **Type**: Whether the app is free or paid.
- **Price**: Price of the app, if applicable.
- **Content Rating**: Age group suitability of the app.
- **Genres**: Genres associated with the app.
- **Last Updated**: Date when the app was last updated.
- **Current Ver**: Current version of the app.
- **Android Ver**: Minimum Android version required for the app.

## Analysis

### Jupyter Notebook: Google_Play_Store_Analysis.ipynb

The Jupyter Notebook performs an in-depth analysis of the Google Play Store data. Key analyses include:

- **Data Cleaning**: 
  - Handling missing values and incorrect data types.
  
- **Exploratory Data Analysis (EDA)**: 
  - Distribution analysis of app ratings and reviews.
  - Analysis of app performance across different categories.
  - Investigating the effect of pricing on app installs.

- **Sentiment Analysis**:
  - Conducting sentiment analysis on app reviews to categorize them as Positive, Neutral, or Negative using TextBlob.
  
- **Visualizations**:
  - Various plots and graphs to illustrate insights from the data.

### Power BI Dashboard: Google_Play_Store_Dashboard.pbix

The Power BI file contains an interactive dashboard for visualizing key metrics and trends from the Google Play Store data. Features include:

- **Interactive Charts**:
  - Charts showing app ratings, reviews, and installs by category.
  - Analysis of app performance based on pricing and review sentiment.

- **Filters and Slicers**:
  - Options to filter data by app category, type, and other attributes.
  
- **Data Insights**:
  - Key insights and trends visualized through various Power BI components.

## Getting Started

### Prerequisites

- Python 3.12 or newer
- Jupyter Notebook
- Power BI Desktop (for viewing the Power BI file)

### Installation

1. **Clone the Repository**:

    ```bash
    git clone https://github.com/your-username/google-play-store-data-analysis.git
    cd google-play-store-data-analysis
    ```

2. **Set Up Python Environment**:

    - Install required Python packages. If a `requirements.txt` file is available, use:

        ```bash
        pip install -r requirements.txt
        ```

    - If not, ensure you have the following packages installed:

        ```bash
        pip install pandas numpy matplotlib seaborn textblob
        ```

3. **Run the Jupyter Notebook**:

    - Open the Jupyter Notebook and execute cells to perform the analysis.

        ```bash
        jupyter notebook notebooks/Google_Play_Store_Analysis.ipynb
        ```

4. **Open the Power BI Dashboard**:

    - Use Power BI Desktop to open and interact with the `.pbix` file.

    - Download Power BI Desktop from [Microsoft's website](https://powerbi.microsoft.com/desktop).

## Usage

- **Jupyter Notebook**: Review the analysis and visualizations within the notebook to understand the data insights and trends.

- **Power BI Dashboard**: Interact with the dashboard to explore different aspects of the data and gain insights through dynamic visualizations.

## Contributing

Contributions to improve the analysis or add new features are welcome. Please submit issues or pull requests with your suggestions or changes.

## Contact

For questions or feedback, please contact [![GMail](https://img.shields.io/badge/-GMail-D14836?style=flat&logo=GMail&logoColor=white)](mailto:azharhuzaifa123@gmail.com)
