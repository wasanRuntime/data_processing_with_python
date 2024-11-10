# Spotify Top 50 Tracks 2020 Analysis

## Project Overview
This project explores the *Spotify Top 50 Tracks 2020* dataset to uncover insights into the factors that contribute to a song’s popularity. The primary goal is to identify patterns in the top-performing tracks and answer specific business questions posed by the product manager to inform content strategy. The analysis includes data cleaning, exploratory data analysis (EDA), and feature-based analysis to reveal key trends in popular music.

**Find the Jupyter notebook [here](Data_Processing_with_Pandas.ipynb)**

## Dataset
The dataset, sourced from Kaggle, contains data on 50 popular tracks from 2020, with several attributes detailing each song’s features. These include:

- **Track Title**
- **Artist Name**
- **Album**
- **Genre**
- **Danceability**
- **Loudness**
- **Acousticness**
- **Track Length**, and more.

### Dataset Source
The dataset can be accessed from Kaggle: [Spotify Top 50 Tracks 2020](https://www.kaggle.com/datasets/atillacolak/top-50-spotify-tracks-2020)

## Objectives
This analysis aims to achieve the following:

1. **Data Cleaning**:
   - Handle missing values
   - Remove duplicates and irrelevant features
   - Treat outliers to ensure data quality

2. **Exploratory Data Analysis (EDA)**:
   - Analyze categorical and numeric features
   - Identify the most popular artists and albums
   - Examine top tracks based on key features like danceability, loudness, and track length
   - Explore genre popularity and feature correlations

3. **Business Insights**:
   - Identify the key features influencing song popularity
   - Understand genre-based differences in metrics like danceability, loudness, and acousticness
   - Provide recommendations for content strategy based on the analysis

4. **Suggestions for Improvement**:
   - Propose potential areas for future analyses and data improvements

## Installation and Usage

### Prerequisites
To run the analysis, ensure you have the following libraries installed:

- `pandas`
- `seaborn`
- `matplotlib`

You can install them using pip:

```bash
pip install pandas seaborn matplotlib
```

### Running the Notebook
1. Clone the repository to your local machine.
2. Open the Jupyter notebook Data_Processing_with_Pandas.ipynb.
3. Run the cells in sequence to perform the analysis.
### License
This project is licensed under the MIT License - see the LICENSE file for details.

### Acknowledgments
The dataset was sourced from **[Kaggle: Spotify Top 50 Tracks 2020](Data_Processing_with_Pandas.ipynb)**.
Thanks to the contributors of the dataset for making this analysis possible.
