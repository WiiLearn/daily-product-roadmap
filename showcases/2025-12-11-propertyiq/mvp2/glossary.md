# Domain Glossary: Propertyiq Mvp2

> **Generated**: 2025-12-11 11:51:35  
> **Version**: 1.0.0

---

## Overview

Domain terminology extracted from MAS artifacts for **Propertyiq Mvp2**.

| Term | Type | Definition | Source |
|------|------|------------|--------|
| Approval_Required? | plan | A pricing tier in PropertyIQ-mvp2 offering specific features and capabilities for target users with Verification Complete?, Neighborhood growth prediction | business_process |
| MVP1_property_data | plan | A pricing tier in PropertyIQ-mvp2 offering specific features and capabilities for target users with Customer, Account Manager | swimlane |
| Hr | default | A key element in the PropertyIQ-mvp2 system related to system operations | unknown |
| POINT | phase | A stage in the user journey where users point and progress through the journey with USING, MVP1 | user_journey |
| Under_Review | step | A process step that under review as part of the workflow with Verification Complete?, Approval Required? in the workflow | business_process |
| Account_Manager | role | A stakeholder role in the PropertyIQ-mvp2 system responsible for workflow activities and decision-making with Customer, Compliance Officer | swimlane |
| MVP1_user_reviews | role | A stakeholder role in the PropertyIQ-mvp2 system responsible for workflow activities and decision-making with Customer, Account Manager | swimlane |
| Compliance_Officer | role | A stakeholder role in the PropertyIQ-mvp2 system responsible for workflow activities and decision-making with Customer, Account Manager | swimlane |
| Neighborhood_growth_prediction | step | A process step that neighborhood growth prediction as part of the workflow with Enhanced ROI projection analytics, Machine learning-based risk assessment system in the workflow | value_stream |
| USING | phase | A stage in the user journey where users using and progress through the journey with MVP1, BUILDING | user_journey |
| Machine_learning-based_risk_assessment_system | condition | A decision point that evaluates criteria to determine the appropriate outcome with Neighborhood growth prediction, Enhanced ROI projection analytics | value_stream |
| PAIN | phase | A stage in the user journey where users pain and progress through the journey with USING, MVP1 | user_journey |
| Smart_Financial_Analytics | condition | A decision point that evaluates criteria to determine the appropriate outcome with Standard threshold, LOW | decision_tree |
| Neighborhood_growth_prediction_USING_MVP1_neighborhood_data | default | A key element in the PropertyIQ-mvp2 system related to system operations | unknown |
| HIGH | condition | A decision point that evaluates criteria to determine the appropriate outcome with Smart Financial Analytics, Standard threshold | decision_tree |
| support | team | A functional team responsible for specialized tasks and deliverables in the workflow | unknown |
| MEDIUM | condition | A decision point that evaluates criteria to determine the appropriate outcome with Smart Financial Analytics, Standard threshold | decision_tree |
| Approved | plan | A pricing tier in PropertyIQ-mvp2 offering specific features and capabilities for target users with Verification Complete?, Approval Required? | business_process |
| Automated_due_diligence_insights_BUILDING_ON_MVP1_checklist | condition | A decision point that evaluates criteria to determine the appropriate outcome | unknown |
| MVP1_neighborhood_data | role | A stakeholder role in the PropertyIQ-mvp2 system responsible for workflow activities and decision-making with Customer, Account Manager | swimlane |
| Enhanced_ROI_projection_analytics_BUILDING_ON_MVP1_ROI_calculator | plan | A pricing tier in PropertyIQ-mvp2 offering specific features and capabilities for target users | unknown |
| Standard_threshold | condition | A decision point that evaluates criteria to determine the appropriate outcome with Smart Financial Analytics, LOW | decision_tree |
| LOW | condition | A decision point that evaluates criteria to determine the appropriate outcome with Smart Financial Analytics, Standard threshold | decision_tree |
| Automated_due_diligence_insights | step | A process step that automated due diligence insights as part of the workflow with Neighborhood growth prediction, Enhanced ROI projection analytics in the workflow | value_stream |
| Advisor | agent | An AI agent that provides guidance and assistance with Customer, Account Manager for users | swimlane |
| Persona | default | A key element in the PropertyIQ-mvp2 system related to system operations | unknown |
| Machine_learning-based_risk_assessment_system_USING_MVP1_property_data | plan | A pricing tier in PropertyIQ-mvp2 offering specific features and capabilities for target users | unknown |
| Compliance | default | A key element in the PropertyIQ-mvp2 system related to system operations | unknown |
| CRITICAL | condition | A decision point that evaluates criteria to determine the appropriate outcome with Smart Financial Analytics, Standard threshold | decision_tree |
| Rejected | step | A process step that rejected as part of the workflow with Verification Complete?, Approval Required? in the workflow | business_process |
| MVP1_ROI_calculator | role | A stakeholder role in the PropertyIQ-mvp2 system responsible for workflow activities and decision-making with Customer, Account Manager | swimlane |
| BUILDING | phase | A stage in the user journey where users building and progress through the journey with USING, MVP1 | user_journey |
| User_behavior_analytics_for_personalized_recommendations_USING_MVP1_user_reviews | role | A stakeholder role in the PropertyIQ-mvp2 system responsible for workflow activities and decision-making | unknown |
| MVP1 | phase | A stage in the user journey where users mvp1 and progress through the journey with USING, BUILDING | user_journey |
| Enhanced_ROI_projection_analytics | plan | A pricing tier in PropertyIQ-mvp2 offering specific features and capabilities for target users with Neighborhood growth prediction, Machine learning-based risk assessment system | value_stream |
| MVP1_checklist | condition | A decision point that evaluates criteria to determine the appropriate outcome with Customer, Account Manager | swimlane |
| Analyst | role | A stakeholder role in the PropertyIQ-mvp2 system responsible for workflow activities and decision-making with Customer, Account Manager | swimlane |
| System | default | A key element in the PropertyIQ-mvp2 system related to system operations | unknown |
| Verification_Complete? | step | A process step that verification complete? as part of the workflow with Approval Required?, Neighborhood growth prediction in the workflow | business_process |
| Customer | role | A stakeholder role in the PropertyIQ-mvp2 system responsible for workflow activities and decision-making with Account Manager, Compliance Officer | swimlane |
| User | role | A stakeholder role in the PropertyIQ-mvp2 system responsible for workflow activities and decision-making | unknown |

---

## Entity Types


### plan

- **Approval_Required?**: A pricing tier in PropertyIQ-mvp2 offering specific features and capabilities for target users with Verification Complete?, Neighborhood growth prediction
- **MVP1_property_data**: A pricing tier in PropertyIQ-mvp2 offering specific features and capabilities for target users with Customer, Account Manager
- **Approved**: A pricing tier in PropertyIQ-mvp2 offering specific features and capabilities for target users with Verification Complete?, Approval Required?
- **Enhanced_ROI_projection_analytics_BUILDING_ON_MVP1_ROI_calculator**: A pricing tier in PropertyIQ-mvp2 offering specific features and capabilities for target users
- **Machine_learning-based_risk_assessment_system_USING_MVP1_property_data**: A pricing tier in PropertyIQ-mvp2 offering specific features and capabilities for target users
- **Enhanced_ROI_projection_analytics**: A pricing tier in PropertyIQ-mvp2 offering specific features and capabilities for target users with Neighborhood growth prediction, Machine learning-based risk assessment system


### default

- **Hr**: A key element in the PropertyIQ-mvp2 system related to system operations
- **Neighborhood_growth_prediction_USING_MVP1_neighborhood_data**: A key element in the PropertyIQ-mvp2 system related to system operations
- **Persona**: A key element in the PropertyIQ-mvp2 system related to system operations
- **Compliance**: A key element in the PropertyIQ-mvp2 system related to system operations
- **System**: A key element in the PropertyIQ-mvp2 system related to system operations


### phase

- **POINT**: A stage in the user journey where users point and progress through the journey with USING, MVP1
- **USING**: A stage in the user journey where users using and progress through the journey with MVP1, BUILDING
- **PAIN**: A stage in the user journey where users pain and progress through the journey with USING, MVP1
- **BUILDING**: A stage in the user journey where users building and progress through the journey with USING, MVP1
- **MVP1**: A stage in the user journey where users mvp1 and progress through the journey with USING, BUILDING


### step

- **Under_Review**: A process step that under review as part of the workflow with Verification Complete?, Approval Required? in the workflow
- **Neighborhood_growth_prediction**: A process step that neighborhood growth prediction as part of the workflow with Enhanced ROI projection analytics, Machine learning-based risk assessment system in the workflow
- **Automated_due_diligence_insights**: A process step that automated due diligence insights as part of the workflow with Neighborhood growth prediction, Enhanced ROI projection analytics in the workflow
- **Rejected**: A process step that rejected as part of the workflow with Verification Complete?, Approval Required? in the workflow
- **Verification_Complete?**: A process step that verification complete? as part of the workflow with Approval Required?, Neighborhood growth prediction in the workflow


### role

- **Account_Manager**: A stakeholder role in the PropertyIQ-mvp2 system responsible for workflow activities and decision-making with Customer, Compliance Officer
- **MVP1_user_reviews**: A stakeholder role in the PropertyIQ-mvp2 system responsible for workflow activities and decision-making with Customer, Account Manager
- **Compliance_Officer**: A stakeholder role in the PropertyIQ-mvp2 system responsible for workflow activities and decision-making with Customer, Account Manager
- **MVP1_neighborhood_data**: A stakeholder role in the PropertyIQ-mvp2 system responsible for workflow activities and decision-making with Customer, Account Manager
- **MVP1_ROI_calculator**: A stakeholder role in the PropertyIQ-mvp2 system responsible for workflow activities and decision-making with Customer, Account Manager
- **User_behavior_analytics_for_personalized_recommendations_USING_MVP1_user_reviews**: A stakeholder role in the PropertyIQ-mvp2 system responsible for workflow activities and decision-making
- **Analyst**: A stakeholder role in the PropertyIQ-mvp2 system responsible for workflow activities and decision-making with Customer, Account Manager
- **Customer**: A stakeholder role in the PropertyIQ-mvp2 system responsible for workflow activities and decision-making with Account Manager, Compliance Officer
- **User**: A stakeholder role in the PropertyIQ-mvp2 system responsible for workflow activities and decision-making


### condition

- **Machine_learning-based_risk_assessment_system**: A decision point that evaluates criteria to determine the appropriate outcome with Neighborhood growth prediction, Enhanced ROI projection analytics
- **Smart_Financial_Analytics**: A decision point that evaluates criteria to determine the appropriate outcome with Standard threshold, LOW
- **HIGH**: A decision point that evaluates criteria to determine the appropriate outcome with Smart Financial Analytics, Standard threshold
- **MEDIUM**: A decision point that evaluates criteria to determine the appropriate outcome with Smart Financial Analytics, Standard threshold
- **Automated_due_diligence_insights_BUILDING_ON_MVP1_checklist**: A decision point that evaluates criteria to determine the appropriate outcome
- **Standard_threshold**: A decision point that evaluates criteria to determine the appropriate outcome with Smart Financial Analytics, LOW
- **LOW**: A decision point that evaluates criteria to determine the appropriate outcome with Smart Financial Analytics, Standard threshold
- **CRITICAL**: A decision point that evaluates criteria to determine the appropriate outcome with Smart Financial Analytics, Standard threshold
- **MVP1_checklist**: A decision point that evaluates criteria to determine the appropriate outcome with Customer, Account Manager


### team

- **support**: A functional team responsible for specialized tasks and deliverables in the workflow


### agent

- **Advisor**: An AI agent that provides guidance and assistance with Customer, Account Manager for users


---

## Source References

| Source Diagram | Entities Count |
|----------------|----------------|
| user_journey | 5 |
| swimlane | 10 |
| decision_tree | 6 |
| value_stream | 4 |
| business_process | 9 |

---

*Generated by MAS Compiler Glossary Generator*