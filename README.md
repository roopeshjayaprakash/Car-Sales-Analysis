# Car-Sales-Analysis

## Project Overview :
### KPI Requirements

1. Sales Overview:
  Year-to-Date (YTD) Total Sales
  Month-to-Date (MTD) Total Sales
  Year-over-Year (YOY) Growth in Total Sales
  Difference between YTD Sales and Previous Year-to-Date (PTYD) Sales
2. Average Price Analysis:
  YTD Average Price
  MTD Average Price
  YOY Growth in Average Price
  Difference between YTD Average Price and PTYD Average Price
3. Cars Sold Metrics:
  YTD Cars Sold
  MTD Cars Sold
  YOY Growth in Cars Sold
  Difference between YTD Cars Sold and PTYD Cars Sold

### Charts in the Project:

1. YTD Sales Weekly Trend: Display a line chart illustrating the weekly trend of YTD sales. The X-axis should represent weeks, and the Y-axis should show the total sales amount.
2. YTD Total Sales by Body Style: Visualize the distribution of YTD total sales across different car body styles using a Pie chart.
3. YTD Total Sales by Color: Present the contribution of various car colors to the YTD total sales through a pie chart.
3. YTD Cars Sold by Dealer Region: Showcase the YTD sales data based on different dealer regions using a map chart to visualize the sales distribution geographically.
5. Company-Wise Sales Trend in Grid Form: Provide a tabular grid that displays the sales trend for each company. The grid should showcase the company name along with their YTD sales figures.
6. Details Grid Showing All Car Sales Information: Create a detailed grid that presents all relevant information for each car sale, including car model, body style, colour, sales amount, dealer region, date, etc

## Steps invloved:
1. Data Exploration and Standardisation:
   ![Project DATA Quality](https://github.com/user-attachments/assets/8fb65e79-256f-4cd9-9185-a5c74ac1049a)
   Checking for any inconsistensies in the Data through Power Query

    ![P2 Data Cleaning 2](https://github.com/user-attachments/assets/872d3b72-fa2d-4ca0-ba9e-97966de93ed3)
   Standardising the data by renaming the Data within the same category but different labels given

   ### for performing any Time Intelligence functions it is recommended to use calendar table

   ![DAX Function1](https://github.com/user-attachments/assets/b5fab81f-f68d-4dfe-aa6b-8eae61fb9804)

   Creating Calendar Table using DAX function
    Populating the table with Month, Year, Date columns using DAX functions for performing comparitive analysis.
![DAX 2](https://github.com/user-attachments/assets/3ceefa90-8e3e-4226-8c29-729e064d8f2a)
![DAX3](https://github.com/user-attachments/assets/6357b2b4-9af5-4077-9831-7fa47f86bd3f)
![DAX4](https://github.com/user-attachments/assets/22a31654-eb94-4b42-ac5c-d3cf284fed80)

3. Data Modeling:
   
   After the table was created we had to create a connection between the calendar table and the Car Data Table.
   
   

   
