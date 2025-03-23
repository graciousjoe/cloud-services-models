**Cloud-Services-Models**  
**Overview:**

This repository contains research and documentation on cloud service models, focusing on offerings from two major cloud providers(AWS and GCP), examples of IaaS, PaaS and SaaS from our daily interactions, as well as a hands-on setup of a managed service using AWS Elastic Beanstalk.

**Cloud Providers and Their Offerings**  
**1\. Amazon Web Services (AWS)**

Amazon Web Services (AWS) is a secure, comprehensive and easy-to-use cloud computing platform used to manage hardware and infrastructure of resources. It was launched in 2006 by Amazon as a pioneer cloud service to provide scalable, on-demand cloud computing services. Although initially designed to support Amazon’s internal infrastructure, it quickly became the leading cloud provider worldwide. AWS reduces the expense and complexity of purchasing and running resources on-site for business and individuals. It offers various services and has over 200 data centres all over the world, ensuring global availability and redundancy.

**Popular AWS Services**

AWS offers a vast range of services that power businesses and applications globally. Here are some of its key services:

i. Compute  
ii. Storage  
iii. Database  
iv. Networking and Content Delivery  
v. Security and Identity  
Popular Compute Services include: Elastic Compute Cloud (EC2), AWS Lambda, Amazon Lightsail, Elastic Beanstalk, AWS Batch.  
Storage Services include: Amazon S3, Amazon Elastic Block Storage (EBS), Amazon Elastic File Storage (EFS), AWS Backup, AWS Snowball.

Database Services: Amazon Relational Database (RDS), Amazon DynamoDB, Amazon Redshift, Amazon Aurora, Amazon ElastiCache.

Networking and Content Delivery: Amazon Virtual Private Cloud (VPC), Amazon CloudFront, AWS Route 53, AWS Direct Connect.

Security and Identity: AWS Identity and Access Management (IAM), AWS Shield, AWS Web Application Firewall (WAF), Amazon GuardDuty.

Other AWS Services include: Analytics, Artificial Intelligence, Machine Learning, Internet of Things (IoT), Blockchain, Developer Tools, Application Integration.  
AWS provides a solution for almost every cloud computing need, making it a dominant force in the industry.

**AWS Pricing Models**

AWS follows flexible pricing models such as:  
• Pay-as-you-go: Here, you only pay for what you use. It is the most flexible pricing model with no upfront cost.  
• Reserved Instances: Offers discounted long-term commitments.  
• Spot Instances: In this pricing model, you purchase unused capacity at lower prices.  
• Savings plans: Commit for lower pricing.

**Everyone loves freebies\! (wink)**

AWS provides a Free Tier Account for new users to test services. However, these services have varying free trial periods. Some services are always free, some have limited trial periods while others have a 12-month validity period.

**AWS Unique Features:**

AWS offers the broadest range of cloud services, covering compute, storage, AI, and more, with a global infrastructure spanning 44 regions for high availability and low latency.It also leads in security and compliance, with robust tools like IAM and AWS Shield.

**2\. Google Cloud Platform (GCP)**

Google Cloud Platform (GCP) was launched in 2008, built on the same infrastructure that powers Google Search, YouTube, and Gmail. It provides a wide range of cloud solutions, from computing and storage to AI and security, making it a top choice for businesses and developers looking for scalability, reliability, and cutting-edge technology.

**GCP Services**

i. Compute Services- Compute Engine, App Engine, Kubernetes Engine (GKE), Cloud Functions, Cloud Run  
ii. Storage & Databases- Cloud Storage, Persistent Disks, Filestore, Cloud SQL, Cloud Spanner, Firestore, Bigtable  
iii. Networking- Virtual Private Cloud (VPC), Cloud Load Balancing, Cloud CDN, Cloud Interconnect, Cloud DNS  
iv. Security & Identity- Identity and Access Management (IAM), Cloud Armor, Security Command Center• Confidential Computing  
v. AI & Machine Learning- Vertex AI, AutoML, TensorFlow Enterprise, Vision AI, Natural Language AI  
vi. Data Analytics- BigQuery, Cloud Dataflow, Cloud Dataproc, Looker, Pub/Sub

**Pricing Models**

GCP offers flexible pricing options:  
• Pay-as-you-go – Pay only for what you use  
• Committed Use Discounts (CUDs) – Up to 57% off for long-term commitments  
• Sustained Use Discounts (SUDs) – Automatic savings for consistent usage  
• Spot VMs – Cost-effective option for short-term workloads  
• Per-second billing – Ensures cost efficiency

**Free Tier Account**

GCP provides a $300 free credit for new users, valid for 90 days. There’s also an always free tier, with some exciting offers.

**Unique Features**

What makes GCP stand out?  
• Live VM Migration – Keeps virtual machines running even during maintenance  
• Global Fiber Network – Faster speeds and low latency  
• Powerful AI/ML Capabilities – Advanced tools for data science and automation  
• Sustainability – 100% renewable energy goal  
• BigQuery – A leading serverless data analytics platform

**Cloud Services Models in Daily Interactions**  
**1\. IaaS (Infrastructure as a Service)**

IaaS offers virtualized computing resources over the internet. Users can rent IT infrastructure such as servers, storage, and networking on a pay-as-you-go basis, allowing for more control and flexibility.  
Examples of IaaS are ﻿﻿Amazon Web Services (AWS) EC2: Provides scalable virtual servers (instances) for running applications and storing data and ﻿﻿Microsoft Azure.

**2\. PaaS (Platform as a Service)**

PaaS provides a platform that allows developers to build, deploy, and manage applications without dealing with the underlying infrastructure. It is best suited for software developers needing a runtime environment.  
Examples of PaaS in our daily interactions are-  
Heroku: A platform that enables developers to build, run, and operate applications entirely in the cloud, supporting various programming languages.  
Google App Engine: A cloud computing platform for developing and hosting web applications in Google-managed data centers.

**3\. SaaS (Software as a Service)**

SaaS provides software applications over the internet. Users can access the software via a web browser without needing to install or maintain it on their local devices.  
Examples of SaaS in our daily interactions- ﻿﻿Google Workspace: Includes applications like Gmail, Google Docs, and Google Drive, which are accessible online and require no local installation.

**Managed Service Setup: AWS Elastic Beanstalk**  
**Step 1: Creating the Environment**  
• Chose AWS Elastic Beanstalk for automatic deployment and management of applications.  
• Selected a region (us-east-1: United States, Virginia).  
• Configured the environment name and platform.  
• Used the default service role and attached necessary permissions.  
• Launched the environment.  
**Step 2: Verifying the Setup**  
• Checked the AWS Elastic Beanstalk console to confirm environment creation.  
• Noted health status and available logs.  
**Step 3: Terminating the Environment**  
• After testing, the environment was terminated to avoid unnecessary costs.

**Screenshots**  
Screenshots of the Elastic Beanstalk setup are included in the screenshots folder.

