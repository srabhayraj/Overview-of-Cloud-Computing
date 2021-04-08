# Overview of Cloud Computing


## What is a Cloud
  Cloud is collection of computing resources which are accessed through the internet.
  
## What is Cloud Computing
  Cloud Computing is the use of software and hardware to provide services like storage, VM, servers and many more over the network. Or we can say Cloud computing is the delivery of on-demand computing services—including servers, storage, databases, networking, software, analytics, and intelligence over the Internet.
  
## Benefits of using Cloud Computing
  -	Enables access to cloud resources.
  -	Enables access to cloud services.
  -	Builds virtualization concept.
  -	Provide the option pay as you use.

## Why Cloud Computing
  -	Traditional Computing companies had to spent a lot of money and time on infrastructure, hardware and other operational aspects.
  -	By using cloud computing all these troubleshoots are managed by cloud service provider, so we just had to focus on our business.
  -	Cloud enables the developers to get their applications to market quickly.
  -	As long as internet connection is on user can access their required application.
  -	Even there are some applications which run offline.
  -	Cloud based services are ideal for business with growing and fluctuating bandwidth demand.
  -	As it is flexible you can easily scale down the cloud capacity as per requirement.
  -	Cloud Computing reduces the cost of managing and maintaining IT system.
  -	Cloud services providers offer resources and using these resources rather than expensive system and equipment you can save money.

## What is a Cloud Provider
  A cloud service provider is a third-party company offering a cloud-based platform, infrastructure, application or storage services.
  
## What are the advantages of Cloud Computing
  - Pay as you go (or consumption-based payment) - you are paying only for what you are using. No upfront payments and payment stops when resources are no longer used.
  - Scalable - resources are scaled down or up based on demand
  - Less Cost
  - 24 x 7 Availability	
  - Security
  - Reliability

## Types of Cloud Services or Cloud Computing Service Models
  <b>IaaS</b> - Infrastructure as a service (IaaS) is a form of cloud computing that provides virtualized computing resources over the internet. Eg., AWS {S3, EC2}, GCE (Google Compute Engine), Microsoft Azure. </br></br>
  <b>PaaS</b> - Platform-as-a-service (PaaS) is a type of cloud computing offering in which the service provider delivers a platform to clients, enabling them to develop, run, and manage business applications without the need to build and maintain the infrastructure. Eg., AWS Elastic Beanstalk, AWS Lambda </br></br>
  <b>SaaS</b> - Software as a service (SaaS) is a cloud computing model in which a third-party provider host the applications and makes them available to customers over the Internet. Eg., Google Workspace, Dropbox, Cisco WebEx </br></br>

![Service_model](https://github.com/srabhayraj/Overview-of-Cloud-Computing/blob/main/images/service_model.png)
</br></br>

## Types of Cloud or Cloud Deployment Model
  <b>Private Cloud</b>- It is a cloud-based infrastructure used by stand-alone organizations. It offers greater control over security. The data is backed up by a firewall and internally, and can be hosted internally or externally. Private clouds are perfect for organizations that have high-security requirements, high management demands, and availability requirements. </br></br>
  <b>Public Cloud</b>- This type of cloud services is provided on a network for public use. Customers have no control over the location of the infrastructure. It is based on a shared cost model for all the users, or in the form of a licensing policy such as pay per user. Public deployment models in the cloud are perfect for organizations with growing and fluctuating demands. It is also popular among businesses of all sizes for their web applications, webmail, and storage of non-sensitive data. </br></br>
  <b>Community Cloud</b>- It is a mutually shared model between organizations that belong to a particular community such as banks, government organizations, or commercial enterprises. Community members generally share similar issues of privacy, performance, and security. This type of deployment model of cloud computing is managed and hosted internally or by a third-party vendor. </br></br>
  <b>Hybrid Cloud</b>- This model incorporates the best of both private and public clouds, but each can remain as separate entities. Further, as part of this deployment of cloud computing model, the internal, or external providers can provide resources. A hybrid cloud is ideal for scalability, flexibility, and security. A perfect example of this scenario would be that of an organization who uses the private cloud to secure their data and interacts with its customers using the public cloud. </br></br>
  
![Deployment_model](https://github.com/srabhayraj/Overview-of-Cloud-Computing/blob/main/images/deployment_model.png)
</br></br>

## Cloud Computing Architecture

![Cloud_architecture](https://github.com/srabhayraj/Overview-of-Cloud-Computing/blob/main/images/cloud_architecture.jpg)
</br></br>

## Era before Cloud Computing or Earlier Strategy

![Earlier_strategy](https://github.com/srabhayraj/Overview-of-Cloud-Computing/blob/main/images/earlier_strategy.png)
</br></br>
  - Information on centralized servers. 
  - For access on demand. 
  - Clients connect to the centralized server to access the information. 
  - Any new information stored on the centralized server. 
  - Centralized servers served a dual role of providing compute and storage capacities to end-users. 

## Characteristics of Cloud Computing
  - Resource pooling
  - Broad network access
  - On-demand self-service (Self Provisioning)
  - Rapid elasticity
  - Measured service

## What is Virtualization
  Virtualization refers to the creation of a virtual resource such as a server, desktop, operating system, file, storage or network.
  The main goal of virtualization is to manage workloads by radically transforming traditional computing to make it more scalable.

```
Note:
    To access cloud services, we need a platform from which we can access the resources. And the platform which we commonly use is known as aws. There are more patforms available from which we can access the services. These are Azure, GCP, etc.
```

## What is AWS
  AWS stands for Amazon Web Services.
  The AWS service is provided by the Amazon that uses distributed IT infrastructure to provide different IT resources available on demand. 
  It provides different services such as infrastructure as a service (IaaS), platform as a service (PaaS) and packaged software as a service (SaaS).
  
## Some common AWS Services

  ## EC2
    EC2 stands for Amazon Elastic Compute Cloud.
Amazon EC2 is a web service that provides resizable compute capacity in the cloud.
Amazon EC2 reduces the time required to obtain and boot new user instances to minutes rather than in older days, if you need a server then you had to put a purchase order, and cabling is done to get a new server which is a very time-consuming process. 
Now, Amazon has provided an EC2 which is a virtual machine in the cloud that completely changes the industry.

  ## EBS
    EBS stands for Elastic Block Store.
EC2 is a virtual server in a cloud while EBS is a virtual disk in a cloud.
Amazon EBS allows you to create storage volumes and attach them to the EC2 instances.
Once the storage volume is created, you can create a file system on the top of these volumes, and then you can run a database, store the files, applications or you can even use them as a block device in some other way.

  ## S3
    S3 stands for Simple Storage Service.
S3 is a safe place to store the files.
It is Object-based storage, i.e., you can store the images, word files, pdf files, etc.
The files which are stored in S3 can be from 0 Bytes to 5 TB.
Files are stored in Bucket. A bucket is like a folder available in S3 that stores the files.

  ## VPC
    VPC stands for Virtual Private Cloud.
Amazon Virtual Private Cloud (Amazon VPC) provides a logically isolated area of the AWS cloud where you can launch AWS resources in a virtual network that you define.
You have complete control over your virtual networking environment, including a selection of your IP address range, the creation of subnets, and configuration of route tables and network gateways.


