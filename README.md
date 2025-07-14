# Muhammad Cikal Merdeka - Data Analytics/Science Portofolio (Guidance Repository)

## About

> **UPDATE MARCH 2025: My summary of projects now available on my [Canva portfolio website](https://mcikalmerdeka.my.canva.site/). Please refer to that link for all project details and updates. This repository will be maintained solely for [certification documentation](https://github.com/mcikalmerdeka/Data-Analyst-Scientist-Portofolio/tree/main#certificates).**

This repository serves to showcase my skills and as a platform to share my projects, and a way to track my progress in Data Analytics and Data Science-related topics.

<b>! Note : 
- Modifications have been made to several projects in alignment with the integration of recently acquired knowledge. It can be in the form of using a more effective method or simply adding new parameters to a code. Consistency in learning and improvement is the key.
- Sometimes the additional code has not been run yet, so it will appear that the output is not available. For example, I learned something new that is useful while working on Project 8, and the code for that new thing was copied and the syntax was adjusted according to Project 5, but it hasn't been run there yet. Although I already ran most of of them during my free time.
- Documentation or additional information about the new thing or even just a concept of something is sometimes added in a markdown cell below its code to serve as a reminder for me later on.</b>

## Table of Contents
* [About](https://github.com/mcikalmerdeka/Data-Analyst-Scientist-Portofolio?tab=readme-ov-file#about)
* [Portfolio Projects](https://github.com/mcikalmerdeka/Data-Analyst-Scientist-Portofolio?tab=readme-ov-file#portfolio-projects)
* [Certificates](https://github.com/mcikalmerdeka/Data-Analyst-Scientist-Portofolio/tree/main#certificates)

## Portfolio Projects
Here are some data analytics and data science projects I have worked on. The tech stack used varies for each project, but overall, the combined stack across all projects includes:

* SQL (PostgreSQL, MySQL, Microsoft Access)
* Python (numpy, pandas, scipy, matplotlib, seaborn, scikit-learn, etc)
* Microsoft Excel/Google Sheets
* BI Tools (Tableau, Power BI, Looker Studio, Metabase)
* Version Control (Git -> GitHub)
* Cloud Services / Data Warehousing Solutions (BigQuery, Snowflake)

### 1. Indonesia College Entrance Examination - UTBK 2019
* Repository : [Indonesia_College_Entrance_Examination_UTBK_2019 Codes (Python and SQL)](https://github.com/mcikalmerdeka/Indonesia-College-Entrance-Examination-UTBK-2019)

* Tableau Dashboard : [Link to Tableau Public Dashboard](https://public.tableau.com/app/profile/cikal.merdeka/viz/IndonesiaCollegeEntranceExamination-UTBK2019Result/IndonesiaCollegeEntranceExamination-UTBK2019ResultScience?publish=yes)

* Goal : To analyze and compile a report on the results of the 2019 UTBK (Academic Potential Test for State Universities) for both the Science & Technology (SAINTEK) and Social Humanities (SOSHUM) clusters.

* Description : UTBK SBMPTN is the annual college entrance exam held by and for state universities in Indonesia. This data was collected from a ranking site where exam takers could submit their score in order to gauge how well they did in comparison to others. There are about 147 thousand samples (out of 1.1 million total scores) and this data is not indicative of the whole 1.1 million dataset as it is collected from a third-party sources (with maybe some invalid data strewn in). This dataset also contains the major picked by those exam-takers.

* Personal Notes : This is my first personal project after 2.5 months of starting to learn data-related fields from scratch. I chose the education field because it is one of the domain I have a passion and interest in, and if given the opportunity, I would like to experience what's it like to work in that domain in the future, though i also want to learn about other domains as well like e-commerce, retail, finance, etc. There are several shortcomings in this project, but I did my best and learned many technical and non-technical aspects, one of which is the difficulty of finding raw data in Indonesia compared to English-language data. Most of the data is confined within government or private institutions, and very little is available as open-source data.

### 2. US Based Ecommerce Company Sales Performance
* Repository : [Ecommerce Sales Codes (Python and SQL)](https://github.com/mcikalmerdeka/US-Based-Ecommerce-Company-Sales-Performance)

* Tableau Dashboard : [Link to Tableau Public Dashboard](https://public.tableau.com/app/profile/cikal.merdeka/viz/USBasedEcommerceCompanySalesPerformance/SalesPerformanceDashboard?publish=yes)

* Goal : To analyze key indicators in a ecommerce company sales data in order to gain insights into their business performance.

* Description : A US Based Ecommerce Sales Company wants us to create a sales dashboard showing information of YTD sales and various others to generate insights for improving business performance. The given dataset contains information on 113 thousand sales records based on product categories, customer segments, cities, and states of customer residence, and various many others.

* Personal Notes : I am embarking on this project to enhance my proficiency in handling datasets with numerous variables and parameters, which also includes a time dimension represented by date values. Among the datasets known for encompassing a diverse range of columns, sales data, particularly in the realm of e-commerce, as i know is one of the most common and rich sources.

### 3. Ecommerce Google Ads Data Analysis
* Repository : [Ecommerce Google Ads Analysis](https://github.com/mcikalmerdeka/Ecommerce-Google-Ads-Data-Analysis)

* Looker Studio Dashboard : [Link to Looker Studio Dashboard](https://lookerstudio.google.com/reporting/90de1d92-08c9-47af-b13d-76bb93010a33)

* Goal : To analyze Google Ads data from an ecommerce company and find insights from the performance metrics of each campaign conducted.

* Description : This was originally from my bootcamp task on Looker Studio, but I think I would just add it to this list for kind of like a mini project. The dataset used is from Looker Studio's sample data of AdWords (now known as Google Ads) Data, which contains information about the metrics of each campaign. The task demanded us to formulate our own list of metrics to be displayed based on our own data understanding, and in this case, I am using ROAS (Return on Ad Spend) as the main metric to analyze its performance.

* Personal Notes : There is a drawback in using Looker Studio's sample data where the provided data is always updated. As a result, the display of performance metrics that was initially done in comparison to the previous period (the previous month) may be affected. The original dashboard presentation during the analysis can be viewed in the report file. I wanted to do more analysis using SQL or Python but unfortunately the sample data can't be downloaded.

### 4. Loan Prediction Based on Customer Behavior
* Repository : [Loan Prediction (Python)](https://github.com/mcikalmerdeka/Dackers)

* Goal :
  
  - Enhanced credit risk evaluation: Improve the assessment of credit risk by implementing machine learning models. (MAIN)
  - Increased efficiency: Streamline the credit risk assessment process for greater effectiveness and reduced processing time. (SECONDARY)

* Description : A lending company needs to verify loan applications from its prospective borrowers (customers). The manual verification procedure conducted by the company has resulted in numerous inaccurate assessments, leading to loans being granted to borrowers who ultimately fail to repay (default). This has proven detrimental to the company as it incurs financial losses without any return. Additionally, the manual verification process also consumes a considerable amount of time. Building on this issue, the company aims to develop an automated system that can predict the creditworthiness of prospective borrowers in the future based on past borrower data to reduce the selection of potential customers with high default risks.

* Personal Notes : This is the final project of the bootcamp I am currently attending, and the project has been ongoing since the first week of the new year in 2024, with the expectation to conclude by early March as there are still materials to study in class. I hold the role of a team leader, guiding my other 6 team members. In each stage of the project, I consistently create rough sketches (early start) of what the outcomes will look like so that task assignments for each team member can be done effectively.

### 5. British Airways Flight Booking Prediction
* Repository : [Flight Booking Prediction (Python)](https://github.com/mcikalmerdeka/British-Airways-Flight-Booking-Prediction)
 
* Goal : Improving the business metrics of Customer Acquisition Rate (The rate at which the airline acquires new customers who book flights or holidays) which enable British Airways to be proactive in acquiring potential customers by predicting their likelihood to book flights or holidays
 
* Description : The project aims to empower British Airways with a data-driven approach to customer acquisition, enabling the airline to predict and understand customer booking behavior. The success of the project lies in building a robust predictive model and translating its results into actionable strategies for acquiring customers before they embark on their holidays. Recognizing the evolving dynamics of customer behavior, the project emphasizes the need for airlines to be proactive rather than reactive
 
* Personal Notes : This is one of the major assignments for a course I'm taking, focusing on job simulation as a data scientist at British Airways. Since the boot camp I'm currently enrolled in has progressed to the modeling stage, I am now actively undertaking projects related to machine learning, specifically predictive modeling. In previous projects, my emphasis was more on descriptive and diagnostic analysis.

### 6. Airline Customer Value Analysis With Clustering Algorithms
* Repository : [Airline Customer Clustering (Python)](https://github.com/mcikalmerdeka/Airline-Customer-Value-Analysis-With-Clustering-Algorithms)
 
* Goal : Creating customer segmentation to analyze strategies and business recommendations for a specific group in an airline company.
 
* Description : An airline company intends to expand its business on their Frequent Flyer Program, a program created to motivate enrolled airline customers to accumulate points (also known as miles, kilometers, or segments) that can later be redeemed for air travel or other rewards. In this scenario, data scientists are tasked with dividing customers into several groups based on information that can depict the value of each customer.
 
* Personal Notes : This is one of the tasks from the bootcamp I am currently attending, focusing on unsupervised learning. However, in this case, I have made several further improvements, such as a more in-depth analysis in feature selection and the underlying thinking process, attempting to compare the results with other number of cluster, and so on.

### 7. Prediction of Solar Energy Potential Based on Weather and Location Data
* Repository : [Solar Energy Prediction (Python)](https://github.com/mcikalmerdeka/Prediction-of-Solar-Energy-Potential-Based-on-Weather-and-Location-Data)
 
* Goal : Analyzing the potential solar energy power (Watts) that can be generated based on the weather and location characteristics at a specific time.
 
* Description:

  * The anticipated surge in electricity demand, projected to increase by approximately 30% by 2035 according to the US Department of Energy, necessitates substantial investments in sustainable renewable energy resources to meet this growth.

  * Addressing this challenge could be facilitated through the adoption of solar energy, as suggested by the same report. It indicates the potential for solar energy to contribute up to 40% of the country's electricity supply by 2035, a significant increase from its current contribution of 3%.

  * In order to enhance the solar energy infrastructure, identifying new locations with the utmost potential for consistent solar electricity generation becomes crucial. Utilizing predictive modeling, based on diverse features, can aid in pinpointing such sites.

* Personal Notes : After studying machine learning algorithms, I became curious about their applications in my specific field of focus during my physics studies, which is solar energy research. Consequently, I attempted to find some research in this area and came across a paper that employs various machine learning techniques to predict power output for horizontal solar panels using 14 months of data collected from 12 northern-hemisphere locations. I utilized the raw dataset from this paper, which I found on Kaggle. While I am unsure if it represents only a sample or the entire dataset (very likely just sample data), it still serves as a valuable resource for learning about the analysis in solar energy.

### 8. Youtube Video Views Prediction
* Repository : [Youtube Views Prediction (Python)](https://github.com/mcikalmerdeka/Youtube-Video-Views-Prediction)
 
* Goal : To predict the number of views that a specific video will have when uploaded to the YouTube platform.
 
* Description : As a data scientist, we are requested by a client to analyze the number of views that a video is likely to obtain when uploaded to YouTube platform, utilizing historical statistical data. This includes factors such as upload time, trending duration, the quantity of tags used, and others. The project is aimed at understanding the algorithms of YouTube at the moment (dataset time), enabling the development of more effective content creation strategies for client in the future.
 
* Personal Notes : This is part of a supervised learning task from the boot camp I am attending. However, in this case, I have made several further improvements, such as trying different modeling algorithms, checking with combinations of other features in modelling, experimenting with the text features such as video titles, tags and description (this one is actually quite challenging since they are a mix between English and Indian), while also adding some additional explanations.

### 9. Enhancing PV Grid Management Through AC-Power Prediction
* Repository : [Prediction of AC-Power (Python)](https://github.com/mcikalmerdeka/Enhancing-PV-Grid-Management-Through-AC-Power-Prediction)
 
* Goal :
  
  * Analyzing the potential AC-Power generated in next couple of days for better grid management.
  * Identify the need for panel cleaning/maintenance through sensor and inverter data.
 
* Description: This data has been gathered at two solar power plants in India over a 34 day period. It has two pairs of files - each pair has one power generation dataset and one sensor readings dataset. The power generation datasets are gathered at the inverter level - each inverter has multiple lines of solar panels attached to it. The sensor data is gathered at a plant level - single array of sensors optimally placed at the plant.

* Personal Notes : In the previous solar energy prediction dataset, although predictions could still be made optimally, I realized that there were some limitations in the dataset that hindered in-depth analysis. Therefore, after i finished the project I searched for another dataset with different types of features and more well-documented data values in terms of sensor data recording over time, and the addition of important irradiation feature in solar cell analysis. Although this dataset does not provide information regarding geospatial aspects like dataset before, this is more interesting to play around regarding electrical data analysis.

### 10. Analyzing eCommerce Business Performance with SQL
* Repository : [eCommerce Business Performance (SQL)](https://github.com/mcikalmerdeka/Analyzing-eCommerce-Business-Performance-with-SQL)
 
* Goal : Analyzed eCommerce business data related to customer growth activity, product quality, and payment type to draw insights and business recommendation.
 
* Description: This dataset was generously provided by Olist, the largest department store in Brazilian marketplaces. The dataset has information of 100k orders from 2016 to 2018 made at multiple marketplaces in Brazil. Its features allows viewing an order from multiple dimensions: from order status, price, payment and freight performance to customer location, product attributes and finally reviews written by customers.

* Personal Notes : This project is the first of mini project creation activities from my extended data science bootcamp program in Rakamin, the next four project will also be assosiated with this program. I learned some new challenging things here that weren't deeply taught in the bootcamp program such as using some advanced SQL like window function, creating ERD, learning to write more readable SQL queries, etc.

### (More can be seen in my repositories, haven't add proper documentation for them in here) 

# Certificates

The knowledge I gained from these certifications is applied to the projects here. Some of the projects displayed here are also part of these certifications

- [LangChain - Develop AI Agents with LangChain & LangGraph](https://www.udemy.com/certificate/UC-ce89ae61-4853-4a37-8667-e9daa886a784/) (July 2025) - Udemy (Provided by Eden Marco)
- [Data Engineering 101: The Beginner's Guide](https://www.udemy.com/certificate/UC-e33b2c7f-f6f4-4d20-93e3-b0d899c66d45/) (June 2025) - Udemy (Provided by Seungchan Lee, Nami Kim, and DeepIntuitions AI)
- [AI-Powered A/B Testing](https://www.sololearn.com/en/certificates/CC-XDUYTIKK) (June 2025) - SoloLearn
- [Vibe Coding](https://www.sololearn.com/certificates/CC-5ABO34DW) (June 2025) - SoloLearn
- [Data Analytics with AI](https://www.sololearn.com/certificates/CC-3FNJOQAH) (June 2025) - SoloLearn
- [Prompt Engineering](https://www.sololearn.com/certificates/CC-JEJSEL29) (Apr 2025) - SoloLearn
- [Mathematics](https://learn.365datascience.com/c/a274dd427d) (Nov 2024) - 365 Data Science
- [Advanced Microsoft Excel](https://learn.365datascience.com/c/fe0fcfb85e) (Nov 2024) - 365 Data Science
- [Building Business Reports Using Power BI](https://learn.365datascience.com/c/4f592dbc0d) (Nov 2024) - 365 Data Science
- [Communication and Presentation Skills for Analysts and Managers](https://learn.365datascience.com/c/7b6b11f549) (Nov 2024) - 365 Data Science
- [Data Analysis with Excel Pivot Tables](https://learn.365datascience.com/c/2854240346) (Nov 2024) - 365 Data Science
- [Dates and Times in Python](https://learn.365datascience.com/c/d12f9843cc) (Nov 2024) - 365 Data Science
- [Power Query and Data Modeling](https://learn.365datascience.com/c/3455fad502) (Nov 2024) - 365 Data Science
- [Web Scraping and API Fundamentals in Python](https://learn.365datascience.com/c/2f7c16b191) (Nov 2024) - 365 Data Science
- [The Complete dbt (Data Build Tool) Bootcamp: Zero to Hero](https://www.udemy.com/certificate/UC-5a12a947-c8fb-40b3-85cf-f62e42214eb3/) (Oct 2024) - Udemy (Provided by Zoltan C. Toth & Miklos Petridisz)
- [dbt Fundamentals](https://credentials.getdbt.com/5a43fe14-4a58-47a6-9431-67ab1536965e) (Oct 2024) - dbt Labs
- [Artificial Intelligence Fundamentals](https://www.credly.com/badges/eaa83aa7-4bbe-40fb-b7a8-3fe3a3a184c7/linked_in_profile) (Sep 2024) - IBM
- [Building AI Solutions Using Advanced Algorithms and Open Source Frameworks](https://www.credly.com/badges/87770225-041f-4c2d-aac5-b964a6b3e700/linked_in_profile) (Sep 2024) - IBM
- [Fundamentals of Credit](http://credentials.corporatefinanceinstitute.com/5bae48df-6da7-4e09-8917-1f801ec78b95) (Sep 2024) - Corporate Finance Institute® (CFI)
- [SQL (Advanced)](https://www.hackerrank.com/certificates/c988a0d3a98b) (Sep 2024) - HackerRank
- [Enterprise Data Science in Practice](https://www.credly.com/badges/cc256810-57f2-4cbe-8330-76375598559c/linked_in_profile) (Aug 2024) - IBM
- [Getting Started with Data](https://www.credly.com/badges/d958d618-c907-4eaf-8d92-016222daad65/linked_in_profile) (Aug 2024) - IBM
- [Introduction to Business Intelligence](http://credentials.corporatefinanceinstitute.com/21840fb0-414f-474d-a66f-ffa7c0f50448) (Aug 2024) - Corporate Finance Institute® (CFI)
- [Machine Learning for Data Science Projects](https://www.credly.com/badges/631b6d76-0379-4795-979c-da756198fc1d/linked_in_profile) (Aug 2024) - IBM
- [Accounting Fundamentals](http://credentials.corporatefinanceinstitute.com/26beadd5-1a7a-4e5e-8d89-3f1f452264b7) (Jul 2024) - Corporate Finance Institute® (CFI)
- [Introduction to FinTech](http://credentials.corporatefinanceinstitute.com/e8da5147-584b-434d-b8a9-da901d65a75c) (Jul 2024) - Corporate Finance Institute® (CFI)
- [Statistics Fundamentals](http://credentials.corporatefinanceinstitute.com/f4db1d0c-168a-48e5-8383-2a617c8c7ed3) (Jul 2024) - Corporate Finance Institute® (CFI)
- [Excel for Data Analysts](https://drive.google.com/file/d/10ZkB9YjE1Heo_owtI9PuOB89YGOdViEE/view?usp=sharing) (Mar 2024) - Analytics Mentor
- [Data Analytics and Visualization Job Simulation](https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/Accenture%20North%20America/hzmoNKtzvAzXsEqx8_Accenture%20North%20America_WBpJPGhbSKFR2PAD6_1705948009927_completion_certificate.pdf) (Jan 2024) - Forage (Provided by Accenture)
- [Data Science Job Simulation](https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/British%20Airways/NjynCWzGSaWXQCxSX_British%20Airways_WBpJPGhbSKFR2PAD6_1706540756636_completion_certificate.pdf) (Jan 2024) - Forage (Provided by British Airways)
- [Coding For Data](https://www.sololearn.com/certificates/CC-8SJ7FKJK) (Des 2023) - SoloLearn
- [SQL Intermediate](https://www.sololearn.com/en/certificates/CC-SQEKSSHP) (Des 2023) - SoloLearn
- [Data Visualization with Python](https://courses.cognitiveclass.ai/certificates/97250f3b57ee4ccc87906450d399039b) (Des 2023) - Cognitive Class (Provided by IBM)
- [Data Analysis with Python](https://courses.cognitiveclass.ai/certificates/35346a4e982d4a5a94c8c50d4247994e) (Des 2023) - Cognitive Class (Provided by IBM)
- [Data Science Methodology](https://courses.cognitiveclass.ai/certificates/d9d1a1af372f47fb85ab2dbc8c74f5a1) (Des 2023) - Cognitive Class (Provided by IBM)
- [SQL Intermediate](https://www.hackerrank.com/certificates/1eecdfa2b4ab) (Des 2023) - HackerRank
- [SQL and Relational Databases 101](https://courses.cognitiveclass.ai/certificates/338643d54e454302a7ff4ca6073a00a0) (Des 2023) - Cognitive Class (Provided by IBM)
- [The Complete SQL Bootcamp](https://www.udemy.com/certificate/UC-2460c9b6-d5e0-4e14-8c91-802a11046cc2/) (Nov 2023) - Udemy (Provided by Jose Portilla)
- [Intro to Data Analytics](https://drive.google.com/file/d/1vqZEuCimcQCCdbHjBzP4vuJLDVzCsQ36/view) (Oct 2023) - RevoU
- [SQL Basic](https://www.hackerrank.com/certificates/6051b8e2b20a) (Oct 2023) - HackerRank
- [Pyhton For Beginners](https://courses.opencv.org/certificates/b48811a77bee403590a01822c480912b) (Sep 2023) - OpenCV
