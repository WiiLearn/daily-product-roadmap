# Knowledge Document: Propertyiq Mvp2

> **Generated**: 2025-12-11 11:51:35  
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
    - "Automated due diligence insights"
    - "BUILDING"
    - "CRITICAL"
    - "Compliance Officer"
    - "Enhanced ROI projection analytics"
    - "HIGH"
    - "LOW"
    - "MEDIUM"
    - "MVP1"
    - "MVP1 ROI calculator"
    - "MVP1 checklist"
    - "MVP1 neighborhood data"
    - "MVP1 property data"
    - "MVP1 user reviews"
    - "Machine learning-based risk assessment system"
---

---

## Overview

This document captures the domain knowledge extracted from MAS artifacts for **Propertyiq Mvp2**.

Smart Financial Analytics: AI-powered insights and forecasting. I want to build a property investment analysis platform called PropertyIQ that uses AI to evaluate real estate opportunities, predicts neighborhood growth patterns, calculates ROI projections, and pro

---

## RACI Matrix

Responsibility assignment matrix for process steps.

| Process Step | Account Manager | Advisor | Analyst | Approval Required? | Approved | Automated due diligence insights | CRITICAL | Compliance Officer | Customer | Enhanced ROI projection analytics | HIGH | LOW | MEDIUM | Machine learning-based risk assessment system | Neighborhood growth prediction | Persona | Rejected | Smart Financial Analytics | Standard threshold | System | Under Review | User | Verification Complete? | support ||--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|| Account Manager Neighborhood growth prediction USING MVP1 neighborhood data | R/A | I | I | - | - | - | - | I | I | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - || Compliance Officer Enhanced ROI projection analytics BUILDING ON MVP1 ROI calculator | C | I | I | - | - | - | - | R/A | I | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - || Analyst Machine learning-based risk assessment system USING MVP1 property data | I | I | R/A | - | - | - | - | C | I | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - || Advisor Automated due diligence insights BUILDING ON MVP1 checklist | I | R/A | C | - | - | - | - | I | I | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - || Customer User behavior analytics for personalized recommendations USING MVP1 user reviews | I | C | I | - | - | - | - | I | R/A | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - || action | - | - | - | - | - | - | I | - | - | - | I | I | I | - | - | - | - | I | I | - | - | - | - | R/A || flow: | - | - | - | - | - | I | - | - | I | I | - | - | - | I | I | I | - | - | - | R/A | - | I | - | - || Neighborhood growth prediction | - | - | - | I | I | I | - | - | - | I | - | - | - | I | R/A | I | I | - | - | I | I | I | I | - || Enhanced ROI projection analytics | - | - | - | I | I | I | - | - | - | R/A | - | - | - | I | C | I | I | - | - | I | I | I | I | - || Machine learning-based risk assessment system | - | - | - | I | I | I | - | - | - | C | - | - | - | I | I | I | I | - | - | R/A | I | I | I | - || Automated due diligence insights | - | - | - | I | I | R/A | - | - | - | I | - | - | - | I | I | I | I | - | - | C | I | I | I | - || User behavior analytics for personalized recommendations | - | - | - | I | I | C | - | - | - | I | - | - | - | I | I | R/A | I | - | - | I | I | I | I | - |
**Legend:**
- **R** = Responsible (does the work)
- **A** = Accountable (owns the decision)
- **C** = Consulted (provides input)
- **I** = Informed (kept updated)


---

## Business Rules

Automated decision logic extracted from decision tree diagrams.
### BR-001: Threshold Assessment

- **Condition**: `Is the condition above the standard threshold?`
- **Action**: Route to Condition is LOW, no action required
- **Automation**: Manual
- **Priority**: P1
- **Source**: 899309d0-f77d-442b-8991-695052024215
### BR-002: Business Rule Evaluation

- **Condition**: `Is the condition at a medium level?`
- **Action**: Route to Condition is LOW, no action required
- **Automation**: Manual
- **Priority**: P2
- **Source**: 899309d0-f77d-442b-8991-695052024215
### BR-003: Business Rule Evaluation

- **Condition**: `Is the condition at a high level?`
- **Action**: Route to Condition is LOW, no action required
- **Automation**: Manual
- **Priority**: P2
- **Source**: 899309d0-f77d-442b-8991-695052024215
---

## Non-Functional Requirements

### Performance Requirements

| ID | Requirement | Source | Verification | Priority |
|----|-------------|--------|--------------|----------|| NFR-PERF-1 | System SHALL complete task within 4 hours | 14a4afec-1e06-403f-97b8-0287a236e6ae:slas | Measure response time for task operation | P1 || NFR-PERF-2 | System SHALL complete task within 6 hours | 14a4afec-1e06-403f-97b8-0287a236e6ae:slas | Measure response time for task operation | P1 || NFR-PERF-3 | System SHALL complete task within 8 hours | 14a4afec-1e06-403f-97b8-0287a236e6ae:slas | Measure response time for task operation | P1 |
### Accessibility Requirements

| ID | Requirement | Source | Verification | Priority |
|----|-------------|--------|--------------|----------|| NFR-A11Y-1 | System SHALL comply with WCAG 2.1 compliance requirements | 8e373cce-2172-4902-8e0f-511748148962:accessibility_needs | WCAG audit for WCAG 2.1 compliance | P0 || NFR-A11Y-2 | System SHALL comply with Screen reader support requirements | 8e373cce-2172-4902-8e0f-511748148962:accessibility_needs | WCAG audit for Screen reader support | P0 || NFR-A11Y-3 | System SHALL comply with Keyboard navigation requirements | 8e373cce-2172-4902-8e0f-511748148962:accessibility_needs | WCAG audit for Keyboard navigation | P0 |
### Automation Requirements

| ID | Requirement | Source | Verification | Priority |
|----|-------------|--------|--------------|----------|| NFR-AUTO-1 | advisor SHALL be Automated | 14a4afec-1e06-403f-97b8-0287a236e6ae:automation_hints | Verify automated implementation for advisor | P1 || NFR-AUTO-2 | risk assessment SHALL be Automated | 14a4afec-1e06-403f-97b8-0287a236e6ae:automation_hints | Verify automated implementation for risk assessment | P1 || NFR-AUTO-3 | analytics for SHALL be Manual | 14a4afec-1e06-403f-97b8-0287a236e6ae:automation_hints | Verify manual implementation for analytics for | P2 || NFR-AUTO-4 | automated SHALL be Automated | 752b5dfe-6409-4d58-a168-fa61a1904550:automation_hints | Verify automated implementation for automated | P1 || NFR-AUTO-5 | auto SHALL be Automated | 752b5dfe-6409-4d58-a168-fa61a1904550:automation_hints | Verify automated implementation for auto | P1 || NFR-AUTO-6 | risk assessment SHALL be Automated | 752b5dfe-6409-4d58-a168-fa61a1904550:automation_hints | Verify automated implementation for risk assessment | P1 || NFR-AUTO-7 | manual SHALL be Manual | 752b5dfe-6409-4d58-a168-fa61a1904550:automation_hints | Verify manual implementation for manual | P2 || NFR-AUTO-8 | analytics for SHALL be Manual | 752b5dfe-6409-4d58-a168-fa61a1904550:automation_hints | Verify manual implementation for analytics for | P2 || NFR-AUTO-9 | automated SHALL be Automated | a05c9f75-b28a-4ad9-b29b-e24bf01ff598:automation_hints | Verify automated implementation for automated | P1 || NFR-AUTO-10 | analytics workflow SHALL be Automated | a05c9f75-b28a-4ad9-b29b-e24bf01ff598:automation_hints | Verify automated implementation for analytics workflow | P1 || NFR-AUTO-11 | risk assessment SHALL be Automated | a05c9f75-b28a-4ad9-b29b-e24bf01ff598:automation_hints | Verify automated implementation for risk assessment | P1 || NFR-AUTO-12 | manual SHALL be Manual | a05c9f75-b28a-4ad9-b29b-e24bf01ff598:automation_hints | Verify manual implementation for manual | P2 || NFR-AUTO-13 | analytics for SHALL be Manual | a05c9f75-b28a-4ad9-b29b-e24bf01ff598:automation_hints | Verify manual implementation for analytics for | P2 |

---

## Quality Metrics

| Metric | Value | Source |
|--------|-------|--------|
| Diagrams Analyzed | 5 | MAS Compiler |
| RACI Entries | 12 | business_analysis |
| Business Rules | 3 | decision_tree |
| NFRs Generated | 19 | ux/business_analysis |
| EARS Requirements | 73 | metadata mapping |

---

*Generated by MAS Compiler Knowledge Spec Generator*