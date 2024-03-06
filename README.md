<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution


After setting up osTicket and configuring your help desk, the next critical phase involves managing tickets throughout their lifecycle. This section provides insights into creating, triaging, and resolving common help desk tickets, alongside specifying Service Level Agreements (SLA) for each.

#### Common Help Desk Tickets and Their SLAs

1. **Sev-A (High Priority):**
   - **Example:** Entire mobile/online banking system is down.
   - **SLA:** 1 hour, 24/7 response time.
   - **Assigned To:** System Administrators (SysAdmins).

2. **Sev-B (Medium Priority):**
   - **Example 1:** Accounting department needs Adobe software upgrade, currently broken.
   - **SLA:** 4 hours, 24/7 response time.
   - **Example 2:** Marketing team cannot access the CRM, impacting campaign launches.
   - **SLA:** 4 hours, 24/7 response time.
   - **Assigned To:** Level II Support.

3. **Sev-B/C (Medium/Low Priority):**
   - **Example:** CFO’s laptop is running slow, potentially impacting financial operations.
   - **SLA:** 2 hours, business hours response time.
   - **Assigned To:** Level I Support for initial diagnosis, escalate to Level II if needed.

4. **Sev-C (Low Priority):**
   - **Example 1:** Employee requests installation of a new software for productivity enhancement.
   - **SLA:** 8 hours, business hours response time.
   - **Example 2:** Routine hardware check-up and maintenance for the HR department.
   - **SLA:** Next business day.
   - **Assigned To:** Level I Support.

#### Ticket Lifecycle Management

The lifecycle of a ticket typically involves the following stages:

1. **Ticket Creation:**
   - Users report an issue or request via the web interface, email, or phone. The ticket is logged in osTicket.

2. **Ticket Triage:**
   - The support team evaluates the ticket based on priority, SLA, and expertise required. The ticket is then assigned to the appropriate department or team.

3. **Ticket Assignment:**
   - Within the designated team, the ticket is assigned to an individual agent who has the skills and capacity to resolve the issue or fulfill the request.

4. **Working the Issue:**
   - The assigned agent works on the ticket, communicating with the user for additional information or to provide updates. Solutions may involve direct fixes, workarounds, or escalation to a higher level of support.

5. **Resolution and Closure:**
   - Once the issue is resolved, the ticket is marked as resolved. The user is notified of the resolution and asked to confirm that the solution is satisfactory.

6. **Feedback and Improvement:**
   - Users may provide feedback on their support experience. This feedback is valuable for continuous improvement of the help desk operations.

#### Best Practices for Ticket Management

- **Prioritize Tickets Based on Impact and Urgency:** Use the SLA guidelines to prioritize work and ensure timely responses.
- **Keep Communication Open:** Regular updates to the user about the status of their ticket can improve satisfaction and manage expectations.
- **Document Solutions:** Maintain a knowledge base of common issues and resolutions to speed up response times for future tickets.
- **Analyze Trends:** Regularly review ticket patterns to identify systemic issues or training opportunities.

By adhering to these guidelines and continuously refining your ticket lifecycle process, you can ensure your help desk operates efficiently and effectively, maintaining high levels of user satisfaction and operational excellence.

## IMPORTANT
When you are finsished with the lab, delete your Azure resources. This is crucial, as you will be charged credits for having resource groups. Best practice is to delete all resource groups and double check that they are deleted properly.

Thanks for following along this lab!
