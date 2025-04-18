# NHS (76%)
Data analysis of NHS healthcare data, aimed at improving service delivery and identifying key patterns in patient care.

## Project Overview
This project aimed to assist the **National Health Services (NHS)** in understanding the utilisation of its healthcare services, with a particular focus on missed appointments, service capacity, and exploring external data sources like Twitter (now rebranded as X). The analysis was intended to inform decisions about infrastructure and resource expansion to meet the needs of an increasing population.

### Key Objectives:
- Refine the business questions provided by the NHS into actionable analytic questions.
- Perform exploratory data analysis (EDA) on internal and external data to uncover trends and insights.
- Provide data-driven recommendations to stakeholders regarding resource allocation, capacity, and missed appointments.
- Explore Twitter data for relevant trends that could inform decision-making.

## Tools and Technologies Used
- **Python**: For data exploration, data wrangling, and visualization. Libraries used include:
  - `pandas`: Data manipulation and wrangling.
  - `matplotlib`, `seaborn`: Data visualization.
  - `numpy`: Numerical operations.
  - `scikit-learn`: For any basic machine learning (if applicable).
- **SQL**: For querying internal datasets, filtering, and aggregating the data to answer specific questions.
- **Jupyter Notebooks**: For performing data analysis and documenting the process.

## Key Questions to Address
The primary business questions we were exploring were:
1. **Has there been adequate staff and capacity in the networks?**
2. **What was the actual utilisation of resources?**
3. **What are the reasons behind missed appointments, and how can this issue be addressed?**

### Specific Analytic Questions:
- What is the **number of locations**, **service settings**, **context types**, **national categories**, and **appointment statuses** in the datasets?
- What is the **date range** of the provided datasets, and which **service settings** reported the most appointments for a specific period?
- How many **appointments and records** exist per month?
- What are the **monthly** and **seasonal trends** in appointments across different service settings, context types, and national categories?
- What are the **top trending hashtags** from the supplied Twitter data, and how can this information be utilized for better decision-making?
- What **insights** can be gained from **missed appointments** data, and how can these be used to reduce avoidable costs?

## Insights and Analysis
### Data Exploration:
- **Service Utilisation**: Analysis of service utilisation trends across different locations, service settings, and patient categories.
- **Missed Appointments**: Identification of patterns in missed appointments, such as seasonality, trends in specific demographics, and service settings.
- **External Data (Twitter)**: Analysis of social media trends to identify potential correlations or public sentiment regarding healthcare services.

### Visualizations:
- **Monthly and Seasonal Trends**: Visualizations showing appointment volumes over time.
- **Service Performance**: Insights into which services and locations are seeing the highest demand, and which have the highest rate of missed appointments.
- **Trending Topics**: Visualization of popular hashtags related to healthcare and NHS services on Twitter.

## Report
The accompanying **report** will summarize:
- The data analysis process, including key findings from both the internal and external datasets.
- Recommendations for the NHS regarding infrastructure planning, staffing, and reducing missed appointments.
- Actionable insights for improving resource allocation and service delivery.

## Files Included
- `actual_duration.csv`: Details of appointments made by patients. For example, the regional information, date, duration, and number of appointments pertaining to a certain class.
- `appointments_regional.csv`: Details on the type of appointments made by patients. For example, regional information, the month of appointment, appointment status, healthcare professional, appointment mode, the time between booking and the appointment, as well as the number of appointments pertaining to a certain class.
- `national_categories.xlsx`: Details of the national categories of appointments made by patients. For example, the regional information, date of appointment, service setting, type of context, national category, and the number of appointments pertaining to a certain class.
- `metadata_nhs.txt`: Details of the data set, data quality, and reference.
- `tweets.csv`: Data related to healthcare in the UK scraped from Twitter.

## Reflections and Recommendations
This analysis provides valuable insights into NHS service utilisation, missed appointments, and the potential to leverage external data sources like Twitter for informed decision-making. Key recommendations include:
- **Improved Resource Allocation**: Focus on specific service settings and regions experiencing high demand and missed appointments.
- **Reducing Missed Appointments**: Implement targeted interventions based on identified patterns, such as reminders or outreach campaigns.
- **Using Social Media Data**: Analyze public sentiment to gauge healthcare service quality and identify emerging issues.
