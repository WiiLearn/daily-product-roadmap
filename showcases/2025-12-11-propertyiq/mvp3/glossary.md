# Domain Glossary: Propertyiq Mvp3

> **Generated**: 2025-12-11 11:52:07  
> **Version**: 1.0.0

---

## Overview

Domain terminology extracted from MAS artifacts for **Propertyiq Mvp3**.

| Term | Type | Definition | Source |
|------|------|------------|--------|
| Collaboration_platform_for_real_estate_professionals | plan | A pricing tier in PropertyIQ-mvp3 offering specific features and capabilities for target users | unknown |
| Approval_Required? | plan | A pricing tier in PropertyIQ-mvp3 offering specific features and capabilities for target users with Verification Complete?, Approved | business_process |
| Hr | default | A key element in the PropertyIQ-mvp3 system related to system operations | unknown |
| POINT | phase | A stage in the user journey where users point and progress through the journey with ENRICHING, MVP2 | user_journey |
| Under_Review | step | A process step that under review as part of the workflow with Verification Complete?, Approval Required? in the workflow | business_process |
| Account_Manager | role | A stakeholder role in the PropertyIQ-mvp3 system responsible for workflow activities and decision-making with Customer, Compliance Officer | swimlane |
| Compliance_Officer | role | A stakeholder role in the PropertyIQ-mvp3 system responsible for workflow activities and decision-making with Customer, Account Manager | swimlane |
| USING | phase | A stage in the user journey where users using and progress through the journey with ENRICHING, MVP2 | user_journey |
| User | role | A stakeholder role in the PropertyIQ-mvp3 system responsible for workflow activities and decision-making | unknown |
| PAIN | phase | A stage in the user journey where users pain and progress through the journey with ENRICHING, MVP2 | user_journey |
| HIGH | condition | A decision point that evaluates criteria to determine the appropriate outcome with Financial Ecosystem, Standard threshold | decision_tree |
| support | team | A functional team responsible for specialized tasks and deliverables in the workflow | unknown |
| MEDIUM | condition | A decision point that evaluates criteria to determine the appropriate outcome with Financial Ecosystem, Standard threshold | decision_tree |
| Approved | plan | A pricing tier in PropertyIQ-mvp3 offering specific features and capabilities for target users with Verification Complete?, Approval Required? | business_process |
| Standard_threshold | condition | A decision point that evaluates criteria to determine the appropriate outcome with Financial Ecosystem, LOW | decision_tree |
| API_integration_for_real-time_market_data | step | A process step that api integration for real-time market data as part of the workflow with Investment property analytics dashboard in the workflow | value_stream |
| Partnership_with_lenders_providing_real-time_valuation_reports | plan | A pricing tier in PropertyIQ-mvp3 offering specific features and capabilities for target users | unknown |
| Integration_with_real_estate_MLS_for_comprehensive_listings | default | A key element in the PropertyIQ-mvp3 system related to system operations | unknown |
| LOW | condition | A decision point that evaluates criteria to determine the appropriate outcome with Financial Ecosystem, Standard threshold | decision_tree |
| MVP2 | phase | A stage in the user journey where users mvp2 and progress through the journey with ENRICHING, USING | user_journey |
| Advisor | agent | An AI agent that provides guidance and assistance with Customer, Account Manager for users | swimlane |
| Financial_Ecosystem | condition | A decision point that evaluates criteria to determine the appropriate outcome with Standard threshold, LOW | decision_tree |
| Compliance | default | A key element in the PropertyIQ-mvp3 system related to system operations | unknown |
| CRITICAL | condition | A decision point that evaluates criteria to determine the appropriate outcome with Financial Ecosystem, Standard threshold | decision_tree |
| Rejected | step | A process step that rejected as part of the workflow with Verification Complete?, Approval Required? in the workflow | business_process |
| MVP1 | phase | A stage in the user journey where users mvp1 and progress through the journey with ENRICHING, MVP2 | user_journey |
| Investment_property_analytics_dashboard | plan | A pricing tier in PropertyIQ-mvp3 offering specific features and capabilities for target users with API integration for real-time market data | value_stream |
| Analyst | role | A stakeholder role in the PropertyIQ-mvp3 system responsible for workflow activities and decision-making with Customer, Account Manager | swimlane |
| System | default | A key element in the PropertyIQ-mvp3 system related to system operations | unknown |
| Verification_Complete? | step | A process step that verification complete? as part of the workflow with Approval Required?, Approved in the workflow | business_process |
| Customer | role | A stakeholder role in the PropertyIQ-mvp3 system responsible for workflow activities and decision-making with Account Manager, Compliance Officer | swimlane |
| ENRICHING | phase | A stage in the user journey where users enriching and progress through the journey with MVP2, USING | user_journey |

---

## Entity Types


### plan

- **Collaboration_platform_for_real_estate_professionals**: A pricing tier in PropertyIQ-mvp3 offering specific features and capabilities for target users
- **Approval_Required?**: A pricing tier in PropertyIQ-mvp3 offering specific features and capabilities for target users with Verification Complete?, Approved
- **Approved**: A pricing tier in PropertyIQ-mvp3 offering specific features and capabilities for target users with Verification Complete?, Approval Required?
- **Partnership_with_lenders_providing_real-time_valuation_reports**: A pricing tier in PropertyIQ-mvp3 offering specific features and capabilities for target users
- **Investment_property_analytics_dashboard**: A pricing tier in PropertyIQ-mvp3 offering specific features and capabilities for target users with API integration for real-time market data


### default

- **Hr**: A key element in the PropertyIQ-mvp3 system related to system operations
- **Integration_with_real_estate_MLS_for_comprehensive_listings**: A key element in the PropertyIQ-mvp3 system related to system operations
- **Compliance**: A key element in the PropertyIQ-mvp3 system related to system operations
- **System**: A key element in the PropertyIQ-mvp3 system related to system operations


### phase

- **POINT**: A stage in the user journey where users point and progress through the journey with ENRICHING, MVP2
- **USING**: A stage in the user journey where users using and progress through the journey with ENRICHING, MVP2
- **PAIN**: A stage in the user journey where users pain and progress through the journey with ENRICHING, MVP2
- **MVP2**: A stage in the user journey where users mvp2 and progress through the journey with ENRICHING, USING
- **MVP1**: A stage in the user journey where users mvp1 and progress through the journey with ENRICHING, MVP2
- **ENRICHING**: A stage in the user journey where users enriching and progress through the journey with MVP2, USING


### step

- **Under_Review**: A process step that under review as part of the workflow with Verification Complete?, Approval Required? in the workflow
- **API_integration_for_real-time_market_data**: A process step that api integration for real-time market data as part of the workflow with Investment property analytics dashboard in the workflow
- **Rejected**: A process step that rejected as part of the workflow with Verification Complete?, Approval Required? in the workflow
- **Verification_Complete?**: A process step that verification complete? as part of the workflow with Approval Required?, Approved in the workflow


### role

- **Account_Manager**: A stakeholder role in the PropertyIQ-mvp3 system responsible for workflow activities and decision-making with Customer, Compliance Officer
- **Compliance_Officer**: A stakeholder role in the PropertyIQ-mvp3 system responsible for workflow activities and decision-making with Customer, Account Manager
- **User**: A stakeholder role in the PropertyIQ-mvp3 system responsible for workflow activities and decision-making
- **Analyst**: A stakeholder role in the PropertyIQ-mvp3 system responsible for workflow activities and decision-making with Customer, Account Manager
- **Customer**: A stakeholder role in the PropertyIQ-mvp3 system responsible for workflow activities and decision-making with Account Manager, Compliance Officer


### condition

- **HIGH**: A decision point that evaluates criteria to determine the appropriate outcome with Financial Ecosystem, Standard threshold
- **MEDIUM**: A decision point that evaluates criteria to determine the appropriate outcome with Financial Ecosystem, Standard threshold
- **Standard_threshold**: A decision point that evaluates criteria to determine the appropriate outcome with Financial Ecosystem, LOW
- **LOW**: A decision point that evaluates criteria to determine the appropriate outcome with Financial Ecosystem, Standard threshold
- **Financial_Ecosystem**: A decision point that evaluates criteria to determine the appropriate outcome with Standard threshold, LOW
- **CRITICAL**: A decision point that evaluates criteria to determine the appropriate outcome with Financial Ecosystem, Standard threshold


### team

- **support**: A functional team responsible for specialized tasks and deliverables in the workflow


### agent

- **Advisor**: An AI agent that provides guidance and assistance with Customer, Account Manager for users


---

## Source References

| Source Diagram | Entities Count |
|----------------|----------------|
| user_journey | 6 |
| swimlane | 5 |
| decision_tree | 6 |
| value_stream | 2 |
| business_process | 5 |

---

*Generated by MAS Compiler Glossary Generator*