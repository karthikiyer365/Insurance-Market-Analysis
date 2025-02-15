# Insurance Market Analysis
Analysis of Indian Insurance Market using open-source data. 
The primary objective of this project is to understand the performance of the different PSBs, Commercial and Nationalized banks from 2020 - 2024 to identify the affect of Covid-19 and development of the organizations since. We look at data from January 2020 for a pre-Covid look and the trend hence.

We compare at two levels. 
    A - We take a look at the differnt industries level such as Agriculture, Marine, Motor, Liability and Machinery to understand the comparitive investment of the different insurance lenders to understand market leader performance. 
    B - We take a look at the organizational level, to understand the growth of the organizations in the different insurance markets from 2020 - 2024  


This repository consists of two files with the work and details as follows:
1. Insurance Data Reader.ipynb
    
    This file is a web scraper file, used to fetch the data available at the [GIC Corporations public website](https://www.gicouncil.in/statistics/industry-statistics/segment-wise-report-on-homepage/).
      

    What the file does:
    - Parses the website to extract the Cloud links for the Segment Wise reports for Q1, Q2, Q3, Q4 from 2020 - 2024.
    - Identifies the missing report links and updates them from the recevied reports.
    - Extracts the data from the manufactured links to form the dataframe using pandas.
    - Cleans and Generates calucalted columns

    The output of this extraction process is sent to the PowerBi file.

2. Insurance Market Portfolio.pbix
    
    This file is the Dashboard to view our finding. It has two sheets.
    Sheet 1 - Industry level - Trend chart to view how different organizations spends in each Quarter for any give industry.
    Sheet 2 - ORganization level - Division charts to identify the investment growth of any given organization in different industries.
