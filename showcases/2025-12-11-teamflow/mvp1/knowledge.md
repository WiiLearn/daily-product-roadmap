# Knowledge Document: Teamflow Mvp1

> **Generated**: 2025-12-11 11:34:30  
> **Version**: 1.0.0  
> ---
mas:
  version: "1.0.0"
  diagrams:
    - business_process
    - decision_tree
    - swimlane
    - user_journey
    - value_stream
  actors:
    - "Admin"
  screens:
    - "Platform"
    - "Project tracking dashboard"
    - "Under Review"
    - "dashboard"
  entities:
    - "Approval Required?"
    - "Approved"
    - "Async"
    - "Async video messaging system"
    - "CRITICAL"
    - "Complete"
    - "Core"
    - "Core Platform Features"
    - "Developer"
    - "Features"
    - "HIGH"
    - "LOW"
    - "MEDIUM"
    - "PAIN"
    - "POINT"
    - "Product Owner"
    - "Project"
    - "Rejected"
    - "Standard threshold"
    - "Support Agent"
---

---

## Overview

This document captures the domain knowledge extracted from MAS artifacts for **Teamflow Mvp1**.

Core Platform Features: Essential functionality and user management. I want to build a remote team collaboration platform called TeamFlow that combines async video messaging, AI-powered meeting summaries, project tracking, and virtual office spaces to help distributed 

---

## RACI Matrix

Responsibility assignment matrix for process steps.

| Process Step | Admin | Approval Required? | Approved | Async video messaging system | CRITICAL | Core Platform Features | Developer | HIGH | LOW | MEDIUM | Product Owner | Project tracking dashboard | Rejected | Standard threshold | Support Agent | System | Team activity feed | Under Review | User | User task assignment tool | Verification Complete? | Virtual office space interface ||--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|| Admin Async video messaging system | R/A | - | - | - | - | - | I | - | - | - | I | - | - | - | I | - | - | - | I | - | - | - || Developer Project tracking dashboard | C | - | - | - | - | - | R/A | - | - | - | I | - | - | - | I | - | - | - | I | - | - | - || Product Owner Virtual office space interface | I | - | - | - | - | - | C | - | - | - | R/A | - | - | - | I | - | - | - | I | - | - | - || Support Agent User task assignment tool | I | - | - | - | - | - | I | - | - | - | C | - | - | - | R/A | - | - | - | I | - | - | - || User Team activity feed | I | - | - | - | - | - | I | - | - | - | I | - | - | - | C | - | - | - | R/A | - | - | - || action | - | - | - | - | I | R/A | - | I | I | I | - | - | - | I | - | - | - | - | - | - | - | - || flow: | - | - | - | I | - | - | - | - | - | - | - | I | - | - | - | R/A | I | - | I | I | - | I || Async Video Messaging System | - | I | I | I | - | - | - | - | - | - | - | I | I | - | - | R/A | I | I | I | I | I | I || Project Tracking Dashboard | - | I | I | I | - | - | - | - | - | - | - | R/A | I | - | - | C | I | I | I | I | I | I || Virtual Office Space Interface | - | I | I | I | - | - | - | - | - | - | - | C | I | - | - | I | I | I | I | I | I | R/A || User Task Assignment Tool | - | I | I | I | - | - | - | - | - | - | - | I | I | - | - | I | I | I | R/A | I | I | C || Team Activity Feed | - | I | I | I | - | - | - | - | - | - | - | I | I | - | - | I | R/A | I | C | I | I | I |
**Legend:**
- **R** = Responsible (does the work)
- **A** = Accountable (owns the decision)
- **C** = Consulted (provides input)
- **I** = Informed (kept updated)


---

## Business Rules

Automated decision logic extracted from decision tree diagrams.
### BR-001: Threshold Assessment

- **Condition**: `Is the feature request within the standard threshold?`
- **Action**: Route to Approve feature request: Low impact
- **Automation**: Manual
- **Priority**: P1
- **Source**: 1ad6fcf7-9fb5-40e8-818b-58b9f4fbe740
### BR-002: Business Rule Evaluation

- **Condition**: `Is the impact LOW?`
- **Action**: Route to Approve feature request: Low impact
- **Automation**: Manual
- **Priority**: P2
- **Source**: 1ad6fcf7-9fb5-40e8-818b-58b9f4fbe740
### BR-003: Business Rule Evaluation

- **Condition**: `Is the impact MEDIUM?`
- **Action**: Route to Approve feature request: Low impact
- **Automation**: Manual
- **Priority**: P2
- **Source**: 1ad6fcf7-9fb5-40e8-818b-58b9f4fbe740
### BR-004: Business Rule Evaluation

- **Condition**: `Is the impact HIGH?`
- **Action**: Route to Approve feature request: Low impact
- **Automation**: Manual
- **Priority**: P2
- **Source**: 1ad6fcf7-9fb5-40e8-818b-58b9f4fbe740
### BR-005: Business Rule Evaluation

- **Condition**: `Is the impact CRITICAL?`
- **Action**: Route to Approve feature request: Low impact
- **Automation**: Manual
- **Priority**: P2
- **Source**: 1ad6fcf7-9fb5-40e8-818b-58b9f4fbe740
---

## Non-Functional Requirements

### Performance Requirements

| ID | Requirement | Source | Verification | Priority |
|----|-------------|--------|--------------|----------|| NFR-PERF-1 | System SHALL complete task within 4 hours | 1184d8e4-8566-453a-b09a-f5f18507c248:slas | Measure response time for task operation | P1 || NFR-PERF-2 | System SHALL complete task within 6 hours | 1184d8e4-8566-453a-b09a-f5f18507c248:slas | Measure response time for task operation | P1 || NFR-PERF-3 | System SHALL complete task within 8 hours | 1184d8e4-8566-453a-b09a-f5f18507c248:slas | Measure response time for task operation | P1 |
### Accessibility Requirements

| ID | Requirement | Source | Verification | Priority |
|----|-------------|--------|--------------|----------|| NFR-A11Y-1 | System SHALL comply with WCAG compliance requirements | 6e9e497e-54ee-48e7-9d52-9528bac55a71:accessibility_needs | WCAG audit for WCAG compliance | P0 || NFR-A11Y-2 | System SHALL comply with screen reader support requirements | 6e9e497e-54ee-48e7-9d52-9528bac55a71:accessibility_needs | WCAG audit for screen reader support | P0 || NFR-A11Y-3 | System SHALL comply with keyboard navigation requirements | 6e9e497e-54ee-48e7-9d52-9528bac55a71:accessibility_needs | WCAG audit for keyboard navigation | P0 |
### Automation Requirements

| ID | Requirement | Source | Verification | Priority |
|----|-------------|--------|--------------|----------|| NFR-AUTO-1 | video messaging SHALL be Automated | 1184d8e4-8566-453a-b09a-f5f18507c248:automation_hints | Verify automated implementation for video messaging | P1 || NFR-AUTO-2 | support SHALL be Manual | 1184d8e4-8566-453a-b09a-f5f18507c248:automation_hints | Verify manual implementation for support | P2 || NFR-AUTO-3 | video messaging SHALL be Automated | bf1a200b-f20e-4619-b3cc-e7925316f393:automation_hints | Verify automated implementation for video messaging | P1 || NFR-AUTO-4 | manual SHALL be Manual | bf1a200b-f20e-4619-b3cc-e7925316f393:automation_hints | Verify manual implementation for manual | P2 || NFR-AUTO-5 | automated SHALL be Automated | 65bd6aee-8acb-4435-b153-02ac6ace0524:automation_hints | Verify automated implementation for automated | P1 || NFR-AUTO-6 | features workflow SHALL be Automated | 65bd6aee-8acb-4435-b153-02ac6ace0524:automation_hints | Verify automated implementation for features workflow | P1 || NFR-AUTO-7 | video messaging SHALL be Automated | 65bd6aee-8acb-4435-b153-02ac6ace0524:automation_hints | Verify automated implementation for video messaging | P1 || NFR-AUTO-8 | manual SHALL be Manual | 65bd6aee-8acb-4435-b153-02ac6ace0524:automation_hints | Verify manual implementation for manual | P2 |

---

## Quality Metrics

| Metric | Value | Source |
|--------|-------|--------|
| Diagrams Analyzed | 5 | MAS Compiler |
| RACI Entries | 12 | business_analysis |
| Business Rules | 5 | decision_tree |
| NFRs Generated | 14 | ux/business_analysis |
| EARS Requirements | 69 | metadata mapping |

---

*Generated by MAS Compiler Knowledge Spec Generator*