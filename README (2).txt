================================================================================
  NETFLIX DATA ANALYSIS
  Exploratory Data Analysis (EDA) of Netflix Movies Dataset
================================================================================

PROJECT OVERVIEW
----------------
This project performs an Exploratory Data Analysis (EDA) on a Netflix movies
dataset. The goal is to uncover trends, patterns, and insights about movie
genres, popularity, and release history available on Netflix.

--------------------------------------------------------------------------------

DATASET
-------
File      : NetflixData.csv
Rows      : ~25,779 (after cleaning and genre expansion)
Columns   : Release_Date, Title, Overview, Popularity, Vote_Count,
            Vote_Average, Original_Language, Genre, Poster_Url

--------------------------------------------------------------------------------

PROJECT STRUCTURE
-----------------
  Netflix-Data-Analysis/
  |
  |-- NetflixData.csv                        # Raw dataset
  |-- Netflix_Data_Analysis__2_kk.ipynb      # Main analysis notebook
  |-- README.txt                             # Project documentation

--------------------------------------------------------------------------------

ANALYSIS STEPS
--------------
1. Data Loading
   - Loaded the dataset into a Pandas DataFrame.

2. Data Preview & Structure
   - Inspected first rows, column names, data types, and shape.

3. Statistical Summary
   - Generated descriptive statistics for numerical columns.

4. Data Quality Check
   - Identified and removed duplicate rows.
   - Identified and removed rows with missing values.

5. Data Preprocessing / Transformation
   - Converted Release_Date to datetime format and extracted the year.
   - Dropped irrelevant columns: Overview, Poster_Url, Original_Language.
   - Split multi-genre entries into separate rows (one genre per row).

6. Data Visualization (5 key questions answered)
   - Q1: Which genre appears most often?
   - Q2: Which movies have the highest popularity?
   - Q3: How has movie production changed over time?
   - Q4: Which genres have the highest average popularity?
   - Q5: What is the distribution of popularity scores?

--------------------------------------------------------------------------------

KEY FINDINGS
------------
* Drama is the most common genre on Netflix.
* Spider-Man: No Way Home has the highest popularity score in the dataset,
  followed by The Batman, No Exit, and Encanto.
* Movie releases increased significantly after the year 2000, reflecting
  rapid growth in the film industry and streaming platforms.
* Adventure movies have the highest average popularity among all genres.
  Action and Science Fiction also rank highly.
* Popularity scores are heavily right-skewed — most movies are average,
  while only a small number become blockbuster hits.

--------------------------------------------------------------------------------

TECHNOLOGIES USED
-----------------
  Language   : Python 3
  Libraries  :
    - pandas          (data manipulation)
    - plotly.express  (interactive visualizations)

  Environment: Google Colab / Jupyter Notebook

--------------------------------------------------------------------------------

HOW TO RUN
----------
1. Clone the repository:
     git clone https://github.com/your-username/Netflix-Data-Analysis.git

2. Open the notebook:
     Netflix_Data_Analysis__2_kk.ipynb

3. Run all cells in order (top to bottom).

   Note: If running locally, install required libraries first:
     pip install pandas plotly

   Note: Update the dataset path in the notebook if not using Google Colab:
     df = pd.read_csv('NetflixData.csv')

--------------------------------------------------------------------------------

AUTHOR
------
  GitHub : https://github.com/your-username

================================================================================
