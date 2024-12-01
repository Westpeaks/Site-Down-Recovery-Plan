# Site Down Recovery Plan

The purpose of this doc is to track all critical operations, personnel contact information, and key procedures to perform in the event of a complete site disruption.

**Major Goals of the Site Down Recovery Plan**
---

- To minimize the time to remediate in the event of a site going down.
- To limit the extent of disruption.
- To provide quick and stable restoration of service.
- To ensure that clients are clearly and properly communicated with in the event of an interruption.
- To ensure that the proper internal resources are communicated with in the event of an interruption.
- To assess what preventative measures can be taken in the future so further disruptions do not occur.

**Key Personnel and Contact Information**
--- 

The following team members will be the key points of contact for a remediation strategy. 
 
| Name | Email | Role |
|----------|----------|----------|
| Wes Peak | wesley@hooli.com | Technical Suport Manager |
| Richard Hendricks | richard@hooli.com | Software Engineering Manager | 
| Gavin Belson | gavin@hooli.com | CEO (communication with CEO will need to be discussed with prior managers)|

**Identify the Scope**
---

1. What apps are affected?
2. What feeds are affected?
3. What hardware was potentially affected? This must be thoroughly documented as well as the plan to remediate the affected hardware. It is important to obtain this documentation for the site reliability engineers and document this in the support ticket notes.
4. Any potential loss of data must also be noted and documented within the ticket. New client work tickets to recover the data will need to be created and linked to the support ticket.
5. Once this is determined, an initial response must be sent to the client to inform them that we are currently working to resolve the issue. All three key personnel should be included in the initial email chain. Key points of contact on the account should also be identified and included on the email chain.

**Identify Root Cause**
---

1. Once the root cause is identified, notify the key points of contact and let them know that we are working on a resolution.
2. Communicating additional information to the client must be discussed with the key personnel and agreed upon before being included in communication regarding the root cause.
3. Notify the key personnel once communication has been sent.

**Resolve Issue**
---

1. If issue is unresolved by end of day (EOD), then a next day strategy meeting needs to be to be scheduled. This will involve the key personnel listed above.
2. During the meeting, a plan for resolution for the next day must be formulated. Communication for the next day will also need to be established and discussed as well as what will be reported to the client before the close of business.
3. Once a resolution is achieved, it must be tested before notifying the customer that the site is back up. A full site assessment will need be performed. This will include checking all applications are running and functioning as expected. You will also need to validate that the appropriate services are running on the site servers.
4. Once this has been accomplished, the customer will need to be notified for validation that the issue is resolved. If the customer prompts about future mitigation, communication regarding this should be planned and handled through your direct report who will then escalate as necessary.
5. The entirety of down time must be documented in the support ticket under the field _Time Tracked_. 

**Implement Remediation Plan for Future Events**
---

If the issue is large enough, it may require a future remediation plan meeting with the key personnel. Otherwise, schedule one with your direct report. Discuss and document the following: 
1. Is this issue common?
2. Could this issue occur at other sites?
3. Identify what can be done to prevent this from occurring at other sites or reoccurring.
4. Develop a strategy to implement prevention measures.
5. CLW tickets and/or ENG tickets must then be created to execute plan.
6. Schedule a follow up to track progress of remediation plan. 

