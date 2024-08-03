# geo_spatial_analysis_zomato_case_study
# Zomato Data Analysis Project

## Project Overview
Welcome to the "Zomato Data Analysis" project. This project offers a comprehensive analysis of Zomato data using Python. We employ various data analysis methods to uncover insights within the Zomato dataset.

## Zomato Data
We've gathered a diverse range of data from Zomato to conduct our analysis, exploring various aspects of restaurant data, customer reviews, and geographical information. All the datasets are provided in the project repository.

## Problem Statement
In this case study, we focus on various aspects of Zomato data analysis, including:

1. **Data Collection and Preprocessing**
   - Reading Data from SQL Database

2. **Analyzing Relationship Between Online Order and Rating**
   - Understanding how online orders correlate with restaurant ratings

3. **Text Cleaning**
   - Cleaning the text data to remove unwanted characters, stopwords, and perform other preprocessing steps

4. **Performing Unigram, Bi-gram, and Trigram Analysis**
   - Analyzing the frequency of unigrams, bi-grams, and trigrams in the text data

5. **Extracting Geographical Coordinates**
   - Geocoding addresses or using available latitude and longitude data for spatial analysis

6. **Performing Spatial Analysis**
   - Understanding the distribution and density of restaurants using interactive maps and heatmaps

7. **Automating Spatial Analysis**
   - Automating the spatial analysis process to make it repeatable and efficient

For detailed code explanations and analysis, please refer to the accompanying Jupyter Notebook (ipynb) files within the repository. Our primary IDE is Jupyter Notebook.

## Modules Used
We've harnessed the power of several Python libraries for this analysis, including but not limited to:

- `pandas`: For data manipulation and analysis, providing data structures and operations for manipulating numerical tables and time series.
- `numpy`: For numerical operations, offering support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays.
- `matplotlib`: For creating static, animated, and interactive visualizations in Python.
- `seaborn`: For statistical data visualization, built on top of matplotlib and closely integrated with pandas data structures.
- `sqlite3`: For interacting with the SQL database, allowing us to execute SQL queries and fetch data.
- `warnings`: To manage warning messages, allowing us to control the display of warnings.
- `RegexpTokenizer` (from `nltk`): For tokenizing text using regular expressions, helping in text preprocessing.
- `stopwords` (from `nltk`): For removing common words that do not add much meaning to the text analysis.
- `FreqDist` (from `nltk`): For computing the frequency distribution of terms in the text data.
- `bigrams` (from `nltk`): For creating bigrams from text, which are pairs of consecutive words.
- `trigrams` (from `nltk`): For creating trigrams from text, which are triplets of consecutive words.
- `Nominatim` (from `geopy.geocoders`): For geocoding addresses, converting them into geographical coordinates.
- `folium`: For creating interactive maps, allowing for easy visualization of geospatial data.
- `HeatMap` (from `folium.plugins`): For creating heatmaps on maps, showing the density of data points.

## Graphs and Visualizations
Our analysis is complemented by a variety of visually engaging graphs and visualizations, such as:

- **Stacked Bar Graphs**
- **Line Graphs**
- **Heatmaps on Geographical Maps**

## To acces the data visit on this link
https://drive.google.com/drive/folders/1b8N1bJT88cxssBSnWTZa-HMtntSi47Ls?usp=sharing

Thank you for exploring this project! Feel free to dive into the code and analysis to better understand the fascinating world of Zomato data.

## Contributing
Contributions and feedback are welcome! If you have suggestions or improvements, please open issues and submit pull requests to enhance this project.

## Contact
For questions or inquiries, please feel free to contact me at:

Aryan Yadav (mailto:ayaryan489@gmail.com)



