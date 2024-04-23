# matplotlib_challenge
## Study Overview
Objective: Compare the performance of our drug of interest, Capomulin, against other treatment regimens.
Dataset: The study involved 249 mice identified with SCC tumors who received various drug regimens. Tumor development was observed and measured over 45 days.

## Data Preparation:
Merge the mouse metadata and study results into a single DataFrame.
Check for any duplicate mouse IDs with duplicate time points and clean the data accordingly.

## Summary Statistics:
Generate a DataFrame of summary statistics including mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

## Bar Charts and Pie Charts:
Create bar charts showing the total number of rows (Mouse ID/Timepoints) for each drug regimen.
Generate pie charts to illustrate the distribution of female versus male mice in the study.

## Quartiles, Outliers, and Box Plot:
Calculate quartiles, IQR, and identify potential outliers across promising treatment regimens.
Create a box plot to visualize the distribution of the final tumor volume for all mice in each treatment group.

## Line Plot and Scatter Plot:
Plot a line graph of tumor volume versus time point for a single mouse treated with Capomulin.
Generate a scatter plot of mouse weight versus average observed tumor volume for the Capomulin treatment regimen.

## Correlation and Regression:
Calculate the correlation coefficient and linear regression model between mouse weight and average observed tumor volume for the Capomulin treatment regimen.
Plot the linear regression model on top of the scatter plot.

## Conclusion
Through comprehensive analysis and visualization techniques, valuable insights into different drug regimens, particularly Capomulin, were identified. Findings are saved in Jupyter Notebook.
