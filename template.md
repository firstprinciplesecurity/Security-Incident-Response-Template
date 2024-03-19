# Security Incident/Investigation Template

## 👑 Authors: Ashley Tolbert and Swathi Joshi 
#### 🗓️ Publish Date: March 19, 2024

**“Ticket # or INVESTIGATION # or CODENAME “** 

Best Practice is to have a numbering or naming system. Link it at the top of the document. Make sure access permissions are accurate. 

**[Confidential] [Ristricted] [Highky Ristricted]** 

Use the correct classification type based on your internal company policy/guideline. 

**📞 Bridge Information: [Details]**

**👻 Incident Commander: [Name]**

**📝 Scribe: [Name]**

**Summary:** Point-in-time summary of the incident. Needs to be updated periodically. 

**Blast Radius/Exposure:** Number of systems, number of customers, number of records, types of fields, etc  

**Historical Analysis:** One of the challenges while handling the incident is that facts keep changing as the investigation progresses. This section is dedicated to keeping all analysis information here. Don't worry about keeping all the information in chronological order, often events don't make sense while the investigation is progressing. 

  | Time | Analysis Notes | 
  | :---: | :---: |
  |       |      | 
  |       |      | 
  |       |      | 

  
**Timeline (in UTC):** Using the historical information you can now form a timeline.


| Event | Timestamp | Notes |  
| :---: | :---: | :---: |
|        |        |        | 
|        |        |        | 
|        |        |        | 

**Questions:**  All participants questions and queries should be logged here. 

**Evidence:**

      Logs: Link to storage  
      Artifacts: (Screenshots, Images dmgs, etc)

**Action items:** Keep track of all ongoing action items. We have noticed that day-by-day action items are easier than by subject or by team. 
 
**Date1** 
- Action item 1 - Owner 1
- Action item 2- Owner 2 
- Action item 3- Owner 3

**Date 2**
- Action item 1 - Owner 1
- Action item 2- Owner 2 
- Action item 3- Owner 2 

**Incident Categorization:** If there is a way you label incidents this would be a good spot to assign a label. DDOS, exfiltration, malware, crypto mining, misconfiguration to name a few. Extremely useful when you want to do a year in review of incidents or look at quarterly trending.    

**Incident Cost (Aspirational):** One of the things Ashley and I have been toying with on the side is figuring out cost of an incident in two ways 
- How much did the incident cost to handle?  (Responder time)
- How much did the incident save the company? ( Risk unrealized)  
More to come here. We have developed a few models we want to share as a follow-up post.

**Related Incidents:** In the age of ML it's only reasonable to build an incident knowledgement system. We often found while on call our peers would ping us and say “Hey I have dealt with a similar incident it was 1234”. While handling the incident or during the post-incident review we encourage teams to tag similar incidents. It will help minimize the mean time to resolve and the next person on call will thank you!

# 🎯 Executive Incident Summary 

> Summary

- What happened, what’s the business risk for the company?

> Risk Level: 'Critical' 'High' 'Med'

> Status: 'Investigating' 'Mitigating' 'Stable' 'Closed'

> Actions 

 - What steps were taken to contain or resolve?

> Next Steps 

 - What steps are pending, what’s outstanding
   
> Update Frequency

  - When will be the next update? 
If the incident is closed or resolved, call out there will be no more updates. 
