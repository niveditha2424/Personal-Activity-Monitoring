# Reproducible-Research-Project-1
Coursera Reproducible Research Project 1
# Personal Activity Monitoring

This project analyzes data from a personal activity monitoring device that collects step counts at 5-minute intervals throughout the day. The data consists of two months' worth of activity data, including the number of steps taken in each interval. The analysis involves cleaning and processing the data, and then generating several visualizations to explore the data further.

## Data Description

The dataset consists of the following variables:

- **steps**: The number of steps taken in a 5-minute interval (missing values are represented as *NA*).
- **date**: The date on which the measurement was taken in YYYY-MM-DD format.
- **interval**: The identifier for the 5-minute interval during which the measurement was taken.

The data can be downloaded from the course website:

- Dataset: [Activity Monitoring Data](https://d396qusza40orc.cloudfront.net/repdata%2Fdata%2Factivity.zip)

## Project Description

This project performs the following tasks:

1. **Data Loading & Cleaning**: The dataset is loaded, and missing values are handled.
2. **Exploratory Data Analysis**: Various statistical analyses and visualizations are performed to understand the activity patterns.
3. **Imputation**: Missing data for steps is imputed using the mean value for each 5-minute interval.
4. **Visualization**:
   - A histogram of total steps taken per day.
   - A time-series plot showing the average number of steps taken per 5-minute interval.
   - Panel plots comparing average steps on weekdays and weekends.

## Files in This Repository

- `README.md`: This file, providing an overview of the project.
- `activity.csv`: The original raw data file containing the activity data.
- `run_analysis.R`: The R script used for analyzing the data and generating the results.
- `activity_plot.png`: The image of the final plots.
- `CodeBook.md`: Describes the variables and transformations applied to the data.

## Setup

1. **Install Required Packages**:  
   The following R packages are required for this project:
   - `data.table`
   - `ggplot2`
   - `scales`
   - `lubridate`

2. **Run the Script**:  
   To replicate the analysis, run the `run_analysis.R` script. This script:
   - Downloads and loads the dataset.
   - Performs data cleaning and transformation.
   - Generates the requested plots.

3. **Data Source**:  
   The dataset used in this project was obtained from the [Coursera Reproducible Research course](https://www.coursera.org/learn/reproducible-research).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Coursera's Reproducible Research course for providing the dataset and structure for the project.
