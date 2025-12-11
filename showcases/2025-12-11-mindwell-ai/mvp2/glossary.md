# Domain Glossary: Mindwell Ai Mvp2

> **Generated**: 2025-12-11 10:51:38  
> **Version**: 1.0.0

---

## Overview

Domain terminology extracted from MAS artifacts for **Mindwell Ai Mvp2**.

| Term | Type | Definition | Source |
|------|------|------------|--------|
| MVP1 | phase | A stage in the user journey where users mvp1 and progress through the journey with USING, BUILDING | user_journey |
| Physician | role | A stakeholder role in the MindWell AI-mvp2 system responsible for workflow activities and decision-making with Patient, Caregiver | swimlane |
| MVP1_User_Dashboard | role | A stakeholder role in the MindWell AI-mvp2 system responsible for workflow activities and decision-making | unknown |
| USING | phase | A stage in the user journey where users using and progress through the journey with MVP1, BUILDING | user_journey |
| AI-driven_mood_analysis | step | A process step that ai-driven mood analysis as part of the workflow with MVP1 mood tracking data, Session personalization suggestions in the workflow | value_stream |
| Session_personalization_suggestions | step | A process step that session personalization suggestions as part of the workflow with AI-driven mood analysis, MVP1 mood tracking data in the workflow | value_stream |
| MVP1_Therapy_Session_Generator | default | A key element in the MindWell AI-mvp2 system related to system operations | unknown |
| Intelligent_Health_Insights | condition | A decision point that evaluates criteria to determine the appropriate outcome with treatment, protocol | decision_tree |
| Caregiver | role | A stakeholder role in the MindWell AI-mvp2 system responsible for workflow activities and decision-making with Patient, Physician | swimlane |
| Nurse | role | A stakeholder role in the MindWell AI-mvp2 system responsible for workflow activities and decision-making with Patient, Caregiver | swimlane |
| Therapist | default | A key element in the MindWell AI-mvp2 system related to system operations | unknown |
| Behavioral_trends_identification | condition | A decision point that evaluates criteria to determine the appropriate outcome with AI-driven mood analysis, MVP1 mood tracking data | value_stream |
| ticket | condition | A decision point that evaluates criteria to determine the appropriate outcome with Intelligent Health Insights, treatment | decision_tree |
| Rejected | step | A process step that rejected as part of the workflow with Verification Complete?, Approval Required? in the workflow | business_process |
| User | role | A stakeholder role in the MindWell AI-mvp2 system responsible for workflow activities and decision-making | unknown |
| MVP1_mood_tracking_data | role | A stakeholder role in the MindWell AI-mvp2 system responsible for workflow activities and decision-making with Patient, Caregiver | swimlane |
| AI_System | default | A key element in the MindWell AI-mvp2 system related to system operations | unknown |
| Specialist | role | A stakeholder role in the MindWell AI-mvp2 system responsible for workflow activities and decision-making with Patient, Caregiver | swimlane |
| therapy | condition | A decision point that evaluates criteria to determine the appropriate outcome with Intelligent Health Insights, treatment | decision_tree |
| medication | condition | A decision point that evaluates criteria to determine the appropriate outcome with Intelligent Health Insights, treatment | decision_tree |
| BUILDING | phase | A stage in the user journey where users building and progress through the journey with USING, MVP1 | user_journey |
| POINT | phase | A stage in the user journey where users point and progress through the journey with USING, MVP1 | user_journey |
| Hr | default | A key element in the MindWell AI-mvp2 system related to system operations | unknown |
| feature | condition | A decision point that evaluates criteria to determine the appropriate outcome with Intelligent Health Insights, treatment | decision_tree |
| Customer | role | A stakeholder role in the MindWell AI-mvp2 system responsible for workflow activities and decision-making | unknown |
| Under_Review | step | A process step that under review as part of the workflow with Verification Complete?, Approval Required? in the workflow | business_process |
| access | condition | A decision point that evaluates criteria to determine the appropriate outcome with Intelligent Health Insights, treatment | decision_tree |
| MVP1_progress_data | plan | A pricing tier in MindWell AI-mvp2 offering specific features and capabilities for target users with Patient, Caregiver | swimlane |
| System | default | A key element in the MindWell AI-mvp2 system related to system operations | unknown |
| Approval_Required? | plan | A pricing tier in MindWell AI-mvp2 offering specific features and capabilities for target users with Verification Complete?, AI-driven mood analysis | business_process |
| Patient_Portal | default | A key element in the MindWell AI-mvp2 system related to system operations | unknown |
| protocol | plan | A pricing tier in MindWell AI-mvp2 offering specific features and capabilities for target users with Intelligent Health Insights, treatment | decision_tree |
| Predictive_analytics_for_therapy_outcomes | step | A process step that predictive analytics for therapy outcomes as part of the workflow with AI-driven mood analysis, MVP1 mood tracking data in the workflow | value_stream |
| MVP1_booking_system | role | A stakeholder role in the MindWell AI-mvp2 system responsible for workflow activities and decision-making with Patient, Caregiver | swimlane |
| support | team | A functional team responsible for specialized tasks and deliverables with Intelligent Health Insights, treatment in the workflow | decision_tree |
| Persona | default | A key element in the MindWell AI-mvp2 system related to system operations | unknown |
| treatment | condition | A decision point that evaluates criteria to determine the appropriate outcome with Intelligent Health Insights, protocol | decision_tree |
| Automated_reminders_for_therapy_sessions | step | A process step that automated reminders for therapy sessions as part of the workflow with AI-driven mood analysis, MVP1 mood tracking data in the workflow | value_stream |
| Approved | plan | A pricing tier in MindWell AI-mvp2 offering specific features and capabilities for target users with Verification Complete?, Approval Required? | business_process |
| PAIN | phase | A stage in the user journey where users pain and progress through the journey with USING, MVP1 | user_journey |
| Patient | role | A stakeholder role in the MindWell AI-mvp2 system responsible for workflow activities and decision-making with Caregiver, Physician | swimlane |
| Verification_Complete? | step | A process step that verification complete? as part of the workflow with Approval Required?, AI-driven mood analysis in the workflow | business_process |

---

## Entity Types


### phase

- **MVP1**: A stage in the user journey where users mvp1 and progress through the journey with USING, BUILDING
- **USING**: A stage in the user journey where users using and progress through the journey with MVP1, BUILDING
- **BUILDING**: A stage in the user journey where users building and progress through the journey with USING, MVP1
- **POINT**: A stage in the user journey where users point and progress through the journey with USING, MVP1
- **PAIN**: A stage in the user journey where users pain and progress through the journey with USING, MVP1


### role

- **Physician**: A stakeholder role in the MindWell AI-mvp2 system responsible for workflow activities and decision-making with Patient, Caregiver
- **MVP1_User_Dashboard**: A stakeholder role in the MindWell AI-mvp2 system responsible for workflow activities and decision-making
- **Caregiver**: A stakeholder role in the MindWell AI-mvp2 system responsible for workflow activities and decision-making with Patient, Physician
- **Nurse**: A stakeholder role in the MindWell AI-mvp2 system responsible for workflow activities and decision-making with Patient, Caregiver
- **User**: A stakeholder role in the MindWell AI-mvp2 system responsible for workflow activities and decision-making
- **MVP1_mood_tracking_data**: A stakeholder role in the MindWell AI-mvp2 system responsible for workflow activities and decision-making with Patient, Caregiver
- **Specialist**: A stakeholder role in the MindWell AI-mvp2 system responsible for workflow activities and decision-making with Patient, Caregiver
- **Customer**: A stakeholder role in the MindWell AI-mvp2 system responsible for workflow activities and decision-making
- **MVP1_booking_system**: A stakeholder role in the MindWell AI-mvp2 system responsible for workflow activities and decision-making with Patient, Caregiver
- **Patient**: A stakeholder role in the MindWell AI-mvp2 system responsible for workflow activities and decision-making with Caregiver, Physician


### step

- **AI-driven_mood_analysis**: A process step that ai-driven mood analysis as part of the workflow with MVP1 mood tracking data, Session personalization suggestions in the workflow
- **Session_personalization_suggestions**: A process step that session personalization suggestions as part of the workflow with AI-driven mood analysis, MVP1 mood tracking data in the workflow
- **Rejected**: A process step that rejected as part of the workflow with Verification Complete?, Approval Required? in the workflow
- **Under_Review**: A process step that under review as part of the workflow with Verification Complete?, Approval Required? in the workflow
- **Predictive_analytics_for_therapy_outcomes**: A process step that predictive analytics for therapy outcomes as part of the workflow with AI-driven mood analysis, MVP1 mood tracking data in the workflow
- **Automated_reminders_for_therapy_sessions**: A process step that automated reminders for therapy sessions as part of the workflow with AI-driven mood analysis, MVP1 mood tracking data in the workflow
- **Verification_Complete?**: A process step that verification complete? as part of the workflow with Approval Required?, AI-driven mood analysis in the workflow


### default

- **MVP1_Therapy_Session_Generator**: A key element in the MindWell AI-mvp2 system related to system operations
- **Therapist**: A key element in the MindWell AI-mvp2 system related to system operations
- **AI_System**: A key element in the MindWell AI-mvp2 system related to system operations
- **Hr**: A key element in the MindWell AI-mvp2 system related to system operations
- **System**: A key element in the MindWell AI-mvp2 system related to system operations
- **Patient_Portal**: A key element in the MindWell AI-mvp2 system related to system operations
- **Persona**: A key element in the MindWell AI-mvp2 system related to system operations


### condition

- **Intelligent_Health_Insights**: A decision point that evaluates criteria to determine the appropriate outcome with treatment, protocol
- **Behavioral_trends_identification**: A decision point that evaluates criteria to determine the appropriate outcome with AI-driven mood analysis, MVP1 mood tracking data
- **ticket**: A decision point that evaluates criteria to determine the appropriate outcome with Intelligent Health Insights, treatment
- **therapy**: A decision point that evaluates criteria to determine the appropriate outcome with Intelligent Health Insights, treatment
- **medication**: A decision point that evaluates criteria to determine the appropriate outcome with Intelligent Health Insights, treatment
- **feature**: A decision point that evaluates criteria to determine the appropriate outcome with Intelligent Health Insights, treatment
- **access**: A decision point that evaluates criteria to determine the appropriate outcome with Intelligent Health Insights, treatment
- **treatment**: A decision point that evaluates criteria to determine the appropriate outcome with Intelligent Health Insights, protocol


### plan

- **MVP1_progress_data**: A pricing tier in MindWell AI-mvp2 offering specific features and capabilities for target users with Patient, Caregiver
- **Approval_Required?**: A pricing tier in MindWell AI-mvp2 offering specific features and capabilities for target users with Verification Complete?, AI-driven mood analysis
- **protocol**: A pricing tier in MindWell AI-mvp2 offering specific features and capabilities for target users with Intelligent Health Insights, treatment
- **Approved**: A pricing tier in MindWell AI-mvp2 offering specific features and capabilities for target users with Verification Complete?, Approval Required?


### team

- **support**: A functional team responsible for specialized tasks and deliverables with Intelligent Health Insights, treatment in the workflow


---

## Source References

| Source Diagram | Entities Count |
|----------------|----------------|
| user_journey | 5 |
| swimlane | 10 |
| decision_tree | 9 |
| value_stream | 10 |
| business_process | 10 |

---

*Generated by MAS Compiler Glossary Generator*