# YouTube-Channel-Performance-Analysis-Using-BI
## Project Overview
This project aims to apply **Business Intelligence** (BI) techniques to analyze the performance and efficiency of YouTube channels on a global scale. By leveraging data from the **Global YouTube Statistics 2023** dataset, this project explores key performance indicators (KPIs) such as subscriber count, video views, upload frequency, video length, category, and country of origin. Our goal is to identify trends, uncover factors influencing channel success, and provide actionable insights for content creators to optimize channel performance.

<p align="center">
  <img src="https://github.com/nnbankdeyu/YouTube-Channel-Performance-Analysis-Using-BI/blob/main/youtube%20logo.png" alt="Youtube logo">
</p>

**Course**: Business Intelligence
Institution: University of Economics Ho Chi Minh City (UEH) - School of Technology and Design
Instructor: Phạm Thị Thanh Tâm, MSc

**Team Members**
- Nguyễn Đào Giang
- Võ Ngọc Mỹ Kim
- Nguyễn Thị Ngọc Nhi
- Văn Ngọc Như Quỳnh
- Nguyễn Ngọc Phương Trinh
- Nguyễn Nhật Thảo Vy

## Project Objective
The main objective of this project is to analyze YouTube channel performance by evaluating factors such as:
- Subscriber growth
- Video view trends
- Frequency of uploads
- Video length and engagement
- Categories and content types
- Regional and country-specific trends

We aim to provide insights to help content creators understand how these factors affect their channel's reach, visibility, and engagement, and suggest strategies to enhance their performance in a competitive digital environment.

## Business Problem and Dataset
With over 2.5 billion users worldwide, YouTube is a leading platform for content creators. However, creators face increasing challenges in standing out due to rising competition, algorithm changes, and shifting audience preferences. The project investigates the trends that affect YouTube channel performance, utilizing data from Kaggle's Global YouTube Statistics 2023 dataset. This dataset contains key information on top-performing YouTube channels, including:
- Number of subscribers
- Total video views
- Monthly and yearly earnings
- Category and type of content
- Country of origin

The dataset includes 995 records and 28 attributes, such as `rank`, `subscribers`, `video_views`, `category`, and `created_year`.

## Methodology
### 1. ETL Process:
**Extract**: We extracted the Global YouTube Statistics 2023 dataset from Kaggle.

**Transform**:
- Cleaned the dataset by removing duplicates and irrelevant columns (e.g., Latitude, Longitude).
- Handled missing values in fields such as Category, Country, Channel Type, and ranks by replacing them with appropriate default values or means.
- Corrected data inconsistencies, such as invalid characters in the Youtuber field, by standardizing names and eliminating extraneous characters.

**Load**: The transformed data was loaded into Power BI for further analysis and visualization.
  
### 2. Data Modeling:
Created dimension and fact tables to store structured information about:
- Time (e.g., year, month)
- Regions and countries
- YouTuber categories and awards
- Types of YouTubers (e.g., Entertainment, Music, People & Blogs)
- Video views and rankings

<p align="center">
  <img src="https://github.com/nnbankdeyu/YouTube-Channel-Performance-Analysis-Using-BI/blob/main/BI_Youtube_Data%20Modeling.png" alt="Youtube Data Modeling">
</p>  

Implemented transformations to align the data structure with Power BI's analytical capabilities.

### 3. Analysis:
We conducted the following analyses:
- Overview of YouTube Channel Performance: Analyzed general performance metrics of channels by subscriber count, video views, and upload frequency.
- Yearly and Monthly Performance: Tracked the performance trends of channels over time, identifying seasonal patterns and yearly growth.
- Regional and Country-based Analysis: Explored how geographical factors influence channel performance, with the U.S. and India leading in YouTuber presence.
- Category and Subcategory Performance: Investigated performance differences across categories such as Entertainment, Music, and People & Blogs, with Entertainment channels having the highest number of top performers.
- YouTuber Types and Awards: Analyzed how YouTube Creator Awards (e.g., Silver, Gold, Diamond Play Buttons) correlate with subscriber counts and views.

<p align="center">
  <a href="https://github.com/nnbankdeyu/YouTube-Channel-Performance-Analysis-Using-BI/blob/main/BI_Youtube_Dashboard_Reports.pdf">View Full Report (PDF)</a>
</p>


[View Full Report](https://github.com/nnbankdeyu/YouTube-Channel-Performance-Analysis-Using-BI/blob/main/BI_Youtube_Dashboard_Reports.pdf)


## Key Insights
- **Growth Trends**: YouTube channels have shown consistent growth over the years, but subscriber trends have plateaued for top-performing channels in recent years, likely due to increased competition and changing viewer preferences.
- **Regional Insights**: The majority of top YouTube creators come from India and the United States, with channels in these regions showing the highest engagement and subscription rates.
- **Content Categories**: Categories like Entertainment and Music dominate in terms of both channel count and viewership, while niche categories like Nonprofits & Activism and Autos & Vehicles have much smaller representation.
- **Influence of Video Length and Frequency**: Channels with higher upload frequency and longer video content tend to have better subscriber growth and viewer engagement.
- **Impact of YouTube Creator Awards**: Channels with YouTube Creator Awards tend to exhibit higher engagement metrics, indicating the importance of community recognition.

## Tools and Technologies
- **Python**: Used for data preprocessing and cleaning, including handling missing data and transforming raw data into usable formats.
- **Power BI**: Utilized for data visualization, modeling, and performing detailed analysis. Dashboards were created to present insights clearly and effectively.
- **Excel**: Employed during the initial stages for exploratory data analysis (EDA) and descriptive statistics.

## Challenges
- **Data Quality Issues**: Handling missing and inconsistent data was a significant part of the data preprocessing stage, requiring a robust approach to ensure clean, usable data.
- **Complexity of Analysis**: Given the large variety of categories and countries, segmentation and categorization required careful planning to ensure meaningful insights could be drawn.

## Conclusion and Recommendations
This project provided actionable insights into YouTube channel performance, highlighting critical factors such as upload frequency, content type, and regional trends that affect channel success. Content creators are encouraged to:
- Increase video upload frequency and maintain high-quality content to boost subscriber growth.
- Tailor content based on regional preferences and viewer habits.
- Focus on achieving YouTube Creator Awards to increase community engagement and channel visibility.
