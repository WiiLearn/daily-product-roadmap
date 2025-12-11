# Knowledge Document: Mindwell Ai Mvp1

> **Generated**: 2025-12-11 10:50:58  
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
    - "Progress tracking dashboard"
    - "Under Review"
  entities:
    - "Approval Required?"
    - "Approved"
    - "Care"
    - "Caregiver"
    - "Complete"
    - "Coordination"
    - "Core"
    - "Core Care Coordination"
    - "Mood"
    - "Mood tracking interface"
    - "Nurse"
    - "PAIN"
    - "POINT"
    - "Patient"
    - "Personalized"
    - "Personalized therapy session generator"
    - "Physician"
    - "Rejected"
    - "Specialist"
    - "Therapist directory with profiles"
---

---

## Overview

This document captures the domain knowledge extracted from MAS artifacts for **Mindwell Ai Mvp1**.

Core Care Coordination: Foundation for patient-provider coordination. I want to build a mental health therapy platform called MindWell AI that provides personalized cognitive behavioral therapy sessions, mood tracking, and connects users with licensed therapists for vir

---

## RACI Matrix

Responsibility assignment matrix for process steps.

| Process Step | Approval Required? | Approved | Caregiver | Core Care Coordination | Customer | Mood tracking interface | Nurse | Patient | Persona | Personalized therapy session generator | Physician | Progress tracking dashboard | Rejected | Specialist | System | Therapist directory with profiles | Under Review | Verification Complete? | Virtual consultation booking system | access | feature | medication | protocol | support | therapy | ticket | treatment ||--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|| Caregiver Personalized therapy session generator | - | - | R/A | - | - | - | I | I | - | - | I | - | - | I | - | - | - | - | - | - | - | - | - | - | - | - | - || Physician Mood tracking interface | - | - | C | - | - | - | I | I | - | - | R/A | - | - | I | - | - | - | - | - | - | - | - | - | - | - | - | - || Nurse Therapist directory with profiles | - | - | I | - | - | - | R/A | I | - | - | C | - | - | I | - | - | - | - | - | - | - | - | - | - | - | - | - || Specialist Virtual consultation booking system | - | - | I | - | - | - | C | I | - | - | I | - | - | R/A | - | - | - | - | - | - | - | - | - | - | - | - | - || Patient Progress tracking dashboard | - | - | I | - | - | - | I | R/A | - | - | I | - | - | C | - | - | - | - | - | - | - | - | - | - | - | - | - || action | - | - | - | I | - | - | - | - | - | - | - | - | - | - | - | - | - | - | - | I | I | I | I | R/A | I | I | I || flow: | - | - | - | - | I | I | - | - | R/A | I | - | I | - | - | I | I | - | - | I | - | - | - | - | - | - | - | - || Personalized therapy session generator | I | I | - | - | - | I | - | - | R/A | I | - | I | I | - | I | I | I | I | I | - | - | - | - | - | - | - | - || Mood tracking interface | I | I | - | - | - | R/A | - | - | C | I | - | I | I | - | I | I | I | I | I | - | - | - | - | - | - | - | - || Therapist directory with profiles | I | I | - | - | - | C | - | - | I | I | - | I | I | - | I | R/A | I | I | I | - | - | - | - | - | - | - | - || Virtual consultation booking system | I | I | - | - | - | I | - | - | I | I | - | I | I | - | R/A | C | I | I | I | - | - | - | - | - | - | - | - || Progress tracking dashboard | I | I | - | - | - | I | - | - | I | I | - | R/A | I | - | C | I | I | I | I | - | - | - | - | - | - | - | - |
**Legend:**
- **R** = Responsible (does the work)
- **A** = Accountable (owns the decision)
- **C** = Consulted (provides input)
- **I** = Informed (kept updated)


---

## Business Rules

Automated decision logic extracted from decision tree diagrams.
### BR-001: Business Rule Evaluation

- **Condition**: `Is the treatment protocol standard?`
- **Action**: Route to Grant access to the approved medication therapy
- **Automation**: Manual
- **Priority**: P2
- **Source**: cb37bc53-4b64-4eb9-8758-ce9853df1cb2
### BR-002: Business Rule Evaluation

- **Condition**: `Is the therapy medication approved?`
- **Action**: Route to Grant access to the approved medication therapy
- **Automation**: Manual
- **Priority**: P2
- **Source**: cb37bc53-4b64-4eb9-8758-ce9853df1cb2
### BR-003: Business Rule Evaluation

- **Condition**: `Is additional support required?`
- **Action**: Route to Grant access to the approved medication therapy
- **Automation**: Manual
- **Priority**: P2
- **Source**: cb37bc53-4b64-4eb9-8758-ce9853df1cb2
---

## Non-Functional Requirements

### Performance Requirements

| ID | Requirement | Source | Verification | Priority |
|----|-------------|--------|--------------|----------|| NFR-PERF-1 | System SHALL complete task within 4 hours | 6fc21313-eddc-4012-8248-4c9483a0167e:slas | Measure response time for task operation | P1 || NFR-PERF-2 | System SHALL complete task within 6 hours | 6fc21313-eddc-4012-8248-4c9483a0167e:slas | Measure response time for task operation | P1 || NFR-PERF-3 | System SHALL complete task within 8 hours | 6fc21313-eddc-4012-8248-4c9483a0167e:slas | Measure response time for task operation | P1 |
### Accessibility Requirements

| ID | Requirement | Source | Verification | Priority |
|----|-------------|--------|--------------|----------|| NFR-A11Y-1 | System SHALL comply with WCAG 2.1 compliance requirements | ae79cc79-e028-42e9-9bb8-2713e41010f3:accessibility_needs | WCAG audit for WCAG 2.1 compliance | P0 || NFR-A11Y-2 | System SHALL comply with Screen reader support requirements | ae79cc79-e028-42e9-9bb8-2713e41010f3:accessibility_needs | WCAG audit for Screen reader support | P0 || NFR-A11Y-3 | System SHALL comply with Keyboard navigation requirements | ae79cc79-e028-42e9-9bb8-2713e41010f3:accessibility_needs | WCAG audit for Keyboard navigation | P0 |
### Automation Requirements

| ID | Requirement | Source | Verification | Priority |
|----|-------------|--------|--------------|----------|| NFR-AUTO-1 | consultation booking SHALL be Automated | 6fc21313-eddc-4012-8248-4c9483a0167e:automation_hints | Verify automated implementation for consultation booking | P1 || NFR-AUTO-2 | api SHALL be Automated | 6fc21313-eddc-4012-8248-4c9483a0167e:automation_hints | Verify automated implementation for api | P1 || NFR-AUTO-3 | caregiver SHALL be Manual | 6fc21313-eddc-4012-8248-4c9483a0167e:automation_hints | Verify manual implementation for caregiver | P2 || NFR-AUTO-4 | consultation booking SHALL be Automated | 6caa4019-f9e3-4996-8e4b-9ce3ff51c633:automation_hints | Verify automated implementation for consultation booking | P1 || NFR-AUTO-5 | api SHALL be Automated | 6caa4019-f9e3-4996-8e4b-9ce3ff51c633:automation_hints | Verify automated implementation for api | P1 || NFR-AUTO-6 | manual SHALL be Manual | 6caa4019-f9e3-4996-8e4b-9ce3ff51c633:automation_hints | Verify manual implementation for manual | P2 || NFR-AUTO-7 | person SHALL be Manual | 6caa4019-f9e3-4996-8e4b-9ce3ff51c633:automation_hints | Verify manual implementation for person | P2 || NFR-AUTO-8 | automated SHALL be Automated | 2781b40a-5faa-41bf-9983-4115c056fcb4:automation_hints | Verify automated implementation for automated | P1 || NFR-AUTO-9 | coordination workflow SHALL be Automated | 2781b40a-5faa-41bf-9983-4115c056fcb4:automation_hints | Verify automated implementation for coordination workflow | P1 || NFR-AUTO-10 | consultation booking SHALL be Automated | 2781b40a-5faa-41bf-9983-4115c056fcb4:automation_hints | Verify automated implementation for consultation booking | P1 || NFR-AUTO-11 | api SHALL be Automated | 2781b40a-5faa-41bf-9983-4115c056fcb4:automation_hints | Verify automated implementation for api | P1 || NFR-AUTO-12 | manual SHALL be Manual | 2781b40a-5faa-41bf-9983-4115c056fcb4:automation_hints | Verify manual implementation for manual | P2 || NFR-AUTO-13 | person SHALL be Manual | 2781b40a-5faa-41bf-9983-4115c056fcb4:automation_hints | Verify manual implementation for person | P2 |

---

## Quality Metrics

| Metric | Value | Source |
|--------|-------|--------|
| Diagrams Analyzed | 5 | MAS Compiler |
| RACI Entries | 12 | business_analysis |
| Business Rules | 3 | decision_tree |
| NFRs Generated | 19 | ux/business_analysis |
| EARS Requirements | 75 | metadata mapping |

---

*Generated by MAS Compiler Knowledge Spec Generator*