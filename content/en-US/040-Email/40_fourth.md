---
title: "Agentless Email API"
chapter: false
weight: 40
---

## Agentless Email API
Similar to the Agentless SMS API that we covered earlier, Genesys Cloud also provides an Agentless Email API. As the name suggests, this API allows you to send emails programmatically without involving an agent. This API uses the same outbound domain that you set up for Outbound Email Campaigns. Let's consider a few use cases for using the Agentless Email API as opposed to an Outbound Email Campaign. 

- You want to notify a customer of the shipment of a product they ordered
- You want to send an email to a customer if they abandon a process that you want them to complete on your website, such as signing up for services 
    - this example combines the Agentless Email API with the power of Predictive Engagement
- Email a customer confirmation for an appointment that they scheduled over the phone
    - in this example, the email could be triggered by a button in a script

These are just a few examples. The ability to programmatically engage via different channels based on events that you define is one of the very powerful tools in Genesys Cloud CX!

Follow the same steps as before when we imported the Agentless SMS API data action, but this time use the agentlessEmailAPI.json file.