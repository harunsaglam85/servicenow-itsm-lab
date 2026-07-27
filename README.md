# servicenow-itsm-lab
ServiceNow ITSM incident management demonstration - developer instance
# ServiceNow ITSM Lab

Hands-on incident management demonstration using a ServiceNow Personal Developer Instance (Zurich release).

## Overview

ServiceNow is the industry-standard IT Service Management (ITSM) platform used by the majority of enterprise IT departments for ticketing, incident management, and service delivery. This project demonstrates a complete incident lifecycle from creation through resolution, showing practical familiarity with the tool most commonly requested in IT support and help desk job postings.

## Environment

| Component | Details |
|-----------|---------|
| Platform | ServiceNow Personal Developer Instance |
| Release | Zurich |
| Role | Admin |
| Instance | dev210377.service-now.com |

## What I Demonstrated

- Provisioned a personal ServiceNow developer instance
- Created a new incident ticket with full categorization (Category, Impact, Urgency, Priority)
- Assigned caller information and detailed problem description
- Added work notes documenting the troubleshooting process
- Resolved the incident with resolution code and resolution notes
- Reviewed the complete audit trail showing every field change and timestamp

## Walkthrough

### 1. Instance Provisioned
![Instance Dashboard](screenshots/01-instance-provisioned.png)

Personal developer instance successfully provisioned and running on the Zurich release, confirmed online with admin access.

### 2. Incident Created
![Incident Created](screenshots/02-incident-created.png)

Created a new incident ticket (INC0010002) reporting a VPN connectivity issue. Filled out caller information, category, impact, urgency, and a detailed description of the reported problem — mirroring how a real help desk agent documents an incoming issue.

### 3. Incident in Queue
![Incident List](screenshots/03-incident-list.png)

The new incident appears in the active incident queue, ready for assignment and triage — the same view a help desk team uses to manage their workload.

### 4. Resolution and Audit Trail
![Resolution Info](screenshots/04-resolution-info.png)

Documented the troubleshooting steps taken (verified VPN client version, reset credentials, confirmed successful authentication) as work notes, then resolved the ticket with a resolution code and resolution notes. The activity timeline shows a complete audit trail — every field change and note timestamped automatically, demonstrating the accountability and documentation standards required in enterprise IT support.

## Skills Demonstrated

- ServiceNow incident management workflow
- ITSM ticket lifecycle: creation, categorization, prioritization, resolution
- Technical documentation and work note best practices
- Understanding of incident state transitions and resolution codes
- Familiarity with enterprise ticketing tools referenced across IT support job postings
