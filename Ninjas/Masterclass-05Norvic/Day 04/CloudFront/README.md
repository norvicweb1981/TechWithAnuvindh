# Getting Ahead of CloudFront

**AWS CloudFront is a Content Delivery Network service that accelerates distribution of static and dynamic web content.**

**What is CloudFront?**
-  web service that speeds up the distribution of web content like html, css, js and image files to users.

**Key Features**
-   Availability - Redundancy by supporting multiple origins for backend architecture.
-   Security - Protection against network and application layer attacks.
-   Realtime metrics and logging - Integrated with CloudWatch and provides realtime logs.
-   Continous deployment - Deploy two separate identical environment safely.

**How CloudFront Works**

![screenshot](/Ninjas/Masterclass-05Norvic/Day%2004/Assets/CloudFrontWorks.png)

**Benefits**
-   Low Latency by caching content at locations close to users
-   High transfer speeds to deliver content quickly by using AWS backbone.

**Use cases**
-   Fast and secure websites, Stream live and on-demand video, distribute patches and updates.

**Integration**
-   Integrates with EC2, S3, Application Load Balancers or any custom HTTP origin.

**Getting Started**
-   Create an S3 bucket then upload content in the bucket then create a CloudFront distribution that uses S3 origin with OAC.

**Best Practices**
-   Analyze ussage patterns and select the appropriate pricing tier. 
-   Regularly monitor and analyze AWS CloudFront costs.

**Challenges and Solutions**
-   Caching related issues - Analyze cache behaviors and align it with your content's caching requirements.

**Pricing overview**
-   ![screenshot](/Ninjas/Masterclass-05Norvic/Day%2004/Assets/CloudFrontPricing.png)

**Case Studies**
-   Full website delivery, Adaptive video streaming, API protection and acceleration.

**Conclusion**
-   AWS CloudFront delivers fast distribution of web content using a network of data centres providing low latency and performance.
