---
title: "List Management"
chapter: false
weight: 10
---

## Create the Contact List
Once again, we will create a contact list in excel. We'll still have the customer name and phone number but now we want to include some additional columns. The columns we will create are as follows:
- Customer Name - Name of the person we are sending the text to
- Company - Name of the company the *customer name* works for
- Phone Number - The phone number we are reaching out to
    - Make this your cell phone that way you can ensure it works
    - note: this must be in E164 format. For example, +19876543210
    - Typically excel will exclude the plus sign if you just type it in. You must provide formatting to the cells and then under Number > Category choose Custom. Then input *+000* in the type
    ![Format Cell](/images/formatCell.jpg)
- Delivery Date ISO - The delivery date in ISO format
    - We are adding this date in ISO format so we can make decisions based on the dates in our contact list filters
    - Here is an example of a date in ISO format: 2022-07-15T00:00Z
    - Make this date one that occurs in the next two days (either tomorrow or the day after)
- Delivery Date Normal - The delivery date in normal to-read format
    - We are adding a secondary delivery date in a normal format so we can include this value in the text message we will send to the customer
    - Make this the same date as the one in ISO format
- Tracking ID - Any string of alphanumeric characters 
    - We will include the tracking ID in the text we send to the customer as well

In the end, your contact list should look like this.
![SMS Contact List](/images/smsContactList.jpg)

Just like before, in the voice section, we will save this list as a CSV file and then upload the Contact List under List Management. Click to create a new contact list and give it a descriptive name, such as "G Freight Deliveries." Upload your CSV file and then select the Phone Number column and choose cell as the type. Once you've done that, go ahead and save the list!
![SMS Upload List](/images/smsUploadList.jpg)

## Filter the List
We don't want to text everyone on the list at random. For this campaign, we only want to text people with deliveries if their delivery is arriving within the next two days. To do this, navigate within List Management to the Contact List Filters tab. Click to create a new Contact List Filter and give it a descriptive name such as "Upcoming Delivery." For the contact list dropdown, choose the contact list that you just created.

We now need to create two conditions:
1. The first condition is based on the Delivery Date ISO column and we want to be earlier than 2 days in the future
2. The second condition is also based on the Delivery Date ISO column and we want it to be later than 0 days in the past
![Upcoming Delivery Filter](/images/upcomingDeliveryFilter.jpg)

As you can see in the screenshot, because the filter is looking for both conditions, it will only contact contacts that match both conditions. You can also preview the filter to ensure that your contact matches the contact list filter. Once you've confirmed your contact matches the contact list filter, you can save and move to the next section!