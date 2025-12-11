# Domain Glossary: Propertyiq Mvp1

> **Generated**: 2025-12-11 11:51:02  
> **Version**: 1.0.0

---

## Overview

Domain terminology extracted from MAS artifacts for **Propertyiq Mvp1**.

| Term | Type | Definition | Source |
|------|------|------------|--------|
| Property_investment_search_engine | plan | A pricing tier in PropertyIQ-mvp1 offering specific features and capabilities for target users with ROI projection calculator, Neighborhood growth trend analysis | value_stream |
| Approval_Required? | plan | A pricing tier in PropertyIQ-mvp1 offering specific features and capabilities for target users with Verification Complete?, Property investment search engine | business_process |
| Hr | default | A key element in the PropertyIQ-mvp1 system related to system operations | unknown |
| POINT | phase | A stage in the user journey where users point and progress through the journey with PAIN, Customer | user_journey |
| Under_Review | step | A process step that under review as part of the workflow with Verification Complete?, Approval Required? in the workflow | business_process |
| Account_Manager | role | A stakeholder role in the PropertyIQ-mvp1 system responsible for workflow activities and decision-making with Customer, Compliance Officer | swimlane |
| touchpoints | phase | A stage in the user journey where users touchpoints and progress through the journey with PAIN, POINT | user_journey |
| calculator | phase | A stage in the user journey where users calculator and progress through the journey with PAIN, POINT | user_journey |
| search | phase | A stage in the user journey where users search and progress through the journey with PAIN, POINT | user_journey |
| Verification_Complete? | step | A process step that verification complete? as part of the workflow with Approval Required?, Property investment search engine in the workflow | business_process |
| Property | plan | A pricing tier in PropertyIQ-mvp1 offering specific features and capabilities for target users with PAIN, POINT | user_journey |
| Compliance_Officer | role | A stakeholder role in the PropertyIQ-mvp1 system responsible for workflow activities and decision-making with Customer, Account Manager | swimlane |
| Automated_due_diligence_checklist | condition | A decision point that evaluates criteria to determine the appropriate outcome with Property investment search engine, ROI projection calculator | value_stream |
| PAIN | phase | A stage in the user journey where users pain and progress through the journey with POINT, Customer | user_journey |
| HIGH | condition | A decision point that evaluates criteria to determine the appropriate outcome with Core Financial Management, Standard threshold | decision_tree |
| Core | phase | A stage in the user journey where users core and progress through the journey with PAIN, POINT | user_journey |
| support | team | A functional team responsible for specialized tasks and deliverables in the workflow | unknown |
| Management | phase | A stage in the user journey where users management and progress through the journey with PAIN, POINT | user_journey |
| investment | phase | A stage in the user journey where users investment and progress through the journey with PAIN, POINT | user_journey |
| ROI_projection_calculator | plan | A pricing tier in PropertyIQ-mvp1 offering specific features and capabilities for target users with Property investment search engine, Neighborhood growth trend analysis | value_stream |
| MEDIUM | condition | A decision point that evaluates criteria to determine the appropriate outcome with Core Financial Management, Standard threshold | decision_tree |
| Core_Financial_Management | condition | A decision point that evaluates criteria to determine the appropriate outcome with Standard threshold, LOW | decision_tree |
| Approved | plan | A pricing tier in PropertyIQ-mvp1 offering specific features and capabilities for target users with Verification Complete?, Approval Required? | business_process |
| Investor | default | A key element in the PropertyIQ-mvp1 system related to system operations | unknown |
| Analyst | role | A stakeholder role in the PropertyIQ-mvp1 system responsible for workflow activities and decision-making with Customer, Account Manager | swimlane |
| projection | plan | A pricing tier in PropertyIQ-mvp1 offering specific features and capabilities for target users with PAIN, POINT | user_journey |
| Standard_threshold | condition | A decision point that evaluates criteria to determine the appropriate outcome with Core Financial Management, LOW | decision_tree |
| LOW | condition | A decision point that evaluates criteria to determine the appropriate outcome with Core Financial Management, Standard threshold | decision_tree |
| score | condition | A decision point that evaluates criteria to determine the appropriate outcome with PAIN, POINT | user_journey |
| Advisor | agent | An AI agent that provides guidance and assistance with Customer, Account Manager for users | swimlane |
| Compliance | default | A key element in the PropertyIQ-mvp1 system related to system operations | unknown |
| CRITICAL | condition | A decision point that evaluates criteria to determine the appropriate outcome with Core Financial Management, Standard threshold | decision_tree |
| Rejected | step | A process step that rejected as part of the workflow with Verification Complete?, Approval Required? in the workflow | business_process |
| engine | phase | A stage in the user journey where users engine and progress through the journey with PAIN, POINT | user_journey |
| Neighborhood_growth_trend_analysis | step | A process step that neighborhood growth trend analysis as part of the workflow with Property investment search engine, ROI projection calculator in the workflow | value_stream |
| emotional | phase | A stage in the user journey where users emotional and progress through the journey with PAIN, POINT | user_journey |
| User-generated_property_review_system | role | A stakeholder role in the PropertyIQ-mvp1 system responsible for workflow activities and decision-making with Property investment search engine, ROI projection calculator | value_stream |
| Complete | step | A process step that complete as part of the workflow with PAIN, POINT in the workflow | user_journey |
| System | default | A key element in the PropertyIQ-mvp1 system related to system operations | unknown |
| Financial | phase | A stage in the user journey where users financial and progress through the journey with PAIN, POINT | user_journey |
| Customer | role | A stakeholder role in the PropertyIQ-mvp1 system responsible for workflow activities and decision-making with PAIN, POINT | user_journey |
| User | role | A stakeholder role in the PropertyIQ-mvp1 system responsible for workflow activities and decision-making | unknown |

---

## Entity Types


### plan

- **Property_investment_search_engine**: A pricing tier in PropertyIQ-mvp1 offering specific features and capabilities for target users with ROI projection calculator, Neighborhood growth trend analysis
- **Approval_Required?**: A pricing tier in PropertyIQ-mvp1 offering specific features and capabilities for target users with Verification Complete?, Property investment search engine
- **Property**: A pricing tier in PropertyIQ-mvp1 offering specific features and capabilities for target users with PAIN, POINT
- **ROI_projection_calculator**: A pricing tier in PropertyIQ-mvp1 offering specific features and capabilities for target users with Property investment search engine, Neighborhood growth trend analysis
- **Approved**: A pricing tier in PropertyIQ-mvp1 offering specific features and capabilities for target users with Verification Complete?, Approval Required?
- **projection**: A pricing tier in PropertyIQ-mvp1 offering specific features and capabilities for target users with PAIN, POINT


### default

- **Hr**: A key element in the PropertyIQ-mvp1 system related to system operations
- **Investor**: A key element in the PropertyIQ-mvp1 system related to system operations
- **Compliance**: A key element in the PropertyIQ-mvp1 system related to system operations
- **System**: A key element in the PropertyIQ-mvp1 system related to system operations


### phase

- **POINT**: A stage in the user journey where users point and progress through the journey with PAIN, Customer
- **touchpoints**: A stage in the user journey where users touchpoints and progress through the journey with PAIN, POINT
- **calculator**: A stage in the user journey where users calculator and progress through the journey with PAIN, POINT
- **search**: A stage in the user journey where users search and progress through the journey with PAIN, POINT
- **PAIN**: A stage in the user journey where users pain and progress through the journey with POINT, Customer
- **Core**: A stage in the user journey where users core and progress through the journey with PAIN, POINT
- **Management**: A stage in the user journey where users management and progress through the journey with PAIN, POINT
- **investment**: A stage in the user journey where users investment and progress through the journey with PAIN, POINT
- **engine**: A stage in the user journey where users engine and progress through the journey with PAIN, POINT
- **emotional**: A stage in the user journey where users emotional and progress through the journey with PAIN, POINT
- **Financial**: A stage in the user journey where users financial and progress through the journey with PAIN, POINT


### step

- **Under_Review**: A process step that under review as part of the workflow with Verification Complete?, Approval Required? in the workflow
- **Verification_Complete?**: A process step that verification complete? as part of the workflow with Approval Required?, Property investment search engine in the workflow
- **Rejected**: A process step that rejected as part of the workflow with Verification Complete?, Approval Required? in the workflow
- **Neighborhood_growth_trend_analysis**: A process step that neighborhood growth trend analysis as part of the workflow with Property investment search engine, ROI projection calculator in the workflow
- **Complete**: A process step that complete as part of the workflow with PAIN, POINT in the workflow


### role

- **Account_Manager**: A stakeholder role in the PropertyIQ-mvp1 system responsible for workflow activities and decision-making with Customer, Compliance Officer
- **Compliance_Officer**: A stakeholder role in the PropertyIQ-mvp1 system responsible for workflow activities and decision-making with Customer, Account Manager
- **Analyst**: A stakeholder role in the PropertyIQ-mvp1 system responsible for workflow activities and decision-making with Customer, Account Manager
- **User-generated_property_review_system**: A stakeholder role in the PropertyIQ-mvp1 system responsible for workflow activities and decision-making with Property investment search engine, ROI projection calculator
- **Customer**: A stakeholder role in the PropertyIQ-mvp1 system responsible for workflow activities and decision-making with PAIN, POINT
- **User**: A stakeholder role in the PropertyIQ-mvp1 system responsible for workflow activities and decision-making


### condition

- **Automated_due_diligence_checklist**: A decision point that evaluates criteria to determine the appropriate outcome with Property investment search engine, ROI projection calculator
- **HIGH**: A decision point that evaluates criteria to determine the appropriate outcome with Core Financial Management, Standard threshold
- **MEDIUM**: A decision point that evaluates criteria to determine the appropriate outcome with Core Financial Management, Standard threshold
- **Core_Financial_Management**: A decision point that evaluates criteria to determine the appropriate outcome with Standard threshold, LOW
- **Standard_threshold**: A decision point that evaluates criteria to determine the appropriate outcome with Core Financial Management, LOW
- **LOW**: A decision point that evaluates criteria to determine the appropriate outcome with Core Financial Management, Standard threshold
- **score**: A decision point that evaluates criteria to determine the appropriate outcome with PAIN, POINT
- **CRITICAL**: A decision point that evaluates criteria to determine the appropriate outcome with Core Financial Management, Standard threshold


### team

- **support**: A functional team responsible for specialized tasks and deliverables in the workflow


### agent

- **Advisor**: An AI agent that provides guidance and assistance with Customer, Account Manager for users


---

## Source References

| Source Diagram | Entities Count |
|----------------|----------------|
| user_journey | 16 |
| swimlane | 5 |
| decision_tree | 6 |
| value_stream | 5 |
| business_process | 10 |

---

*Generated by MAS Compiler Glossary Generator*