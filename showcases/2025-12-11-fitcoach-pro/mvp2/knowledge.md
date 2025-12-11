# Knowledge Document: Fitcoach Pro Mvp2

> **Generated**: 2025-12-11 11:06:40  
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
    - "Under Review"
  entities:
    - "AI Nutrition Feedback"
    - "Adaptive Routines"
    - "Adaptive Routines USING MVP1 progress tracking"
    - "Advanced Analytics"
    - "Approval Required?"
    - "Approved"
    - "BUILDING"
    - "CRITICAL"
    - "Developer"
    - "Dynamic Goal Adjustment"
    - "HIGH"
    - "LOW"
    - "MEDIUM"
    - "MVP1"
    - "MVP1 photo recognition"
    - "MVP1 progress tracking"
    - "MVP1 user profiles"
    - "MVP1 workout generator"
    - "MVP1+wearable data"
    - "PAIN"
---

---

## Overview

This document captures the domain knowledge extracted from MAS artifacts for **Fitcoach Pro Mvp2**.

Advanced Analytics: AI-powered insights and automation. I want to build an AI-powered fitness coaching app called FitCoach Pro that creates personalized workout plans, tracks nutrition through photo recognition, and adapts routines based on user progress a

---

## RACI Matrix

Responsibility assignment matrix for process steps.

| Process Step | AI Nutrition Feedback | Adaptive Routines | Adaptive Routines USING MVP1 progress tracking | Admin | Advanced Analytics | Approval Required? | Approved | CRITICAL | Developer | Dynamic Goal Adjustment | HIGH | LOW | MEDIUM | MVP1 photo recognition | MVP1 progress tracking | MVP1 user profiles | MVP1 workout generator | MVP1+wearable data | Predictive Progress Tracking | Product Owner | Rejected | Standard threshold | Support Agent | Under Review | User | Verification Complete? | Workout Plan Optimization ||--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|| Admin Workout Plan Optimization USING MVP1 workout generator | - | - | - | R/A | - | - | - | - | I | - | - | - | - | - | - | - | - | - | - | I | - | - | I | - | I | - | - || Developer AI Nutrition Feedback BUILDING ON MVP1 photo recognition | - | - | - | C | - | - | - | - | R/A | - | - | - | - | - | - | - | - | - | - | I | - | - | I | - | I | - | - || Product Owner Adaptive Routines USING MVP1 progress tracking | - | - | - | I | - | - | - | - | C | - | - | - | - | - | - | - | - | - | - | R/A | - | - | I | - | I | - | - || Support Agent Predictive Progress Tracking USING MVP1+wearable data | - | - | - | I | - | - | - | - | I | - | - | - | - | - | - | - | - | - | - | C | - | - | R/A | - | I | - | - || User Dynamic Goal Adjustment BUILDING ON MVP1 user profiles | - | - | - | I | - | - | - | - | I | - | - | - | - | - | - | - | - | - | - | I | - | - | C | - | R/A | - | - || action | - | - | - | - | R/A | - | - | I | - | - | I | I | I | - | - | - | - | - | - | - | - | I | - | - | - | - | - || flow: | I | I | - | - | - | - | - | - | - | I | - | - | - | I | I | I | I | I | I | - | - | - | - | - | R/A | - | I || Workout Plan Optimization | - | - | I | - | - | I | I | - | - | - | - | - | - | - | - | - | - | - | - | - | I | - | - | I | R/A | I | - || AI Nutrition Feedback | - | - | I | - | - | I | I | - | - | - | - | - | - | - | - | - | - | - | - | - | I | - | - | I | C | R/A | - || Adaptive Routines | - | - | I | - | - | R/A | I | - | - | - | - | - | - | - | - | - | - | - | - | - | I | - | - | I | I | C | - || Predictive Progress Tracking | - | - | R/A | - | - | C | I | - | - | - | - | - | - | - | - | - | - | - | - | - | I | - | - | I | I | I | - || Dynamic Goal Adjustment | - | - | C | - | - | I | R/A | - | - | - | - | - | - | - | - | - | - | - | - | - | I | - | - | I | I | I | - |
**Legend:**
- **R** = Responsible (does the work)
- **A** = Accountable (owns the decision)
- **C** = Consulted (provides input)
- **I** = Informed (kept updated)


---

## Business Rules

Automated decision logic extracted from decision tree diagrams.
### BR-001: Business Rule Evaluation

- **Condition**: `Is the analytics result LOW, MEDIUM, HIGH, or CRITICAL?`
- **Action**: Route to Approve advanced analytics for implementation
- **Automation**: Manual
- **Priority**: P2
- **Source**: 8025e9c3-986f-48d2-8a68-67f6007276cd
### BR-002: Threshold Assessment

- **Condition**: `Is the result above the Standard threshold?`
- **Action**: Route to Approve advanced analytics for implementation
- **Automation**: Manual
- **Priority**: P1
- **Source**: 8025e9c3-986f-48d2-8a68-67f6007276cd
---

## Non-Functional Requirements

### Performance Requirements

| ID | Requirement | Source | Verification | Priority |
|----|-------------|--------|--------------|----------|| NFR-PERF-1 | System SHALL complete task within 4 hours | 73e7f5a4-5a95-45b5-8817-dd3cd9b434af:slas | Measure response time for task operation | P1 || NFR-PERF-2 | System SHALL complete task within 6 hours | 73e7f5a4-5a95-45b5-8817-dd3cd9b434af:slas | Measure response time for task operation | P1 || NFR-PERF-3 | System SHALL complete task within 8 hours | 73e7f5a4-5a95-45b5-8817-dd3cd9b434af:slas | Measure response time for task operation | P1 |
### Accessibility Requirements

| ID | Requirement | Source | Verification | Priority |
|----|-------------|--------|--------------|----------|| NFR-A11Y-1 | System SHALL comply with WCAG 2.1 AA requirements | 2c4ed951-329c-441a-abb6-c800aeb5443e:accessibility_needs | WCAG audit for WCAG 2.1 AA | P0 || NFR-A11Y-2 | System SHALL comply with Screen reader support requirements | 2c4ed951-329c-441a-abb6-c800aeb5443e:accessibility_needs | WCAG audit for Screen reader support | P0 || NFR-A11Y-3 | System SHALL comply with Keyboard navigation requirements | 2c4ed951-329c-441a-abb6-c800aeb5443e:accessibility_needs | WCAG audit for Keyboard navigation | P0 |
### Automation Requirements

| ID | Requirement | Source | Verification | Priority |
|----|-------------|--------|--------------|----------|| NFR-AUTO-1 | support SHALL be Manual | 73e7f5a4-5a95-45b5-8817-dd3cd9b434af:automation_hints | Verify manual implementation for support | P2 || NFR-AUTO-2 | manual SHALL be Manual | 33ff1ce6-143d-479c-8874-9971b22e2c95:automation_hints | Verify manual implementation for manual | P2 || NFR-AUTO-3 | automated SHALL be Automated | d4ead8f8-cfeb-4801-b43b-84fc6f642dc5:automation_hints | Verify automated implementation for automated | P1 || NFR-AUTO-4 | analytics workflow SHALL be Automated | d4ead8f8-cfeb-4801-b43b-84fc6f642dc5:automation_hints | Verify automated implementation for analytics workflow | P1 || NFR-AUTO-5 | manual SHALL be Manual | d4ead8f8-cfeb-4801-b43b-84fc6f642dc5:automation_hints | Verify manual implementation for manual | P2 |

---

## Quality Metrics

| Metric | Value | Source |
|--------|-------|--------|
| Diagrams Analyzed | 5 | MAS Compiler |
| RACI Entries | 12 | business_analysis |
| Business Rules | 2 | decision_tree |
| NFRs Generated | 11 | ux/business_analysis |
| EARS Requirements | 60 | metadata mapping |

---

*Generated by MAS Compiler Knowledge Spec Generator*