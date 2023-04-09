# Module-13-Challenge
Module 13 Notes
## Overview

Data Analysts, not only need to analyze data but also need to visualize the data. This is helpful in conveying your results to a broad audience. 

As an experienced Data Analyst, I have found Data Visualizes for the web to help my audience(my clients)  better understand my findings.   

By the end of this module, as the assigned Data Analyst,  will be able to: 
•	Create basic plots with Plotly, including bar charts, line charts, and pie charts.

•	Use D3.json() to fetch external data, such as CSV files and web APIs.

•	Parse data in JSON format.

•	Use functional programming in JavaScript to manipulate data.

•	Use JavaScript's Math library to manipulate numbers.

•	Use event handlers in JavaScript to add interactivity to a data visualization.

•	How to use interactivity to enhance your visualizations.

•	Deploy an interactive chart to GitHub Pages.


##Purpose 

(This module is built around a project that mirrors a real-world scenario that would require data analysis and visualization, as outlined in Module 13. )

As a Data Analyst, I am helping Roza, the client, to create engaging and dynamic charts. My role is to help Roza identify the best way to share her information with her audience. Roza has a partially completed dashboard that she needs to finish. She has a completed panel for demographic information and now needs to visualize the bacterial data for each volunteer. 

Specifically, her volunteers should be able to identify the top 10 bacterial species in their belly buttons. That way, if Improbable Beef identifies a species as a candidate to manufacture synthetic beef, Roza's volunteers will be able to identify whether that species is found in the

(As per module 13) In addition, as the assigned Data Analyst, I will illustrate how java script can better convey Roza/s data analysis conclusions. This goal will be achieved by utilizing the following:
•	Java to convey data visualization that is both attractive (user friendly), accessible, and interactive. 

•	Plotly which is a Java Visualization library which offers interactivity. 


##Deliverable 1: Create a Horizontal Bar Chart (35 points)

Using your knowledge of JavaScript, Plotly, and D3.js, create a horizontal bar chart to display the top 10 bacterial species (OTUs) when an individual’s ID is selected from the dropdown menu on the webpage. 

1.	In Step 1, we’ve provided the code for the buildCharts(); function that contains the argument sample, which is the sample that is selected from the dropdown menu.

2.	In Step 2, we’ve provided the code to retrieve the samples.json file using the d3.json().then() method.

3.	In Step 3, create a variable that has the array for all the samples.

![image](https://user-images.githubusercontent.com/117233641/230756736-a98b2800-2cf6-4970-9d52-7d07392e4dbe.png)
 

4.	In Step 4, create a variable that will hold an array that contains all the data from the new sample that is chosen from the dropdown menu. To retrieve the data from the new sample, filter the variable created in Step 3 for the sample id that matches the new sample id chosen from the dropdown menu and passed into the buildCharts() function as the argument.

5.	In Step 5, create a variable that holds the first sample in the array.

![image](https://user-images.githubusercontent.com/117233641/230756741-aa58d03e-7362-4611-a622-8093f6e7b722.png)

 

6.	In Step 6, create variables that have arrays for otu_ids, otu_labels, and sample_values.

![image](https://user-images.githubusercontent.com/117233641/230756749-289a1026-34dd-4ca7-85ab-3a4f3d2d5751.png)

 
7.	In Step 7, create the yticks for the bar chart.

![image](https://user-images.githubusercontent.com/117233641/230756754-7df70798-e283-423e-9a2a-5f3c669057b8.png)
 

In Steps 8-10, create the trace object, the layout, and Plotly.newPlot() function for the horizontal bar chart.

8.	In Step 8, create the trace object for the bar chart, where the x values are the sample_values and the hover text for the bars are the otu_labels in descending order.

9.	In Step 9, create the layout for the bar chart that includes a title.

10.	In Step 10, use the Plotly.newPlot() function to plot the trace object with the layout.

 ![image](https://user-images.githubusercontent.com/117233641/230756759-5ff25654-ac43-43e0-961b-adf5d3458581.png)

![image](https://user-images.githubusercontent.com/117233641/230756775-6cae7f8b-a6d7-494a-8b4d-b05f7d0a9179.png)




##Deliverable 2: Create a Bubble Chart (30 points)

Using your knowledge of JavaScript, Plotly, and D3.js, create a bubble chart that will display the following when an individual’s ID is selected from the dropdown menu webpage:
      •	The otu_ids as the x-axis values.

      •	The sample_values as the y-axis values.

      •	The sample_values as the marker size.

      •	The otu_ids as the marker colors.

      •	The otu_labels as the hover-text values.

 ![image](https://user-images.githubusercontent.com/117233641/230756800-d5ab0dac-83f9-4e91-a5eb-0ff92746ed93.png)


bubble chart image:

 ![image](https://user-images.githubusercontent.com/117233641/230756816-332849e9-38e6-4382-837b-7ae13378c795.png)


Deliverable 3: Create a Gauge Chart (20 points)

Using your knowledge of JavaScript, Plotly, and D3.js, create a gauge chart that displays the weekly washing frequency's value, and display the value as a measure from 0-10 on the progress bar in the gauge chart when an individual ID is selected from the dropdown menu.

![image](https://user-images.githubusercontent.com/117233641/230756828-8d8c33a3-e790-43d8-a455-d9b089a707d5.png)

 ![image](https://user-images.githubusercontent.com/117233641/230756842-383ef4a1-0263-4b09-8a9a-c2b1a0c988fd.png)
 


##Deliverable 4: Customize the Dashboard (15 points)

Use your knowledge of HTML and Bootstrap to customize the webpage for your dashboard.
Customize your dashboard with three of the following:

      o	Add an image to the jumbotron.

      o	Add background color or a variety of compatible colors to the webpage.

      o	Use a custom font with contrast for the colors.

      o	Add more information about the project as a paragraph on the page.

      o	Add information about what each graph visualizes, either under or next to each graph.

      o	Make the webpage mobile-responsive.

      o	Change the layout of the page.

      o	Add a navigation bar that allows you to select the bar or bubble chart on the page.

 ![image](https://user-images.githubusercontent.com/117233641/230756852-b06e6625-d7b1-40ad-8e58-3c0ca26a29c1.png)

