# DMV Music Alliance — Volunteer Onboarding System

## Table of Contents

- [Project Overview](#project-overview)
- [Tools](#tools)
- [Organizational Context](#organizational-context)
- [Problem Diagnosis](#problem-diagnosis)
- [Design Goals and Constraints](#design-goals-and-constraints)
- [Workflow Redesign](#workflow-redesign)
- [Data Model and Workflow Logic](#data-model-and-workflow-logic)
- [Projected Impact](#projected-impact)
- [Implementation Status](implementation-status)
- [Key Learnings](#key-learnings)
- [Why This Case Study Matters](#why-this-case-study-matters)


## Project Overview
DMV Music Alliance relied on an informal, founder-managed onboarding process for new volunteers. The lack of standardized workflows and centralized data created delays, confusion, and unnecessary manual coordination. I redesigned the onboarding process as a structured, system-driven workflow, consolidating data capture, scheduling, task management, and follow-ups into a single operational pipeline.

The proposed system reduced founder bottlenecks, improved visibility into onboarding status, and created a repeatable onboarding experience designed to scale with minimal overhead. While the system was fully designed and documented, full implementation was ultimately paused due to leadership indecision rather than technical constraints.


## Tools
The following tools and technologies were used in this project:

- **ClickUp:**	Central workflow engine and system of record
- **DMV Website:**	Single intake point for volunteer applications
- **Calendly:**	Embedded interview scheduling
- **Gmail / Calendar:**	Consolidated communication and visibility


## Organizational Context
- Volunteer-based nonprofit music organization
- Small, cross-functional team
- Remote / hybrid collaboration
- No dedicated operations or technical owner

Onboarding responsibilities were distributed informally across leadership, with most coordination handled manually by the founder.


## Problem Diagnosis
### Observed Issues

- Onboarding knowledge lived in emails and individuals’ heads rather than systems
- Founder served as the primary coordination point, creating a bottleneck
- Volunteer data entered multiple times across different tools
- No clear onboarding status or ownership at each step
- Volunteers often unclear on what to do after interviews

### Operational Risks
- Delayed volunteer activation
- Inconsistent onboarding experiences
- High cognitive load on leadership
- Poor scalability as volunteer volume increased
### Core problem:
The organization lacked a single source of truth and a defined onboarding workflow.

## Design Goals and Constraints
### Design Goals
- Centralize volunteer data into one system of record
- Make onboarding status explicit and visible
- Reduce manual coordination and follow-ups
- Create a repeatable, low-maintenance process

### Constraints
- Non-technical stakeholders
- Limited tolerance for process change
- Reliance on existing tools (Google Workspace)

## Workflow Redesign
### Original Workflow (Before)
#### Characteristics
- Founder-managed, email-driven coordination
- Multiple unlinked data sources
- Implicit onboarding steps
- No structured follow-up or progress tracking

#### Workflow Breakdown
1. Volunteer applies via external listing (e.g., Idealist)
2. Volunteer signs up again on DMV website
3. Volunteer separately schedules interview via Calendly
4. Founder receives multiple emails and manually matches records
5. Founder prepares for interview by cross-referencing emails
6. Volunteer waits for ClickUp invite with no status updates
7. Founder manually assigns permissions and role information
8. Volunteer completes loosely defined training task
9. No follow-ups or check-ins

### Proposed Workflow (After)
#### Design Principle:
Minimize handoffs by consolidating data capture, scheduling, and communication into a single entry point.

### Phase 1: Centralized Sign-Up & Pre-Boarding
- Volunteer applies directly through the DMV Music Alliance website
- Application form captures all required onboarding data in one submission
- Calendly is embedded at the end of the sign-up flow, allowing immediate interview scheduling
- A single consolidated email is automatically sent containing:
  - Volunteer application details
  - Scheduled interview date and time
  - Clear next-step expectations
#### Impact:
Eliminates duplicate sign-ups and fragmented email threads while creating one unified volunteer record.

### Phase 2: Interview Preparation
- Founder receives one consolidated notification per volunteer
- Pre-interview checklist auto-generated in ClickUp
- Volunteer role preferences and submitted information available in one place
#### Impact:
Reduces preparation time and cognitive load for leadership.

### Phase 3: Interview
- Interview conducted as usual
- Interview notes and decision logged directly in ClickUp
- Volunteer status updated immediately, triggering the next workflow phase
#### Impact:
Removes post-interview ambiguity and manual follow-ups.

### Phase 4: Workspace Setup
- Volunteer automatically added to ClickUp via onboarding template
- Role-specific permissions applied
- Orientation and training tasks pre-assigned with owners and deadlines
#### Impact:
Standardizes onboarding regardless of who conducts the interview.

### Phase 5: Training & Orientation
- Structured task checklist guides volunteers through:
  - ClickUp basics
  - Resource access
  - Initial role-specific tasks
- Task statuses provide real-time progress visibility
#### Impact:
Volunteers know exactly what to do and leadership can track onboarding at a glance.

### Phase 6: Follow-Up & Integration
- Automated reminders trigger check-ins after defined intervals
- Feedback captured for continuous improvement
- Volunteer marked “active” only after onboarding completion
#### Impact:
Reduces volunteer drop-off and accelerates time to productivity.


## Data Model and Workflow Logic
Each onboarding record captured standardized fields:
- Volunteer name
- Role / function
- Onboarding phase
- Task owner
- Status
- Key dates (application, interview, activation)

This enabled ClickUp to function as a single source of truth, replacing informal tracking across email and calendars.

## Projected Impact
| Metric                    | Before   | After (Projected)     |
| ------------------------- | -------- | --------------------- |
| Founder coordination load | High     | Significantly reduced |
| Onboarding clarity        | Low      | High                  |
| Manual follow-ups         | Frequent | Minimal               |
| Process scalability       | Poor     | Repeatable            |

## Implementation Status
The onboarding system was fully designed, documented, and reviewed with internal stakeholders. Full rollout was paused due to leadership indecision rather than technical or operational blockers.

This reflected a common constraint in volunteer-led organizations, where decision-making capacity can lag behind operational readiness.

## Key Learnings
- Operational clarity reduces friction more effectively than additional effort
- Automation is most impactful when paired with clear ownership and status definitions
- Organizational readiness is as critical as technical feasibility

## Why This Case Study Matters
This project demonstrates my ability to:
- Diagnose operational breakdowns
- Translate ambiguity into structured systems
- Design scalable workflows using existing tools
- Apply data operations principles in low-resource environments
- Balance ideal solutions with real organizational constraints
