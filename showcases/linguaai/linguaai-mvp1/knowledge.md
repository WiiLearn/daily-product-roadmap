# Knowledge Document: Linguaai Mvp1

> **Generated**: 2025-12-10 13:28:06  
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
    - "Progress Tracking Dashboard"
    - "User progress tracking dashboard"
  entities:
    - "AI Tutor"
    - "AI tutors"
    - "Addresses"
    - "Aligns"
    - "Cultural Immersion Content"
    - "Ensures"
    - "Incorporates"
    - "Interactive vocabulary quizzes"
    - "LinguaAI"
    - "MVP1"
    - "Personalized lesson plans"
    - "Reflects"
    - "Speech Recognition Module"
---

---

## Overview

This document captures the domain knowledge extracted from MAS artifacts for **Linguaai Mvp1**.

Core Functionality: Essential features and user experience. I want to build a language learning platform called LinguaAI that uses AI tutors for conversational practice, adapts lessons to individual learning styles, provides real-time pronunciation feedback, a

---

## RACI Matrix

Responsibility assignment matrix for process steps.

| Process Step | AI Tutor | AI tutor | AI tutors | Cultural Immersion Content | Cultural immersion content | Interactive vocabulary quizzes | LinguaAI | Persona | Personalized lesson plans | Progress Tracking Dashboard | Speech Recognition Module | Speech recognition module | System | User | User progress tracking dashboard ||--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|| Aligns with the semantic context provided above | I | - | - | I | - | - | - | - | - | I | I | - | - | R/A | - || Addresses the specific requirements of Core Functionality | R/A | - | - | I | - | - | - | - | - | I | I | - | - | C | - || Ensures consistency with the product vision and domain | C | - | - | I | - | - | - | - | - | I | R/A | - | - | I | - || Incorporates the job statements and market insights | I | - | - | I | - | - | - | - | - | R/A | C | - | - | I | - || Reflects the core activities and value stream | I | - | - | R/A | - | - | - | - | - | C | I | - | - | I | - || Aligns with the semantic context provided above | - | - | I | - | I | I | I | I | I | - | - | I | R/A | I | I || Addresses the specific requirements of Core Functionality | - | - | I | - | I | I | I | R/A | I | - | - | I | C | I | I || Ensures consistency with the product vision and domain | - | - | I | - | I | I | I | C | I | - | - | I | I | R/A | I || Incorporates the job statements and market insights | - | - | I | - | I | I | R/A | I | I | - | - | I | I | C | I || Reflects the core activities and value stream | - | - | R/A | - | I | I | C | I | I | - | - | I | I | I | I || Aligns with the semantic context provided above | - | - | I | - | I | I | I | I | I | - | - | I | R/A | I | I || Addresses the specific requirements of Core Functionality | - | - | I | - | I | I | I | R/A | I | - | - | I | C | I | I || Ensures consistency with the product vision and domain | - | - | I | - | I | I | I | C | I | - | - | I | I | R/A | I || Incorporates the job statements and market insights | - | - | I | - | I | I | R/A | I | I | - | - | I | I | C | I || Reflects the core activities and value stream | - | - | R/A | - | I | I | C | I | I | - | - | I | I | I | I || Engage in Practice Conversations | - | I | - | - | I | I | - | I | I | - | - | I | R/A | I | I || Customize Personalized Lesson Plans | - | I | - | - | I | I | - | R/A | I | - | - | I | C | I | I || Receive Pronunciation Feedback | - | I | - | - | I | I | - | C | I | - | - | I | I | R/A | I || Experience Augmented Reality Scenarios | - | R/A | - | - | I | I | - | I | I | - | - | I | I | C | I || Maintain Engagement and Motivation | - | C | - | - | I | I | - | I | R/A | - | - | I | I | I | I || Ensure Learning Accuracy | - | I | - | - | I | R/A | - | I | C | - | - | I | I | I | I |
**Legend:**
- **R** = Responsible (does the work)
- **A** = Accountable (owns the decision)
- **C** = Consulted (provides input)
- **I** = Informed (kept updated)


---

## Business Rules

Automated decision logic extracted from decision tree diagrams.
### BR-001: Business Rule Evaluation

- **Condition**: `Is user proficiency known?`
- **Action**: Route to Provide personalized lesson plans based on user proficiency
- **Automation**: Manual
- **Priority**: P2
- **Source**: bc26ee7c-2824-402a-bfa1-b537de10cff8
### BR-002: Business Rule Evaluation

- **Condition**: `Is user engaging with quizzes?`
- **Action**: Route to Provide personalized lesson plans based on user proficiency
- **Automation**: Manual
- **Priority**: P2
- **Source**: bc26ee7c-2824-402a-bfa1-b537de10cff8
### BR-003: Business Rule Evaluation

- **Condition**: `Is speech recognition enabled?`
- **Action**: Route to Provide personalized lesson plans based on user proficiency
- **Automation**: Manual
- **Priority**: P2
- **Source**: bc26ee7c-2824-402a-bfa1-b537de10cff8
### BR-004: Business Rule Evaluation

- **Condition**: `Is user progress being tracked?`
- **Action**: Route to Provide personalized lesson plans based on user proficiency
- **Automation**: Manual
- **Priority**: P2
- **Source**: bc26ee7c-2824-402a-bfa1-b537de10cff8
### BR-005: Business Rule Evaluation

- **Condition**: `Is cultural content available?`
- **Action**: Route to Provide personalized lesson plans based on user proficiency
- **Automation**: Manual
- **Priority**: P2
- **Source**: bc26ee7c-2824-402a-bfa1-b537de10cff8
---

## Non-Functional Requirements

### Performance Requirements

| ID | Requirement | Source | Verification | Priority |
|----|-------------|--------|--------------|----------|
### Accessibility Requirements

| ID | Requirement | Source | Verification | Priority |
|----|-------------|--------|--------------|----------|| NFR-A11Y-1 | System SHALL comply with WCAG 2.1 compliance requirements | 4b90bd94-4e64-4d85-bc00-ada401bc5e7f:accessibility_needs | WCAG audit for WCAG 2.1 compliance | P0 || NFR-A11Y-2 | System SHALL comply with Screen reader support requirements | 4b90bd94-4e64-4d85-bc00-ada401bc5e7f:accessibility_needs | WCAG audit for Screen reader support | P0 || NFR-A11Y-3 | System SHALL comply with Keyboard navigation requirements | 4b90bd94-4e64-4d85-bc00-ada401bc5e7f:accessibility_needs | WCAG audit for Keyboard navigation | P0 |
### Automation Requirements

| ID | Requirement | Source | Verification | Priority |
|----|-------------|--------|--------------|----------|| NFR-AUTO-1 | system SHALL be Automated | 658e89a0-d3a8-4a0c-8c9c-0a5fc42a640d:automation_hints | Verify automated implementation for system | P1 || NFR-AUTO-2 | enterprise SHALL be Automated | 658e89a0-d3a8-4a0c-8c9c-0a5fc42a640d:automation_hints | Verify automated implementation for enterprise | P1 || NFR-AUTO-3 | person SHALL be Manual | 658e89a0-d3a8-4a0c-8c9c-0a5fc42a640d:automation_hints | Verify manual implementation for person | P2 || NFR-AUTO-4 | system SHALL be Automated | bc26ee7c-2824-402a-bfa1-b537de10cff8:automation_hints | Verify automated implementation for system | P1 || NFR-AUTO-5 | person SHALL be Manual | bc26ee7c-2824-402a-bfa1-b537de10cff8:automation_hints | Verify manual implementation for person | P2 || NFR-AUTO-6 | system SHALL be Automated | 86064b0d-e35d-467b-8a4d-f5bf6c690353:automation_hints | Verify automated implementation for system | P1 || NFR-AUTO-7 | person SHALL be Manual | 86064b0d-e35d-467b-8a4d-f5bf6c690353:automation_hints | Verify manual implementation for person | P2 || NFR-AUTO-8 | system SHALL be Automated | 3c9566f6-bd45-4887-a7a6-c380d8106600:automation_hints | Verify automated implementation for system | P1 || NFR-AUTO-9 | learns through SHALL be Manual | 3c9566f6-bd45-4887-a7a6-c380d8106600:automation_hints | Verify manual implementation for learns through | P2 |

---

## Quality Metrics

| Metric | Value | Source |
|--------|-------|--------|
| Diagrams Analyzed | 5 | MAS Compiler |
| RACI Entries | 21 | business_analysis |
| Business Rules | 5 | decision_tree |
| NFRs Generated | 12 | ux/business_analysis |
| EARS Requirements | 92 | metadata mapping |

---

*Generated by MAS Compiler Knowledge Spec Generator*