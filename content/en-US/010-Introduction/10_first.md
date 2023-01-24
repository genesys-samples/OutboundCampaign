---
title: "List Management"
chapter: false
weight: 10
---
## List Management
Proactive outreach is only successful if you are reaching out to the right people. If we were comparing building a house and building an outbound campaign, list management would be like laying the foundation. A good contact list not only has the right people on it - but it is also filterable. This means that you can set calling rules and limits based on the data that lives in the list. 

### Uploading the List
Contact Lists in Genesys Cloud CX can be uploaded via CSV file or API. The list itself must contain a column in which you are specifying either a phone number or an email (or both). Beyond that, the list can contain as much information as you want. Adding additional columns to your list is good practice. Take a look at the screenshot below and then we'll explain how we use those columns to make decisions for our campaign.
![Contact List](/images/contactList.jpg)
As you can see, the columns differentiate one contact from the next. For example, Erica has a higher account balance and is a VIP customer. This means we might want to give her higher priority when we place the call. 

### Contact List Filters
Going back to the previous screenshot, Erica also isn't signed up as an online user. Perhaps a business wants to push its customers to sign up online because they've noticed online users spend more with them. They might apply what we call a Contact List filter to run a campaign to reach out only to people who aren't online users yet. Instead of having to create a separate contact list, you can simply apply conditions to the campaign through Contact List Filters. Here is an example of the use case we just outlined.
![Contact List Filter](/images/contactListFilter.jpg)

### DNC Lists
A DNC (Do Not Contact) list is a source of phone numbers or email addresses to exclude from a campaign. DNC lists help organizations stay compliant with legislative requirements. Genesys Cloud CX supports three types of DNC entries:
1. Internal - Administrators can create an internal DNC list by uploading a file of telephone numbers. Administrators commonly acquire these numbers from state and federal agencies, purchase them from third-party providers, or use in-house corporate records. Internal DNC lists can include an expiration DateTime column to block attempts for a certain period. Contact attempts can resume after the expiration date.
2. Gryphon - integrates Outbound Dialing with just-in-time DNC scrubbing provided by Gryphon Network Corporation’s web service. To use this feature, you must have a subscription with the provider. 
3. DNC.com - integrates Outbound Dialing with just-in-time DNC scrubbing provided by Contact Center Compliance Corporation’s web service. To use this feature, you must have a subscription with the provider.

### Attempt Controls 
Have you ever been called by the same number way too many times? It's extremely frustrating to be on the receiving end of that. As a business, you don't want to be frustrating the people you are calling. You also want to stay within any compliance requirements. Attempt Controls are a way to limit the frequency with that you are reaching out to certain customers or certain numbers.


* Disclaimer - This workshop will not provide any legal guidance. Please consult with your legal/compliance team about how you can stay within compliance requirements.