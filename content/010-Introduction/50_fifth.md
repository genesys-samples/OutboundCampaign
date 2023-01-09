---
title: "Rule Management"
chapter: false
weight: 50
---

## Rule Management
Rules are a great way for you to take intelligent actions either before a call is placed or after a call ends. They use a condition and action framework. In other words, if the conditions are met, then this action will take place. Genesys Cloud CX has three different types of rules that you can manage. 

### Call Rule Sets
Call Rules are for voice campaigns. They can be either pre-call or wrap-up rules. Pre-call means the rule will be evaluated before a call is placed and wrap-up means the rule will be evaluated after the call is over. Let's take a look at an example of both a pre-call and a wrap-up rule. We'll also be covering these when we get to the follow-along section later in the workshop. 

This pre-call rule evaluates the account balance for the contact and then switches the campaign dialing mode to preview if their account balance is over $100,000. 
![Pre-Call Rule](/images/preCallRule.jpg)
This wrap-up rule schedules a callback for 5 minutes in the future if the system disposition is disconnect.
![Wrap-up Rule](/images/wrapUpRulev2.jpg)

### Digital Rule Sets
Digital Rule sets are essentially the same as Call Rule sets except these are applied to SMS and Email campaigns. Instead of pre-call and wrap-up, digital rules use pre-contact and post-contact. The conditions and actions are slightly different as they are more targeted toward digital interactions. While they may have differences, they are conceptually used the same way as Call Rule Sets. 

### Campaign Rule Sets
Unlike Call and Digital Rules, Campaign rules apply to the campaigns themselves. These can affect the execution of campaigns, based on the current number of campaign agents or a campaign's percentage of completion. In the example below, if the agent count of the campaign is less than or equal to 10, we turn the campaign off. 
![Campaign Rule](/images/campaignRulev2.jpg)