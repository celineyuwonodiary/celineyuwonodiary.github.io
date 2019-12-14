---
layout: post
title: "Introduction to Cloud Computing"
date: 2019-12-02 12:43:45 +0900
categories: [AWS, FutureTech]
---

### What is Cloud Computing?

When the needs of a company changes, the company's software, hardware, and information resources needs will also change. A company might need to scale-up and use a faster computing system with a larger database. On the other hand, a company may need to scale-down and use a simpler system.

With the traditional on-premise IT infrastructure, it is hard for a business to scale-up or down. A company that needs to scale-up will need to upgrade its IT Infrastructure, which takes time and money. In contrast, scaling-down means not being able to use their IT Infrastructure optimally and paying for unused resources.

Cloud computing allows companies to simply connect and use resources stored in virtual data centers via the internet. The companies will only have to pay to use these resources at a pay per use basis. This on-demand system saves companies time and money, and makes it very easy for a company to scale-up or down.

### Three Deployment Models of Cloud Computing

<img src="https://www.cloudflare.com/resources/images/slt3lc6tev37/2jBaVWKgbOUNLDNw7QJYPh/563316b4290e2919f7510ae59a3ae3ca/public-cloud-vs-private-cloud.svg" alt="Private Cloud vs Public Cloud" width="750px" />

**Private Cloud**

In a Private Cloud, the cloud server is only managed by one company and maintained in a private network. It is highly secure and is best for companies that handle sensitive data like the government. The server can be stored on-premise or hosted, but is commonly stored on-premises in the company's data center. Private cloud providers include IBM Cloud Private and Liquid Web. A company has to pay for maintenance costs only for on-premise Private Cloud and not on a hosted Private Cloud. An on-premise Private Cloud can be compared to a traditional on-premise IT infrastructure, where these two terms differ is that the former is a deployment model and the latter refers to the location of the server.

**Public cloud**

A Public Cloud means that the cloud infrastructure is made available to the general public and is owned by cloud service providers like AWS and Azure. This is the most commonly used cloud deployment model. It is off-site and a server may be shared between multiple companies, also called multi-tenancy. It has a lower upfront cost with a pay as you go model, making it a flexible option. Most businesses use this.

**Hybrid cloud**

Hybrid Cloud uses both private and public clouds. Companies may use services from multiple cloud providers and this is called multi cloud, but many cloud providers also provide the hybrid cloud service. It is efficient because companies can choose which cloud to store their resources in depending the type of resource.

### Three Cloud Computing Service Models (Pyramid Form)

![Differences between IaaS, PaaS, and SaaS](https://mycloudblog7.files.wordpress.com/2013/06/screen-shot-2015-06-09-at-2-13-05-pm1.png?w=780&h=372)

**Infrastructure as a Service (IaaS)**

In an IaaS, the company has entire control over the IT infrastructure, including the application, data, runtime, and middleware. Target users are system administrators and network architects. The company has no control over the virtual environment where the operating system runs in. Examples of IaaS are AWS EC2 and S3.

- **Pros:** Cloud provides Infrastructure, enhanced scalability.
- **Cons:** Security issues, network delays, needs staff to maintain the infrastructure.

**Platform as a Service (PaaS)**

For Paas, the development environment, operating system, web server, and database is provided by the vendor. This means that developers can build, compile, and run their programs without worrying about the underlying infrastructure. Examples of Paas are Red Hat, AWS Elastic Beanstalk, and Heroku.

- **Pros:** Cost effective and scalable, faster market for developers, easy deployment of web applications.
- **Cons:** Developers limited to providers' language and tools, migration issues.

**Software as a Service (SaaS)**

SaaS is ready to use application that is accessible in the browser via the internet. The target users are the average end user of a web application like you and me. With SaaS, there is no need to install a software on PC, and one software is available for use by multiple users.
Examples of SaaS includes Gmail, Google Docs, and Salesforce.

- **Pros:** Universally available.
- **Cons:** Internet and browser issues.

### Top Cloud Providers

1. **AWS:** Focuses on mainly on IaaS (EC2, S3) but has PaaS (Elastic Beanstalk).
2. **Microsoft Azure:** Focuses on AI, analytics, and IoT, Azure Compute and offers services in the category of IaaS (Azure Virtual Machines) and PaaS (Azure App Service - Windows Based). PaaS caters toward Windows-based development.
3. **Google Cloud**: Offers similar services to Azure, including Iaas (Google Compute Engine) and PaaS (Google App Engine). PaaS caters toward Linux-based development.

### Resources

[Cloud Computing: What is Cloud Computing?](https://www.youtube.com/watch?v=uYGQcmZUTaw) <br/>
[Cloud Computing in the Year 2020](https://www.youtube.com/watch?v=1pBuwKwaHp0) <br/>
[Cloud Computing Services Models - IaaS PaaS SaaS Explained](https://www.youtube.com/watch?v=36zducUX16w) <br/>
[IaaS vs. PaaS options on AWS, Azure and Google Cloud Platform](https://searchcloudcomputing.techtarget.com/tip/IaaS-vs-PaaS-options-on-AWS-Azure-and-Google-Cloud-Platform) <br/>

### Images

[Private Cloud vs Public Cloud](https://www.cloudflare.com/resources/images/slt3lc6tev37/2jBaVWKgbOUNLDNw7QJYPh/563316b4290e2919f7510ae59a3ae3ca/public-cloud-vs-private-cloud.svg)<br/>
[Differences between IaaS, PaaS, and SaaS](https://mycloudblog7.files.wordpress.com/2013/06/screen-shot-2015-06-09-at-2-13-05-pm1.png?w=780&h=372)
