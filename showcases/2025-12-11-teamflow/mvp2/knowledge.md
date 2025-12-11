# Knowledge Document: Teamflow Mvp2

> **Generated**: 2025-12-11 11:34:58  
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
    - "MVP1 project dashboard"
    - "Under Review"
  entities:
    - "AI-powered meeting summary generation"
    - "Advanced Analytics"
    - "Approval Required?"
    - "Approved"
    - "Automated project status updates"
    - "BUILDING"
    - "CRITICAL"
    - "Developer"
    - "HIGH"
    - "Intelligent insights into team performance metrics"
    - "LOW"
    - "MEDIUM"
    - "MVP1"
    - "MVP1 async video messaging"
    - "MVP1 project tracking"
    - "MVP1 task data"
    - "MVP1 user interactions"
    - "PAIN"
    - "POINT"
    - "Product Owner"
---

---

## Overview

This document captures the domain knowledge extracted from MAS artifacts for **Teamflow Mvp2**.

Advanced Analytics: AI-powered insights and automation. I want to build a remote team collaboration platform called TeamFlow that combines async video messaging, AI-powered meeting summaries, project tracking, and virtual office spaces to help distributed 

---

## RACI Matrix

Responsibility assignment matrix for process steps.

| Process Step | AI-powered meeting summary generation | Admin | Advanced Analytics | Approval Required? | Approved | Automated project status updates | CRITICAL | Developer | HIGH | Intelligent insights into team performance metrics | LOW | MEDIUM | MVP1 async video messaging | MVP1 project dashboard | MVP1 project tracking | MVP1 task data | MVP1 user interactions | Product Owner | Recommendation engine for task assignments | Rejected | Sentiment analysis on video messages | Standard threshold | Support Agent | Under Review | User | Verification Complete? | action | condition | into ||--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|| Admin AI-powered meeting summary generation USING MVP1 async video messaging | - | R/A | - | - | - | - | - | I | - | - | - | - | - | - | - | - | - | I | - | - | - | - | I | - | I | - | - | - | - || Developer Sentiment analysis on video messages USING MVP1 user interactions | - | C | - | - | - | - | - | R/A | - | - | - | - | - | - | - | - | - | I | - | - | - | - | I | - | I | - | - | - | - || Product Owner Automated project status updates BUILDING ON MVP1 project tracking | - | I | - | - | - | - | - | C | - | - | - | - | - | - | - | - | - | R/A | - | - | - | - | I | - | I | - | - | - | - || Support Agent Recommendation engine for task assignments USING MVP1 task data | - | I | - | - | - | - | - | I | - | - | - | - | - | - | - | - | - | C | - | - | - | - | R/A | - | I | - | - | - | - || User Intelligent insights into team performance metrics USING MVP1 project dashboard | - | I | - | - | - | - | - | I | - | - | - | - | - | - | - | - | - | I | - | - | - | - | C | - | R/A | - | - | - | - || action | - | - | I | - | - | - | I | - | I | - | I | I | - | - | - | - | - | - | - | - | - | I | - | - | - | - | R/A | I | - || flow: | I | - | - | - | - | I | - | - | - | I | - | - | I | I | I | I | I | - | I | - | I | - | - | - | I | - | - | - | R/A || AI-powered meeting summary generation | R/A | - | - | I | I | I | - | - | - | I | - | - | - | - | - | - | - | - | I | I | I | - | - | I | I | I | - | - | I || Sentiment analysis on video messages | C | - | - | I | I | I | - | - | - | I | - | - | - | - | - | - | - | - | I | I | R/A | - | - | I | I | I | - | - | I || Automated project status updates | I | - | - | I | I | R/A | - | - | - | I | - | - | - | - | - | - | - | - | I | I | C | - | - | I | I | I | - | - | I || Recommendation engine for task assignments | I | - | - | I | I | C | - | - | - | I | - | - | - | - | - | - | - | - | R/A | I | I | - | - | I | I | I | - | - | I || Intelligent insights into team performance metrics | I | - | - | I | I | I | - | - | - | I | - | - | - | - | - | - | - | - | C | I | I | - | - | I | I | I | - | - | R/A |
**Legend:**
- **R** = Responsible (does the work)
- **A** = Accountable (owns the decision)
- **C** = Consulted (provides input)
- **I** = Informed (kept updated)


---

## Business Rules

Automated decision logic extracted from decision tree diagrams.
### BR-001: Business Rule Evaluation

- **Condition**: `Is condition met?`
- **Action**: Route to Action denied: Condition not met
- **Automation**: Manual
- **Priority**: P2
- **Source**: 2248f1f7-4a66-4d31-be34-f39d707a8dbc
### BR-002: Threshold Assessment

- **Condition**: `Is the threshold LOW?`
- **Action**: Route to Action denied: Condition not met
- **Automation**: Manual
- **Priority**: P1
- **Source**: 2248f1f7-4a66-4d31-be34-f39d707a8dbc
### BR-003: Threshold Assessment

- **Condition**: `Is the threshold MEDIUM?`
- **Action**: Route to Action denied: Condition not met
- **Automation**: Manual
- **Priority**: P1
- **Source**: 2248f1f7-4a66-4d31-be34-f39d707a8dbc
### BR-004: Threshold Assessment

- **Condition**: `Is the threshold HIGH?`
- **Action**: Route to Action denied: Condition not met
- **Automation**: Manual
- **Priority**: P1
- **Source**: 2248f1f7-4a66-4d31-be34-f39d707a8dbc
---

## Non-Functional Requirements

### Performance Requirements

| ID | Requirement | Source | Verification | Priority |
|----|-------------|--------|--------------|----------|| NFR-PERF-1 | System SHALL complete task within 4 hours | c6a63a75-17ca-4340-b5e3-6244f326a953:slas | Measure response time for task operation | P1 || NFR-PERF-2 | System SHALL complete task within 6 hours | c6a63a75-17ca-4340-b5e3-6244f326a953:slas | Measure response time for task operation | P1 || NFR-PERF-3 | System SHALL complete task within 8 hours | c6a63a75-17ca-4340-b5e3-6244f326a953:slas | Measure response time for task operation | P1 |
### Accessibility Requirements

| ID | Requirement | Source | Verification | Priority |
|----|-------------|--------|--------------|----------|| NFR-A11Y-1 | System SHALL comply with WCAG 2.1 compliance requirements | 75f3bbdb-c8a1-4a16-a79f-4dbb3dd146b3:accessibility_needs | WCAG audit for WCAG 2.1 compliance | P0 || NFR-A11Y-2 | System SHALL comply with Screen reader support requirements | 75f3bbdb-c8a1-4a16-a79f-4dbb3dd146b3:accessibility_needs | WCAG audit for Screen reader support | P0 || NFR-A11Y-3 | System SHALL comply with Keyboard navigation requirements | 75f3bbdb-c8a1-4a16-a79f-4dbb3dd146b3:accessibility_needs | WCAG audit for Keyboard navigation | P0 |
### Automation Requirements

| ID | Requirement | Source | Verification | Priority |
|----|-------------|--------|--------------|----------|| NFR-AUTO-1 | product owner SHALL be Automated | c6a63a75-17ca-4340-b5e3-6244f326a953:automation_hints | Verify automated implementation for product owner | P1 || NFR-AUTO-2 | support SHALL be Manual | c6a63a75-17ca-4340-b5e3-6244f326a953:automation_hints | Verify manual implementation for support | P2 || NFR-AUTO-3 | automated SHALL be Automated | 6ed72ed3-7cf6-4cb5-a935-b76c14a3fe9e:automation_hints | Verify automated implementation for automated | P1 || NFR-AUTO-4 | auto SHALL be Automated | 6ed72ed3-7cf6-4cb5-a935-b76c14a3fe9e:automation_hints | Verify automated implementation for auto | P1 || NFR-AUTO-5 | manual SHALL be Manual | 6ed72ed3-7cf6-4cb5-a935-b76c14a3fe9e:automation_hints | Verify manual implementation for manual | P2 || NFR-AUTO-6 | automated SHALL be Automated | e07c75b3-4496-4788-ba36-fc7fd08b174f:automation_hints | Verify automated implementation for automated | P1 || NFR-AUTO-7 | analytics workflow SHALL be Automated | e07c75b3-4496-4788-ba36-fc7fd08b174f:automation_hints | Verify automated implementation for analytics workflow | P1 || NFR-AUTO-8 | manual SHALL be Manual | e07c75b3-4496-4788-ba36-fc7fd08b174f:automation_hints | Verify manual implementation for manual | P2 |

---

## Quality Metrics

| Metric | Value | Source |
|--------|-------|--------|
| Diagrams Analyzed | 5 | MAS Compiler |
| RACI Entries | 12 | business_analysis |
| Business Rules | 4 | decision_tree |
| NFRs Generated | 14 | ux/business_analysis |
| EARS Requirements | 75 | metadata mapping |

---

*Generated by MAS Compiler Knowledge Spec Generator*