# Knowledge Document: Propertyiq Mvp1

> **Generated**: 2025-12-10 13:33:54  
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
    []
  screens:
    - "User dashboard for investment tracking"
  entities:
    - "Addresses"
    - "Advanced property search system"
    - "Aligns"
    - "Automated due diligence report generator"
    - "Due Diligence Reports"
    - "Ensures"
    - "Incorporates"
    - "MVP1"
    - "Neighborhood Growth Patterns"
    - "Neighborhood growth trend analysis"
    - "Property Analysis Workflow"
    - "PropertyIQ"
    - "PropertyIQ System"
    - "ROI Projections"
    - "ROI projection calculator"
    - "Reflects"
    - "Stakeholders"
---

---

## Overview

This document captures the domain knowledge extracted from MAS artifacts for **Propertyiq Mvp1**.

Core Platform Features: Essential functionality and user management. I want to build a property investment analysis platform called PropertyIQ that uses AI to evaluate real estate opportunities, predicts neighborhood growth patterns, calculates ROI projections, and pro

---

## RACI Matrix

Responsibility assignment matrix for process steps.

| Process Step | Advanced property search system | Automated due diligence report generator | Due Diligence Reports | Neighborhood Growth Patterns | Neighborhood growth trend analysis | Property Analysis Workflow | PropertyIQ | PropertyIQ System | ROI Projections | ROI projection calculator | Stakeholders | System | User | User dashboard for investment tracking ||--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|| Aligns with the semantic context provided above | - | - | - | - | - | - | - | I | - | - | - | - | R/A | - || Addresses the specific requirements of Core Platform Features | - | - | - | - | - | - | - | R/A | - | - | - | - | C | - || Ensures consistency with the product vision and domain | - | - | - | - | - | - | - | C | - | - | - | - | R/A | - || Incorporates the job statements and market insights | - | - | - | - | - | - | - | R/A | - | - | - | - | C | - || Reflects the core activities and value stream | - | - | - | - | - | - | - | C | - | - | - | - | R/A | - || Aligns with the semantic context provided above | I | I | - | - | I | - | I | - | - | I | - | R/A | I | I || Addresses the specific requirements of Core Platform Features | I | I | - | - | I | - | I | - | - | I | - | C | R/A | I || Ensures consistency with the product vision and domain | I | I | - | - | I | - | R/A | - | - | I | - | I | C | I || Incorporates the job statements and market insights | R/A | I | - | - | I | - | C | - | - | I | - | I | I | I || Reflects the core activities and value stream | C | I | - | - | I | - | I | - | - | R/A | - | I | I | I || Aligns with the semantic context provided above | I | I | - | - | I | - | I | - | - | I | - | R/A | I | I || Addresses the specific requirements of Core Platform Features | I | I | - | - | I | - | I | - | - | I | - | C | R/A | I || Ensures consistency with the product vision and domain | I | I | - | - | I | - | R/A | - | - | I | - | I | C | I || Incorporates the job statements and market insights | R/A | I | - | - | I | - | C | - | - | I | - | I | I | I || Reflects the core activities and value stream | C | I | - | - | I | - | I | - | - | R/A | - | I | I | I || Evaluate Property Opportunities | - | - | I | I | - | I | - | - | I | - | I | R/A | I | - || Analyze Neighborhood Growth Patterns | - | - | I | R/A | - | I | - | - | I | - | I | C | I | - || Generate ROI Projections | - | - | I | C | - | I | - | - | R/A | - | I | I | I | - || Produce Due Diligence Reports | - | - | R/A | I | - | I | - | - | C | - | I | I | I | - || Share Insights with Stakeholders | - | - | C | I | - | I | - | - | I | - | R/A | I | I | - |
**Legend:**
- **R** = Responsible (does the work)
- **A** = Accountable (owns the decision)
- **C** = Consulted (provides input)
- **I** = Informed (kept updated)


---

## Business Rules

Automated decision logic extracted from decision tree diagrams.
### BR-001: Business Rule Evaluation

- **Condition**: `Is the Advanced property search system ready for deployment?`
- **Action**: Route to Deploy Advanced property search system
- **Automation**: Manual
- **Priority**: P2
- **Source**: e471eb68-2762-49d9-ac13-262e7157fa11
### BR-002: Business Rule Evaluation

- **Condition**: `Is the ROI projection calculator ready for deployment?`
- **Action**: Route to Deploy Advanced property search system
- **Automation**: Manual
- **Priority**: P2
- **Source**: e471eb68-2762-49d9-ac13-262e7157fa11
### BR-003: Business Rule Evaluation

- **Condition**: `Is the Neighborhood growth trend analysis ready for deployment?`
- **Action**: Route to Deploy Advanced property search system
- **Automation**: Manual
- **Priority**: P2
- **Source**: e471eb68-2762-49d9-ac13-262e7157fa11
### BR-004: Business Rule Evaluation

- **Condition**: `Is the Automated due diligence report generator ready for deployment?`
- **Action**: Route to Deploy Advanced property search system
- **Automation**: Manual
- **Priority**: P2
- **Source**: e471eb68-2762-49d9-ac13-262e7157fa11
### BR-005: Business Rule Evaluation

- **Condition**: `Is the User dashboard for investment tracking ready for deployment?`
- **Action**: Route to Deploy Advanced property search system
- **Automation**: Manual
- **Priority**: P2
- **Source**: e471eb68-2762-49d9-ac13-262e7157fa11
---

## Non-Functional Requirements

### Performance Requirements

| ID | Requirement | Source | Verification | Priority |
|----|-------------|--------|--------------|----------|
### Accessibility Requirements

| ID | Requirement | Source | Verification | Priority |
|----|-------------|--------|--------------|----------|| NFR-A11Y-1 | System SHALL comply with WCAG 2.1 compliance requirements | df209dc2-b9aa-489d-bbe3-2da2f514a6a4:accessibility_needs | WCAG audit for WCAG 2.1 compliance | P0 || NFR-A11Y-2 | System SHALL comply with Screen reader support requirements | df209dc2-b9aa-489d-bbe3-2da2f514a6a4:accessibility_needs | WCAG audit for Screen reader support | P0 || NFR-A11Y-3 | System SHALL comply with Keyboard navigation requirements | df209dc2-b9aa-489d-bbe3-2da2f514a6a4:accessibility_needs | WCAG audit for Keyboard navigation | P0 |
### Automation Requirements

| ID | Requirement | Source | Verification | Priority |
|----|-------------|--------|--------------|----------|| NFR-AUTO-1 | automated SHALL be Automated | f715bbb3-8f58-480b-8b94-fc7e82301834:automation_hints | Verify automated implementation for automated | P1 || NFR-AUTO-2 | auto SHALL be Automated | f715bbb3-8f58-480b-8b94-fc7e82301834:automation_hints | Verify automated implementation for auto | P1 || NFR-AUTO-3 | property search SHALL be Automated | f715bbb3-8f58-480b-8b94-fc7e82301834:automation_hints | Verify automated implementation for property search | P1 || NFR-AUTO-4 | enterprise SHALL be Automated | f715bbb3-8f58-480b-8b94-fc7e82301834:automation_hints | Verify automated implementation for enterprise | P1 || NFR-AUTO-5 | automated SHALL be Automated | e471eb68-2762-49d9-ac13-262e7157fa11:automation_hints | Verify automated implementation for automated | P1 || NFR-AUTO-6 | auto SHALL be Automated | e471eb68-2762-49d9-ac13-262e7157fa11:automation_hints | Verify automated implementation for auto | P1 || NFR-AUTO-7 | property search SHALL be Automated | e471eb68-2762-49d9-ac13-262e7157fa11:automation_hints | Verify automated implementation for property search | P1 || NFR-AUTO-8 | automated SHALL be Automated | 334b781b-667e-4a9a-b65d-c914a1c90736:automation_hints | Verify automated implementation for automated | P1 || NFR-AUTO-9 | auto SHALL be Automated | 334b781b-667e-4a9a-b65d-c914a1c90736:automation_hints | Verify automated implementation for auto | P1 || NFR-AUTO-10 | property search SHALL be Automated | 334b781b-667e-4a9a-b65d-c914a1c90736:automation_hints | Verify automated implementation for property search | P1 || NFR-AUTO-11 | users generate SHALL be Automated | d6ce75e5-33a4-438d-a906-115a2f405e54:automation_hints | Verify automated implementation for users generate | P1 || NFR-AUTO-12 | property search SHALL be Automated | d6ce75e5-33a4-438d-a906-115a2f405e54:automation_hints | Verify automated implementation for property search | P1 |

---

## Quality Metrics

| Metric | Value | Source |
|--------|-------|--------|
| Diagrams Analyzed | 5 | MAS Compiler |
| RACI Entries | 20 | business_analysis |
| Business Rules | 5 | decision_tree |
| NFRs Generated | 15 | ux/business_analysis |
| EARS Requirements | 77 | metadata mapping |

---

*Generated by MAS Compiler Knowledge Spec Generator*