---
title: "List Management and Queues"
chapter: false
weight: 10
---

## Creating Our List

As we learned from an earlier section, the very first thing needed for any outbound campaign is a list of people to call, email or text In today's case, we will be building a basic list of our "prospects" to include, which in this case, is you!

We begin by creating our CSV file in excel. For today's workshop, our list will be very basic. We are only looking to include the name of the prospect, their phone number and any extra desired fields such as prospective interests taken from the G Freight site. Since we are only looking to start by making this functional, we will just add a name and phone number in the steps below:

First, we will open excel and create a new workbook. Once we have created our workbook, we will be creating two columns. The first column will be "Prospect Name" and the second will be "Phone Number". Then, add your desired name as well as a phone number you will be able to answer once called such as your cell or work number.

![image](/images/listdatafield.png)

> Note: Putting your friends phone number in here is funny, but remember, they will get a call!

Next, we will need to save the file as a CSV. To do this in excel, click Save As and select CSV as the file type, as shown below.

![image](/images/csvsaveas.png)![image](/images/csvsave.png)

Now that we have our list created, it's time to upload our list in the Genesys CX UI. We will navigate to Admin > Outbound > List Management

Once we have reached list management, we will click create new and upload our list as shown below:

Once your list successfully uploads, you will need to name your list, and then select the column that the system will recognize where the phone number is found. In this view, Genesys gives you a visual of what is recognized in terms of columns. As we create more complex lists with more data sets to be taken into account, we take the recognized columns and tie them to attributes such as times zones, account balances and more. For today's workshop, we will focus on just tying the phone number column. 

![image](/images/createnewlist.png)![image](/images/uploadlist.png)


## Creating Our Queue
For the campaign to know which agents to send the interaction to, we will need to create a queue with agents we would like to handle the outbound interactions. To do this, we navigate from Admin > Contact Center > Queues. Next, create a new queue and add our user as an agent. Name the queue something relational to outbound, for easier reference when creating our outbound campaign. 
> Shortcut tip: if your using the same agents and configurations as another queue, you may select that queue with the "copy settings and members from" button

![image](/images/createqueue.png)![image](/images/queuemembers.png)![image](/images/addusertoqueue.png)

Congratulations! You have now successfully created your contact list and queue. Next, we will be creating the rule that dictates when the callers in this list can be called.