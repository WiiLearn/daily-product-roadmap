# Knowledge Document: Propertyiq Mvp3

> **Generated**: 2025-12-11 11:52:07  
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
    - "Investment property analytics dashboard"
    - "Under Review"
  entities:
    - "API integration for real-time market data"
    - "Account Manager"
    - "Advisor"
    - "Analyst"
    - "Approval Required?"
    - "Approved"
    - "CRITICAL"
    - "Compliance Officer"
    - "ENRICHING"
    - "Financial Ecosystem"
    - "HIGH"
    - "LOW"
    - "MEDIUM"
    - "MVP1"
    - "MVP2"
    - "PAIN"
    - "POINT"
    - "Rejected"
    - "Standard threshold"
    - "USING"
---

---

## Overview

This document captures the domain knowledge extracted from MAS artifacts for **Propertyiq Mvp3**.

Financial Ecosystem: Banking integrations and marketplace. I want to build a property investment analysis platform called PropertyIQ that uses AI to evaluate real estate opportunities, predicts neighborhood growth patterns, calculates ROI projections, and pro

---

## RACI Matrix

Responsibility assignment matrix for process steps.

| Process Step | API integration for real-time market data | Account Manager | Advisor | Analyst | Approval Required? | Approved | CRITICAL | Compliance Officer | Customer | Financial Ecosystem | HIGH | Investment property analytics dashboard | LOW | MEDIUM | Rejected | Standard threshold | System | Under Review | User | Verification Complete? | support ||--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|| Account Manager Investment property analytics dashboard ENRICHING MVP2 predictions | - | R/A | I | I | - | - | - | I | I | - | - | - | - | - | - | - | - | - | - | - | - || Compliance Officer API integration for real-time market data USING MVP1+MVP2 analytics | - | C | I | I | - | - | - | R/A | I | - | - | - | - | - | - | - | - | - | - | - | - || Analyst Partnership with lenders providing real-time valuation reports USING MVP1+MVP2 data | - | I | I | R/A | - | - | - | C | I | - | - | - | - | - | - | - | - | - | - | - | - || Advisor Integration with real estate MLS for comprehensive listings USING MVP1+MVP2 features | - | I | R/A | C | - | - | - | I | I | - | - | - | - | - | - | - | - | - | - | - | - || Customer Collaboration platform for real estate professionals USING MVP1+MVP2 user behavior analytics | - | I | C | I | - | - | - | I | R/A | - | - | - | - | - | - | - | - | - | - | - | - || action | - | - | - | - | - | - | I | - | - | I | I | - | I | I | - | I | R/A | - | - | - | I || flow: | I | - | - | - | - | - | - | - | I | - | - | I | - | - | - | - | R/A | - | I | - | - || Investment property analytics dashboard ENRICHING MVP2 predictions | - | - | - | - | I | I | - | - | - | - | - | - | - | - | I | - | R/A | I | I | I | - || API integration for real-time market data USING MVP1+MVP2 analytics | - | - | - | - | I | I | - | - | - | - | - | - | - | - | I | - | C | I | R/A | I | - || Partnership with lenders providing real-time valuation reports USING MVP1+MVP2 data | - | - | - | - | I | I | - | - | - | - | - | - | - | - | I | - | I | I | C | R/A | - || Integration with real estate MLS for comprehensive listings USING MVP1+MVP2 features | - | - | - | - | R/A | I | - | - | - | - | - | - | - | - | I | - | I | I | I | C | - || Collaboration platform for real estate professionals USING MVP1+MVP2 user behavior analytics | - | - | - | - | C | I | - | - | - | - | - | - | - | - | I | - | I | I | R/A | I | - |
**Legend:**
- **R** = Responsible (does the work)
- **A** = Accountable (owns the decision)
- **C** = Consulted (provides input)
- **I** = Informed (kept updated)


---

## Business Rules

Automated decision logic extracted from decision tree diagrams.
### BR-001: Threshold Assessment

- **Condition**: `Is the condition above the Standard threshold?`
- **Action**: Route to Condition is LOW, no action required
- **Automation**: Manual
- **Priority**: P1
- **Source**: 3d289f69-0d3b-466c-996d-a680acea4f4d
### BR-002: Business Rule Evaluation

- **Condition**: `Is the condition at a MEDIUM level?`
- **Action**: Route to Condition is LOW, no action required
- **Automation**: Manual
- **Priority**: P2
- **Source**: 3d289f69-0d3b-466c-996d-a680acea4f4d
### BR-003: Business Rule Evaluation

- **Condition**: `Is the condition at a HIGH level?`
- **Action**: Route to Condition is LOW, no action required
- **Automation**: Manual
- **Priority**: P2
- **Source**: 3d289f69-0d3b-466c-996d-a680acea4f4d
---

## Non-Functional Requirements

### Performance Requirements

| ID | Requirement | Source | Verification | Priority |
|----|-------------|--------|--------------|----------|| NFR-PERF-1 | System SHALL complete task within 4 hours | 5a5b4897-71ef-4b54-9701-073a02fff47e:slas | Measure response time for task operation | P1 || NFR-PERF-2 | System SHALL complete task within 6 hours | 5a5b4897-71ef-4b54-9701-073a02fff47e:slas | Measure response time for task operation | P1 || NFR-PERF-3 | System SHALL complete task within 8 hours | 5a5b4897-71ef-4b54-9701-073a02fff47e:slas | Measure response time for task operation | P1 |
### Accessibility Requirements

| ID | Requirement | Source | Verification | Priority |
|----|-------------|--------|--------------|----------|| NFR-A11Y-1 | System SHALL comply with WCAG compliance requirements | 4e90b4a7-99a5-4111-9e00-98bc545e341a:accessibility_needs | WCAG audit for WCAG compliance | P0 || NFR-A11Y-2 | System SHALL comply with Screen reader support requirements | 4e90b4a7-99a5-4111-9e00-98bc545e341a:accessibility_needs | WCAG audit for Screen reader support | P0 || NFR-A11Y-3 | System SHALL comply with Keyboard navigation requirements | 4e90b4a7-99a5-4111-9e00-98bc545e341a:accessibility_needs | WCAG audit for Keyboard navigation | P0 |
### Automation Requirements

| ID | Requirement | Source | Verification | Priority |
|----|-------------|--------|--------------|----------|| NFR-AUTO-1 | system SHALL be Automated | 5a5b4897-71ef-4b54-9701-073a02fff47e:automation_hints | Verify automated implementation for system | P1 || NFR-AUTO-2 | compliance officer SHALL be Automated | 5a5b4897-71ef-4b54-9701-073a02fff47e:automation_hints | Verify automated implementation for compliance officer | P1 || NFR-AUTO-3 | officer api SHALL be Automated | 5a5b4897-71ef-4b54-9701-073a02fff47e:automation_hints | Verify automated implementation for officer api | P1 || NFR-AUTO-4 | advisor SHALL be Automated | 5a5b4897-71ef-4b54-9701-073a02fff47e:automation_hints | Verify automated implementation for advisor | P1 || NFR-AUTO-5 | api SHALL be Automated | 5a5b4897-71ef-4b54-9701-073a02fff47e:automation_hints | Verify automated implementation for api | P1 || NFR-AUTO-6 | system SHALL be Automated | 3d289f69-0d3b-466c-996d-a680acea4f4d:automation_hints | Verify automated implementation for system | P1 || NFR-AUTO-7 | system SHALL be Automated | ea5baa9f-8b1e-4afd-9af0-c402be7c3916:automation_hints | Verify automated implementation for system | P1 || NFR-AUTO-8 | api SHALL be Automated | ea5baa9f-8b1e-4afd-9af0-c402be7c3916:automation_hints | Verify automated implementation for api | P1 || NFR-AUTO-9 | manual SHALL be Manual | ea5baa9f-8b1e-4afd-9af0-c402be7c3916:automation_hints | Verify manual implementation for manual | P2 || NFR-AUTO-10 | automated SHALL be Automated | d33f3640-0e14-4d6d-91a5-30c9efcb2f17:automation_hints | Verify automated implementation for automated | P1 || NFR-AUTO-11 | ecosystem workflow SHALL be Automated | d33f3640-0e14-4d6d-91a5-30c9efcb2f17:automation_hints | Verify automated implementation for ecosystem workflow | P1 || NFR-AUTO-12 | system SHALL be Automated | d33f3640-0e14-4d6d-91a5-30c9efcb2f17:automation_hints | Verify automated implementation for system | P1 || NFR-AUTO-13 | api SHALL be Automated | d33f3640-0e14-4d6d-91a5-30c9efcb2f17:automation_hints | Verify automated implementation for api | P1 || NFR-AUTO-14 | manual SHALL be Manual | d33f3640-0e14-4d6d-91a5-30c9efcb2f17:automation_hints | Verify manual implementation for manual | P2 |

---

## Quality Metrics

| Metric | Value | Source |
|--------|-------|--------|
| Diagrams Analyzed | 5 | MAS Compiler |
| RACI Entries | 12 | business_analysis |
| Business Rules | 3 | decision_tree |
| NFRs Generated | 20 | ux/business_analysis |
| EARS Requirements | 67 | metadata mapping |

---

*Generated by MAS Compiler Knowledge Spec Generator*