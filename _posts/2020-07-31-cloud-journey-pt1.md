---
layout: post
title: "Journey into the Cloud: Part 1"
tags:
- Career
- Blogging
- Writing
- Cloud
- AWS
- Google Cloud
thumbnail_path: blog/cloud-journey/cloud.jpg
---

# Journey into the Cloud: Part 1 - AWS Cloud Practitioner Certification
These days businesses are looking at improving operational efficiency and agility by leveraging technology. For a majority of businesses both large and small, opportunities exist to make use of cloud-based solutions to run some of their systems. These can be in terms of computing power, storage, or utilizing some of the big data, and machine learning solutions offered by Azure, Google, and AWS.

Towards the end of 2019, the client I am working at announced that it had chosen AWS as its preferred cloud partner. As a business, the client would be slowly migrating some of its systems to the cloud to increase its agility and save on IT operation costs. Globally a lot of organizations, are also taking the steps of moving away from monolith on-premise applications to smaller sized cloud-native applications running in the cloud.

Such trends mean that going into 2020, I had to start learning more about the cloud. Learning about AWS was a natural first step, as this is by far the major player in terms of offering cloud services. 

{% include image.html
path="blog/cloud-journey/aws-certifications.jpg"
alt="AWS Certifications" %}


AWS has a whole catalogue of certifications under its stable. They are categorized under foundational, associate, professional and speciality exams. 
One can also separate them according to roles. If you are starting or working in a less technical role, then the Cloud Practitioner exam is a good exam to try out first.  

Individuals in more technical roles, like developers and architects, might find it more useful to tackle the exams tailored for those roles. As a first foray into the cloud, I decided to write the AWS Cloud Practitioner exam as this would give me a broad understanding of AWS and its service offerings.

## AWS Cloud Practitioner

{% include image.html
path="blog/cloud-journey/aws-cloud-practitioner.png"
alt="AWS Cloud Practitioner" %}

[AWS Certified Cloud Practitioner](https://aws.amazon.com/certification/certified-cloud-practitioner/) is a recommended, optional step toward achieving an Associate-level or Specialty certification. As a foundational level exam, it equips individuals with an overall understanding of the AWS Cloud. The exam itself is 65 questions and has a time limit of 90 minutes. You need to score a *minimum of 700 out of 1000 points to pass the exam*. 
The question format of the exam is multiple-choice and multiple-response.

The knowledge required to pass the exam is organized into four test domains, these are:
 * ***Cloud concepts***
 * ***Security***
 * ***Technology***
 * ***Billing and Pricing***. 
 
 Within each test domain, there are several objectives, which broadly describe the knowledge and experience expected to pass the exam. I will discuss the key objectives for each domain below:

### Cloud Concepts:
This domain 28% of the exam and covers objectives such as the AWS Cloud, and its value proposition, identifying the aspects of AWS economics, and listing the different cloud architecture design principles. You should be able to describe the benefits of public cloud services and be able to define what types of services are available on AWS. As well as understanding the advantages of the cloud. You also need to understand the design principles of creating cloud architectures, this includes loose coupling, scaling (vertically and horizontally), bootstrapping, and automation. 

### Security:
Covering 24% of the exam, Security is another key domain, and talks about the AWS shared responsibility model, which defines who is responsible for different aspects of the technology stack from the data center through to servers, firewall rules, and data encryption. The other major topics include identity and access management, AWS Cloud security and compliance concepts protection, and other tools and services for security support.

### Technology:
Technology is the most important domain of the AWS Certified Cloud Practitioner certification exam. To get through this section you have to obtain a working knowledge of core AWS services. Some of these services are some of AWS's compute offerings such as ECS, Lambda, Elastic Beanstalk, and ECS. Storage services that frequently appear in the exam are RDS, Amazon DynamoDb, and S3. Other key services include Route 53 for routing, ELB for load balancing, and SNS for messaging. To ace this section, you need to understand the core AWS services and what they are used for. Developing a deep level of knowledge of the services will not be required, but you do need to understand its purpose, benefits, and use cases.

One also needs to understand the underlying global infrastructure, which makes up the AWS Cloud. This includes regions, availability zones, and edge locations. Make sure you understand which services are globally or regionally defined. You should also know the customer configurable building blocks of cloud services including VPCs, and subnets, and connectivity options such as Internet Gateways, VPN and Direct Connect. Being able to differentiate between NAT Instances and NAT Gateways, and the relative benefits of each service will also be key. 

### Billing and Pricing: 
Billing and Pricing domain focuses on comparing and contrasting the various pricing models of AWS services. Most services on AWS are offered on a pay per use basis, but there are options to reduce costs by locking into 1 or 3-year contracts. Some services such as VPC, CloudFormation, and IAM are free, as well as inbound data transfer. However, the resources creates by Cloud formation and outbound data incur costs. Another key learning outcome is to be able to compare and contrast the various pricing models for AWS. 

As well as being able to recognize the various account structures concerning AWS billing and pricing. Accounts can be organized into Organizations for centralized management and consolidated billing. You might want separate account structures to manage different policies for production and non-production resources, or you might implement consolidate billing to take advantage of volume discounts. For billing support, you need to know the services and tools available to you and what levels of support you can get from AWS support plans. Tools include AWS Cost Explorer, AWS Simple Monthly Calculator, and Total Cost of Ownership calculator.

##  Finding Study Material

After getting an understanding of the key learning objectives, I needed to formulate a plan of action to prepare and write the exam. The following were the key resources I utilized:

### Neal Davis’s AWS Certified Cloud Practitioner Ultimate Exam Training: 

{% include image.html
path="blog/cloud-journey/neal-davis.jpeg"
alt="AWS Cloud Practitioner" %}
This course covered all the domains with key labs outlining how you utilize AWS key compute, storage, and networking services. Coupled with the [course](https://www.udemy.com/course/aws-certified-cloud-practitioner-training-course/) on Udemy, the author provides detailed slides and a cheat sheet that was very handy when I needed to quickly review concepts. 
You can find the additional resources on this [link](https://digitalcloud.training/certification-training/aws-certified-cloud-practitioner).

Another key advantage of this course was the handy end of module quizzes, which helped reinforce learning, and highlighted areas I still needed to review. With over 12+ hours of video content, and several labs, this course took me about a month to complete, and this became the basis of my final preparations for the exam.

## Practice, practice, practice

{% include image.html
path="blog/cloud-journey/practice.jpg"
alt="Practice" %}

For practice exams, I also utilized Neal Davis's AWS Certified Cloud Practitioner Practice Exams 2020 Udemy [course](https://www.udemy.com/course/aws-certified-cloud-practitioner-practice-exams-c/), which came with five exams similar to the ones I got on exam day.  Neal recommends getting to a point of scoring 80% or more in the practice exams before booking your exam. I [booked](https://www.aws.training/certification?src=exam-prep) my exam a month in advance and used the weekends to take and review the practice exams twice before taking the actual exam.  By then I was averaging scores above 90% and was confident I would pass the exam. I wrote the exam on the 12th of June 2020, with a final score of 965/1000.


## Next Steps

After completing my exam I signed up for the [Google Africa Developer Scholarship](https://help.pluralsight.com/help/google-africa-developer-scholarship-2020). My focus will be on completing the Cloud Engineer track. 

{% include image.html
path="blog/cloud-journey/gads.jpeg"
alt="Google African Developer Scholarship" %}

In my next blog post, I will be sharing my experience going through all phases of the program.
