---
title: "Automation Tools"
chapter: false
weight: 40
---
## Automating Outbound

So far in the use case we discussed, G Freight is about half way there to having a fully automated outbound system. There are several ways customers can automate their outbound capabilities powered by Genesys and our extensive open APIs. Lets talk about how we could further automate their environment in this case.

Below are just some of the available APIs to date with specific outbound endpoints. 

![image](/images/outboundapis.png)

G Freight, using predictive engagement and back end APIs with their CRM, could automatically populate leads from their websites and determine what services the customers are interested in based on their behavior. From there, we could create a customer record with all the required information gathered on that customer. 

Furthering the automation, we saw that creating the list was a manual process. However, we could utilize APIs to then automatically trigger a call and update the contact list creating new entries with one of the many APIs we could find in our developer center. One example of APIs that could be used would be what we find below:

![image](/images/addcontactapi.png)

There are also other tools such as Terraform, the Genesys CLI and blueprints that can be utilized to further automate the outbound environment. In future sessions, we will be taking a deeper dive into what automating these systems look like. Stay tuned!