# Case Study — Internal Intranet Operations Platform  
## Improving Visibility, Monitoring and Operational Response

## Overview
- **Project type:** Internal operations platform (Intranet)
- **Environment:** Production (real-world usage)
- **Role:** Sole developer
- **Focus:** Operations, monitoring, security, and system visibility

This case study describes the design and implementation of an internal intranet platform developed to centralize operational information, improve monitoring visibility, and accelerate incident response in a production environment.

## Context
Daily IT operations relied on multiple disconnected tools, manual checks, scripts, and informal communication channels.  
This fragmentation made it harder to quickly identify issues, track incidents, and act efficiently during operational problems.
The need was clear: **a single internal platform to centralize visibility, monitoring, and operational workflows**.

## Problem Statement
Before the platform:
- Monitoring data was spread across different tools
- Incident tracking was manual and inconsistent
- Asset information lacked a centralized view
- Operational response depended heavily on individual knowledge
- Visibility during incidents was limited and reactive

This increased response time and reduced clarity during critical situations.

## Solution
An internal intranet platform was designed and implemented to act as a **single operational control panel**, integrating monitoring, asset visibility, and internal processes.
The platform evolved directly from real operational demands observed during daily work.

## Core Features
### User Management & Access Control
- Authenticated user access
- Individual user accounts
- Action traceability and accountability

### Integrated Ticketing System
- Users can open support tickets directly in the platform
- Tickets classified by issue type (network, camera, infrastructure)
- Status tracking and resolution workflow
- Automatic identification of who opened and handled each ticket

### Monitoring & Observability
- Integration with **PRTG** and **Zabbix**
- Real-time visualization of monitored devices
- Simplified dashboards for non-technical users
- Faster identification of network and infrastructure issues

### Logs & Audit Trail
- Centralized logging of user actions
- Increased transparency and operational security
- Support for incident investigation and post-mortem analysis

### Asset Mapping
- Interactive map with manually defined coordinates
- Visual representation of strategic points and assets
- Improved operational awareness and logistics

### User Interface & Usability
- Clean and intuitive interface
- Reorganized layout focused on daily operational needs
- Reduced cognitive load during incident response

## Technical Architecture
- **Backend:** Python (Flask)
- **Database:** MariaDB / SQLite (depending on context)
- **Frontend:** HTML, CSS, JavaScript
- **Monitoring:** PRTG, Zabbix
- **Authentication:** Login-based access control
- **Deployment:** Internal production environment

## Impact
After adoption in production:
- Operational issues became easier to visualize and understand
- Incident response time was reduced
- Monitoring data became accessible to a wider audience
- Manual checks were significantly reduced
- Decision-making during incidents became faster and clearer

The platform shifted operations from a reactive model to a **more proactive and structured approach**.

## Security & Operational Considerations
- Access restricted to authenticated users
- User actions logged for traceability
- Sensitive operational information handled internally
- Screenshots and data shared publicly have sensitive details intentionally removed

## Key Learnings
This project reinforced practical knowledge in:
- Building systems driven by real operational needs
- Observability and monitoring concepts
- Security-conscious internal tooling
- Full ownership of a production system
- Translating infrastructure problems into usable software solutions

## Ethical and Disclosure Notice
This repository documents an internal system architecture and operational approach.

No sensitive data, credentials, internal addresses, or proprietary information are disclosed.  
All examples and images have been sanitized to protect the organization.

## Author
**Luiz Maia**  
Infrastructure & Operations Engineer  
Focus on monitoring, internal systems, automation, and reliability
