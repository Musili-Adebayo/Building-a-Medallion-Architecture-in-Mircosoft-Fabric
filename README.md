# Building-a-Medallion-Architecture-in-Mircosoft-Fabric

![Architecture](https://github.com/Musili-Adebayo/Building-a-Medallion-Architecture-in-Mircosoft-Fabric/blob/main/Medallion%20Architecture.jpg)

##  Project Summary
For this project, I created the Medallion Architecture for data organisation in a lakehouse in Microsoft Fabric. I demonstrated how to level up your data quality from bronze (raw), to silver (validated), and finally to gold (enriched), all ready for super-efficient analytics.
This was my in-person presentation for the [Microsoft Fabric Nigeria Community](https://community.fabric.microsoft.com/t5/Microsoft-Fabric-Nigeria/gh-p/MicrosoftFabricNigeria) and [dbrownconsulting](https://www.linkedin.com/posts/dbrownconsulting_analyticsmeetup-dbrownconsulting-microsoftfabric-activity-7255201470994673668-hX6G?utm_source=share&utm_medium=member_desktop) on 26th of October 2024. 

1. Created Lakehouse
2. Data Ingestion. 
3. Silver Data Transformation.
4. Gold Data Transformation.
5. Data Modelling.
6. Data Visualization in Power BI Service.


## Data Sources: 
Datasource: Data was sourced from the popular adventure works data you can [download here](https://github.com/Musili-Adebayo/Building-a-Medallion-Architecture-in-Mircosoft-Fabric/tree/main/Sample_Adventureworks_Dataset).

## Creating Lakehouse: 
In Synapse Data Engineering, create three Lakehouses called Sales_Bronze, Sales_Silver and Sales_Gold.

## Data Ingestion:
+ In the Sales_Bronze Lakehouse, Upload the [Sample Adventureworks Dataset](https://github.com/Musili-Adebayo/Building-a-Medallion-Architecture-in-Mircosoft-Fabric/tree/main/Sample_Adventureworks_Dataset).

![Sales_Bronze](https://github.com/Musili-Adebayo/Building-a-Medallion-Architecture-in-Mircosoft-Fabric/blob/main/Sales_Bronze.png)


 ## Silver Data Transformation.
In the Sales_Silver Lakehouse, click on new Notebook to transform data for the Sales_Silver Lakehouse or you can import the 
[Silver_Data_Transformation Notebook](https://github.com/Musili-Adebayo/Building-a-Medallion-Architecture-in-Mircosoft-Fabric/blob/main/Silver_Data_Transformation.ipynb) 

![Silver_Data_Transformation](https://github.com/Musili-Adebayo/Building-a-Medallion-Architecture-in-Mircosoft-Fabric/blob/main/Sales_Silver.png) 


