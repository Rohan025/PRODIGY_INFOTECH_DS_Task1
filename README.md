# PRODIGY_INFOTECH_DS_Task1
The script begins by importing the essential libraries: pandas for data handling and matplotlib.pyplot for visual representation.

It then loads an Excel file called "Land_use_per_gram_of_protein.xlsx" into a DataFrame with pd.read_excel(). This DataFrame will contain the data needed for the bar chart.

Next, the script extracts the required data for the bar chart from the DataFrame. It assigns the 'Food_Type' column values to the variable x and the 'Land_Use_in_sqm' column values to the variable y.

A new figure is created with dimensions 10x6 inches using plt.figure(figsize=(10, 6)).

The script then generates a bar chart using plt.bar(x, y), with x values as the x-axis labels and y values as the heights of the bars.

The chart is customized by labeling the x-axis, y-axis, and the title using plt.xlabel(), plt.ylabel(), and plt.title(), respectively. The x-axis is labeled 'Food Type', the y-axis 'Land Use (sqm)', and the chart is titled 'Bar Chart'.

Finally, the chart is displayed using plt.show(), which either opens a separate window or shows the chart directly in a Jupyter Notebook or a similar environment.





