# Domain Glossary: Fitcoach Pro Mvp2

> **Generated**: 2025-12-11 11:06:40  
> **Version**: 1.0.0

---

## Overview

Domain terminology extracted from MAS artifacts for **Fitcoach Pro Mvp2**.

| Term | Type | Definition | Source |
|------|------|------------|--------|
| MVP1_progress_tracking | plan | A pricing tier in FitCoach Pro-mvp2 offering specific features and capabilities for target users with Admin, Developer | swimlane |
| Approval_Required? | plan | A pricing tier in FitCoach Pro-mvp2 offering specific features and capabilities for target users with Verification Complete?, Adaptive Routines USING MVP1 progress tracking | business_process |
| Hr | default | A key element in the FitCoach Pro-mvp2 system related to system operations | unknown |
| POINT | phase | A stage in the user journey where users point and progress through the journey with USING, MVP1 | user_journey |
| Under_Review | step | A process step that under review as part of the workflow with Verification Complete?, Approval Required? in the workflow | business_process |
| Developer | role | A stakeholder role in the FitCoach Pro-mvp2 system responsible for workflow activities and decision-making with Admin, Product Owner | swimlane |
| USING | phase | A stage in the user journey where users using and progress through the journey with MVP1, BUILDING | user_journey |
| MVP1_photo_recognition | role | A stakeholder role in the FitCoach Pro-mvp2 system responsible for workflow activities and decision-making with Admin, Developer | swimlane |
| User | role | A stakeholder role in the FitCoach Pro-mvp2 system responsible for workflow activities and decision-making | unknown |
| AI_Nutrition_Feedback | step | A process step that ai nutrition feedback as part of the workflow with Workout Plan Optimization, Adaptive Routines in the workflow | value_stream |
| PAIN | phase | A stage in the user journey where users pain and progress through the journey with USING, MVP1 | user_journey |
| HIGH | condition | A decision point that evaluates criteria to determine the appropriate outcome with Advanced Analytics, Standard threshold | decision_tree |
| Predictive_Progress_Tracking | plan | A pricing tier in FitCoach Pro-mvp2 offering specific features and capabilities for target users with Workout Plan Optimization, AI Nutrition Feedback | value_stream |
| MVP1_workout_generator | role | A stakeholder role in the FitCoach Pro-mvp2 system responsible for workflow activities and decision-making with Admin, Developer | swimlane |
| Product | plan | A pricing tier in FitCoach Pro-mvp2 offering specific features and capabilities for target users | unknown |
| MEDIUM | condition | A decision point that evaluates criteria to determine the appropriate outcome with Advanced Analytics, Standard threshold | decision_tree |
| Approved | plan | A pricing tier in FitCoach Pro-mvp2 offering specific features and capabilities for target users with Verification Complete?, Approval Required? | business_process |
| Workout_Plan_Optimization | plan | A pricing tier in FitCoach Pro-mvp2 offering specific features and capabilities for target users with AI Nutrition Feedback, Adaptive Routines | value_stream |
| Advanced_Analytics | condition | A decision point that evaluates criteria to determine the appropriate outcome with Standard threshold, LOW | decision_tree |
| Product_Owner | role | A stakeholder role in the FitCoach Pro-mvp2 system responsible for workflow activities and decision-making with Admin, Developer | swimlane |
| Standard_threshold | condition | A decision point that evaluates criteria to determine the appropriate outcome with Advanced Analytics, LOW | decision_tree |
| LOW | condition | A decision point that evaluates criteria to determine the appropriate outcome with Advanced Analytics, Standard threshold | decision_tree |
| Support_Agent | team | A functional team responsible for specialized tasks and deliverables with Admin, Developer in the workflow | swimlane |
| Adaptive_Routines_USING_MVP1_progress_tracking | plan | A pricing tier in FitCoach Pro-mvp2 offering specific features and capabilities for target users with Verification Complete?, Approval Required? | business_process |
| MVP1_user_profiles | role | A stakeholder role in the FitCoach Pro-mvp2 system responsible for workflow activities and decision-making with Admin, Developer | swimlane |
| MVP1+wearable_data | role | A stakeholder role in the FitCoach Pro-mvp2 system responsible for workflow activities and decision-making with Admin, Developer | swimlane |
| Rejected | step | A process step that rejected as part of the workflow with Verification Complete?, Approval Required? in the workflow | business_process |
| CRITICAL | condition | A decision point that evaluates criteria to determine the appropriate outcome with Advanced Analytics, Standard threshold | decision_tree |
| BUILDING | phase | A stage in the user journey where users building and progress through the journey with USING, MVP1 | user_journey |
| MVP1 | phase | A stage in the user journey where users mvp1 and progress through the journey with USING, BUILDING | user_journey |
| Support | team | A functional team responsible for specialized tasks and deliverables in the workflow | unknown |
| Adaptive_Routines | step | A process step that adaptive routines as part of the workflow with Workout Plan Optimization, AI Nutrition Feedback in the workflow | value_stream |
| Verification_Complete? | step | A process step that verification complete? as part of the workflow with Approval Required?, Adaptive Routines USING MVP1 progress tracking in the workflow | business_process |
| Dynamic_Goal_Adjustment | step | A process step that dynamic goal adjustment as part of the workflow with Workout Plan Optimization, AI Nutrition Feedback in the workflow | value_stream |
| Admin | role | A stakeholder role in the FitCoach Pro-mvp2 system responsible for workflow activities and decision-making with Developer, Product Owner | swimlane |

---

## Entity Types


### plan

- **MVP1_progress_tracking**: A pricing tier in FitCoach Pro-mvp2 offering specific features and capabilities for target users with Admin, Developer
- **Approval_Required?**: A pricing tier in FitCoach Pro-mvp2 offering specific features and capabilities for target users with Verification Complete?, Adaptive Routines USING MVP1 progress tracking
- **Predictive_Progress_Tracking**: A pricing tier in FitCoach Pro-mvp2 offering specific features and capabilities for target users with Workout Plan Optimization, AI Nutrition Feedback
- **Product**: A pricing tier in FitCoach Pro-mvp2 offering specific features and capabilities for target users
- **Approved**: A pricing tier in FitCoach Pro-mvp2 offering specific features and capabilities for target users with Verification Complete?, Approval Required?
- **Workout_Plan_Optimization**: A pricing tier in FitCoach Pro-mvp2 offering specific features and capabilities for target users with AI Nutrition Feedback, Adaptive Routines
- **Adaptive_Routines_USING_MVP1_progress_tracking**: A pricing tier in FitCoach Pro-mvp2 offering specific features and capabilities for target users with Verification Complete?, Approval Required?


### default

- **Hr**: A key element in the FitCoach Pro-mvp2 system related to system operations


### phase

- **POINT**: A stage in the user journey where users point and progress through the journey with USING, MVP1
- **USING**: A stage in the user journey where users using and progress through the journey with MVP1, BUILDING
- **PAIN**: A stage in the user journey where users pain and progress through the journey with USING, MVP1
- **BUILDING**: A stage in the user journey where users building and progress through the journey with USING, MVP1
- **MVP1**: A stage in the user journey where users mvp1 and progress through the journey with USING, BUILDING


### step

- **Under_Review**: A process step that under review as part of the workflow with Verification Complete?, Approval Required? in the workflow
- **AI_Nutrition_Feedback**: A process step that ai nutrition feedback as part of the workflow with Workout Plan Optimization, Adaptive Routines in the workflow
- **Rejected**: A process step that rejected as part of the workflow with Verification Complete?, Approval Required? in the workflow
- **Adaptive_Routines**: A process step that adaptive routines as part of the workflow with Workout Plan Optimization, AI Nutrition Feedback in the workflow
- **Verification_Complete?**: A process step that verification complete? as part of the workflow with Approval Required?, Adaptive Routines USING MVP1 progress tracking in the workflow
- **Dynamic_Goal_Adjustment**: A process step that dynamic goal adjustment as part of the workflow with Workout Plan Optimization, AI Nutrition Feedback in the workflow


### role

- **Developer**: A stakeholder role in the FitCoach Pro-mvp2 system responsible for workflow activities and decision-making with Admin, Product Owner
- **MVP1_photo_recognition**: A stakeholder role in the FitCoach Pro-mvp2 system responsible for workflow activities and decision-making with Admin, Developer
- **User**: A stakeholder role in the FitCoach Pro-mvp2 system responsible for workflow activities and decision-making
- **MVP1_workout_generator**: A stakeholder role in the FitCoach Pro-mvp2 system responsible for workflow activities and decision-making with Admin, Developer
- **Product_Owner**: A stakeholder role in the FitCoach Pro-mvp2 system responsible for workflow activities and decision-making with Admin, Developer
- **MVP1_user_profiles**: A stakeholder role in the FitCoach Pro-mvp2 system responsible for workflow activities and decision-making with Admin, Developer
- **MVP1+wearable_data**: A stakeholder role in the FitCoach Pro-mvp2 system responsible for workflow activities and decision-making with Admin, Developer
- **Admin**: A stakeholder role in the FitCoach Pro-mvp2 system responsible for workflow activities and decision-making with Developer, Product Owner


### condition

- **HIGH**: A decision point that evaluates criteria to determine the appropriate outcome with Advanced Analytics, Standard threshold
- **MEDIUM**: A decision point that evaluates criteria to determine the appropriate outcome with Advanced Analytics, Standard threshold
- **Advanced_Analytics**: A decision point that evaluates criteria to determine the appropriate outcome with Standard threshold, LOW
- **Standard_threshold**: A decision point that evaluates criteria to determine the appropriate outcome with Advanced Analytics, LOW
- **LOW**: A decision point that evaluates criteria to determine the appropriate outcome with Advanced Analytics, Standard threshold
- **CRITICAL**: A decision point that evaluates criteria to determine the appropriate outcome with Advanced Analytics, Standard threshold


### team

- **Support_Agent**: A functional team responsible for specialized tasks and deliverables with Admin, Developer in the workflow
- **Support**: A functional team responsible for specialized tasks and deliverables in the workflow


---

## Source References

| Source Diagram | Entities Count |
|----------------|----------------|
| user_journey | 5 |
| swimlane | 9 |
| decision_tree | 6 |
| value_stream | 10 |
| business_process | 6 |

---

*Generated by MAS Compiler Glossary Generator*