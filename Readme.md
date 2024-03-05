Requirements Specifications Document

1.	 Introduction – The document specifies the data pipeline, as the product, to be used to enhance revenue and understanding customer behavior. We will be preparing the data for the data analysts/scientists of the organization to enable better decision making.

a.	Purpose – The purpose of the product is to prepare a ready-to-analyze dataset(s) to track the customer behavior, condition of customer so that the Health Care Insurance (HCI) company can customize offers for them to buy insurance policies and also calculate royalties to the existing customers or the customer who have purchased policies in the past. 

b.	Intended Audience and Use - The data scientist(s), data analysts, project manager. Developers, product owner and related subject matter experts (SMEs)

c.	Product Scope - 
Benefit- The benefits of the product is to reduce ETL processing time of the data and enhance cost effectiveness, 
Objectives are to extract the data from local file system and store it in a Datalake (AWS S3). Transform, clean and validate, the data from the datalake, using Databricks, and load into Datawarehouse (AWS Redshift) for further analysis 
Goals intended is to maximum query performance and optimize other processing task related to ETL and present a validated and cleaned dataset for analysis. This should relate to overall business goals, especially if teams outside of development will have access to the SRS.

d.	Definitions and Acronyms - ETL --> Extract, Transform and Load.  



4.	Overall Description - Description of the product (pipeline) we’re going to build.
Why is this product needed? --> To ensure low latency, scalable and secure data pipeline.
Who is it for? --> For the client & product owner to maximize revenue
Is it a new product? -->  Yes
Is it an add-on to a product you’ve already created? --> No
Is this going to integrate with another product?  Sometime in the future maybe 
Understanding and getting your team aligned on the answers to these questions on the front end makes creating the product much easier and more efficient for everyone involved.

a.	 User Needs – 
Who will use the product and how ? --> Data Analyst/Scientist and might be released as a ETL tool. 
Understanding the various users of the product and their needs is a critical part of the SRS writing process.

b.	 Assumptions and Dependencies – Understating and laying out these assumptions ahead of time will help with headaches later. 
What are we assuming will be true? --> Data availability and requirements are fixed. We will also be fixed on the platforms used and the use cases.
Are we assuming current technology? --> Yes mostly related to Apache frameworks and AWS cloud technologies.
Are we basing this on a Windows framework? --> No, Ubuntu Linux framework.  
We need to take stock of these technical assumptions to better understand where our product might fail or not operate perfectly.



3.	System Features and Requirements -In order for the development team to meet the requirements properly, we must include as much detail as possible.
4.	Breaking down our requirements into categories.
Functional Requirements – Cloud services for deployment from any region (AWS S3, Redshift). Scalability, and security of the codes. The following needs to be analyzed, cleaned and validated:
Claim Analysis
Subscriber Analysis
Group Analysis
Hospital Analysis
Subgroup Subscription Analysis
Claims Rejection Analysis
City-wise Claims Analysis
Policy Type Analysis
Premium Analysis
Profitable Group Analysis
Patient Demographics Analysis
High-Value Insurance Coverage Analysis

b.	External Interface Requirements - 
i.	User --> Product Owner, Analysts.
ii.	Hardware --> CPU, RAM, Storage Disks
iii.	Software --> Distributed File System, S3 for Storage, Query, Python 3, Pyspark, Databricks/AWS EMR, GitHub (for Version Control) 
iv.	Communications --> Jira and Teams.

c.	System Features - 

d.	Nonfunctional Requirements - 
i.	Performance requirements --> Optimized query performance, low latency network, Optimized processing time, automated scripts, 
ii.	Safety requirements
iii.	Security requirements
iv.	Usability requirements
v.	Scalability requirements


Code needs to be secured and optimized.
5mins vs 2mins
Function needs to be optimal. Function needs to be able to work in a distributed system.  non-functional requirements.


