Javian Mack
# Project 4 — Group 6 Meeting 1 Record
**Project:** CampusConnect — Architecture (Sprint 4)
**Recorder:** Javian Mack
**Date and time:** [Confirm actual meeting date/time]
**Location/platform:** [Confirm]
**Attendance:** [Record actual attendees]
**Record type:** Prepared discussion notes and agenda; actual meeting not verified

## Meeting 1 — Architecture and cloud-based software
### Prepared discussion notes
1. Software architecture describes the major parts of an application and how they communicate. Three common architecture patterns for comparison are layered (three-tier), client-server, and microservices.
2. Proposed CampusConnect architecture: browser-based React/TypeScript frontend, Node.js/Express API backend, and shared PostgreSQL database. This design suits the three agreed feature packages.
3. Cloud-based software is accessed over the Internet and hosted on remote infrastructure. Docker packages applications with dependencies as images; a container runs an image, and the Docker daemon manages containers and images.
4. Suggested deployment: frontend and backend in separate Docker containers, persistent PostgreSQL as a managed cloud service or a separate development container.

### Product Backlog Items
| PBI | Status | Sprint | Estimate | Assigned | Reviewer |
| --- | --- | --- | --- | --- | --- |
| Cloud architecture and container description | Drafted, pending review | 4 | 1 day | Javian Mack | Demetric Noble |
| Event Listings component and events table | Drafted, pending review | 4 | 2 days | Javian Mack | Justine Williams |
| Academic Resources component and resources table | Proposed | 4 | 2 days | Demetric Noble | Javian Mack |
| Notification component and notifications table | Proposed | 4 | 2 days | Justine Williams | Demetric Noble |
| Integration and schema review | Proposed | 4 | 1 day | All members | All members |
| Three meeting records and repository submission | In progress | 4 | 3 meetings | All members | All members |

### Assigned follow-up actions (proposed, not yet approved)
- Javian: document frontend/backend containers, Event Listings component, and events database table.
- Demetric: document Academic Resources component and academic_resources table.
- Justine: document Notifications component and notifications table.

### Actual meeting details — complete after the meeting
- **What members actually discussed:** [Enter discussion summary]
- **Progress reported by Javian:** [Enter]
- **Progress reported by Demetric:** [Enter]
- **Progress reported by Justine:** [Enter]
- **Decisions approved by those present:** [Enter]
- **Blockers:** [Enter]
- **Next meeting date/time:** [Enter]

**Verification note:** Content above is a prepared outline based on existing CampusConnect documentation. It is not evidence the team met or agreed to the proposed actions.