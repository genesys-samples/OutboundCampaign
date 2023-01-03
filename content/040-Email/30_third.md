---
title: "Creating the Campaign"
chapter: false
weight: 30
---

## Creating the Campaign
Now that we have our list and a message to send to them, we're ready to create our campaign! Now, of course, we could apply other settings like filters and rules but this is a pretty simple email campaign we are setting up. Follow along to create G Freight's email campaign: 

1. Navigate to Genesys Cloud CX Admin > Campaign Management > Choose the Digital Campaigns tab
2. Click to create a new campaign and give it a descriptive name such as G Freight Holiday Campaign
3. We'll then set the following options: 
    - Contact List - Choose the list we created for the email campaign
    - Type - Set to Email
    - Email Column - Choose the column in your list that houses the email addresses
    - Email Campaign Template - Choose the Email Campaign Template where we created the message we are going to email out
    - From Address - Choose an email address to go with the domain you have set up for Outbound email 
    - Friendly Name - Choose a friendly name that it will show the email is coming from such as "G Freight"
4. At this point, your campaign should look something like this 
![Create an Email Campaign](/images/createEmailCampaign.jpg)
5. Optionally specify a reply to address if you'd like people to be able to respond to your emails
    - See this link about managing ACD Email https://help.mypurecloud.com/articles/manage-acd-email-routing/
6. You are now ready to save!

## Run the Campaign
Just like we tested before, we are now ready to test the email campaign. As long as you provided your email in the contact list, you should receive an email when we turn the campaign on. 

From the Campaign Management > Digital Campaigns dashboard, find the email campaign we just created. Toggle the campaign on and then you should receive an email. Congrats!

Note: Be sure to check your spam if you didn't receive the email.
