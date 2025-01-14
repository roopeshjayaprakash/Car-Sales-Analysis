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

2. Data Modeling:
   ![Model Connection 0](https://github.com/user-attachments/assets/30bc4235-b2ed-4899-ab18-f4820d8959c1)

   Establishing relationshop between the columns
   Date Column is the primary key on which the tables shall be connected
   ![Model Connection 1](https://github.com/user-attachments/assets/6774cdf5-bf04-42cf-818b-6d33fd67fafc)

3. Dashboard Design
   Background Layout 
   ![Car Sales Background 1](https://github.com/user-attachments/assets/984f5644-2298-485c-be8b-e284299f14db)

   Advanced Calculations for creating measures
   ![Measure2](https://github.com/user-attachments/assets/3e759862-b5ca-4997-a1e2-dd265978b3d3)
   
   
![measure3](https://github.com/user-attachments/assets/1930d426-ec97-40fc-a0b3-8c74ea31e33d)

    ![Measure YoY (1)](https://github.com/user-attachments/assets/f4484315-d5d4-4ebf-8c98-4e010450a05c)

4. Dynamic Features:
   ![Dynamic](https://github.com/user-attachments/assets/5c027227-e70b-4f5d-bae4-56e78f7d3991)
![Dynamic colour changing rules](https://github.com/user-attachments/assets/82f36d2d-3d92-4b03-b705-88a5ef9d96ae)![Dyna](https://github.com/user-attachments/assets/ac402f74-f84d-4834-a29d-3a019751bdf8)![Dynamic colour changing rules 2 Avg Price Diff](https://github.com/user-attachments/assets/66cce1ed-b402-488b-97e2-492533aa0204)

5. Dashboard Overview:
   

![Dashboard Details Page](https://github.com/user-attachments/assets/bd8a2fb1-953b-4223-a487-a30c576296b4)![Dashboard Overview Page](https://github.com/user-attachments/assets/69dd57a1-cc04-4630-86bc-2570fc70c45c)

