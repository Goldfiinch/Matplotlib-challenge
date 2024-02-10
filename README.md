# Matplotlib-challenge

Instructions
- This assignment is broken down into the following tasks:
- Prepare the data.
- Generate summary statistics.
- Create bar charts and pie charts.
- Calculate quartiles, find outliers, and create a box plot.
- Create a line plot and a scatter plot.
- Calculate correlation and regression.
- Submit your final analysis.

Analysis
- Summary Statistics:
  - Capomulin and Ramicane seem to have performed the best with their mean & median tumor volumes being the lowest compared to the other drug regimens. Naftisol performed the worst. Even the Placebo regimen performed better than Naftisol which could support an argument that the drug potentially increases tumor volume.

- Bar & Pie Charts:
  - Based on the visualized data in the bar charts, the two best-performing drugs (Capomulin & Ramicane) had the most # of observed timepoints, meaning that the mice treated by those drugs lived longer.
The pie charts don’t show any significant patterns in the data because the percentage of male-to-female mice is relatively equal. However, one could argue that the purpose of the pie chart was to eliminate sex as a variable in the overall analysis.
Quartiles, Outliers and Boxplots:

  - After narrowing down the analysis to just four drugs (Capomulin, Ramicane, Infubinol & Ceftamin), we performed a statistical analysis to determine if there were any outliers. The results were that only one mouse undergoing the Infubinol drug treatment possessed a tumor volume far lower than its other observations (Mouse ID: c326, Timepoint: 31). This could be seen as an argument for Infubinol being inconsistent or unpredictable compared to the other regimens.

- Line Chart:
  - The line chart illustrates the results of a random mouse (m601) undergoing the Capomulin drug treatment. The results show a negative sloping line which supports the argument of Capomulin being successful at reducing overall tumor volume.

- Correlation & Regression:
  - The scatter plot & regression line shows a correlation between average tumor volume and a test subject’s weight. Concluding that a heavier mouse is most likely to have a larger tumor.

Sources:

https://pandas.pydata.org/docs/dev/user_guide/merging.html#merge
https://www.geeksforgeeks.org/find-duplicate-rows-in-a-dataframe-based-on-all-or-selected-columns/#
https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.duplicated.html
https://saturncloud.io/blog/how-to-remove-rows-with-specific-values-in-pandas-dataframe/#:~:text=Another%20method%20to%20remove%20rows,value%20we%20want%20to%20remove.
https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.groupby.html
https://www.w3schools.com/python/pandas/ref_df_agg.asp#:~:text=Definition%20and%20Usage,of%20the%20aggregate()%20method.
https://scales.arabpsychology.com/stats/how-to-add-title-to-pandas-dataframe/
https://www.geeksforgeeks.org/bar-plot-in-matplotlib/
