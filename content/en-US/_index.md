---
title: "Outbound Campaigns with Genesys Cloud CX"
chapter: true
weight: 1
---

# Outbound Campaigns with Genesys Cloud CX

## Welcome to our Outbound Campaign Workshop
Our customer, a Package & Freight delivery firm, is re-imagining the way they engage with their customers. The business, G Freight, already uses Genesys Cloud CX for inbound communications. Now they want to take a more proactive approach to the way they engage with the companies that they do business with. In this workshop, it'll be your job to help G Freight utilize the full breadth of Genesys Cloud CX's outbound suite to satisfy and exceed their needs. G Freight has broken its requirements out by media type and we will take a similar approach to our configuration as we go through the workshop. 

### Voice
G Freight uses the voice channel for sales outreaches. As a B2B company, these are typically high-impact calls where they call business executives of prospective customers. They also need automated list management fed from various sources and pre and post calls rules to help automate lists as they are running.

### SMS
G Freight wants to use SMS for freight delivery updates. For example, they want their businesses to be contacted for the estimated delivery time, delays and any other changes to their deliveries.

### Email
G Freight wants to utilize email campaigns for offering discounts to their customers during the holiday season. Black Friday is coming up, and G Freight wants to gather up more of their customer's shipping needs by offering Black Friday discounts to them.

## Download Key Assets  
As a part of today's workshop, we are giving you access to some key resources that you can use to help G Freight with its outbound endeavors. The resources are: 
- An Agentless SMS API Data Action - This API allows you to send SMS notifications without involving an agent. This feature allows Genesys Cloud to send SMS notifications from backend systems automatically, based on triggered events or from an Architect flow or script.
- An Agentless Email API Data Action - Similar to the SMS API above, this API allows you to send emails without the need to involve an agent. Once again, this allows Genesys to send emails from backend systems or an Architect flow or script.
- Script - Scripts allow you to customize the agent desktop in a way to help agents process interactions. They are a vital part of outbound campaigns.

To download these files, navigate to this GitHub repository, https://github.com/genesys-samples/OutboundCampaignWSDownloadables, and click Code and then "Download ZIP."
![Download Repo](/images/repoDownload.jpg)

You'll then extract the files somewhere where you can find them later on in the workshop. 

## Learning Objectives
- Learn to setup and configure both voice and digital campaigns
- Learn how the Genesys Cloud CX Outbound APIs can be leveraged for automation 
- Understand the different dialing modes offered with Genesys Cloud CX
- Learn how to use Rule Management for Campaigns
- Learn how Genesys Cloud CX leverages Contactable Time Sets to ensure we are calling people at appropriate hours
- Learn how to manage contact lists with Genesys Cloud CX.

## Prerequisites
- Access to a Genesys Cloud CX org where you have access to configure Outbound Campaigns
- We will provide additional prerequisites in each section (Voice, SMS, & Email)