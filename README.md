# Auto-Ticket Classification Using Flow Designer

## Project Overview
This repository contains the complete phase-wise documentation for a ServiceNow Administrator project that uses Flow Designer to automatically classify Incident tickets.

## Project Flow
Incident Created/Updated → Flow Designer Trigger → Read Ticket Details → Decision Logic → Classification → Update Incident

## Classification Model
The documentation uses a configurable rule-based classification approach. Example classifications are Hardware, Software, Network, Access, Email and Other/Manual Review. Exact conditions should be aligned with the team's ServiceNow instance before submission.

## Repository Structure
```text
auto-ticket-classification-using-flow-designer/
├── README.md
├── 01-Brainstorming-and-Ideation/
├── 02-Requirement-Analysis/
├── 03-Project-Design/
│   ├── Workflow.png
│   └── UI-Design.png
├── 04-Project-Planning/
├── 05-Project-Development/
│   ├── Flow-Designer/
│   └── Screenshots/
├── 06-Project-Testing/
├── 07-Project-Documentation/
├── 08-Project-Demonstration/
│   ├── Demo-Video-Link.txt
│   └── Demo-Screenshots/
└── assets/
```

Each numbered phase contains both `.docx` and `.pdf` versions.

## Team
- M. Sivakumar — Team Leader
- M. Subin — Member
- G. Prince Daniel — Member
- M. Kishor — Member
- J. Suthan — Member

## Important Before Submission
Replace placeholders with the actual Flow Designer name, trigger, conditions, field names, actions, execution results and screenshots from the team's ServiceNow instance. The documentation deliberately avoids claiming configuration values that were not supplied.
