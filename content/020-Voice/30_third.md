---
title: "Creating our Campaign"
chapter: false
weight: 30
---

Now that we have created all of the base elements, we to the easy part. Creating our campaign!

We now navigate to Admin > Outbound > Campaign Management. Ensuring you are in the voice campaigns tab, we select "create new"

![image](/images/createnewcamp.png)

Below you will see all of the fields where created our configurations.

1) Naming out Campaign
2) Selecting our Queue
3) Selecting our Contact list
4) Entering a caller ID


![image](/images/campaignconfig.png)

> Note: The caller ID designated has to be another valid number 

![image](/images/timeseterror.png)

 You'll notice when trying to tie in your contactable time set you receive an error noting that you have not designated a time zone for the contact list. Yes, we meant to do this! When we created our list, we had only tied the phone number column as that was the only one recognized. For our campaign today, we do not need to designate timezone as we are setting this to call our own phone. However, In the future, having a time zone field designated within the list would allow the contactable time sets to recognize the time zone of the contact. After all, you don't want to set calls for 9AM Eastern, and have someone receive that call in Pacific standard, 3 hours before you want to call!


Another way we can schedule when the campaign will call is through the schedule tab in the campaign management configuration window. However, Take to mind that this does not configure time zone mapping unless it is designated within the campaign created. 

![image](/images/campschedule.png)

Now its time to test your campaign! Ensure you are on queue and toggle the campaign on. You should receive an interaction within your agent window. 
