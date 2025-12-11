# Domain Glossary: Mindwell Ai Mvp1

> **Generated**: 2025-12-11 10:50:58  
> **Version**: 1.0.0

---

## Overview

Domain terminology extracted from MAS artifacts for **Mindwell Ai Mvp1**.

| Term | Type | Definition | Source |
|------|------|------------|--------|
| Physician | role | A stakeholder role in the MindWell AI-mvp1 system responsible for workflow activities and decision-making with Patient, Caregiver | swimlane |
| Core_Care_Coordination | condition | A decision point that evaluates criteria to determine the appropriate outcome with treatment, protocol | decision_tree |
| Caregiver | role | A stakeholder role in the MindWell AI-mvp1 system responsible for workflow activities and decision-making with Patient, Physician | swimlane |
| Nurse | role | A stakeholder role in the MindWell AI-mvp1 system responsible for workflow activities and decision-making with Patient, Caregiver | swimlane |
| ticket | condition | A decision point that evaluates criteria to determine the appropriate outcome with Core Care Coordination, treatment | decision_tree |
| Rejected | step | A process step that rejected as part of the workflow with Verification Complete?, Approval Required? in the workflow | business_process |
| Progress_tracking_dashboard | plan | A pricing tier in MindWell AI-mvp1 offering specific features and capabilities for target users with Personalized therapy session generator, Mood tracking interface | value_stream |
| score | condition | A decision point that evaluates criteria to determine the appropriate outcome with PAIN, POINT | user_journey |
| Complete | step | A process step that complete as part of the workflow with PAIN, POINT in the workflow | user_journey |
| Mood_tracking_interface | step | A process step that mood tracking interface as part of the workflow with Personalized therapy session generator, Therapist directory with profiles in the workflow | value_stream |
| Specialist | role | A stakeholder role in the MindWell AI-mvp1 system responsible for workflow activities and decision-making with Patient, Caregiver | swimlane |
| therapy | phase | A stage in the user journey where users therapy and progress through the journey with PAIN, POINT | user_journey |
| medication | condition | A decision point that evaluates criteria to determine the appropriate outcome with Core Care Coordination, treatment | decision_tree |
| emotional | phase | A stage in the user journey where users emotional and progress through the journey with PAIN, POINT | user_journey |
| POINT | phase | A stage in the user journey where users point and progress through the journey with PAIN, Patient | user_journey |
| tracking | phase | A stage in the user journey where users tracking and progress through the journey with PAIN, POINT | user_journey |
| Hr | default | A key element in the MindWell AI-mvp1 system related to system operations | unknown |
| Therapist_directory_with_profiles | plan | A pricing tier in MindWell AI-mvp1 offering specific features and capabilities for target users with Personalized therapy session generator, Mood tracking interface | value_stream |
| Care | phase | A stage in the user journey where users care and progress through the journey with PAIN, POINT | user_journey |
| feature | condition | A decision point that evaluates criteria to determine the appropriate outcome with Core Care Coordination, treatment | decision_tree |
| Customer | role | A stakeholder role in the MindWell AI-mvp1 system responsible for workflow activities and decision-making | unknown |
| Under_Review | step | A process step that under review as part of the workflow with Verification Complete?, Approval Required? in the workflow | business_process |
| access | condition | A decision point that evaluates criteria to determine the appropriate outcome with Core Care Coordination, treatment | decision_tree |
| System | default | A key element in the MindWell AI-mvp1 system related to system operations | unknown |
| Core | phase | A stage in the user journey where users core and progress through the journey with PAIN, POINT | user_journey |
| Approval_Required? | plan | A pricing tier in MindWell AI-mvp1 offering specific features and capabilities for target users with Verification Complete?, Personalized therapy session generator | business_process |
| generator | phase | A stage in the user journey where users generator and progress through the journey with PAIN, POINT | user_journey |
| protocol | plan | A pricing tier in MindWell AI-mvp1 offering specific features and capabilities for target users with Core Care Coordination, treatment | decision_tree |
| Mood | phase | A stage in the user journey where users mood and progress through the journey with PAIN, POINT | user_journey |
| support | team | A functional team responsible for specialized tasks and deliverables with Core Care Coordination, treatment in the workflow | decision_tree |
| Personalized | phase | A stage in the user journey where users personalized and progress through the journey with PAIN, POINT | user_journey |
| Coordination | phase | A stage in the user journey where users coordination and progress through the journey with PAIN, POINT | user_journey |
| Virtual_consultation_booking_system | step | A process step that virtual consultation booking system as part of the workflow with Personalized therapy session generator, Mood tracking interface in the workflow | value_stream |
| session | phase | A stage in the user journey where users session and progress through the journey with PAIN, POINT | user_journey |
| Persona | default | A key element in the MindWell AI-mvp1 system related to system operations | unknown |
| treatment | condition | A decision point that evaluates criteria to determine the appropriate outcome with Core Care Coordination, protocol | decision_tree |
| touchpoints | phase | A stage in the user journey where users touchpoints and progress through the journey with PAIN, POINT | user_journey |
| Approved | plan | A pricing tier in MindWell AI-mvp1 offering specific features and capabilities for target users with Verification Complete?, Approval Required? | business_process |
| PAIN | phase | A stage in the user journey where users pain and progress through the journey with POINT, Patient | user_journey |
| Patient | phase | A stage in the user journey where users patient and progress through the journey with PAIN, POINT | user_journey |
| Verification_Complete? | step | A process step that verification complete? as part of the workflow with Approval Required?, Personalized therapy session generator in the workflow | business_process |
| Personalized_therapy_session_generator | step | A process step that personalized therapy session generator as part of the workflow with Mood tracking interface, Therapist directory with profiles in the workflow | value_stream |

---

## Entity Types


### role

- **Physician**: A stakeholder role in the MindWell AI-mvp1 system responsible for workflow activities and decision-making with Patient, Caregiver
- **Caregiver**: A stakeholder role in the MindWell AI-mvp1 system responsible for workflow activities and decision-making with Patient, Physician
- **Nurse**: A stakeholder role in the MindWell AI-mvp1 system responsible for workflow activities and decision-making with Patient, Caregiver
- **Specialist**: A stakeholder role in the MindWell AI-mvp1 system responsible for workflow activities and decision-making with Patient, Caregiver
- **Customer**: A stakeholder role in the MindWell AI-mvp1 system responsible for workflow activities and decision-making


### condition

- **Core_Care_Coordination**: A decision point that evaluates criteria to determine the appropriate outcome with treatment, protocol
- **ticket**: A decision point that evaluates criteria to determine the appropriate outcome with Core Care Coordination, treatment
- **score**: A decision point that evaluates criteria to determine the appropriate outcome with PAIN, POINT
- **medication**: A decision point that evaluates criteria to determine the appropriate outcome with Core Care Coordination, treatment
- **feature**: A decision point that evaluates criteria to determine the appropriate outcome with Core Care Coordination, treatment
- **access**: A decision point that evaluates criteria to determine the appropriate outcome with Core Care Coordination, treatment
- **treatment**: A decision point that evaluates criteria to determine the appropriate outcome with Core Care Coordination, protocol


### step

- **Rejected**: A process step that rejected as part of the workflow with Verification Complete?, Approval Required? in the workflow
- **Complete**: A process step that complete as part of the workflow with PAIN, POINT in the workflow
- **Mood_tracking_interface**: A process step that mood tracking interface as part of the workflow with Personalized therapy session generator, Therapist directory with profiles in the workflow
- **Under_Review**: A process step that under review as part of the workflow with Verification Complete?, Approval Required? in the workflow
- **Virtual_consultation_booking_system**: A process step that virtual consultation booking system as part of the workflow with Personalized therapy session generator, Mood tracking interface in the workflow
- **Verification_Complete?**: A process step that verification complete? as part of the workflow with Approval Required?, Personalized therapy session generator in the workflow
- **Personalized_therapy_session_generator**: A process step that personalized therapy session generator as part of the workflow with Mood tracking interface, Therapist directory with profiles in the workflow


### plan

- **Progress_tracking_dashboard**: A pricing tier in MindWell AI-mvp1 offering specific features and capabilities for target users with Personalized therapy session generator, Mood tracking interface
- **Therapist_directory_with_profiles**: A pricing tier in MindWell AI-mvp1 offering specific features and capabilities for target users with Personalized therapy session generator, Mood tracking interface
- **Approval_Required?**: A pricing tier in MindWell AI-mvp1 offering specific features and capabilities for target users with Verification Complete?, Personalized therapy session generator
- **protocol**: A pricing tier in MindWell AI-mvp1 offering specific features and capabilities for target users with Core Care Coordination, treatment
- **Approved**: A pricing tier in MindWell AI-mvp1 offering specific features and capabilities for target users with Verification Complete?, Approval Required?


### phase

- **therapy**: A stage in the user journey where users therapy and progress through the journey with PAIN, POINT
- **emotional**: A stage in the user journey where users emotional and progress through the journey with PAIN, POINT
- **POINT**: A stage in the user journey where users point and progress through the journey with PAIN, Patient
- **tracking**: A stage in the user journey where users tracking and progress through the journey with PAIN, POINT
- **Care**: A stage in the user journey where users care and progress through the journey with PAIN, POINT
- **Core**: A stage in the user journey where users core and progress through the journey with PAIN, POINT
- **generator**: A stage in the user journey where users generator and progress through the journey with PAIN, POINT
- **Mood**: A stage in the user journey where users mood and progress through the journey with PAIN, POINT
- **Personalized**: A stage in the user journey where users personalized and progress through the journey with PAIN, POINT
- **Coordination**: A stage in the user journey where users coordination and progress through the journey with PAIN, POINT
- **session**: A stage in the user journey where users session and progress through the journey with PAIN, POINT
- **touchpoints**: A stage in the user journey where users touchpoints and progress through the journey with PAIN, POINT
- **PAIN**: A stage in the user journey where users pain and progress through the journey with POINT, Patient
- **Patient**: A stage in the user journey where users patient and progress through the journey with PAIN, POINT


### default

- **Hr**: A key element in the MindWell AI-mvp1 system related to system operations
- **System**: A key element in the MindWell AI-mvp1 system related to system operations
- **Persona**: A key element in the MindWell AI-mvp1 system related to system operations


### team

- **support**: A functional team responsible for specialized tasks and deliverables with Core Care Coordination, treatment in the workflow


---

## Source References

| Source Diagram | Entities Count |
|----------------|----------------|
| user_journey | 16 |
| swimlane | 5 |
| decision_tree | 9 |
| value_stream | 5 |
| business_process | 10 |

---

*Generated by MAS Compiler Glossary Generator*