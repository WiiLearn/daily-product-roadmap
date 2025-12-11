# Domain Glossary: Teamflow Mvp1

> **Generated**: 2025-12-11 11:34:30  
> **Version**: 1.0.0

---

## Overview

Domain terminology extracted from MAS artifacts for **Teamflow Mvp1**.

| Term | Type | Definition | Source |
|------|------|------------|--------|
| Approval_Required? | plan | A pricing tier in TeamFlow-mvp1 offering specific features and capabilities for target users with Verification Complete?, Async video messaging system | business_process |
| Hr | default | A key element in the TeamFlow-mvp1 system related to system operations | unknown |
| POINT | phase | A stage in the user journey where users point and progress through the journey with PAIN, Complete | user_journey |
| Under_Review | step | A process step that under review as part of the workflow with Verification Complete?, Approval Required? in the workflow | business_process |
| messaging | phase | A stage in the user journey where users messaging and progress through the journey with PAIN, POINT | user_journey |
| touchpoints | phase | A stage in the user journey where users touchpoints and progress through the journey with PAIN, POINT | user_journey |
| Project_tracking_dashboard | plan | A pricing tier in TeamFlow-mvp1 offering specific features and capabilities for target users with Async video messaging system, Virtual office space interface | value_stream |
| Verification_Complete? | step | A process step that verification complete? as part of the workflow with Approval Required?, Async video messaging system in the workflow | business_process |
| Platform | screen | A UI screen where users can view and interact with system features with PAIN, POINT | user_journey |
| Features | phase | A stage in the user journey where users features and progress through the journey with PAIN, POINT | user_journey |
| Developer | role | A stakeholder role in the TeamFlow-mvp1 system responsible for workflow activities and decision-making with Admin, Product Owner | swimlane |
| system | phase | A stage in the user journey where users system and progress through the journey with PAIN, POINT | user_journey |
| PAIN | phase | A stage in the user journey where users pain and progress through the journey with POINT, Complete | user_journey |
| HIGH | condition | A decision point that evaluates criteria to determine the appropriate outcome with Core Platform Features, Standard threshold | decision_tree |
| Core | phase | A stage in the user journey where users core and progress through the journey with PAIN, POINT | user_journey |
| Project | plan | A pricing tier in TeamFlow-mvp1 offering specific features and capabilities for target users with PAIN, POINT | user_journey |
| Product | plan | A pricing tier in TeamFlow-mvp1 offering specific features and capabilities for target users | unknown |
| MEDIUM | condition | A decision point that evaluates criteria to determine the appropriate outcome with Core Platform Features, Standard threshold | decision_tree |
| Approved | plan | A pricing tier in TeamFlow-mvp1 offering specific features and capabilities for target users with Verification Complete?, Approval Required? | business_process |
| Standard_threshold | condition | A decision point that evaluates criteria to determine the appropriate outcome with Core Platform Features, LOW | decision_tree |
| Product_Owner | role | A stakeholder role in the TeamFlow-mvp1 system responsible for workflow activities and decision-making with Admin, Developer | swimlane |
| LOW | condition | A decision point that evaluates criteria to determine the appropriate outcome with Core Platform Features, Standard threshold | decision_tree |
| score | condition | A decision point that evaluates criteria to determine the appropriate outcome with PAIN, POINT | user_journey |
| Support_Agent | team | A functional team responsible for specialized tasks and deliverables with Admin, Developer in the workflow | swimlane |
| User_task_assignment_tool | role | A stakeholder role in the TeamFlow-mvp1 system responsible for workflow activities and decision-making with Async video messaging system, Project tracking dashboard | value_stream |
| Admin | role | A stakeholder role in the TeamFlow-mvp1 system responsible for workflow activities and decision-making with Developer, Product Owner | swimlane |
| Rejected | step | A process step that rejected as part of the workflow with Verification Complete?, Approval Required? in the workflow | business_process |
| Team_activity_feed | role | A stakeholder role in the TeamFlow-mvp1 system responsible for workflow activities and decision-making with Async video messaging system, Project tracking dashboard | value_stream |
| CRITICAL | condition | A decision point that evaluates criteria to determine the appropriate outcome with Core Platform Features, Standard threshold | decision_tree |
| tracking | phase | A stage in the user journey where users tracking and progress through the journey with PAIN, POINT | user_journey |
| Async_video_messaging_system | step | A process step that async video messaging system as part of the workflow with Project tracking dashboard, Virtual office space interface in the workflow | value_stream |
| dashboard | screen | A UI screen where users can view and interact with system features with PAIN, POINT | user_journey |
| Virtual_office_space_interface | step | A process step that virtual office space interface as part of the workflow with Async video messaging system, Project tracking dashboard in the workflow | value_stream |
| emotional | phase | A stage in the user journey where users emotional and progress through the journey with PAIN, POINT | user_journey |
| Support | team | A functional team responsible for specialized tasks and deliverables in the workflow | unknown |
| Core_Platform_Features | screen | A UI screen where users can view and interact with system features with Standard threshold, LOW | decision_tree |
| Complete | step | A process step that complete as part of the workflow with PAIN, POINT in the workflow | user_journey |
| video | phase | A stage in the user journey where users video and progress through the journey with PAIN, POINT | user_journey |
| Async | phase | A stage in the user journey where users async and progress through the journey with PAIN, POINT | user_journey |
| User | role | A stakeholder role in the TeamFlow-mvp1 system responsible for workflow activities and decision-making | unknown |

---

## Entity Types


### plan

- **Approval_Required?**: A pricing tier in TeamFlow-mvp1 offering specific features and capabilities for target users with Verification Complete?, Async video messaging system
- **Project_tracking_dashboard**: A pricing tier in TeamFlow-mvp1 offering specific features and capabilities for target users with Async video messaging system, Virtual office space interface
- **Project**: A pricing tier in TeamFlow-mvp1 offering specific features and capabilities for target users with PAIN, POINT
- **Product**: A pricing tier in TeamFlow-mvp1 offering specific features and capabilities for target users
- **Approved**: A pricing tier in TeamFlow-mvp1 offering specific features and capabilities for target users with Verification Complete?, Approval Required?


### default

- **Hr**: A key element in the TeamFlow-mvp1 system related to system operations


### phase

- **POINT**: A stage in the user journey where users point and progress through the journey with PAIN, Complete
- **messaging**: A stage in the user journey where users messaging and progress through the journey with PAIN, POINT
- **touchpoints**: A stage in the user journey where users touchpoints and progress through the journey with PAIN, POINT
- **Features**: A stage in the user journey where users features and progress through the journey with PAIN, POINT
- **system**: A stage in the user journey where users system and progress through the journey with PAIN, POINT
- **PAIN**: A stage in the user journey where users pain and progress through the journey with POINT, Complete
- **Core**: A stage in the user journey where users core and progress through the journey with PAIN, POINT
- **tracking**: A stage in the user journey where users tracking and progress through the journey with PAIN, POINT
- **emotional**: A stage in the user journey where users emotional and progress through the journey with PAIN, POINT
- **video**: A stage in the user journey where users video and progress through the journey with PAIN, POINT
- **Async**: A stage in the user journey where users async and progress through the journey with PAIN, POINT


### step

- **Under_Review**: A process step that under review as part of the workflow with Verification Complete?, Approval Required? in the workflow
- **Verification_Complete?**: A process step that verification complete? as part of the workflow with Approval Required?, Async video messaging system in the workflow
- **Rejected**: A process step that rejected as part of the workflow with Verification Complete?, Approval Required? in the workflow
- **Async_video_messaging_system**: A process step that async video messaging system as part of the workflow with Project tracking dashboard, Virtual office space interface in the workflow
- **Virtual_office_space_interface**: A process step that virtual office space interface as part of the workflow with Async video messaging system, Project tracking dashboard in the workflow
- **Complete**: A process step that complete as part of the workflow with PAIN, POINT in the workflow


### screen

- **Platform**: A UI screen where users can view and interact with system features with PAIN, POINT
- **dashboard**: A UI screen where users can view and interact with system features with PAIN, POINT
- **Core_Platform_Features**: A UI screen where users can view and interact with system features with Standard threshold, LOW


### role

- **Developer**: A stakeholder role in the TeamFlow-mvp1 system responsible for workflow activities and decision-making with Admin, Product Owner
- **Product_Owner**: A stakeholder role in the TeamFlow-mvp1 system responsible for workflow activities and decision-making with Admin, Developer
- **User_task_assignment_tool**: A stakeholder role in the TeamFlow-mvp1 system responsible for workflow activities and decision-making with Async video messaging system, Project tracking dashboard
- **Admin**: A stakeholder role in the TeamFlow-mvp1 system responsible for workflow activities and decision-making with Developer, Product Owner
- **Team_activity_feed**: A stakeholder role in the TeamFlow-mvp1 system responsible for workflow activities and decision-making with Async video messaging system, Project tracking dashboard
- **User**: A stakeholder role in the TeamFlow-mvp1 system responsible for workflow activities and decision-making


### condition

- **HIGH**: A decision point that evaluates criteria to determine the appropriate outcome with Core Platform Features, Standard threshold
- **MEDIUM**: A decision point that evaluates criteria to determine the appropriate outcome with Core Platform Features, Standard threshold
- **Standard_threshold**: A decision point that evaluates criteria to determine the appropriate outcome with Core Platform Features, LOW
- **LOW**: A decision point that evaluates criteria to determine the appropriate outcome with Core Platform Features, Standard threshold
- **score**: A decision point that evaluates criteria to determine the appropriate outcome with PAIN, POINT
- **CRITICAL**: A decision point that evaluates criteria to determine the appropriate outcome with Core Platform Features, Standard threshold


### team

- **Support_Agent**: A functional team responsible for specialized tasks and deliverables with Admin, Developer in the workflow
- **Support**: A functional team responsible for specialized tasks and deliverables in the workflow


---

## Source References

| Source Diagram | Entities Count |
|----------------|----------------|
| user_journey | 16 |
| swimlane | 4 |
| decision_tree | 6 |
| value_stream | 5 |
| business_process | 10 |

---

*Generated by MAS Compiler Glossary Generator*