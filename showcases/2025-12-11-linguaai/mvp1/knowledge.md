# Knowledge Document: Linguaai Mvp1

> **Generated**: 2025-12-11 11:45:45  
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
    - "Approval Required?"
    - "Approved"
    - "CRITICAL"
    - "Complete"
    - "Core"
    - "Core Functionality"
    - "Cultural context videos for immersive learning"
    - "Developer"
    - "Functionality"
    - "HIGH"
    - "Interactive"
    - "Interactive lesson modules for different languages"
    - "LOW"
    - "MEDIUM"
    - "PAIN"
    - "POINT"
    - "Product Owner"
    - "Rejected"
    - "Standard threshold"
    - "Support Agent"
---

---

## Overview

This document captures the domain knowledge extracted from MAS artifacts for **Linguaai Mvp1**.

Core Functionality: Essential features and user experience. I want to build a language learning platform called LinguaAI that uses AI tutors for conversational practice, adapts lessons to individual learning styles, provides real-time pronunciation feedback, a

---

## RACI Matrix

Responsibility assignment matrix for process steps.

| Process Step | Admin | Approval Required? | Approved | CRITICAL | Core Functionality | Cultural context videos for immersive learning | Developer | HIGH | Interactive lesson modules for different languages | LOW | MEDIUM | Persona | Product Owner | Rejected | Standard threshold | Support Agent | Under Review | User | User profiling for personalized learning paths | Verification Complete? ||--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|| Admin Interactive lesson modules for different languages | R/A | - | - | - | - | - | I | - | - | - | - | - | I | - | - | I | - | I | - | - || Developer User profiling for personalized learning paths | C | - | - | - | - | - | R/A | - | - | - | - | - | I | - | - | I | - | I | - | - || Product Owner Voice recognition technology to evaluate pronunciation | I | - | - | - | - | - | C | - | - | - | - | - | R/A | - | - | I | - | I | - | - || Support Agent Cultural context videos for immersive learning | I | - | - | - | - | - | I | - | - | - | - | - | C | - | - | R/A | - | I | - | - || User Progress tracking dashboard to visualize learning milestones | I | - | - | - | - | - | I | - | - | - | - | - | I | - | - | C | - | R/A | - | - || action | - | - | - | I | R/A | - | - | I | - | I | I | - | - | - | I | - | - | - | - | - || flow: | - | - | - | - | - | I | - | - | I | - | - | R/A | - | - | - | - | - | I | I | - || Interactive lesson modules for different languages | - | I | I | - | - | I | - | - | R/A | - | - | I | - | I | - | - | I | I | I | I || User profiling for personalized learning paths | - | I | I | - | - | I | - | - | C | - | - | R/A | - | I | - | - | I | I | I | I || Voice recognition technology to evaluate pronunciation | - | I | I | - | - | I | - | - | I | - | - | C | - | I | - | - | I | I | I | R/A || Cultural context videos for immersive learning | - | I | I | - | - | R/A | - | - | I | - | - | I | - | I | - | - | I | I | I | C || Progress tracking dashboard to visualize learning milestones | - | I | I | - | - | C | - | - | R/A | - | - | I | - | I | - | - | I | I | I | I |
**Legend:**
- **R** = Responsible (does the work)
- **A** = Accountable (owns the decision)
- **C** = Consulted (provides input)
- **I** = Informed (kept updated)


---

## Business Rules

Automated decision logic extracted from decision tree diagrams.
### BR-001: Threshold Assessment

- **Condition**: `Is functionality meeting standard threshold?`
- **Action**: Route to Functionality is at a high level, proceed with full implementation
- **Automation**: Manual
- **Priority**: P1
- **Source**: 0d37750b-8f9e-4d99-a25b-0c4e6dd2606e
### BR-002: Business Rule Evaluation

- **Condition**: `Is functionality at medium level?`
- **Action**: Route to Functionality is at a high level, proceed with full implementation
- **Automation**: Manual
- **Priority**: P2
- **Source**: 0d37750b-8f9e-4d99-a25b-0c4e6dd2606e
### BR-003: Business Rule Evaluation

- **Condition**: `Is functionality at low level?`
- **Action**: Route to Functionality is at a high level, proceed with full implementation
- **Automation**: Manual
- **Priority**: P2
- **Source**: 0d37750b-8f9e-4d99-a25b-0c4e6dd2606e
---

## Non-Functional Requirements

### Performance Requirements

| ID | Requirement | Source | Verification | Priority |
|----|-------------|--------|--------------|----------|| NFR-PERF-1 | System SHALL complete task within 4 hours | f2326a91-5242-4a8e-8442-390c7abd3d85:slas | Measure response time for task operation | P1 || NFR-PERF-2 | System SHALL complete task within 6 hours | f2326a91-5242-4a8e-8442-390c7abd3d85:slas | Measure response time for task operation | P1 || NFR-PERF-3 | System SHALL complete task within 8 hours | f2326a91-5242-4a8e-8442-390c7abd3d85:slas | Measure response time for task operation | P1 |
### Accessibility Requirements

| ID | Requirement | Source | Verification | Priority |
|----|-------------|--------|--------------|----------|| NFR-A11Y-1 | System SHALL comply with WCAG 2.1 compliance requirements | 60a24c8e-1d01-4782-b60a-cb3b2387cbc6:accessibility_needs | WCAG audit for WCAG 2.1 compliance | P0 || NFR-A11Y-2 | System SHALL comply with Screen reader support requirements | 60a24c8e-1d01-4782-b60a-cb3b2387cbc6:accessibility_needs | WCAG audit for Screen reader support | P0 || NFR-A11Y-3 | System SHALL comply with Keyboard navigation requirements | 60a24c8e-1d01-4782-b60a-cb3b2387cbc6:accessibility_needs | WCAG audit for Keyboard navigation | P0 |
### Automation Requirements

| ID | Requirement | Source | Verification | Priority |
|----|-------------|--------|--------------|----------|| NFR-AUTO-1 | profiling for SHALL be Manual | f2326a91-5242-4a8e-8442-390c7abd3d85:automation_hints | Verify manual implementation for profiling for | P2 || NFR-AUTO-2 | support SHALL be Manual | f2326a91-5242-4a8e-8442-390c7abd3d85:automation_hints | Verify manual implementation for support | P2 || NFR-AUTO-3 | manual SHALL be Manual | 3efb3312-7701-49f6-baba-c9c1169c2dfa:automation_hints | Verify manual implementation for manual | P2 || NFR-AUTO-4 | profiling for SHALL be Manual | 3efb3312-7701-49f6-baba-c9c1169c2dfa:automation_hints | Verify manual implementation for profiling for | P2 || NFR-AUTO-5 | automated SHALL be Automated | b4565611-7a40-452b-8358-a3b37e7a30ea:automation_hints | Verify automated implementation for automated | P1 || NFR-AUTO-6 | functionality workflow SHALL be Automated | b4565611-7a40-452b-8358-a3b37e7a30ea:automation_hints | Verify automated implementation for functionality workflow | P1 || NFR-AUTO-7 | manual SHALL be Manual | b4565611-7a40-452b-8358-a3b37e7a30ea:automation_hints | Verify manual implementation for manual | P2 || NFR-AUTO-8 | profiling for SHALL be Manual | b4565611-7a40-452b-8358-a3b37e7a30ea:automation_hints | Verify manual implementation for profiling for | P2 |

---

## Quality Metrics

| Metric | Value | Source |
|--------|-------|--------|
| Diagrams Analyzed | 5 | MAS Compiler |
| RACI Entries | 12 | business_analysis |
| Business Rules | 3 | decision_tree |
| NFRs Generated | 14 | ux/business_analysis |
| EARS Requirements | 62 | metadata mapping |

---

*Generated by MAS Compiler Knowledge Spec Generator*