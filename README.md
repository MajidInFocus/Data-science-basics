# Data Science Basics - Student Performance Analysis

## Project Overview
This project analyzes student performance data using Python, focusing on basic data cleaning, statistical analysis, and visualization techniques.

## Dataset
The analysis uses 'StudentsPerformance.csv' which contains:
- Student gender
- Parental education level
- Race/ethnicity
- Performance scores in math, reading, and writing

## Analysis Performed
1. Data Cleaning
   - Handling missing values
   - Standardizing gender labels (M/F)
   - Simplifying race/ethnicity data
   - Removing unnecessary columns

2. Exploratory Data Analysis
   - Basic statistical analysis
   - Group-wise performance analysis by gender
   - Analysis based on parental education levels
   - Population distribution studies

3. Visualizations
   - Math score distribution histogram
   - Reading vs Math scores scatter plot
   - 3D correlation plot between all subjects
   - Gender distribution pie chart
   - Parental education level bar chart
   - Comprehensive performance comparison across education levels

## Key Findings
- Gender-based performance variations:
  - Female students: Higher average in reading (72.6) and writing (72.5)
  - Male students: Higher average in math (68.7)
- Parental education impact:
  - Students with parents having master's degrees show highest overall performance
  - Notable performance variations across different education levels

## Technologies Used
- Python
- Pandas
- Matplotlib
- NumPy
- Matplotlib 3D toolkit

## Running the Code
1. Clone this repository
2. Install required dependencies:
   ```
   pip install pandas numpy matplotlib
   ```
3. Run the Jupyter notebook or Python scripts in the `src` directory

## Experimentation & Improvements
Want to experiment with the code? Here are some suggestions:
1. Modify visualization parameters:
   - Change color schemes in plots
   - Adjust figure sizes and layouts
   - Try different plot types (box plots, violin plots, etc.)

2. Enhance the analysis:
   - Add new statistical measures
   - Create additional cross-tabulations
   - Implement different normalization techniques

3. Feature Engineering:
   - Create composite scores
   - Add new derived metrics
   - Implement performance categories

4. Code Structure:
   - Modularize the code into functions
   - Add error handling
   - Implement data validation checks

Feel free to submit pull requests with your improvements!