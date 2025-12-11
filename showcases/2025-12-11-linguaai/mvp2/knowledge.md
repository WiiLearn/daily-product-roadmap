# Knowledge Document: Linguaai Mvp2

> **Generated**: 2025-12-11 11:46:23  
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
    - "Analytics dashboard for learner performance"
    - "Under Review"
  entities:
    - "AI-driven lesson adaptation"
    - "Approval Required?"
    - "Approved"
    - "BUILDING"
    - "CRITICAL"
    - "Conversational practice simulations"
    - "Developer"
    - "Enhanced Features"
    - "HIGH"
    - "LOW"
    - "MEDIUM"
    - "MVP1"
    - "PAIN"
    - "POINT"
    - "Personalized AI tutor recommendations"
    - "Product Owner"
    - "Real-time pronunciation feedback"
    - "Rejected"
    - "Standard threshold"
    - "Support Agent"
---

---

## Overview

This document captures the domain knowledge extracted from MAS artifacts for **Linguaai Mvp2**.

Enhanced Features: Advanced capabilities and analytics. I want to build a language learning platform called LinguaAI that uses AI tutors for conversational practice, adapts lessons to individual learning styles, provides real-time pronunciation feedback, a

---

## RACI Matrix

Responsibility assignment matrix for process steps.

| Process Step | AI-driven lesson adaptation | Admin | Agent | Analytics dashboard for learner performance | Approval Required? | Approved | CRITICAL | Conversational practice | Conversational practice simulations | Developer | Enhanced Features | HIGH | LOW | MEDIUM | Persona | Personalized AI tutor recommendations | Product Owner | Real-time pronunciation feedback | Rejected | Show | Standard threshold | Support | Support Agent | Under Review | User | Verification Complete? | multi-tier approval logic ||--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|| Admin AI-driven lesson adaptation USING MVP1 user profiling | - | I | I | - | - | - | - | I | - | I | - | - | - | - | I | - | I | - | - | I | - | I | I | - | R/A | - | - || Developer Real-time pronunciation feedback USING MVP1 voice recognition technology | - | I | I | - | - | - | - | I | - | R/A | - | - | - | - | I | - | I | - | - | I | - | I | I | - | C | - | - || Product Owner Conversational practice simulations USING MVP1 interactive lesson modules | - | I | I | - | - | - | - | R/A | - | C | - | - | - | - | I | - | I | - | - | I | - | I | I | - | I | - | - || Support Agent Personalized AI tutor recommendations BUILDING ON MVP1 progress tracking | - | I | R/A | - | - | - | - | C | - | I | - | - | - | - | I | - | I | - | - | I | - | I | I | - | I | - | - || User Analytics dashboard for learner performance BUILDING ON MVP1 progress tracking | - | I | C | - | - | - | - | I | - | I | - | - | - | - | I | - | I | - | - | I | - | I | I | - | R/A | - | - || action | - | - | - | - | - | - | I | - | - | - | R/A | I | I | I | - | - | - | - | - | - | I | - | - | - | - | - | I || flow: | I | - | - | I | - | - | - | - | I | - | - | - | - | - | R/A | I | - | I | - | - | - | - | - | - | I | - | - || AI-driven lesson adaptation | - | - | - | - | I | I | - | - | - | - | - | - | - | - | R/A | - | - | - | I | - | - | - | - | I | I | I | - || Real-time pronunciation feedback | - | - | - | - | I | I | - | - | - | - | - | - | - | - | C | - | - | - | I | - | - | - | - | I | R/A | I | - || Conversational practice simulations | - | - | - | - | I | I | - | - | - | - | - | - | - | - | I | - | - | - | I | - | - | - | - | I | C | R/A | - || Personalized AI tutor recommendations | - | - | - | - | I | I | - | - | - | - | - | - | - | - | R/A | - | - | - | I | - | - | - | - | I | I | C | - || Analytics dashboard for learner performance | - | - | - | - | I | R/A | - | - | - | - | - | - | - | - | C | - | - | - | I | - | - | - | - | I | I | I | - |
**Legend:**
- **R** = Responsible (does the work)
- **A** = Accountable (owns the decision)
- **C** = Consulted (provides input)
- **I** = Informed (kept updated)


---

## Business Rules

Automated decision logic extracted from decision tree diagrams.
### BR-001: Business Rule Evaluation

- **Condition**: `Is the request for Enhanced Features?`
- **Action**: Route to Approve Enhanced Features request at HIGH level
- **Automation**: Manual
- **Priority**: P2
- **Source**: dc5efe56-fe88-4f68-9c8f-e202254db6d6
### BR-002: Threshold Assessment

- **Condition**: `Does the request meet the Standard threshold?`
- **Action**: Route to Approve Enhanced Features request at HIGH level
- **Automation**: Manual
- **Priority**: P1
- **Source**: dc5efe56-fe88-4f68-9c8f-e202254db6d6
### BR-003: Business Rule Evaluation

- **Condition**: `Is the approval level HIGH?`
- **Action**: Route to Approve Enhanced Features request at HIGH level
- **Automation**: Manual
- **Priority**: P2
- **Source**: dc5efe56-fe88-4f68-9c8f-e202254db6d6
### BR-004: Business Rule Evaluation

- **Condition**: `Is the approval level MEDIUM?`
- **Action**: Route to Approve Enhanced Features request at HIGH level
- **Automation**: Manual
- **Priority**: P2
- **Source**: dc5efe56-fe88-4f68-9c8f-e202254db6d6
---

## Non-Functional Requirements

### Performance Requirements

| ID | Requirement | Source | Verification | Priority |
|----|-------------|--------|--------------|----------|| NFR-PERF-1 | System SHALL complete task within 4 hours | 4c81e42b-00b7-47cf-a0df-a91669769ffe:slas | Measure response time for task operation | P1 || NFR-PERF-2 | System SHALL complete task within 6 hours | 4c81e42b-00b7-47cf-a0df-a91669769ffe:slas | Measure response time for task operation | P1 || NFR-PERF-3 | System SHALL complete task within 8 hours | 4c81e42b-00b7-47cf-a0df-a91669769ffe:slas | Measure response time for task operation | P1 |
### Accessibility Requirements

| ID | Requirement | Source | Verification | Priority |
|----|-------------|--------|--------------|----------|| NFR-A11Y-1 | System SHALL comply with WCAG 2.1 compliance requirements | 1a91f661-0e5c-4f8d-b06e-cc0318b39ed2:accessibility_needs | WCAG audit for WCAG 2.1 compliance | P0 || NFR-A11Y-2 | System SHALL comply with Screen reader support requirements | 1a91f661-0e5c-4f8d-b06e-cc0318b39ed2:accessibility_needs | WCAG audit for Screen reader support | P0 || NFR-A11Y-3 | System SHALL comply with Keyboard navigation requirements | 1a91f661-0e5c-4f8d-b06e-cc0318b39ed2:accessibility_needs | WCAG audit for Keyboard navigation | P0 |
### Automation Requirements

| ID | Requirement | Source | Verification | Priority |
|----|-------------|--------|--------------|----------|| NFR-AUTO-1 | support agent SHALL be Manual | 4c81e42b-00b7-47cf-a0df-a91669769ffe:automation_hints | Verify manual implementation for support agent | P2 || NFR-AUTO-2 | support SHALL be Manual | 4c81e42b-00b7-47cf-a0df-a91669769ffe:automation_hints | Verify manual implementation for support | P2 || NFR-AUTO-3 | manual SHALL be Manual | 00d25c56-a302-4d45-b20d-50b82211cae3:automation_hints | Verify manual implementation for manual | P2 || NFR-AUTO-4 | person SHALL be Manual | 00d25c56-a302-4d45-b20d-50b82211cae3:automation_hints | Verify manual implementation for person | P2 || NFR-AUTO-5 | automated SHALL be Automated | cf1d69fb-25a1-442a-8963-ddbc3e42aa04:automation_hints | Verify automated implementation for automated | P1 || NFR-AUTO-6 | features workflow SHALL be Automated | cf1d69fb-25a1-442a-8963-ddbc3e42aa04:automation_hints | Verify automated implementation for features workflow | P1 || NFR-AUTO-7 | person SHALL be Manual | cf1d69fb-25a1-442a-8963-ddbc3e42aa04:automation_hints | Verify manual implementation for person | P2 |

---

## Quality Metrics

| Metric | Value | Source |
|--------|-------|--------|
| Diagrams Analyzed | 5 | MAS Compiler |
| RACI Entries | 12 | business_analysis |
| Business Rules | 4 | decision_tree |
| NFRs Generated | 13 | ux/business_analysis |
| EARS Requirements | 69 | metadata mapping |

---

*Generated by MAS Compiler Knowledge Spec Generator*