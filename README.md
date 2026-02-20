**CHICAGO TAXI DATA ETL JAN 2024 on AWS & BI INSIGHTS on POWER BI**

This repository contains an end to end pipeline that ingest Chicago Taxi Data using AWS Lambda. The ingested data is stored in an S3 data lake. The data stored in the S3 bucket is fed into a Glue Job created with AWS glue and the transformed data is exposed to Analytics using Amazon Athena. The entire process is orchestrated with AWS Step Functions and Monitored via Cloudwatch logs. Athena is connected to Power BI through DirectQuery to create the BI dashboard.

**POWER BI DASHBOARD**

<img width="1008" height="569" alt="image" src="https://github.com/user-attachments/assets/f48a6183-c67d-4dbf-9bcf-4dd1c040792b" />

**CLOUDWATCH LOGS**

This pipeline did not require an Alarm as the data pulled was past data pulled only once. (Used AWS Free Tier)

<img width="975" height="198" alt="image" src="https://github.com/user-attachments/assets/2bca7061-8714-48e5-9b72-b9725cc401e2" />

**GLUE JOB**

<img width="879" height="92" alt="image" src="https://github.com/user-attachments/assets/b84f80fd-9c74-48dd-aaed-be7c6aed2ae7" />

**SUCCESSFUL GLUE CRAWLER (CLOUDWATCH)**

<img width="933" height="179" alt="image" src="https://github.com/user-attachments/assets/ed659ef7-ff52-4880-b5bd-a4754d93e16f" />

**STEP FUNCTIONS: GRAPH VIEW**

<img width="744" height="571" alt="image" src="https://github.com/user-attachments/assets/e25b683b-dd22-4ed5-a3c3-8a7ca8f6bf8d" />








