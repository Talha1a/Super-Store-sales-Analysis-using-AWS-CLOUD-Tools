# Superstore Sales Data Analysis with AWS

## Project Overview
This project utilizes AWS services to perform a detailed analysis of superstore sales data. The solution integrates data storage, metadata cataloging, SQL-based querying, and interactive visualizations to derive actionable insights.

---

## Key Features
- **Scalable Cloud-Based Solution**: Built on AWS S3, Glue, Athena, and QuickSight.
- **Serverless Data Querying**: Perform SQL queries on data directly from S3 using Athena without loading it into a database.
- **Interactive Dashboards**: Gain insights from intuitive visualizations in QuickSight.

---

## Tools and Services
- **AWS S3**: For secure and scalable data storage.
- **AWS Glue**: For metadata extraction and catalog creation.
- **AWS Athena**: For querying data directly using SQL.
- **AWS QuickSight**: For designing interactive dashboards.

---

## Workflow
1. **Data Ingestion**:
   - Downloaded sales data from Kaggle and uploaded it to an S3 bucket.
2. **Metadata Cataloging**:
   - Configured AWS Glue Crawlers to fetch metadata and create a data catalog.
3. **Data Analysis**:
   - Used AWS Athena to query data stored in S3 for insights such as:
     - Total sales by region.
     - Profit margins by product category.
     - Customer segmentation by purchase frequency.
     - Seasonal sales trends.
4. **Visualization**:
   - Created an interactive dashboard in AWS QuickSight featuring:
     - Regional sales heatmaps.
     - Sales trends line charts.
     - Profitability bar charts.
     - Customer segmentation pie charts.

---

## Results
- **Regional Sales**: Western region had the highest sales; Southern region showed potential for growth.
- **Profit Margins**: Office supplies yielded consistent profits, while technology products had lower margins despite high sales.
- **Customer Insights**: A significant portion of revenue came from repeat customers.
- **Seasonal Trends**: Sales peaked in Q4, highlighting seasonal shopping behavior.

---

## Challenges and Solutions
- **Data Format Compatibility**: Ensured proper CSV formatting to avoid errors.
- **Query Optimization**: Applied partitioning and filtering in Athena for efficient querying.
- **Dashboard Design**: Used user-friendly visuals and filters for intuitive navigation.

---

## Future Enhancements
- Automate the ETL process with AWS Lambda for real-time data ingestion and analysis.
- Use machine learning models in AWS SageMaker for predictive analytics.
- Explore additional datasets for deeper insights.

---

## Getting Started
1. Clone the repository.
2. Configure your AWS environment.
3. Upload the Kaggle dataset to an S3 bucket.
4. Set up Glue Crawlers and Athena for querying.
5. Integrate Athena data with QuickSight to create dashboards.

---

## Dataset
- **Source**: [Kaggle Superstore Sales Data](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

---


