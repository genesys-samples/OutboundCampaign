---
title: "Time Zones"
chapter: false
weight: 30
---

## Managing Time Zones
Businesses, of course, don't want to be calling and texting their customers at all hours of the night. But what about global businesses, with customers in multiple different time zones? Let's explore two options that Genesys Cloud offers to help businesses only contact their customers at optimal times of the day. 

### Contactable Time Sets
Contactable Time Sets allow you to specify the time zone of the caller in the contact list. The administrator then defines the set of contactable times that correspond to the given time zones. In this example, any contact who has the America/Chicago time zone column in the contact list will only be called during these local hours. 
![Contactable Time Set](/images/contactableTimeSet.jpg)
You can then add other time zones to your contactable time set as well. You can see here that this is a US-based campaign and covers Eastern, Central, Mountain and Pacific time zones.
![Time Set](/images/timeSet.jpg)
The last step is to assign this Contactable Time set to a campaign. While the campaign is running, it will check for the time zone column and then only call if we are within the acceptable local hours. 
