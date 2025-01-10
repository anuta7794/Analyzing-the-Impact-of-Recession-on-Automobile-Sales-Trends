# Analyzing the Impact of Recession on Automobile Sales Trends in Python

### Overview:

This Project is a part of the "Data Visualization with Python" IBM course and aims to showcase data analysis skills in Python such as:

+ Implementing data visualization techniques and plots using Python libraries, such as **_Matplotlib_** and **_Seaborn_**;

+ Creating different types of charts and plots such as line, area, histograms, bar, pie, box, scatter, and bubble;

+ Generating interactive dashboards containing scatter, line, bar, bubble, and pie, charts using the Dash framework and Plotly library.

### Scenario:

I have been hired by XYZAutomotives as a data scientist. My first task is to analyze the historical data and give the company directors insights on how the sales were affected during times of recession. I will provide a number of charts/plots to visualize the data and make it easy for the directors to understand your analysis.

In this project I will create visualizations using **_Matplotlib_**, **_Seaborn_**, and **_Pandas_**.

### Dataset:

The data used in this project has been artifically created by IBM Skills Network for the purpose of this assignment only. No real data has been used.

The dataset includes the following variables:

1.	Date: The date of the observation.
2.	Recession: A binary variable indicating recession perion; 1 means it was recession, 0 means it was normal.
3.	Automobile_Sales: The number of vehicles sold during the period.
4.	GDP: The per capita GDP value in USD.
5.	Unemployment_Rate: The monthly unemployment rate.
6.	Consumer_Confidence: A synthetic index representing consumer confidence, which can impact consumer spending and automobile purchases.
7.	Seasonality_Weight: The weight representing the seasonality effect on automobile sales during the period.
8.	Price: The average vehicle price during the period.
9.	Advertising_Expenditure: The advertising expenditure of the company.
10.	Vehicle_Type: The type of vehicles sold; Supperminicar, Smallfamiliycar, Mediumfamilycar, Executivecar, Sports.
11.	Competition: The measure of competition in the market, such as the number of competitors or market share of major manufacturers.
12.	Month: Month of the observation extracted from Date.
13.	Year: Year of the observation extracted from Date.

Recession Periods:

recession period 1 - year 1980

recession period 2 - year 1981 to 1982

recession period 3 - year 1991

recession period 4 - year 2000 to 2001

recession period 5 - year end 2007 to mid 2009

recession period 6 - year 2020 -Feb to April (Covid-19 Impact).

### Steps:

This Project is completed in 2 Parts:

•	Part 1: Creating Visualizations using Matplotlib and Seaborn 
•	Part 2: Creating Dashboard using Plotly and Dash

### _Part 1: Creating Visualizations using Matplotlib and Seaborn_ 

1.1: Developing a **_line chart_** using the functionality of **_pandas_** to show how automobile sales fluctuate from year to year.

![1_Line_Plot_1](https://github.com/user-attachments/assets/d9ee49c1-9d8f-46cb-a04e-e00f176463f0)

1.2: Plotting different lines for categories of vehicle type and analyze the trend to answer the question “Is there a noticeable difference in sales trends between different vehicle types during recession periods?”

![2_Line_Plot_2](https://github.com/user-attachments/assets/45fb0f9d-6007-45b1-9d53-daa1d622781b)

**Insight:** From this plot, we can understand that during recession period, the sales for 'Sports type vehicles' declined because of the high cost of the vehicle while sales of the superminicar and smallfamilycar increased while sales of the superminicar and smallfamilycar increased.

1.3: Using the functionality of **_Seaborn Library_** to create a visualization to compare the sales trend per vehicle type for a recession period with a non-recession period; comparing the sales of different vehicle types during a recession and a non-recession period using the functionality of **_Seaborn Library_** to create this visualization.

![3_Bar_Chart](https://github.com/user-attachments/assets/a11400e1-2495-4600-9462-49a82a892339)

**Insight:** from this plot, we can understand that there is a drastic decline in the overall sales of the automobiles during recession. However, the most affected type of vehicle is executivecar and sports.

1.4: Using **_sub plotting_** to compare the variations in GDP during recession and non-recession period by developing **_line plots_** for each period.

![4_Subplot](https://github.com/user-attachments/assets/8ba9eac2-aa5e-4457-88fb-f7388d49d0a7)

**Insight:** from this plot, it is evident that during recession, the GDP of the country was in a low range, might have affected the overall sales of the company.

1.5: Developing a **_bubble plot_** for displaying the impact of seasonality on Automobile Sales.

![5_Bubble_Plot](https://github.com/user-attachments/assets/bd8fede4-0161-40ef-bd2f-3693b9d937a5)

**Insight:** from this plot, it is evident that seasonality has not affected on the overall sales. However, there is a drastic raise in sales in the month of April.

1.6: Using the functionality of **_Matplotlib_** to develop a **_scatter plot_** to identify the correlation between average vehicle price relate to the sales volume during recessions.

![6_Scatter_Plot](https://github.com/user-attachments/assets/1304761e-c8e5-41b0-90c7-f1418f1ee68c)

1.7: Creating a **_pie chart_** to display the portion of advertising expenditure of XYZAutomotives during recession and non-recession periods.

![7_Pie_Chart_1](https://github.com/user-attachments/assets/03ba6731-dc06-4b64-89e8-22fbde5d9c34)

**Insight:** from the above plot, it seems ABCAutomotives has been spending much more on the advertisements during non-recession periods as compared to during recession times.

1.8: Developing a **_pie chart_** to display the total Advertisement expenditure for each vehicle type during recession period.

![8_Pie_Chart_2](https://github.com/user-attachments/assets/9b7c1629-2fe9-43e7-a65f-8803fefb65d2)

**Insight:** during recession the advertisements were mostly focused on low price range vehicle. A wise decision.

1.9: Developing a **_line plot_** to analyze the effect of the unemployment rate on vehicle type and sales during the Recession Period.

![9_Line_Plot_3](https://github.com/user-attachments/assets/bd0aa0bb-02c9-4c25-b151-5993097f3fd4)

**Insight:** During recession, buying pattern changed, the sales of low range vehicle like superminicar,smallfamilycar and Mediumminicar tend to increase.

### _Part 2: Creating Dashboard using Plotly and Dash_

My second task is to create a suitable **_dashboard_** and add in user interactions so that the directors can select the data they want to review without the need to request new plots.

2.1: Creating a **_Dash application_** and give it a meaningful title.

2.2: Adding drop-down menus to your dashboard with appropriate titles and options.

2.3: Adding a division for output display with appropriate id and class name property

2.4: Creating **_Callbacks_**; Defining the **_callback function_** to update the input container based on the selected statistics and the output container.

2.5: Creating and display graphs for Recession Report Statistics.

![14_RecessionReportGraphs](https://github.com/user-attachments/assets/6860d61b-4c8c-4556-997f-a9b74d7d6aa0)

2.6: Creating and display graphs for Yearly Report Statistics.

![15_YearlyReportGraphs](https://github.com/user-attachments/assets/7b3372ed-008b-4abd-b984-076a68ad0a57)

