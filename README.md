# Stock Market Real Time Data Processing Engine using Kafka - Data Engineering Project

## Project Overview:   
 I successfully executed an end-to-end project on real-time stock market data analysis. Utilizing a combination of technologies including Python, Amazon Web Services (AWS), Apache Kafka, Glue, Athena, and SQL, I was able to develop a simulation app that generated a live stream of data from a csv file, stored it as individual files in an AWS S3 bucket, and queried the data using AWS in-house tools such as Glue Crawler and Athena.

## Architecture:  
<img src="Architecture.jpg">

## Technologies Used:  
* **Python**  
* **AWS**  
**1. S3**  
**2. Athena**  
**3. Glue Crawler**  
**4. Glue Catalog**  
**5. EC2**  
* **Apache Kafka** 

## Project Roadmap:  
  
**1. Data Collection:** Develop a mechanism to extract data from a CSV file using Python and generate a live stream of data using Apache Kafka.  
  
**2. Data Processing:** Transform the live data stream into a format suitable for storage and analysis.  
  
**3. Data Storage:** Store the processed data as individual files in an AWS S3 bucket.  
  
**4. Data Cataloging:** Use AWS Glue Crawler to catalog the data stored in the S3 bucket, making it searchable and queryable.  
  
**5. Data Querying:** Use AWS Athena to perform ad-hoc queries on the cataloged data, allowing for real-time insights and analysis.  
  
**6. Data Visualization:** Create a dashboard to visualize the results of the data queries and provide a clear, actionable representation of the data insights.  
  
**7. Testing and Deployment:** Test the simulation app thoroughly to ensure it is functioning as intended and deploy it to a live environment.  
  
**8. Maintenance and Support:** Monitor the app and provide ongoing maintenance and support to ensure its continued reliability and performance.  
  
  
## Dataset Used:
You can use any dataset, we are mainly interested in operation side of Data Engineering (building data pipeline) 

Here is the dataset that i used - https://github.com/vithun97/Stock-Market-Real-Time-Kafka-Project/blob/main/indexProcessed.csv

## What did I learn?

Through this project, I gained valuable hands-on experience in various aspects of data engineering, including real-time data processing, data storage, and data querying. I honed my skills in using technologies such as **Python**, **AWS**, **Apache Kafka**, **Glue**, **Athena**, and **SQL**, and **learned how to effectively integrate them to build a complete end-to-end solution**. Additionally, I developed my ability to troubleshoot and overcome technical challenges, further strengthening my problem-solving skills. Overall, this project provided me with a comprehensive understanding of the complexities involved in real-time data analysis and reinforced my commitment to continuously improving my skills as a data engineer.








