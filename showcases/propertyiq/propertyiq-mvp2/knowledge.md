# Knowledge Document: Propertyiq Mvp2

> **Generated**: 2025-12-10 13:34:35  
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
    []
  entities:
    - "AI-driven neighborhood growth prediction"
    - "Addresses"
    - "Aligns"
    - "Automated risk assessment reports"
    - "BUILDING"
    - "Due Diligence Reports"
    - "Enhanced user insights"
    - "Ensures"
    - "Incorporates"
    - "MVP1"
    - "MVP2"
    - "Neighborhood Growth Patterns"
    - "Predictive analytics for investment opportunities"
    - "Property Analysis Workflow"
    - "PropertyIQ"
    - "ROI Projections"
    - "Reflects"
    - "Stakeholders"
    - "USING"
---

---

## Overview

This document captures the domain knowledge extracted from MAS artifacts for **Propertyiq Mvp2**.

Advanced Analytics: AI-powered insights and automation. I want to build a property investment analysis platform called PropertyIQ that uses AI to evaluate real estate opportunities, predicts neighborhood growth patterns, calculates ROI projections, and pro

---

## RACI Matrix

Responsibility assignment matrix for process steps.

| Process Step | AI-driven neighborhood growth prediction | Automated risk assessment reports | Due Diligence Reports | MVP1 | Machine learning algorithm for dynamic ROI adjustments | Neighborhood Growth Patterns | Predictive analytics for investment opportunities | Property Analysis Workflow | PropertyIQ | ROI Projections | Stakeholders | System | User ||--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|| Aligns with the semantic context provided above | I | I | - | - | I | - | I | - | - | - | - | - | R/A || Addresses the specific requirements of Advanced Analytics | R/A | I | - | - | I | - | I | - | - | - | - | - | C || Ensures consistency with the product vision and domain | C | I | - | - | R/A | - | I | - | - | - | - | - | I || Incorporates the job statements and market insights | I | I | - | - | C | - | R/A | - | - | - | - | - | I || Reflects the core activities and value stream | I | R/A | - | - | I | - | C | - | - | - | - | - | I || Aligns with the semantic context provided above | I | I | - | - | - | - | I | - | I | - | - | R/A | I || Addresses the specific requirements of Advanced Analytics | I | I | - | - | - | - | I | - | I | - | - | C | R/A || Ensures consistency with the product vision and domain | I | I | - | - | - | - | I | - | R/A | - | - | I | C || Incorporates the job statements and market insights | R/A | I | - | - | - | - | I | - | C | - | - | I | I || Reflects the core activities and value stream | C | I | - | - | - | - | R/A | - | I | - | - | I | I || Aligns with the semantic context provided above | I | I | - | I | - | - | I | - | I | - | - | R/A | I || Addresses the specific requirements of Advanced Analytics | I | I | - | I | - | - | I | - | I | - | - | C | R/A || Ensures consistency with the product vision and domain | I | I | - | I | - | - | I | - | R/A | - | - | I | C || Incorporates the job statements and market insights | R/A | I | - | I | - | - | I | - | C | - | - | I | I || Reflects the core activities and value stream | C | I | - | I | - | - | R/A | - | I | - | - | I | I || Evaluate Property Opportunities | - | - | I | - | - | I | - | I | - | I | I | R/A | I || Analyze Neighborhood Growth Patterns | - | - | I | - | - | R/A | - | I | - | I | I | C | I || Generate ROI Projections | - | - | I | - | - | C | - | I | - | R/A | I | I | I || Produce Due Diligence Reports | - | - | R/A | - | - | I | - | I | - | C | I | I | I || Share Insights with Stakeholders | - | - | C | - | - | I | - | I | - | I | R/A | I | I |
**Legend:**
- **R** = Responsible (does the work)
- **A** = Accountable (owns the decision)
- **C** = Consulted (provides input)
- **I** = Informed (kept updated)


---

## Business Rules

Automated decision logic extracted from decision tree diagrams.
### BR-001: Business Rule Evaluation

- **Condition**: `Is AI-driven neighborhood growth prediction feature enabled?`
- **Action**: Route to AI-driven neighborhood growth prediction feature is not enabled. Please enable it to proceed.
- **Automation**: Manual
- **Priority**: P2
- **Source**: 1efbf8e9-db55-49b4-b766-941fdaa6e7e7
### BR-002: Business Rule Evaluation

- **Condition**: `Is machine learning algorithm for dynamic ROI adjustments implemented?`
- **Action**: Route to AI-driven neighborhood growth prediction feature is not enabled. Please enable it to proceed.
- **Automation**: Manual
- **Priority**: P2
- **Source**: 1efbf8e9-db55-49b4-b766-941fdaa6e7e7
### BR-003: Business Rule Evaluation

- **Condition**: `Is predictive analytics for investment opportunities available?`
- **Action**: Route to AI-driven neighborhood growth prediction feature is not enabled. Please enable it to proceed.
- **Automation**: Manual
- **Priority**: P2
- **Source**: 1efbf8e9-db55-49b4-b766-941fdaa6e7e7
### BR-004: Business Rule Evaluation

- **Condition**: `Are automated risk assessment reports generated?`
- **Action**: Route to AI-driven neighborhood growth prediction feature is not enabled. Please enable it to proceed.
- **Automation**: Manual
- **Priority**: P2
- **Source**: 1efbf8e9-db55-49b4-b766-941fdaa6e7e7
---

## Non-Functional Requirements

### Performance Requirements

| ID | Requirement | Source | Verification | Priority |
|----|-------------|--------|--------------|----------|
### Accessibility Requirements

| ID | Requirement | Source | Verification | Priority |
|----|-------------|--------|--------------|----------|| NFR-A11Y-1 | System SHALL comply with WCAG 2.1 compliance requirements | 71e1ed1f-0894-4db1-97bb-4a15115130e2:accessibility_needs | WCAG audit for WCAG 2.1 compliance | P0 || NFR-A11Y-2 | System SHALL comply with Screen reader support requirements | 71e1ed1f-0894-4db1-97bb-4a15115130e2:accessibility_needs | WCAG audit for Screen reader support | P0 || NFR-A11Y-3 | System SHALL comply with Keyboard navigation requirements | 71e1ed1f-0894-4db1-97bb-4a15115130e2:accessibility_needs | WCAG audit for Keyboard navigation | P0 |
### Automation Requirements

| ID | Requirement | Source | Verification | Priority |
|----|-------------|--------|--------------|----------|| NFR-AUTO-1 | on mvp1 SHALL be Automated | 3cc27f19-baba-4f77-919a-e3aca1262bef:automation_hints | Verify automated implementation for on mvp1 | P1 || NFR-AUTO-2 | property search SHALL be Automated | 3cc27f19-baba-4f77-919a-e3aca1262bef:automation_hints | Verify automated implementation for property search | P1 || NFR-AUTO-3 | enterprise SHALL be Automated | 3cc27f19-baba-4f77-919a-e3aca1262bef:automation_hints | Verify automated implementation for enterprise | P1 || NFR-AUTO-4 | on mvp1 SHALL be Automated | 1efbf8e9-db55-49b4-b766-941fdaa6e7e7:automation_hints | Verify automated implementation for on mvp1 | P1 || NFR-AUTO-5 | property search SHALL be Automated | 1efbf8e9-db55-49b4-b766-941fdaa6e7e7:automation_hints | Verify automated implementation for property search | P1 || NFR-AUTO-6 | on mvp1 SHALL be Automated | 3a5108f6-7167-42cf-9df2-9962bc715c60:automation_hints | Verify automated implementation for on mvp1 | P1 || NFR-AUTO-7 | property search SHALL be Automated | 3a5108f6-7167-42cf-9df2-9962bc715c60:automation_hints | Verify automated implementation for property search | P1 || NFR-AUTO-8 | users generate SHALL be Automated | 415ad35f-e0cb-482d-b0ba-0eca3c47802a:automation_hints | Verify automated implementation for users generate | P1 || NFR-AUTO-9 | on mvp1 SHALL be Automated | 415ad35f-e0cb-482d-b0ba-0eca3c47802a:automation_hints | Verify automated implementation for on mvp1 | P1 || NFR-AUTO-10 | property search SHALL be Automated | 415ad35f-e0cb-482d-b0ba-0eca3c47802a:automation_hints | Verify automated implementation for property search | P1 |

---

## Quality Metrics

| Metric | Value | Source |
|--------|-------|--------|
| Diagrams Analyzed | 5 | MAS Compiler |
| RACI Entries | 20 | business_analysis |
| Business Rules | 4 | decision_tree |
| NFRs Generated | 13 | ux/business_analysis |
| EARS Requirements | 72 | metadata mapping |

---

*Generated by MAS Compiler Knowledge Spec Generator*