**CHICAGO TAXI DATA ETL on AWS & BI INSIGHTS on POWER BI**

This repository contains an end to end pipeline that ingest Chicago Taxi Data using AWS Lambda. The ingested data is stored in an S3 data lake. The data stored in the S3 bucket is fed into a Glue Job created with AWS glue and the transformed data is exposed to Analytics using Amazon Athena. The entire process is orchestrated with AWS Step Functions and Monitored via Cloudwatch logs. Athena is connected to Power BI through DirectQuery to create the BI dashboard.

**POWER BI DASHBOARD**

<img width="1008" height="569" alt="image" src="https://github.com/user-attachments/assets/f48a6183-c67d-4dbf-9bcf-4dd1c040792b" />

**CLOUDWATCH LOGS**



