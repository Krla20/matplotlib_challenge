# matplotlib_challenge
***
# Observations or Inferences
***
#### 1.  By removing duplicates the total number of mice reduced by only one from 249 to 248 mice.
#### 2. The bar graph showed the Drug Regimen Capomulin has the maximum mice number with a total of 230, followed very closely by the Ramicane with 228 and Propriva has the smaller number with 148 mice. 
#### 3. The data a slight difference in quantity of mice by gender  since it showed a total of 123 female mice and 125 male mice.
#### 4.  From the selected treatments Capomulin and Ramicane are more effective reducing the size of tumors.
#### 5. With treatment Capomulin the correlation between mouse weight, and average tumor volume is 0.84. It is a strong positive correlation, when the mouse weight increases the average tumor volume also increases.
#### 6. The regression analysis helped to understand how much the average tumor volume (dependent variable) will change when weight of mice change (independent variables) with the Capomulin treatment. The R-squared value is 0.71, which means 71% the model fit the data, wich is fairely good to predict the data from the model.  *(If you analyze a physical process and have very good measurements, you might expect R-squared values over 90%).*

#*************************************
#Instructions
#*************************************
Before beginning the analysis, check the data for any mouse ID with duplicate time points and remove any data associated with that mouse ID.
Use the cleaned data for the remaining steps.
Generate a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.
Generate a bar plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the total number of measurements taken for each treatment regimen throughout the course of the study. (These plots should look identical)
Generate a pie plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the distribution of female or male mice in the study.(These plots should look identical)

Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.
Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style. (All four box plots should be within the same figure. Use this Matplotlib documentation page for help with changing the style of the outliers.)
Select a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse.
Generate a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.
Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.
Look across all previously generated figures and tables and write at least three observations or inferences that can be made from the data. Include these observations at the top of notebook.

Here are some final considerations:
You must use proper labeling of your plots, to include properties such as: plot titles, axis labels, legend labels, x-axis and y-axis limits, etc.
See the starter workbook for help on what modules to import and expected format of the notebook.
