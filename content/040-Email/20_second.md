---
title: "Email Campaign Template"
chapter: false
weight: 20
---

## Crafting your Email  
Similar to the SMS Campaign, email messages are crafted through Email Campaign Templates. This allows you to create a dynamic email that can be sent to all contacts in your list. Follow along to create your Email Campaign Template: 

1. Navigate to Genesys Cloud CX Admin > Canned Responses
2. Search and find the G Freight library that you created in the SMS section > Click to add a new response
3. Name the Response "Holiday Email Discounts"
4. For the Response Type, choose "Campaign Email Template"
5. Click on the insert substitutions section and import the contact list you created for the email campaign
![Insert Email List](/images/insertEmailList.jpg)
6. Copy this and paste it to the Email Subject line
``` 
Holiday Discount for {{Company}} 
```
7. Copy this and paste it to the Email 
```
Hi {{Name}}, 
Your company has been selected for a special promotion for G Freight. You can sign up for our freight delivery services for 30% off if you sign up before December 25th! 

To sign up, navigate to our website and checkout with the code {{Discount Code}}.

Thank you!

G Freight
```
8. You'll need to replace the items in squiggly brackets with your actual insertion values
    - We must do that because it will not recognize the substitution values if you paste them in. You must use the substitution values in the list
9. Press save and you are ready to create your campaign!

