---
title: "Dialing Modes"
chapter: false
weight: 20
---
## Dialing Modes
To be effective for all types of different outbound campaigns, Genesys Cloud CX offers a wide range of different dialing modes. Dialing modes determine when and how a campaign places a call. These different dialing modes do not apply to our digital campaigns as those are always Agentless. Let's go over the 6 different dialing modes that Genesys Cloud CX offers. If you'd rather read a more in-depth summary of our dialing modes, including the benefits and drawbacks of each dialing mode, navigate to this page in our resource center. https://help.mypurecloud.com/articles/dialing-modes/ 

### 1. Preview 
This dialing mode will present information about the contact to an agent before dialing. An agent first accepts a call, then reviews the contact information, and then manually presses the call button. Preview dialing is typically used to reach high value contacts. 

### 2. Progressive 
Progressive dialing automatically dials one contact for each available agent. For example, if 10 agents are available in a queue, the system will place 10 calls. 

### 3. Power
Power dialing dials multiple phone numbers for every idle agent. It will perform an analysis to determine the risk of call abandonment. If the risk of call abandonment is low, it will increase the number of calls it makes for each available agent. Vice versa, if the risk of call abandonment is high, it decreases the number of calls it makes for each available agent.

### 4. Predictive 
The Predictive dialing mode uses a patented stage-based algorithm to make predictions about agent availability and place calls based on the output of the algorithm. This mode predicts when an agent will become idle and place calls before the agent is available so that by the time a customer answers a call, an agent is just becoming available.

### 5. Agentless
As implied in the name, this dialing mode does not involve an agent. The system responds to live contacts or answering machines based on settings in the Call Analysis Response assigned to the campaign. For example, if the system detects a live person, it can connect the caller to an Outbound Architect flow that plays some TTS (Text to Speech) about an appointment reminder.

### 6. External Calling
External Calling uses a third-party desktop dialer for TCPA (Telephone Customer Protection Act) compliance. An agent will be presented with contact information similar to the Preview dialing mode, but in External Calling, the agent must copy and paste the phone number into the external dialing system. 