# geo_spatial_analysis_zomato_case_study
# Zomato Data Analysis Project

This project involves performing various data analysis tasks on Zomato data using Python. The analysis includes reading data from an SQL database, analyzing the relationship between online orders and ratings, text cleaning, n-gram analysis, extracting geographical coordinates, performing spatial analysis, and automating the spatial analysis process.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Methods](#methods)
  - [Reading Data from SQL Database](#reading-data-from-sql-database)
  - [Analyzing Relationship Between Online Order and Rating](#analyzing-relationship-between-online-order-and-rating)
  - [Text Cleaning](#text-cleaning)
  - [Performing Unigram, Bi-gram, and Trigram Analysis](#performing-unigram-bi-gram-and-trigram-analysis)
  - [Extracting Geographical Coordinates](#extracting-geographical-coordinates)
  - [Performing Spatial Analysis](#performing-spatial-analysis)
  - [Automating Spatial Analysis](#automating-spatial-analysis)
- [Charts Used](#charts-used)
- [Modules Used](#modules-used)
- [Contributing](#contributing)



## Usage
After installing the dependencies, you can run the analysis scripts. Make sure you have the necessary data and database credentials set up.

## Methods
### 1. Reading Data from SQL Database
This step involves connecting to the SQL database where the Zomato data is stored and fetching the necessary data for analysis. We use the sqlite3 module to interact with the database.

### 2. Analyzing Relationship Between Online Order and Rating
In this step, we analyze how online orders correlate with restaurant ratings. This involves statistical analysis and visualization using pandas, numpy, matplotlib, and seaborn.

### 3. Text Cleaning
Text data often contains noise. This step involves cleaning the text data to remove unwanted characters, stopwords, and perform other preprocessing steps. We use RegexpTokenizer from nltk to tokenize the text and stopwords from nltk to remove common words that do not add much meaning.

### 4. Performing Unigram, Bi-gram, and Trigram Analysis
This step involves analyzing the frequency of unigrams, bi-grams, and trigrams in the text data to understand common phrases and keywords. We use FreqDist, bigrams, and trigrams from nltk for this analysis.

### 5. Extracting Geographical Coordinates
We extract geographical coordinates from the data for spatial analysis. This involves geocoding addresses or using available latitude and longitude data. We use Nominatim from geopy.geocoders for geocoding.

### 6. Performing Spatial Analysis
Using the geographical coordinates, we perform spatial analysis to understand the distribution and density of restaurants, and other spatial patterns. We use folium and HeatMap from folium.plugins to create interactive maps and heatmaps.

### 7. Automating Spatial Analysis
This step involves automating the spatial analysis process to make it repeatable and efficient. Scripts are created to automate tasks like data fetching, preprocessing, and analysis.

## Charts Used
### Stacked Bar Graph:
        Used to compare the proportions of different categories.
### Line Graph:
        Used to show trends over time.
### Heatmap on Geographical Map:
        Used to visualize the density and distribution of data points on a map.

## Modules Used
### pandas:
        For data manipulation and analysis.
### numpy:
        For numerical operations.
### matplotlib:
        For creating static, animated, and interactive visualizations.
### seaborn:
        For statistical data visualization.
### sqlite3:
        For interacting with the SQL database.
### warnings:
        To manage warning messages.
### RegexpTokenizer (from nltk):
        For tokenizing text using regular expressions.
### stopwords (from nltk):
        For removing common words that do not add much meaning.
### FreqDist (from nltk):
        For computing the frequency distribution of terms.
### bigrams (from nltk):
        For creating bigrams from text.
### trigrams (from nltk):
        For creating trigrams from text.
### Nominatim (from geopy.geocoders):
        For geocoding addresses.
### folium:
        For creating interactive maps.
### HeatMap (from folium.plugins):
        For creating heatmaps on maps.
### Contributing
        Contributions are welcome! If you have any ideas, suggestions, or bug fixes, feel free to open an issue or submit a pull request.

## Installation

To get started with this project, clone the repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/zomato-data-analysis.git
cd zomato-data-analysis
pip install -r requirements.txt
