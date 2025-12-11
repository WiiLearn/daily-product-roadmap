# Domain Glossary: Fitcoach Pro Mvp3

> **Generated**: 2025-12-11 11:07:13  
> **Version**: 1.0.0

---

## Overview

Domain terminology extracted from MAS artifacts for **Fitcoach Pro Mvp3**.

| Term | Type | Definition | Source |
|------|------|------------|--------|
| Approval_Required? | plan | A pricing tier in FitCoach Pro-mvp3 offering specific features and capabilities for target users with Verification Complete?, Social Sharing of Progress | business_process |
| Hr | default | A key element in the FitCoach Pro-mvp3 system related to system operations | unknown |
| Coach | default | A key element in the FitCoach Pro-mvp3 system related to system operations | unknown |
| POINT | phase | A stage in the user journey where users point and progress through the journey with USING, MVP1 | user_journey |
| Under_Review | step | A process step that under review as part of the workflow with Verification Complete?, Approval Required? in the workflow | business_process |
| Recipe_Suggestions | step | A process step that recipe suggestions as part of the workflow with Social Sharing of Progress, API Integration with Fitness Devices in the workflow | value_stream |
| Gamification_Elements | condition | A decision point that evaluates criteria to determine the appropriate outcome with Social Sharing of Progress, API Integration with Fitness Devices | value_stream |
| Social_Sharing_of_Progress | plan | A pricing tier in FitCoach Pro-mvp3 offering specific features and capabilities for target users with API Integration with Fitness Devices, Recipe Suggestions | value_stream |
| Group_Coaching_Mechanism | step | A process step that group coaching mechanism as part of the workflow with Social Sharing of Progress, API Integration with Fitness Devices in the workflow | value_stream |
| Developer | role | A stakeholder role in the FitCoach Pro-mvp3 system responsible for workflow activities and decision-making with Admin, Product Owner | swimlane |
| USING | phase | A stage in the user journey where users using and progress through the journey with MVP1, MVP2 | user_journey |
| PAIN | phase | A stage in the user journey where users pain and progress through the journey with USING, MVP1 | user_journey |
| HIGH | condition | A decision point that evaluates criteria to determine the appropriate outcome with Enterprise Platform, condition | decision_tree |
| Product | plan | A pricing tier in FitCoach Pro-mvp3 offering specific features and capabilities for target users | unknown |
| MEDIUM | condition | A decision point that evaluates criteria to determine the appropriate outcome with Enterprise Platform, condition | decision_tree |
| condition | condition | A decision point that evaluates criteria to determine the appropriate outcome with Enterprise Platform, action | decision_tree |
| Approved | plan | A pricing tier in FitCoach Pro-mvp3 offering specific features and capabilities for target users with Verification Complete?, Approval Required? | business_process |
| API_Integration_with_Fitness_Devices | step | A process step that api integration with fitness devices as part of the workflow with Social Sharing of Progress, Recipe Suggestions in the workflow | value_stream |
| action | step | A process step that action as part of the workflow with Enterprise Platform, condition in the workflow | decision_tree |
| Standard_threshold | condition | A decision point that evaluates criteria to determine the appropriate outcome with Enterprise Platform, condition | decision_tree |
| Product_Owner | role | A stakeholder role in the FitCoach Pro-mvp3 system responsible for workflow activities and decision-making with Admin, Developer | swimlane |
| LOW | condition | A decision point that evaluates criteria to determine the appropriate outcome with Enterprise Platform, condition | decision_tree |
| Support_Agent | team | A functional team responsible for specialized tasks and deliverables with Admin, Developer in the workflow | swimlane |
| AI_System | default | A key element in the FitCoach Pro-mvp3 system related to system operations | unknown |
| Admin | role | A stakeholder role in the FitCoach Pro-mvp3 system responsible for workflow activities and decision-making with Developer, Product Owner | swimlane |
| MVP2 | phase | A stage in the user journey where users mvp2 and progress through the journey with USING, MVP1 | user_journey |
| Enterprise_Platform | plan | A pricing tier in FitCoach Pro-mvp3 offering specific features and capabilities for target users with condition, action | decision_tree |
| Persona | default | A key element in the FitCoach Pro-mvp3 system related to system operations | unknown |
| Rejected | step | A process step that rejected as part of the workflow with Verification Complete?, Approval Required? in the workflow | business_process |
| CRITICAL | condition | A decision point that evaluates criteria to determine the appropriate outcome with Enterprise Platform, condition | decision_tree |
| ENRICHING | phase | A stage in the user journey where users enriching and progress through the journey with USING, MVP1 | user_journey |
| MVP1 | phase | A stage in the user journey where users mvp1 and progress through the journey with USING, MVP2 | user_journey |
| Support | team | A functional team responsible for specialized tasks and deliverables in the workflow | unknown |
| MVP3 | role | A stakeholder role in the FitCoach Pro-mvp3 system responsible for workflow activities and decision-making with Admin, Developer | swimlane |
| Verification_Complete? | step | A process step that verification complete? as part of the workflow with Approval Required?, Social Sharing of Progress in the workflow | business_process |
| User | role | A stakeholder role in the FitCoach Pro-mvp3 system responsible for workflow activities and decision-making | unknown |

---

## Entity Types


### plan

- **Approval_Required?**: A pricing tier in FitCoach Pro-mvp3 offering specific features and capabilities for target users with Verification Complete?, Social Sharing of Progress
- **Social_Sharing_of_Progress**: A pricing tier in FitCoach Pro-mvp3 offering specific features and capabilities for target users with API Integration with Fitness Devices, Recipe Suggestions
- **Product**: A pricing tier in FitCoach Pro-mvp3 offering specific features and capabilities for target users
- **Approved**: A pricing tier in FitCoach Pro-mvp3 offering specific features and capabilities for target users with Verification Complete?, Approval Required?
- **Enterprise_Platform**: A pricing tier in FitCoach Pro-mvp3 offering specific features and capabilities for target users with condition, action


### default

- **Hr**: A key element in the FitCoach Pro-mvp3 system related to system operations
- **Coach**: A key element in the FitCoach Pro-mvp3 system related to system operations
- **AI_System**: A key element in the FitCoach Pro-mvp3 system related to system operations
- **Persona**: A key element in the FitCoach Pro-mvp3 system related to system operations


### phase

- **POINT**: A stage in the user journey where users point and progress through the journey with USING, MVP1
- **USING**: A stage in the user journey where users using and progress through the journey with MVP1, MVP2
- **PAIN**: A stage in the user journey where users pain and progress through the journey with USING, MVP1
- **MVP2**: A stage in the user journey where users mvp2 and progress through the journey with USING, MVP1
- **ENRICHING**: A stage in the user journey where users enriching and progress through the journey with USING, MVP1
- **MVP1**: A stage in the user journey where users mvp1 and progress through the journey with USING, MVP2


### step

- **Under_Review**: A process step that under review as part of the workflow with Verification Complete?, Approval Required? in the workflow
- **Recipe_Suggestions**: A process step that recipe suggestions as part of the workflow with Social Sharing of Progress, API Integration with Fitness Devices in the workflow
- **Group_Coaching_Mechanism**: A process step that group coaching mechanism as part of the workflow with Social Sharing of Progress, API Integration with Fitness Devices in the workflow
- **API_Integration_with_Fitness_Devices**: A process step that api integration with fitness devices as part of the workflow with Social Sharing of Progress, Recipe Suggestions in the workflow
- **action**: A process step that action as part of the workflow with Enterprise Platform, condition in the workflow
- **Rejected**: A process step that rejected as part of the workflow with Verification Complete?, Approval Required? in the workflow
- **Verification_Complete?**: A process step that verification complete? as part of the workflow with Approval Required?, Social Sharing of Progress in the workflow


### condition

- **Gamification_Elements**: A decision point that evaluates criteria to determine the appropriate outcome with Social Sharing of Progress, API Integration with Fitness Devices
- **HIGH**: A decision point that evaluates criteria to determine the appropriate outcome with Enterprise Platform, condition
- **MEDIUM**: A decision point that evaluates criteria to determine the appropriate outcome with Enterprise Platform, condition
- **condition**: A decision point that evaluates criteria to determine the appropriate outcome with Enterprise Platform, action
- **Standard_threshold**: A decision point that evaluates criteria to determine the appropriate outcome with Enterprise Platform, condition
- **LOW**: A decision point that evaluates criteria to determine the appropriate outcome with Enterprise Platform, condition
- **CRITICAL**: A decision point that evaluates criteria to determine the appropriate outcome with Enterprise Platform, condition


### role

- **Developer**: A stakeholder role in the FitCoach Pro-mvp3 system responsible for workflow activities and decision-making with Admin, Product Owner
- **Product_Owner**: A stakeholder role in the FitCoach Pro-mvp3 system responsible for workflow activities and decision-making with Admin, Developer
- **Admin**: A stakeholder role in the FitCoach Pro-mvp3 system responsible for workflow activities and decision-making with Developer, Product Owner
- **MVP3**: A stakeholder role in the FitCoach Pro-mvp3 system responsible for workflow activities and decision-making with Admin, Developer
- **User**: A stakeholder role in the FitCoach Pro-mvp3 system responsible for workflow activities and decision-making


### team

- **Support_Agent**: A functional team responsible for specialized tasks and deliverables with Admin, Developer in the workflow
- **Support**: A functional team responsible for specialized tasks and deliverables in the workflow


---

## Source References

| Source Diagram | Entities Count |
|----------------|----------------|
| user_journey | 6 |
| swimlane | 7 |
| decision_tree | 8 |
| value_stream | 7 |
| business_process | 10 |

---

*Generated by MAS Compiler Glossary Generator*