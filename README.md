# Experiment-19
# Aim
Real-World and Interactive Visualizations.
# Theory
1. import pandas as pd – Imports the Pandas library as pd for data handling and DataFrame operations in python.
2. import plotly.express as px – Imports Plotly Express as px for creating interactive charts and visualizations.
3. pd.DataFrame() – Creates a Pandas DataFrame (table structure) to store and organize data for analysis.
4. fig = px.treemap(df, path=['Department'], values='Budget', title="sara") – Creates a Plotly treemap chart from the DataFrame where each Department box size represents Budget, with the title "sara".
5. fig.show() – Displays the treemap chart in the output.
6. import numpy as np – Imports NumPy as np for numerical calculations and array handling.
7. import matplotlib.pyplot as plt – Imports Matplotlib plotting module as plt for creating charts.
8. from scipy.cluster.hierarchy import dendrogram, linkage – Imports dendrogram and linkage functions for hierarchical clustering.
9. data = np.array([[5, 3], [10, 15], [15, 12], [24, 10], [30, 30]]) – Creates a NumPy array containing sample 2D data points.
10. linked = linkage(data, method='ward') – Performs hierarchical clustering on the data using Ward’s method.
11. plt.figure(figsize=(6,4)) – Creates a new figure with width 6 inches and height 4 inches.
12. dendrogram(linked) – Plots the dendrogram for the clustered data.
13. plt.xlabel("Data Points") – Labels the x-axis as "Data Points".
14. plt.ylabel("Distance") – Labels the y-axis as "Distance".
15. from matplotlib_venn import venn2 – Imports the venn2 function to create a two-set Venn diagram in python.
16. venn2([A, B], set_labels=('Set A', 'Set B')) – Creates a Venn diagram for Set A and Set B with the given labels.
17. import plotly.graph_objects as go – Imports Plotly Graph Objects as go for creating interactive visualizations.
18. fig = go.Figure(data=[go.Sankey( – Creates a new figure containing a Sankey diagram.
19. node=dict(label=["Admission", "First Year", "Second Year", "Placed"]), – Defines the nodes of the Sankey chart with given labels.
20. link=dict( – Starts defining the flow connections between nodes.
21. source=[0, 1, 2], – Specifies the starting node indexes for each flow.
22. target=[1, 2, 3], – Specifies the ending node indexes for each flow.
23. value=[100, 80, 60]) – Sets the flow values between connected nodes.
24. px.scatter_3d(df, – Starts creating a Plotly 3D scatter plot using the DataFrame df.
25. x='Study_Hours', – Sets the x-axis values as the Study_Hours column.
26. y='Marks', – Sets the y-axis values as the Marks column.
27. z='Attendance', – Sets the z-axis values as the Attendance column.
28. fig = go.Figure() – Creates a new Plotly figure object for interactive charts.
29. fig.add_trace(go.Scatterpolar(r=values, theta=skills, fill='toself', name='Student Skills')) – Adds a radar/polar chart trace using values as radius, skills as categories, fills the shape, and labels it as "Student Skills".
# Conclusion
Real-World and Interactive Visualizations in Python help present data in a dynamic and meaningful way using libraries like Plotly, Matplotlib, and Seaborn. Charts such as radar charts, 3D plots, dashboards, maps, and interactive graphs allow users to explore data through zooming, hovering, filtering, and animations. These visualizations improve user engagement, make complex information easier to understand, and are widely used in business, education, finance, healthcare, and data science.






