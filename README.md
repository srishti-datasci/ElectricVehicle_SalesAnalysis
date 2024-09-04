AtliQ Motors: Electric Vehicle Market Study in India
Problem Statement
AtliQ Motors is a leading automotive company in the USA, known for its expertise in electric vehicles (EVs). Over the past five years, AtliQ Motors has captured a significant 25% share of the electric and hybrid vehicle market in North America. As part of its strategic expansion, the company plans to introduce its top-selling models to the Indian market, where its current share is under 2%. To ensure a successful launch, Bruce Haryali, the head of AtliQ Motors India, has tasked the data analytics team with conducting a comprehensive market analysis of the EV/Hybrid segment in India. Peter Pandey, a data analyst in the team, has been assigned this critical project.

--- Ask: Key Analytical Questions
Chief: Bruce Haryali

Preliminary Analysis Questions:
1. Top & Bottom Performers: Identify the top 3 and bottom 3 manufacturers of 2-wheelers for FY 2023 and 2024 based on sales volume.
2. State Penetration: Which 5 states have the highest penetration rates for 2-wheeler and 4-wheeler EV sales in FY 2024?
3. Sales Decline: List the states that experienced a decline in EV sales from 2022 to 2024.
4. Quarterly Trends: Analyze the quarterly sales trends for the top 5 EV makers (4-wheelers) from 2022 to 2024.
5. Regional Comparison: How do EV sales and penetration rates in Delhi compare to Karnataka in 2024?
6. Growth Analysis: Calculate the compounded annual growth rate (CAGR) in 4-wheeler units for the top 5 manufacturers from 2022 to 2024.
7. State Growth: List the top 10 states with the highest CAGR in total vehicle sales from 2022 to 2024.
8.Seasonal Trends: Identify the peak and low season months for EV sales based on data from 2022 to 2024.
9.Future Projections: Estimate the projected EV sales (2-wheelers and 4-wheelers) for the top 10 states by penetration rate in 2030, using the CAGR from previous years.
10.Revenue Growth: Calculate the revenue growth rate for 4-wheelers and 2-wheelers in India for 2022 vs 2024 and 2023 vs 2024, assuming an average unit price (85K for 2-wheelers, 15L for 4-wheelers).
Secondary Analysis Questions:
1.Customer Motivation: What were the primary reasons for customers choosing 4-wheeler EVs in 2023 and 2024 (e.g., cost savings, environmental concerns, government incentives)?
2.Impact of Subsidies: How have government incentives and subsidies influenced the adoption rates of 2-wheelers and 4-wheelers? Which states provided the most subsidies?
3.Charging Infrastructure: What is the correlation between the availability of charging stations and EV sales/penetration rates in the top 5 states?
4.Brand Ambassador: Who would be an ideal brand ambassador for AtliQ Motors' EV/Hybrid launch in India and why?
5.Manufacturing Location: Which Indian state is ideal for establishing a manufacturing unit, considering subsidies, ease of doing business, and government stability?
6.Recommendations: Provide your top 3 recommendations for AtliQ Motors' strategy in India.
--- Prepare: Data Collection & Organization

   
Data Sources:
The data is available on the Codebasics website(https://codebasics.io/challenge/codebasics-resume-project-challenge), which consolidates various datasets for analysis. Additionally, the raw data can be explored on the Vahan Sewa platform(https://vahan.parivahan.gov.in/vahan4dashboard/vahan/view/reportview.xhtml), which provides public access to vehicle registration information.
Dataset Structure:
The data used in this analysis is structured into three CSV files and one text file (metadata):

dim_date.csv: Contains date-related information, including fiscal year and quarter details.
electric_vehicle_sales_by_makers.csv: Provides sales data by vehicle category and manufacturer.
electric_vehicle_sales_by_state.csv: Includes sales data categorized by state and vehicle type.
--- Process: Data Cleaning & Transformation

Tools:
Power BI: Used for data visualization and analysis.
Power Query: Utilized for data cleaning and transformation.
QuickTime Player & Power Point Presentation: Employed for creating presentations and recording video.


Data Cleaning Steps:
Duplication Removal: Checked and eliminated duplicate records.
Formatting: Ensured consistency in the data, such as standardizing state names (e.g., "DND" to "Dadra Nagar and Haveli & Daman Diu").
In the case of Kerala for the fiscal year 2024, a discrepancy was found where for the month of January the total vehicles sold were recorded as 164, while electric vehicles sold were 734. This inconsistency suggested a data entry error. To correct this, the total vehicle count was replaced with the median of total vehicle sales values for Kerala for the fiscal year 2024 in the 4-wheeler category. The median(13,932) was chosen over the mean due to the presence of the extreme outlier (164), which would have skewed the mean value.

4. Analyze: Key Metrics & Insights
Tools:
Power BI: Used to perform in-depth analysis and visualization of the data.
Important Metrics:
Fiscal Year: The fiscal year in India runs from April 1st to March 31st of the following year.
Penetration Rate: Indicates the proportion of EVs sold as a percentage of total vehicle sales in a specific region or category.
Compound Annual Growth Rate (CAGR): Measures the annual growth rate of sales over a specified period.
Summary
Through this project, AtliQ Motors aims to gain a deeper understanding of the Indian EV market by analyzing sales data, identifying trends, and making strategic recommendations. The insights gathered will help the company make informed decisions regarding its expansion into India.



Live Dashboard (https://app.powerbi.com/view?r=eyJrIjoiNDk4ZTM2Y2QtZmNmMC00NTM1LWE1OWUtMWJhZjRkYWM5YzgyIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)
