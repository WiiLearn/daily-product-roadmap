# Knowledge Document: Wealthpilot Mvp1

> **Generated**: 2025-12-11 11:11:52  
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
    - "Customer"
  screens:
    - "Market trend analysis dashboard"
    - "Under Review"
  entities:
    - "Account Manager"
    - "Advisor"
    - "Analyst"
    - "Approval Required?"
    - "Approved"
    - "Automated performance tracking"
    - "CRITICAL"
    - "Complete"
    - "Compliance Officer"
    - "Core"
    - "Core Financial Management"
    - "Financial"
    - "Goal setting and management tool"
    - "HIGH"
    - "LOW"
    - "MEDIUM"
    - "Management"
    - "Market"
    - "PAIN"
    - "POINT"
---

---

## Overview

This document captures the domain knowledge extracted from MAS artifacts for **Wealthpilot Mvp1**.

Core Financial Management: Basic accounts, transactions, and reporting. I want to build a personal investment platform called WealthPilot that uses AI to analyze market trends, provides automated portfolio rebalancing, and offers personalized investment recommendations ba

---

## RACI Matrix

Responsibility assignment matrix for process steps.

| Process Step | Account Manager | Advisor | Analyst | Approval Required? | Approved | Automated performance tracking | CRITICAL | Compliance Officer | Core Financial Management | Customer | Goal setting and management tool | HIGH | LOW | MEDIUM | Market trend analysis dashboard | Rejected | Risk assessment questionnaire | Standard threshold | Under Review | User | User-friendly investment portfolio builder | Verification Complete? | support ||--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|| Account Manager User-friendly investment portfolio builder | R/A | I | I | - | - | - | - | I | - | I | - | - | - | - | - | - | - | - | - | - | - | - | - || Compliance Officer Market trend analysis dashboard | C | I | I | - | - | - | - | R/A | - | I | - | - | - | - | - | - | - | - | - | - | - | - | - || Analyst Risk assessment questionnaire | I | I | R/A | - | - | - | - | C | - | I | - | - | - | - | - | - | - | - | - | - | - | - | - || Advisor Automated performance tracking | I | R/A | C | - | - | - | - | I | - | I | - | - | - | - | - | - | - | - | - | - | - | - | - || Customer Goal setting and management tool | I | C | I | - | - | - | - | I | - | R/A | - | - | - | - | - | - | - | - | - | - | - | - | - || action | - | - | - | - | - | - | I | - | I | - | - | I | I | I | - | - | - | I | - | - | - | - | R/A || flow: | - | - | - | - | - | I | - | - | - | R/A | I | - | - | - | I | - | I | - | - | I | I | - | - || User-friendly investment portfolio builder | - | - | - | I | I | I | - | - | - | - | I | - | - | - | I | I | I | - | I | R/A | I | I | - || Market trend analysis dashboard | - | - | - | I | I | I | - | - | - | - | I | - | - | - | R/A | I | I | - | I | C | I | I | - || Risk assessment questionnaire | - | - | - | I | I | I | - | - | - | - | I | - | - | - | C | I | R/A | - | I | I | I | I | - || Automated performance tracking | - | - | - | I | I | R/A | - | - | - | - | I | - | - | - | I | I | C | - | I | I | I | I | - || Goal setting and management tool | - | - | - | I | I | C | - | - | - | - | R/A | - | - | - | I | I | I | - | I | I | I | I | - |
**Legend:**
- **R** = Responsible (does the work)
- **A** = Accountable (owns the decision)
- **C** = Consulted (provides input)
- **I** = Informed (kept updated)


---

## Business Rules

Automated decision logic extracted from decision tree diagrams.
### BR-001: Threshold Assessment

- **Condition**: `Is the financial condition below the standard threshold?`
- **Action**: Route to Initiate low-level financial review process
- **Automation**: Manual
- **Priority**: P1
- **Source**: acf90771-5ae5-4296-965c-c6ed15928e63
### BR-002: Business Rule Evaluation

- **Condition**: `Is the financial condition at a medium level?`
- **Action**: Route to Initiate low-level financial review process
- **Automation**: Manual
- **Priority**: P2
- **Source**: acf90771-5ae5-4296-965c-c6ed15928e63
### BR-003: Business Rule Evaluation

- **Condition**: `Is the financial condition high?`
- **Action**: Route to Initiate low-level financial review process
- **Automation**: Manual
- **Priority**: P2
- **Source**: acf90771-5ae5-4296-965c-c6ed15928e63
---

## Non-Functional Requirements

### Performance Requirements

| ID | Requirement | Source | Verification | Priority |
|----|-------------|--------|--------------|----------|| NFR-PERF-1 | System SHALL complete task within 4 hours | bf7b9e8a-bc1b-4adb-b293-aef38451c951:slas | Measure response time for task operation | P1 || NFR-PERF-2 | System SHALL complete task within 6 hours | bf7b9e8a-bc1b-4adb-b293-aef38451c951:slas | Measure response time for task operation | P1 || NFR-PERF-3 | System SHALL complete task within 8 hours | bf7b9e8a-bc1b-4adb-b293-aef38451c951:slas | Measure response time for task operation | P1 |
### Accessibility Requirements

| ID | Requirement | Source | Verification | Priority |
|----|-------------|--------|--------------|----------|| NFR-A11Y-1 | System SHALL comply with WCAG 2.1 compliance requirements | f9d6e78f-7c91-4009-8869-c60c14d1222f:accessibility_needs | WCAG audit for WCAG 2.1 compliance | P0 || NFR-A11Y-2 | System SHALL comply with Screen reader support requirements | f9d6e78f-7c91-4009-8869-c60c14d1222f:accessibility_needs | WCAG audit for Screen reader support | P0 || NFR-A11Y-3 | System SHALL comply with Keyboard navigation requirements | f9d6e78f-7c91-4009-8869-c60c14d1222f:accessibility_needs | WCAG audit for Keyboard navigation | P0 |
### Automation Requirements

| ID | Requirement | Source | Verification | Priority |
|----|-------------|--------|--------------|----------|| NFR-AUTO-1 | advisor SHALL be Automated | bf7b9e8a-bc1b-4adb-b293-aef38451c951:automation_hints | Verify automated implementation for advisor | P1 || NFR-AUTO-2 | automated SHALL be Automated | fb4dce8b-900b-4ae9-8378-9fb366717a68:automation_hints | Verify automated implementation for automated | P1 || NFR-AUTO-3 | auto SHALL be Automated | fb4dce8b-900b-4ae9-8378-9fb366717a68:automation_hints | Verify automated implementation for auto | P1 || NFR-AUTO-4 | manual SHALL be Manual | fb4dce8b-900b-4ae9-8378-9fb366717a68:automation_hints | Verify manual implementation for manual | P2 || NFR-AUTO-5 | automated SHALL be Automated | 504bafa0-183f-410b-b930-8f3771881981:automation_hints | Verify automated implementation for automated | P1 || NFR-AUTO-6 | management workflow SHALL be Automated | 504bafa0-183f-410b-b930-8f3771881981:automation_hints | Verify automated implementation for management workflow | P1 || NFR-AUTO-7 | manual SHALL be Manual | 504bafa0-183f-410b-b930-8f3771881981:automation_hints | Verify manual implementation for manual | P2 |

---

## Quality Metrics

| Metric | Value | Source |
|--------|-------|--------|
| Diagrams Analyzed | 5 | MAS Compiler |
| RACI Entries | 12 | business_analysis |
| Business Rules | 3 | decision_tree |
| NFRs Generated | 13 | ux/business_analysis |
| EARS Requirements | 65 | metadata mapping |

---

*Generated by MAS Compiler Knowledge Spec Generator*