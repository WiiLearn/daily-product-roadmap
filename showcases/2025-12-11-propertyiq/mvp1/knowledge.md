# Knowledge Document: Propertyiq Mvp1

> **Generated**: 2025-12-11 11:51:02  
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
    - "Under Review"
  entities:
    - "Account Manager"
    - "Advisor"
    - "Analyst"
    - "Approval Required?"
    - "Approved"
    - "Automated due diligence checklist"
    - "CRITICAL"
    - "Complete"
    - "Compliance Officer"
    - "Core"
    - "Core Financial Management"
    - "Financial"
    - "HIGH"
    - "LOW"
    - "MEDIUM"
    - "Management"
    - "Neighborhood growth trend analysis"
    - "PAIN"
    - "POINT"
    - "Property"
---

---

## Overview

This document captures the domain knowledge extracted from MAS artifacts for **Propertyiq Mvp1**.

Core Financial Management: Basic accounts, transactions, and reporting. I want to build a property investment analysis platform called PropertyIQ that uses AI to evaluate real estate opportunities, predicts neighborhood growth patterns, calculates ROI projections, and pro

---

## RACI Matrix

Responsibility assignment matrix for process steps.

| Process Step | Account Manager | Advisor | Analyst | Approval Required? | Approved | Automated due diligence checklist | CRITICAL | Compliance Officer | Core Financial Management | Customer | HIGH | LOW | MEDIUM | Neighborhood growth trend analysis | Property investment search engine | ROI projection calculator | Rejected | Standard threshold | System | Under Review | User | User-generated property review system | Verification Complete? | support ||--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|| Account Manager Property investment search engine | R/A | I | I | - | - | - | - | I | - | I | - | - | - | - | - | - | - | - | - | - | - | - | - | - || Compliance Officer ROI projection calculator | C | I | I | - | - | - | - | R/A | - | I | - | - | - | - | - | - | - | - | - | - | - | - | - | - || Analyst Neighborhood growth trend analysis | I | I | R/A | - | - | - | - | C | - | I | - | - | - | - | - | - | - | - | - | - | - | - | - | - || Advisor Automated due diligence checklist | I | R/A | C | - | - | - | - | I | - | I | - | - | - | - | - | - | - | - | - | - | - | - | - | - || Customer User-generated property review system | I | C | I | - | - | - | - | I | - | R/A | - | - | - | - | - | - | - | - | - | - | - | - | - | - || action | - | - | - | - | - | - | I | - | I | - | I | I | I | - | - | - | - | I | - | - | - | - | - | R/A || flow: | - | - | - | - | - | I | - | - | - | I | - | - | - | I | I | I | - | - | R/A | - | I | I | - | - || system (PT: 150 min, WT: 10 hours) | - | - | - | - | - | I | - | - | - | I | - | - | - | I | I | I | - | - | R/A | - | I | I | - | - || Property investment search engine | - | - | - | I | I | I | - | - | - | - | - | - | - | I | R/A | I | I | - | I | I | I | I | I | - || ROI projection calculator | - | - | - | I | I | I | - | - | - | - | - | - | - | I | C | R/A | I | - | I | I | I | I | I | - || Neighborhood growth trend analysis | - | - | - | I | I | I | - | - | - | - | - | - | - | R/A | I | C | I | - | I | I | I | I | I | - || Automated due diligence checklist | - | - | - | I | I | R/A | - | - | - | - | - | - | - | C | I | I | I | - | I | I | I | I | I | - || User-generated property review system | - | - | - | I | I | C | - | - | - | - | - | - | - | I | I | I | I | - | R/A | I | I | I | I | - |
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
- **Action**: Route to Financial condition is LOW, initiate review process
- **Automation**: Manual
- **Priority**: P1
- **Source**: eb055ffe-fc52-4927-b816-d8a8fb74295d
### BR-002: Threshold Assessment

- **Condition**: `Is the financial condition at the standard threshold?`
- **Action**: Route to Financial condition is LOW, initiate review process
- **Automation**: Manual
- **Priority**: P1
- **Source**: eb055ffe-fc52-4927-b816-d8a8fb74295d
### BR-003: Threshold Assessment

- **Condition**: `Is the financial condition above the standard threshold?`
- **Action**: Route to Financial condition is LOW, initiate review process
- **Automation**: Manual
- **Priority**: P1
- **Source**: eb055ffe-fc52-4927-b816-d8a8fb74295d
---

## Non-Functional Requirements

### Performance Requirements

| ID | Requirement | Source | Verification | Priority |
|----|-------------|--------|--------------|----------|| NFR-PERF-1 | System SHALL complete task within 4 hours | 144f5103-8315-43c3-b41f-3a21af8fa26e:slas | Measure response time for task operation | P1 || NFR-PERF-2 | System SHALL complete task within 6 hours | 144f5103-8315-43c3-b41f-3a21af8fa26e:slas | Measure response time for task operation | P1 || NFR-PERF-3 | System SHALL complete task within 8 hours | 144f5103-8315-43c3-b41f-3a21af8fa26e:slas | Measure response time for task operation | P1 |
### Accessibility Requirements

| ID | Requirement | Source | Verification | Priority |
|----|-------------|--------|--------------|----------|| NFR-A11Y-1 | System SHALL comply with WCAG 2.1 compliance requirements | 117f65c9-b22a-4da1-b67a-9bc5f688f7b7:accessibility_needs | WCAG audit for WCAG 2.1 compliance | P0 || NFR-A11Y-2 | System SHALL comply with Screen reader support requirements | 117f65c9-b22a-4da1-b67a-9bc5f688f7b7:accessibility_needs | WCAG audit for Screen reader support | P0 || NFR-A11Y-3 | System SHALL comply with Keyboard navigation requirements | 117f65c9-b22a-4da1-b67a-9bc5f688f7b7:accessibility_needs | WCAG audit for Keyboard navigation | P0 |
### Automation Requirements

| ID | Requirement | Source | Verification | Priority |
|----|-------------|--------|--------------|----------|| NFR-AUTO-1 | advisor SHALL be Automated | 144f5103-8315-43c3-b41f-3a21af8fa26e:automation_hints | Verify automated implementation for advisor | P1 || NFR-AUTO-2 | property review SHALL be Automated | 144f5103-8315-43c3-b41f-3a21af8fa26e:automation_hints | Verify automated implementation for property review | P1 || NFR-AUTO-3 | automated SHALL be Automated | d5ab826d-8a23-4fd9-ac2a-08e52f4944c3:automation_hints | Verify automated implementation for automated | P1 || NFR-AUTO-4 | auto SHALL be Automated | d5ab826d-8a23-4fd9-ac2a-08e52f4944c3:automation_hints | Verify automated implementation for auto | P1 || NFR-AUTO-5 | property review SHALL be Automated | d5ab826d-8a23-4fd9-ac2a-08e52f4944c3:automation_hints | Verify automated implementation for property review | P1 || NFR-AUTO-6 | manual SHALL be Manual | d5ab826d-8a23-4fd9-ac2a-08e52f4944c3:automation_hints | Verify manual implementation for manual | P2 || NFR-AUTO-7 | automated SHALL be Automated | bf929e11-78ee-4d7c-b38b-a708e76938d7:automation_hints | Verify automated implementation for automated | P1 || NFR-AUTO-8 | management workflow SHALL be Automated | bf929e11-78ee-4d7c-b38b-a708e76938d7:automation_hints | Verify automated implementation for management workflow | P1 || NFR-AUTO-9 | property review SHALL be Automated | bf929e11-78ee-4d7c-b38b-a708e76938d7:automation_hints | Verify automated implementation for property review | P1 || NFR-AUTO-10 | manual SHALL be Manual | bf929e11-78ee-4d7c-b38b-a708e76938d7:automation_hints | Verify manual implementation for manual | P2 |

---

## Quality Metrics

| Metric | Value | Source |
|--------|-------|--------|
| Diagrams Analyzed | 5 | MAS Compiler |
| RACI Entries | 13 | business_analysis |
| Business Rules | 3 | decision_tree |
| NFRs Generated | 16 | ux/business_analysis |
| EARS Requirements | 72 | metadata mapping |

---

*Generated by MAS Compiler Knowledge Spec Generator*