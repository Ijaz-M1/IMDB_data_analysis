# IMDB_data_analysis

## Description
This project revolves around a csv dataset containing information on 100 movies sourced from the IMDb database. The dataset was intentionally made as a messy dataset, offering ample opportunities for data cleaning and exploratory data analysis. The primary objective is to apply data cleaning techniques and create compelling visualisations.

## Dataset details
- Source: https://www.kaggle.com/datasets/davidfuenteherraiz/messy-imdb-dataset
- Variables: The dataset encompasses around 100 rows and 11 variables, each providing unique information about the movies. These variables include details such as movie title, release year, genre, runtime, ratings, and more.


## Purpose
The project aims to showcase proficiency in data cleaning and analysis using Python, particularly leveraging the Pandas library in a Jupyter Notebook environment. By addressing the messiness of the dataset, the aim is to extract valuable insights into the characteristics and trends within the IMDb movie data.

## How to install requirements and run the file
[In progress]

## Key steps
### Step 0 - Import libraries and read file
In this initial step, we import the essential Python libraries that are pivotal for conducting the IMDb Movies Data Analysis. These libraries provide powerful tools for data manipulation, analysis, and visualisation. The libraries used for this project:
- Pandas
- NumPy
- Matplotlib.pyplot

We also run the file using pandas and highlight ; as the delimiter


### Step 1 - Understanding the data
In this step, we delve into the IMDb Movies dataset to gain a comprehensive understanding of its structure, dimensions, and the types of information it contains. These initial insights set the stage for subsequent data cleaning and exploratory data analysis.

### Step 2 - Transform the data
In Step 2, we enhance the IMDb Movies dataset by addressing duplicates, null values, and inconsistencies. We identify and handle duplicates in the 'Original title' column, drop columns and rows with exclusive null values, and refine the 'Duration' column by adjusting data types, handling missing values, and correcting entries. The 'Release year' column undergoes formatting improvements for standardised dates. 'Genre' and 'Country' columns are cleaned for whitespaces and variations. Formatting issues in 'Income' are corrected, and the 'Score' column is converted to numeric, with manual input for missing values. This transformation ensures a cleaned and structured dataset, ready for insightful analysis.

### Step 3 - Visualise the data
In Step 3 - Visualise Data, a preliminary exploration using Matplotlib aimed to answer the question, "Can you provide a visual representation of the distribution of countries in your dataset?" The code involved counting the occurrences of each country, creating a bar chart to illustrate the distribution. The x-axis displayed countries, the y-axis represented counts, and the bars were coloured in "LightSalmon." The chart was labelled, with 'Country' on the x-axis, 'Count' on the y-axis, and a title indicating 'Country Distribution.' To enhance readability, x-axis labels were rotated for better visibility. This initial visualisation offers a quick insight into the distribution of countries in the IMDb Movies dataset. For more comprehensive visualisations, the main focus will shift to Power BI.

## Next steps
[In progress]

To elevate the data analysis experience, the next steps involve transitioning to Power BI for more advanced and interactive visualisations. By importing the cleaned IMDb Movies dataset, we can create compelling visual narratives that convey insights more effectively.


## What could be done better
In considering ways to enhance the current project, there are two notable areas for improvement. First, introducing unit testing would provide a systematic means of validating individual functions and methods, contributing to the overall reliability and robustness of the code. Additionally, transitioning towards a more automated approach is recommended to reduce manual input. This shift not only streamlines the workflow but also reduces the likelihood of human errors, making the project more scalable and maintainable in the long run.