# Domain Glossary: Greenthread Mvp1

> **Generated**: 2025-12-11 11:24:02  
> **Version**: 1.0.0

---

## Overview

Domain terminology extracted from MAS artifacts for **Greenthread Mvp1**.

| Term | Type | Definition | Source |
|------|------|------------|--------|
| Approval_Required? | plan | A pricing tier in GreenThread-mvp1 offering specific features and capabilities for target users with Verification Complete?, Eco-friendly brand directory | business_process |
| Carbon_footprint_calculator_for_purchases | step | A process step that carbon footprint calculator for purchases as part of the workflow with Eco-friendly brand directory, Clothing rental management system in the workflow | value_stream |
| Hr | default | A key element in the GreenThread-mvp1 system related to system operations | unknown |
| POINT | phase | A stage in the user journey where users point and progress through the journey with PAIN, Customer | user_journey |
| Delivery_Agent | agent | An AI agent that provides guidance and assistance with Customer, Seller for users | swimlane |
| Under_Review | step | A process step that under review as part of the workflow with Verification Complete?, Approval Required? in the workflow | business_process |
| touchpoints | phase | A stage in the user journey where users touchpoints and progress through the journey with PAIN, POINT | user_journey |
| Carbon | phase | A stage in the user journey where users carbon and progress through the journey with PAIN, POINT | user_journey |
| calculator | phase | A stage in the user journey where users calculator and progress through the journey with PAIN, POINT | user_journey |
| brand | phase | A stage in the user journey where users brand and progress through the journey with PAIN, POINT | user_journey |
| Commerce | phase | A stage in the user journey where users commerce and progress through the journey with PAIN, POINT | user_journey |
| Eco-friendly_brand_directory | step | A process step that eco-friendly brand directory as part of the workflow with Carbon footprint calculator for purchases, Clothing rental management system in the workflow | value_stream |
| Platform | screen | A UI screen where users can view and interact with system features with PAIN, POINT | user_journey |
| User | role | A stakeholder role in the GreenThread-mvp1 system responsible for workflow activities and decision-making | unknown |
| PAIN | phase | A stage in the user journey where users pain and progress through the journey with POINT, Customer | user_journey |
| Warehouse_Staff | role | A stakeholder role in the GreenThread-mvp1 system responsible for workflow activities and decision-making with Customer, Seller | swimlane |
| HIGH | condition | A decision point that evaluates criteria to determine the appropriate outcome with Core Commerce Platform, Standard threshold | decision_tree |
| Core | phase | A stage in the user journey where users core and progress through the journey with PAIN, POINT | user_journey |
| footprint | phase | A stage in the user journey where users footprint and progress through the journey with PAIN, POINT | user_journey |
| MEDIUM | condition | A decision point that evaluates criteria to determine the appropriate outcome with Core Commerce Platform, Standard threshold | decision_tree |
| Approved | plan | A pricing tier in GreenThread-mvp1 offering specific features and capabilities for target users with Verification Complete?, Approval Required? | business_process |
| Clothing_rental_management_system | step | A process step that clothing rental management system as part of the workflow with Eco-friendly brand directory, Carbon footprint calculator for purchases in the workflow | value_stream |
| Standard_threshold | condition | A decision point that evaluates criteria to determine the appropriate outcome with Core Commerce Platform, LOW | decision_tree |
| Customer_Support | role | A stakeholder role in the GreenThread-mvp1 system responsible for workflow activities and decision-making with Customer, Seller | swimlane |
| LOW | condition | A decision point that evaluates criteria to determine the appropriate outcome with Core Commerce Platform, Standard threshold | decision_tree |
| score | condition | A decision point that evaluates criteria to determine the appropriate outcome with PAIN, POINT | user_journey |
| directory | phase | A stage in the user journey where users directory and progress through the journey with PAIN, POINT | user_journey |
| Rejected | step | A process step that rejected as part of the workflow with Verification Complete?, Approval Required? in the workflow | business_process |
| CRITICAL | condition | A decision point that evaluates criteria to determine the appropriate outcome with Core Commerce Platform, Standard threshold | decision_tree |
| Warehouse | default | A key element in the GreenThread-mvp1 system related to system operations | unknown |
| Core_Commerce_Platform | screen | A UI screen where users can view and interact with system features with Standard threshold, LOW | decision_tree |
| friendly | phase | A stage in the user journey where users friendly and progress through the journey with PAIN, POINT | user_journey |
| emotional | phase | A stage in the user journey where users emotional and progress through the journey with PAIN, POINT | user_journey |
| Support | team | A functional team responsible for specialized tasks and deliverables in the workflow | unknown |
| Resale_marketplace_for_pre-owned_clothing | step | A process step that resale marketplace for pre-owned clothing as part of the workflow with Eco-friendly brand directory, Carbon footprint calculator for purchases in the workflow | value_stream |
| Complete | step | A process step that complete as part of the workflow with PAIN, POINT in the workflow | user_journey |
| System | default | A key element in the GreenThread-mvp1 system related to system operations | unknown |
| Verification_Complete? | step | A process step that verification complete? as part of the workflow with Approval Required?, Eco-friendly brand directory in the workflow | business_process |
| Seller | role | A stakeholder role in the GreenThread-mvp1 system responsible for workflow activities and decision-making with Customer, Warehouse Staff | swimlane |
| Customer | role | A stakeholder role in the GreenThread-mvp1 system responsible for workflow activities and decision-making with PAIN, POINT | user_journey |
| User_profile_for_sustainable_preferences | role | A stakeholder role in the GreenThread-mvp1 system responsible for workflow activities and decision-making with Eco-friendly brand directory, Carbon footprint calculator for purchases | value_stream |

---

## Entity Types


### plan

- **Approval_Required?**: A pricing tier in GreenThread-mvp1 offering specific features and capabilities for target users with Verification Complete?, Eco-friendly brand directory
- **Approved**: A pricing tier in GreenThread-mvp1 offering specific features and capabilities for target users with Verification Complete?, Approval Required?


### step

- **Carbon_footprint_calculator_for_purchases**: A process step that carbon footprint calculator for purchases as part of the workflow with Eco-friendly brand directory, Clothing rental management system in the workflow
- **Under_Review**: A process step that under review as part of the workflow with Verification Complete?, Approval Required? in the workflow
- **Eco-friendly_brand_directory**: A process step that eco-friendly brand directory as part of the workflow with Carbon footprint calculator for purchases, Clothing rental management system in the workflow
- **Clothing_rental_management_system**: A process step that clothing rental management system as part of the workflow with Eco-friendly brand directory, Carbon footprint calculator for purchases in the workflow
- **Rejected**: A process step that rejected as part of the workflow with Verification Complete?, Approval Required? in the workflow
- **Resale_marketplace_for_pre-owned_clothing**: A process step that resale marketplace for pre-owned clothing as part of the workflow with Eco-friendly brand directory, Carbon footprint calculator for purchases in the workflow
- **Complete**: A process step that complete as part of the workflow with PAIN, POINT in the workflow
- **Verification_Complete?**: A process step that verification complete? as part of the workflow with Approval Required?, Eco-friendly brand directory in the workflow


### default

- **Hr**: A key element in the GreenThread-mvp1 system related to system operations
- **Warehouse**: A key element in the GreenThread-mvp1 system related to system operations
- **System**: A key element in the GreenThread-mvp1 system related to system operations


### phase

- **POINT**: A stage in the user journey where users point and progress through the journey with PAIN, Customer
- **touchpoints**: A stage in the user journey where users touchpoints and progress through the journey with PAIN, POINT
- **Carbon**: A stage in the user journey where users carbon and progress through the journey with PAIN, POINT
- **calculator**: A stage in the user journey where users calculator and progress through the journey with PAIN, POINT
- **brand**: A stage in the user journey where users brand and progress through the journey with PAIN, POINT
- **Commerce**: A stage in the user journey where users commerce and progress through the journey with PAIN, POINT
- **PAIN**: A stage in the user journey where users pain and progress through the journey with POINT, Customer
- **Core**: A stage in the user journey where users core and progress through the journey with PAIN, POINT
- **footprint**: A stage in the user journey where users footprint and progress through the journey with PAIN, POINT
- **directory**: A stage in the user journey where users directory and progress through the journey with PAIN, POINT
- **friendly**: A stage in the user journey where users friendly and progress through the journey with PAIN, POINT
- **emotional**: A stage in the user journey where users emotional and progress through the journey with PAIN, POINT


### agent

- **Delivery_Agent**: An AI agent that provides guidance and assistance with Customer, Seller for users


### screen

- **Platform**: A UI screen where users can view and interact with system features with PAIN, POINT
- **Core_Commerce_Platform**: A UI screen where users can view and interact with system features with Standard threshold, LOW


### role

- **User**: A stakeholder role in the GreenThread-mvp1 system responsible for workflow activities and decision-making
- **Warehouse_Staff**: A stakeholder role in the GreenThread-mvp1 system responsible for workflow activities and decision-making with Customer, Seller
- **Customer_Support**: A stakeholder role in the GreenThread-mvp1 system responsible for workflow activities and decision-making with Customer, Seller
- **Seller**: A stakeholder role in the GreenThread-mvp1 system responsible for workflow activities and decision-making with Customer, Warehouse Staff
- **Customer**: A stakeholder role in the GreenThread-mvp1 system responsible for workflow activities and decision-making with PAIN, POINT
- **User_profile_for_sustainable_preferences**: A stakeholder role in the GreenThread-mvp1 system responsible for workflow activities and decision-making with Eco-friendly brand directory, Carbon footprint calculator for purchases


### condition

- **HIGH**: A decision point that evaluates criteria to determine the appropriate outcome with Core Commerce Platform, Standard threshold
- **MEDIUM**: A decision point that evaluates criteria to determine the appropriate outcome with Core Commerce Platform, Standard threshold
- **Standard_threshold**: A decision point that evaluates criteria to determine the appropriate outcome with Core Commerce Platform, LOW
- **LOW**: A decision point that evaluates criteria to determine the appropriate outcome with Core Commerce Platform, Standard threshold
- **score**: A decision point that evaluates criteria to determine the appropriate outcome with PAIN, POINT
- **CRITICAL**: A decision point that evaluates criteria to determine the appropriate outcome with Core Commerce Platform, Standard threshold


### team

- **Support**: A functional team responsible for specialized tasks and deliverables in the workflow


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