---
title: "Dialing Modes"
chapter: false
weight: 20
---
## Dialing Modes
To be effective for all types of different outbound campaigns, Genesys Cloud CX offers a wide range of different dialing modes. Dialing modes determine when and how a campaign places a call. These different dialing modes do not apply to our digital campaigns as those are always Agentless. Let's go over the 6 different dialing modes that Genesys Cloud CX offers. If you'd rather read a more in-depth summary of our dialing modes, including the benefits and drawbacks of each dialing mode, navigate to this page in our resource center. https://help.mypurecloud.com/articles/dialing-modes/ 

### 1. Preview 
This dialing mode will present information about the contact to an agent before dialing. An agent first accepts a call, reviews the contact information, and then manually selects the number to be dialed and clicks it to launch the call.

### 2. Progressive 
Progressive dialing automatically dials one contact for each available agent. Call progress analysis will sort out answering machines, fax machines, and SIT tones so that just the live answers are delivered to those available agents.

### 3. Power
Power dialing dials multiple phone numbers for every idle agent. A pacing algorithm will determine the risk of call abandonment. If the risk of call abandonment is low, it will increase the number of calls it makes for each available agent. Vice versa, if the risk of call abandonment is high, it decreases the number of calls it makes for each available agent. Call progress analysis is used again so that just the live answers are delivered to those available agents.

### 4. Predictive 
The Predictive dialing mode uses a patented stage-based algorithm to make predictions about agent availability and place calls based on the output of the algorithm. This mode predicts when an agent will become idle and place calls before the agent is available so that by the time a customer answers a call, an agent is just becoming available. Call progress analysis is used again so that just the live answers are delivered to those available agents.

### 5. Agentless
As implied in the name, this dialing mode does not involve an agent. The system responds to live contacts or answering machines based on settings in the Call Analysis Response assigned to the campaign. For example, if the system detects a live person, it can transfer the caller to an Outbound Architect flow that has self-service (DTMF or even a voice bot) but if it's an Answering Machine it can transfer to a flow that can wait for a beep and simply play a pre-recorded or TTS (Text to Speech) message.

### 6. External Calling
In this mode, the agent will be presented with contact information similar to the Preview dialing mode, but in External Calling, the agent must copy and paste the phone number into a third-party desktop dialer. Some third-party desktop dialers (such as Gryphon Networks) will provide indemnification for their clients and this integration allows our customers to leverage that to avoid risk.