---
title: "Agentless SMS API"
chapter: false
weight: 40
---

## Agentless SMS API
Oftentimes, contacts aren't on a list already when you want to send them a text message. In G Freight's example, they also want to send SMS messages to contacts when there is a delay in their delivery. While you could use the API to add that contact to a contact list to contact through an SMS campaign, wouldn't it be more efficient if you could send an SMS based on the trigger from the external system itself? This way, the customer would receive the text message update as soon as the external system is updated. That is where the Agentless SMS API comes into play.

The Genesys Cloud Agentless SMS API allows developers to send and receive SMS messages without the need for a traditional agent. This API can be integrated into a variety of applications and systems, enabling users to communicate with their customers through SMS seamlessly and efficiently. The API supports both inbound and outbound SMS messaging, as well as the ability to track delivery status and manage responses. With the Genesys Cloud Agentless SMS API, developers can easily add SMS functionality to their applications and improve customer communication and satisfaction. In G Freight's example, they can use this API to send a text message to a customer when an update is made to delivery in their delivery management system.

You have already downloaded the JSON file to import into your org and create a data action that utilizes the Agentless SMS API earlier in the workshop. You can then use this data action in Architect flows or scripts.

Using the agentlessSMSAPI.json file that you downloaded earlier, follow these instructions to import as a data action in your org. https://help.mypurecloud.com/articles/import-or-export-a-data-action-for-integrations/ Importantly, ensure that you are importing as a Genesys Cloud Data Action as this is an internal API call. If you don't have the Genesys Cloud Data Actions integration installed, follow this article. https://help.mypurecloud.com/articles/about-genesys-cloud-data-actions-integration/

To explore other ideas for using the Agentless SMS API, consider the following use cases: 
- Sending an SMS with a 4-digit code for Multi-Factor Authentication in an IVR
- Texting all supervisors if the emergency toggle is ever turned on in Genesys Cloud CX
    - https://help.mypurecloud.com/articles/emergencies/
- Texting a customer a survey after they finish up an interaction
- There are many more use cases. Let your imagination run wild with this one!