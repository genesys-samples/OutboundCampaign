---
title: "SMS Campaign Template"
chapter: false
weight: 20
---

## Crafting our Message
We now need to craft the message that will be sent to our contacts on the list. Genesys Cloud CX offers two ways to craft your message for digital campaigns.
1. SMS Campaign Template - a type of canned response that allows you to dynamically reference values in a contact list
2. Contact List Column - a column in the list that allows you to specify a unique message for each contact row.

For the G Freight SMS campaign, we'll be using an SMS Campaign Template. Follow these steps to create an SMS Campaign Template:
1. Navigate to Genesys Cloud CX Admin > search for Canned responses
2. Click "Manage Libraries" and then click to add a new library and name it "G Freight"
3. Navigate back to the Canned Responses page and search for the G Freight library you just created
4. Add a response in the G Freight library
5. Give the response a descriptive name such as "Delivery Message"
6. For the Response Type, select Campaign SMS Template
7. On the Insert Substitution section, click to insert the contact list that you created earlier for the SMS campaign
![Import Contact List](/images/importContactList.jpg)
8. This should add substitution values for all the columns in your contact list. You can now paste in this message and any value in squiggly brackets will dynamically be filled with the value in the corresponding column for that contact
    ```Hi {{Customer Name}}! 👋 G Freight here. Just wanted to give you a heads up that your package will be delivered on {{Delivery Date}}. You can keep up with where your package is by navigating to our tracking website and providing your tracking ID. www.packagetracker.com {{Tracking ID}}```
9. Your response should look like this. If it does, press save
![SMS Template](/images/smsTemplate.jpg)