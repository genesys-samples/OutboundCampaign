---
title: "SMS Campaigns"
chapter: true
weight: 30
---

## Prerequisites for this section
- SMS Number to use for the campaign

## Getting Started with SMS Campaigns
In this lesson, we'll help G Freight set up an SMS for freight delivery updates. We'll also look at how the Genesys Cloud CX API could be used to help send SMS text messages for delays and delivery changes in a fully automated fashion.

Genesys Cloud CX allows SMS campaigns to be run with either a long or short code phone number. The type of code you need is largely based on specific regulations within the messaging country. Genesys customers bear the responsibility for understanding and complying with country-specific regulations. 

Now before we dive into the configuration, let's get a quick view of the steps we are about to take: 

1. Create a new contact list with a column specifying the delivery date
2. Create a contact list filter to filter out only contacts where the delivery is expected to happen within the next two days
    - for example, if the delivery date is expected to be January 5th those contacts would only receive texts on January 3rd and 4th
3. Create an SMS Campaign template
    - SMS Campaign templates allow you to craft the text message that will be sent to your customers
        - Genesys customers are ultimately responsible for adding standard opt-out language and options to their content
4. Create the campaign
5. Create a schedule for the campaign to run