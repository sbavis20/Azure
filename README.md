# Azure
Azure Services

Compute services: It includes the Microsoft Azure Cloud Services, Azure Virtual Machines, Azure Website, and Azure Mobile Services, which processes the data on the cloud with the help of powerful processors.

Data services: This service is used to store data over the cloud that can be scaled according to the requirements. It includes Microsoft Azure Storage (Blob, Queue Table, and Azure File services), Azure SQL Database, and the Redis Cache.

Application services: It includes services, which help us to build and operate our application, like the Azure Active Directory, Service Bus for connecting distributed systems, HDInsight for processing big data, the Azure Scheduler, and the Azure Media Services.

Network services: It helps you to connect with the cloud and on-premises infrastructure, which includes Virtual Networks, Azure Content Delivery Network, and the Azure Traffic Manager.

Advantages of CLoud Computing

Cost : We dont have to buy software and hardware which reduces the costs.

Speed : Resources can be accessed in few clicks.

Scalability : According to the bussiness requirements we can increase or decrease the resources.

Productivity : We dont have to worry about maintaining software or hardware. So the focus is on  developing bussiness logic. 

Reliability : Backup and recovery of data are less expensive and very fast for bussiness continuity.

Security : Cloud vendors offer set of policies, technologies, and controls that strengthen our data security.

Types of Cloud Computing

Public Cloud 							                Private Cloud 							      Hybrid Cloud
Owned and operated by                 Used inside a single                 Combination of public and 
thrid-party cloud service             business or organization.            private clouds. They provides
provider. Delivers computing                                               flexibility and more deployment
resources such as servers,  											                         options to the business.
software, and storage over 
the internet.

Types of Cloud Services

SaaS 										            Paas 						                       IaaS
Software services 						The developer is responsible     we can rent IT infrastructures
to the end-users						  for the application              like server & virtualmachines(VM)

End-Users								      Software Developers				       IT Administrator

Gmail,salesforce CRM, 		    Heroku,AWS Elastic,              AWS Elastic Compute, 
Google Docs, Office 365				Beanstalk, Google App Engine 	   Microsoft Azure

Azure Storage Building Blocks

Azure Blob: Used to store the unstructured data such as media files, documents etc.

Azure File: Used to share files between two virtual machines. We can share the data between two or more VMs

Archive: Used to archive for cost optimization. We can move less accessed blobs or files into the archive to optimize the cost. However, once you move the data into an archive, it will take some time for the recovery of that data.

Azure Queries: It can be used to store messages.

Azure Tablet: Used to store entities. This is aNoSQL datastore where schema within the table is not enforced.

Azure Disk Storage
Azure Strorsimple
Azure Site Recovery
Azure Data Box
Azure Backup
Azure Monitor
CDN(Content Delivery Network)

Azure Database Service
Deployment options: 
SQL databse (PaaS)    			 														SQL server on vm
Managed	instance				SingleDatabase 					Elastic Pool
migrate old server				managed via logical 			pool of dbs with
								server							a shared set of resources
																managed via a logical server

SQL db as IaaS we are responsible for managing the SQL server on that particular vm

Azure SQL Database service tiers
General Purpose/						Bussiness Critical/								Hyperscale service
Standard model							Premium service tier model						tier model
separation of computing and storage   	cluster of db engine process.					
service. Dependes on Azure premium
Storage.		

SQL database logical server

central administrative point for multiple single or pooled db logins,firewall rules, auditing rules, threat detection policies and failover groups.\

All the dbs on server are created within the same region as the logical server.

Azure db logical server is the parent resource for db, elastic pools, and data warehouses.

Azure SQL Managed Instance
New implementation based on VCore based purchasing model

Advantages
Easy lift and shift 		Fully managed PaaS		New Bussiness Model 			Security

Azure COSMOS Database
NoSQL db 
