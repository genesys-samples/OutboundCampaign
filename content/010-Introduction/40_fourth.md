---
title: "Call Analysis Response"
chapter: false
weight: 40
---

## Call Analysis Response
Genesys Cloud CX uses our own patented Call Progress Analysis to determine whether a call is answered by a live party or an answering machine. Call Analysis Response allows you to define which action should happen based on each detection result. In the image below, you can see that if the system detects an answering machine, we are sending the call to an Outbound Flow. This Outbound Flow (created in Architect) will leave a voicemail using TTS that way we don't waste the time of an agent. On the other hand, if the system detects a live voice, it will transfer the call to an agent to speak with the customer. 
![Call Analysis Response](/images/callAnalysisResponse.jpg)
You'll also notice in the image that there are other response actions. Here is a summary of what each of them does: 
- Disable Post-Connect Call Analysis - when the call connects, the system disables all call analysis and also disables Answering Machine Detection
- Disable Answering Machine Detection - when the call connects, the system transfers without evaluating for a machine
- Enable Beep Detection - use this if you selected a transfer option and want the system to delay the response until after a voicemail beep