
# Netflix Data Analysis

This project involves analyzing Netflix data to derive insights and visualize trends. The analysis is performed using a Jupyter notebook and the dataset is provided in CSV format.

## Project Structure

- `NetflixDataExploration.ipynb`: The Jupyter notebook containing the data analysis and visualizations.
- `netflix_titles.csv`: The dataset containing information about Netflix titles, including movies and TV shows.

## Dataset

The dataset `netflix_titles.csv` includes the following columns:
- `show_id`: Unique ID for each show
- `type`: Type of show (Movie or TV Show)
- `title`: Title of the show
- `director`: Director of the show
- `cast`: Main cast of the show
- `country`: Country where the show was produced
- `date_added`: Date the show was added to Netflix
- `release_year`: Year the show was released
- `rating`: Rating of the show
- `duration`: Duration of the show (minutes for movies, seasons for TV shows)
- `listed_in`: Genres the show is listed under
- `description`: Brief description of the show

## Analysis Overview

The analysis includes:
1. **Data Cleaning**: Handling missing values and correcting data types.
2. **Exploratory Data Analysis (EDA)**: 
   - Distribution of show types (Movies vs TV Shows)
   - Trends in show releases over the years
   - Popular genres and countries of production

## Getting Started

### Prerequisites

To run the analysis, you need the following:
- Python
- Jupyter Notebook
- Libraries: pandas, numpy, matplotlib, seaborn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ShaneRer1/NetflixDataAnalysis.git
   ```
2. Install the required libraries:
   ```
   pip install pandas numpy matplotlib seaborn
   ```

### Running the Analysis

1. Start Jupyter Notebook:
   ```
   jupyter notebook
   ```
2. Open `NetflixDataExploration.ipynb` in Jupyter Notebook and run the cells to perform the analysis.

## Results

The results of the analysis are visualized in the Jupyter notebook. Some key findings include:
- The distribution of movies and TV shows on Netflix.
- Trends in the release of Netflix titles over the years.
- Popular genres and countries producing Netflix content.

## Done By

Shane Ranasinghe

## Acknowledgements

- The dataset is provided by [Kaggle](https://www.kaggle.com/datasets/rahulvyasm/netflix-movies-and-tv-shows/data).
