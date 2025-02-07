# SES and SNS for Everyone

**AWS SES (Simple Email Service) and SNS (Simple Notification Service) is a service that includes message routing and broadcasting capabilities.**

**What is SES and SNS?**
-  SES is designed for high volum email delivery while SNS offers a flexible message delivery across channels.

**Key Features**
-   Allows publishers to send messages to specific topics
-   Message fanout that sends a message to multiple subscribers
-   Supports mutiple protocols
-   Message filtering

**How SES and SNS Works**

![screenshot](/Ninjas/Masterclass-05Norvic/Day%2004/Assets/HowSESSNSWorks.png)

**Benefits**
-   Bulk messaging, competitive per use pricing, active monitoring of metrics

**Use cases**
-   Application monitoring to alert of critical events, Mobile app notifications, Automated workflows.

**Integration**
-   Configure AWS SNS notifications for Amazon SES to notify bounces and delivers it through SNS.   

**Getting Started**
-   SES - Setup SES account, Grant programmatic access (IAM), download AWS SDK to use SES APIs.
-   SNS - Create a topic using SNS console then enable encryption.

**Best Practices**
-   Implement least privilege access to different permissions for specific tasks.

**Challenges and Solutions**
-   Lack of visibility into account inventory - Centralize with IAM Identity Centre or integrate with Active Directory.

**Pricing overview**
![screenshot](/Ninjas/Masterclass-05Norvic/Day%2004/Assets/SESPricing.png)
![screenshot](/Ninjas/Masterclass-05Norvic/Day%2004/Assets/SNSPricing.png)

**Case Studies**
-   SES - Automate transactional messages, Globally deliver marketing emails
-   SNS - Push notifications, Distributed system architecture.

**Conclusion**
-   AWS SES and SNS is a suite of powerful services to handle messaging and communication needs.
