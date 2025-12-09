# Knowledge Document: Wealthpilot Mvp1

> **Generated**: 2025-12-10 12:46:30  
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
    - "Dynamic portfolio tracking dashboard"
    - "Investment Platform"
  entities:
    - "Addresses"
    - "Aligns"
    - "Comprehensive asset search tool"
    - "Core Financial Management"
    - "Ensures"
    - "Financial Insights"
    - "Incorporates"
    - "Investment Profile"
    - "Investment Recommendations"
    - "MVP1"
    - "Market Trends"
    - "Market performance visualization"
    - "Portfolio Management"
    - "Portfolio Rebalancing"
    - "Reflects"
    - "Risk tolerance assessment questionnaire"
    - "User-friendly investment goal setup"
    - "WealthPilot"
---

---

## Overview

This document captures the domain knowledge extracted from MAS artifacts for **Wealthpilot Mvp1**.

Core Financial Management: Basic accounts, transactions, and reporting. I want to build a personal investment platform called WealthPilot that uses AI to analyze market trends, provides automated portfolio rebalancing, and offers personalized investment recommendations ba

---

## RACI Matrix

Responsibility assignment matrix for process steps.

| Process Step | Comprehensive asset search tool | Core Financial Management | Dynamic portfolio tracking dashboard | Financial Insights | Investment Platform | Investment Profile | Investment Recommendations | Market performance visualization | Persona | Portfolio Management | Risk tolerance assessment questionnaire | System | User | User-friendly investment goal setup | WealthPilot | finance ||--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|--------------|| Aligns with the semantic context provided above | - | - | - | - | I | - | - | - | - | - | - | - | R/A | - | - | - || Addresses the specific requirements of Core Financial Management | - | - | - | - | R/A | - | - | - | - | - | - | - | C | - | - | - || Ensures consistency with the product vision and domain | - | - | - | - | C | - | - | - | - | - | - | - | R/A | - | - | - || Incorporates the job statements and market insights | - | - | - | - | R/A | - | - | - | - | - | - | - | C | - | - | - || Reflects the core activities and value stream | - | - | - | - | C | - | - | - | - | - | - | - | R/A | - | - | - || Aligns with the semantic context provided above | I | I | I | - | - | - | - | I | I | - | I | R/A | I | I | I | I || Addresses the specific requirements of Core Financial Management | I | R/A | I | - | - | - | - | I | I | - | I | C | I | I | I | I || Ensures consistency with the product vision and domain | I | C | I | - | - | - | - | I | I | - | I | I | I | I | I | R/A || Incorporates the job statements and market insights | I | I | I | - | - | - | - | I | I | - | I | I | R/A | I | I | C || Reflects the core activities and value stream | I | I | I | - | - | - | - | I | I | - | I | I | C | I | R/A | I || Aligns with the semantic context provided above | I | I | I | - | - | - | - | I | I | - | I | R/A | I | I | I | I || Addresses the specific requirements of Core Financial Management | I | R/A | I | - | - | - | - | I | I | - | I | C | I | I | I | I || Ensures consistency with the product vision and domain | I | C | I | - | - | - | - | I | I | - | I | I | I | I | I | R/A || Incorporates the job statements and market insights | I | I | I | - | - | - | - | I | I | - | I | I | R/A | I | I | C || Reflects the core activities and value stream | I | I | I | - | - | - | - | I | I | - | I | I | C | I | R/A | I || Create Investment Profile | - | - | - | I | - | R/A | I | - | I | I | - | I | I | - | - | I || Set Goals and Risk Tolerance | - | - | - | I | - | C | I | - | R/A | I | - | I | I | - | - | I || Receive Investment Recommendations | - | - | - | I | - | I | R/A | - | C | I | - | I | I | - | - | I || Automate Portfolio Management | - | - | - | I | - | I | C | - | I | R/A | - | I | I | - | - | I || Monitor Financial Insights | - | - | - | R/A | - | I | I | - | I | C | - | I | I | - | - | I |
**Legend:**
- **R** = Responsible (does the work)
- **A** = Accountable (owns the decision)
- **C** = Consulted (provides input)
- **I** = Informed (kept updated)


---

## Business Rules

Automated decision logic extracted from decision tree diagrams.
### BR-001: Business Rule Evaluation

- **Condition**: `Is the user looking for a comprehensive asset search tool?`
- **Action**: Route to Provide comprehensive asset search tool
- **Automation**: Manual
- **Priority**: P2
- **Source**: 139eec69-b7e0-4bd1-84ee-2ecdda261942
### BR-002: Business Rule Evaluation

- **Condition**: `Does the user want to set up investment goals easily?`
- **Action**: Route to Provide comprehensive asset search tool
- **Automation**: Manual
- **Priority**: P2
- **Source**: 139eec69-b7e0-4bd1-84ee-2ecdda261942
### BR-003: Business Rule Evaluation

- **Condition**: `Is the user interested in assessing their risk tolerance?`
- **Action**: Route to Provide comprehensive asset search tool
- **Automation**: Manual
- **Priority**: P2
- **Source**: 139eec69-b7e0-4bd1-84ee-2ecdda261942
### BR-004: Business Rule Evaluation

- **Condition**: `Does the user require dynamic portfolio tracking?`
- **Action**: Route to Provide comprehensive asset search tool
- **Automation**: Manual
- **Priority**: P2
- **Source**: 139eec69-b7e0-4bd1-84ee-2ecdda261942
---

## Non-Functional Requirements

### Performance Requirements

| ID | Requirement | Source | Verification | Priority |
|----|-------------|--------|--------------|----------|
### Accessibility Requirements

| ID | Requirement | Source | Verification | Priority |
|----|-------------|--------|--------------|----------|| NFR-A11Y-1 | System SHALL comply with WCAG 2.1 compliance requirements | 04d543ff-8faf-4895-8fa4-cc43510a222d:accessibility_needs | WCAG audit for WCAG 2.1 compliance | P0 || NFR-A11Y-2 | System SHALL comply with Screen reader support requirements | 04d543ff-8faf-4895-8fa4-cc43510a222d:accessibility_needs | WCAG audit for Screen reader support | P0 || NFR-A11Y-3 | System SHALL comply with Keyboard navigation requirements | 04d543ff-8faf-4895-8fa4-cc43510a222d:accessibility_needs | WCAG audit for Keyboard navigation | P0 |
### Automation Requirements

| ID | Requirement | Source | Verification | Priority |
|----|-------------|--------|--------------|----------|| NFR-AUTO-1 | provides SHALL be Automated | 8988c8aa-f1ef-4672-b604-d466c22da257:automation_hints | Verify automated implementation for provides | P1 || NFR-AUTO-2 | system SHALL be Automated | 8988c8aa-f1ef-4672-b604-d466c22da257:automation_hints | Verify automated implementation for system | P1 || NFR-AUTO-3 | enterprise SHALL be Automated | 8988c8aa-f1ef-4672-b604-d466c22da257:automation_hints | Verify automated implementation for enterprise | P1 || NFR-AUTO-4 | build a SHALL be Manual | 8988c8aa-f1ef-4672-b604-d466c22da257:automation_hints | Verify manual implementation for build a | P2 || NFR-AUTO-5 | and offers SHALL be Manual | 8988c8aa-f1ef-4672-b604-d466c22da257:automation_hints | Verify manual implementation for and offers | P2 || NFR-AUTO-6 | provides SHALL be Automated | 139eec69-b7e0-4bd1-84ee-2ecdda261942:automation_hints | Verify automated implementation for provides | P1 || NFR-AUTO-7 | system SHALL be Automated | 139eec69-b7e0-4bd1-84ee-2ecdda261942:automation_hints | Verify automated implementation for system | P1 || NFR-AUTO-8 | build a SHALL be Manual | 139eec69-b7e0-4bd1-84ee-2ecdda261942:automation_hints | Verify manual implementation for build a | P2 || NFR-AUTO-9 | and offers SHALL be Manual | 139eec69-b7e0-4bd1-84ee-2ecdda261942:automation_hints | Verify manual implementation for and offers | P2 || NFR-AUTO-10 | provides SHALL be Automated | 37884f86-0ea1-4958-b646-8940eeadfa56:automation_hints | Verify automated implementation for provides | P1 || NFR-AUTO-11 | system SHALL be Automated | 37884f86-0ea1-4958-b646-8940eeadfa56:automation_hints | Verify automated implementation for system | P1 || NFR-AUTO-12 | build a SHALL be Manual | 37884f86-0ea1-4958-b646-8940eeadfa56:automation_hints | Verify manual implementation for build a | P2 || NFR-AUTO-13 | and offers SHALL be Manual | 37884f86-0ea1-4958-b646-8940eeadfa56:automation_hints | Verify manual implementation for and offers | P2 || NFR-AUTO-14 | provides SHALL be Automated | 9d6030a7-c7e7-46ec-a2cd-3fff1f7b65c2:automation_hints | Verify automated implementation for provides | P1 || NFR-AUTO-15 | portfolio SHALL be Automated | 9d6030a7-c7e7-46ec-a2cd-3fff1f7b65c2:automation_hints | Verify automated implementation for portfolio | P1 || NFR-AUTO-16 | investment portfolio SHALL be Automated | 9d6030a7-c7e7-46ec-a2cd-3fff1f7b65c2:automation_hints | Verify automated implementation for investment portfolio | P1 || NFR-AUTO-17 | system SHALL be Automated | 9d6030a7-c7e7-46ec-a2cd-3fff1f7b65c2:automation_hints | Verify automated implementation for system | P1 || NFR-AUTO-18 | level without SHALL be Manual | 9d6030a7-c7e7-46ec-a2cd-3fff1f7b65c2:automation_hints | Verify manual implementation for level without | P2 || NFR-AUTO-19 | build a SHALL be Manual | 9d6030a7-c7e7-46ec-a2cd-3fff1f7b65c2:automation_hints | Verify manual implementation for build a | P2 || NFR-AUTO-20 | and offers SHALL be Manual | 9d6030a7-c7e7-46ec-a2cd-3fff1f7b65c2:automation_hints | Verify manual implementation for and offers | P2 || NFR-AUTO-21 | users receive SHALL be Manual | 9d6030a7-c7e7-46ec-a2cd-3fff1f7b65c2:automation_hints | Verify manual implementation for users receive | P2 |

---

## Quality Metrics

| Metric | Value | Source |
|--------|-------|--------|
| Diagrams Analyzed | 5 | MAS Compiler |
| RACI Entries | 20 | business_analysis |
| Business Rules | 4 | decision_tree |
| NFRs Generated | 24 | ux/business_analysis |
| EARS Requirements | 94 | metadata mapping |

---

*Generated by MAS Compiler Knowledge Spec Generator*