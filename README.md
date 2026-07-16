# Private Cloud Modernization TPM Portfolio

[**Open the live demo**](https://danvzla.github.io/private-cloud-modernization-tpm/)

## Portfolio Overview

This interactive portfolio was created to showcase Senior Technical Program Management capabilities to recruiters, hiring managers, and interview teams.

It demonstrates how I would structure, govern, communicate, and execute complex private cloud modernization programs. The portfolio connects executive objectives with integrated planning, Jira-inspired delivery, risk and dependency management, stakeholder reporting, quality controls, operational readiness, benefits realization, and formal closure.

## TPM Capabilities Demonstrated

- Program discovery, scoping, and scenario assessment
- Executive health reporting and decision support
- Integrated schedules, milestones, dependencies, and resource planning
- Jira-inspired initiatives, epics, stories, tasks, backlogs, and sprint boards
- RAID, RACI, change control, decision logs, and governance cadences
- Daily, weekly, executive, CAB, and maintenance-window communications
- Quality gates, acceptance criteria, rollback readiness, and hypercare
- Benefits realization, lessons learned, and program closure
- Executive and detailed views tailored to different stakeholder audiences
- Exportable executive reports, daily call briefs, weekly updates, RAID logs, milestone plans, and Jira backlogs

## Portfolio Structure

The portfolio includes seven illustrative private cloud modernization scenarios:

- Path A: Existing private cloud platform modernization
- Path B1: Standalone infrastructure moving to a new private cloud fleet
- Path B2: Standalone infrastructure joining an existing private cloud fleet
- Path C: Multi-stage infrastructure modernization
- Path D: Legacy platform transformation with significant technical debt
- Path E: Adjacent-release lifecycle upgrade
- Path F: Green Field private cloud deployment

Each scenario includes:

1. **Dashboard**  
   Executive health, active sprint board, schedule, effort assumptions, risks, milestones, and decisions required.

2. **Plan**  
   Timeline, milestones, resource capacity, assumptions, dependencies, and external constraints.

3. **Delivery**  
   Business outcomes, initiatives, epics, stories, tasks, sprint goals, backlogs, Jira boards, and Definition of Done.

4. **Governance**  
   RAID, RACI, decisions, change requests, communications, vendor dependencies, and escalation controls.

5. **Closure**  
   Quality gates, acceptance, operational handoff, hypercare, benefits realization, lessons learned, and formal closure.

## Important Notice

This is an independent personal portfolio created solely to demonstrate Technical Program Management capabilities.

It uses illustrative, non-client data created solely for this portfolio. No client, customer, confidential, proprietary, or restricted information is included.

Product names are used only to provide illustrative technology context. All scenarios, sequences, schedules, effort assumptions, risks, work items, forecasts, and status indicators are examples only.

They are not official vendor guidance, deployment instructions, approved estimates, customer commitments, or representations of completed client engagements.

This portfolio is not affiliated with, endorsed by, or approved by Broadcom or VMware. Any real implementation must be validated against current vendor documentation, compatibility requirements, release guidance, and customer-specific conditions.

## Technology

- HTML
- CSS
- JavaScript
- GitHub Pages

The website is intentionally self-contained and has no external application dependencies.

## Run Locally

```bash
git clone https://github.com/danvzla/private-cloud-modernization-tpm.git
cd private-cloud-modernization-tpm
open index.html
```

## About

Created by **Daniel Mazzini**, Principal Solutions Architect and Senior Technical Program Manager.

[SolTelCo](https://www.soltelco.com/)


## v4 focused rebuild

- Fixed the Discovery-page mobile overflow using CSS Grid containment and responsive table scrolling.
- Reconciled the Open Risks metric with the visible RAID register.
- Expanded Path A governance to eight risks, three assumptions, two issues, four dependencies, five decisions, and a detailed technical RACI.
- Added role-specific Path A ownership including VCF Architect, SDDC Manager Lead, vSphere Lead, NSX Lead, vSAN / Storage Lead, Change Manager, and Operations Owner.
- Added distinct program positions, health states, current sprints, and epic progress profiles for all seven scenarios.
- Preserved the Dashboard / Plan / Delivery / Governance / Closure structure and all export features.


## v5 Plan tab fix

The Plan tab was failing because the timeline renderer referenced by `plan(k)` was missing from the rebuilt JavaScript. The `timelineHtml(k)` function has been restored and the script passes a JavaScript syntax check.
