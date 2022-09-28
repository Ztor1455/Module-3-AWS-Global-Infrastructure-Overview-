# Module 3: AWS Global Infrastructure Overview

## AWS Global Infrastrucutre 
- Purpose is to bring a high-quality global network performance.
- Designed with the ideas to ensure flexibility, reliability, scalability, and security. 
- "To Achieve fault tolerance and stability AWS regions are isolated from one another." interesting that as well data replication is controlled by the user as well. 
- What factors should be considered when selecting regions where users will use AWS services and store data?
  * Data governance and legal requirments 
  + Distance from customers or the latency (Cloud ping allows testing of latency)
  - Service availabilty within the rgion 
  * Costs which varies by region 
- AWS Zones have many availability zones which are isolated locations and include multiple data centers. 
- "You should design your systems to survive the temporary prolonged failure of single Availability Zones in the event of a disaster."
- **Data centers** is where actual data lives and the processing happens; every data center is housed seperatley. 
-  Data centers are desinged with "failure in mind" and are created to minimize the risk of failure.
-  Availability is ensured by being backed up by more than one availability zones.
-  Capacity is secured by AWS itwld monitoring service usage for support availibilty and deploy infrastrucutre.
-  **Points of Presence** is symobolized and carried out by AWS "Amazon Cloudfront"  which delivers content to end users with with reduced latency and is provided with 187 points of presence locations. 

## AWS services and service category overview 
- AWS Global infrasturcture again consists of 'Regions', 'availibility zones', and 'points of presence'. 
- The platform provides on demand utility with pay-as-you-go pricing for storage, databases, and networking. 
- There are 23 different categories of services and products.
- Most used AWS services and capability: 
   + **Amazion Simple Storage Service** or **Amazon S3** is an object storage service. 
   + **Amazon Elastic Block Store** or **Amazon EBS** is an high performance block storage used with Amazon EC2 for both throughput and transaction-intense workloads. 
   +  **Amazon Elastic File System** or **Amazon EFS** provides fully managed elastic network file system. 
   +  **Amazon Simple Storage Services Glacier** is a secured amd low cost AWS S3 Cloud Storage for data archiving and back up.
   +  **Amazon EC2** provides resizable compute capacity in forms of virtual machines, also the scalining service allows for adding and removing instances in users personal conditions. 
   +  **Amazon Elastic Conatiner Service** container orchestration service that supports Docker containers and registration within the service. 
   +  **AWS Elastic Beanstalk** deploying web applications and services on familiar servers. 
   +  **Amazon Elastic Kubernetes Service** creates easy to deploy manage containerized apps that us 'kubernetes'.
   +  **AWS Fargate** compute engine for ECS tha allows users to run containers without managing servers or clusters.                             
- Database service category includes: 
   + **Amazon Relational Database Service** provides resizable capacity and automates administartion tasks. 
   + **Amazon Aurora** a five times faster version of MySQL databases and three times faster than PostgreSQL databases. 
   + **Amazon Redshift** allows users to run analytic queries against petabytes of data.
   + **Amazon Dynamo DB** a NoSQL databas that delivers single-digit millisecond performance with built-in security and restore.
- AWS networking and content delivery services include:
   + **Amazon VPC** allows users to access isolated sections to launch AWS resourcea in a self difined virtual network. 
   + **Elastic Load Balancing** auto distributes incoming app traffic accrosa multiple targets. 
   + **Amazon Cloudfront** a CDN that securely delivers data, videos, and applications. 
   + **AWS Transit Gateway** enables connectivity to Amazon Virtual Private Clouds and on premises networks. 
   + **Amazon Route 53** desinged to give customers a reliable way to youte end users to the internet application
   + **AWS Direct COnnect** provides ways to establish a dedicated network. 
   + **AWS VPN** provides secure private tunnel for networks and devices to the AWS Globale Network. 
