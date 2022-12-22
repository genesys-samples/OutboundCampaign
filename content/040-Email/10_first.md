---
title: "List Management"
chapter: false
weight: 10
---

## Create the list
At this point, you should be pretty familiar with how to create a list via a CSV file. The only difference this time is that you will need a field for email instead of a phone number. In theory, you could have one list with both a phone number and an email field. This would mean that the same list could be used for voice, sms and email campaigns. However, for G Freight, create a list with the following columns: 

- Name - Name of the person we are emailing
- Email - The email address we are sending the email to
- Company - Name of the company the person we are emailing works for
- Discount Code - Discount code the person will be able to use on the G Freight website when signing up to use G Freight for shipping

In the end, it should look like this. 
![Email Contact List](/images/emailContactList.jpg)

Once again, save this as a CSV file on your machine. Navigate in Genesys Cloud CX to Admin > List Management > Create New. Then give the list a descriptive name such as "G Freight Holiday Discounts" and then upload your CSV file.

Instead of selecting a phone column, we will select an email column instead and specify that this is the contact's work email. 
![Create Email List](/images/createEmailList.jpg)

Now you can save your contact list!
