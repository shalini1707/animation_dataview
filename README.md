# animation_dataview
Import Plotly Express:
The first line of code imports the Plotly Express library as px. Plotly Express is a high-level data visualization library that simplifies the creation of interactive visualizations.

Create an Animated Bar Chart:
The px.bar() function is used to generate an animated bar chart. The un_q1 variable represents the data source for the chart. The parameters used are as follows:

x="temp_max": This specifies that the 'temp_max' column will be used as the values along the x-axis of the bar chart.
y="date": This sets the 'date' column to determine the values along the y-axis.
hover_name="weather": The 'weather' column is used to provide additional information when hovering over the bars.
color="precipitation": The color of the bars is determined by the 'precipitation' column.
animation_frame="wind": The 'wind' column is used to create the animation frames, allowing viewers to see changes over time.
Display the Chart:
The last line, fig.show(), displays the generated animated bar chart. This command is what renders the visualization so that it can be viewed and interacted with.

![image](https://github.com/shalini1707/animation_dataview/assets/134158826/4c7675d1-a91c-4937-8c52-80152142bb60)












