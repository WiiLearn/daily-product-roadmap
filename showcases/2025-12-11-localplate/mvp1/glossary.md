# Domain Glossary: Localplate Mvp1

> **Generated**: 2025-12-11 11:29:13  
> **Version**: 1.0.0

---

## Overview

Domain terminology extracted from MAS artifacts for **Localplate Mvp1**.

| Term | Type | Definition | Source |
|------|------|------------|--------|
| service | component | A system component that handles service operations with PAIN, POINT | user_journey |
| catalog | phase | A stage in the user journey where users catalog and progress through the journey with PAIN, POINT | user_journey |
| Approval_Required? | plan | A pricing tier in LocalPlate-mvp1 offering specific features and capabilities for target users with Verification Complete?, Local artisan product catalog | business_process |
| Hr | default | A key element in the LocalPlate-mvp1 system related to system operations | unknown |
| POINT | phase | A stage in the user journey where users point and progress through the journey with PAIN, Customer | user_journey |
| Delivery_Agent | agent | An AI agent that provides guidance and assistance with Customer, Seller for users | swimlane |
| Under_Review | step | A process step that under review as part of the workflow with Verification Complete?, Approval Required? in the workflow | business_process |
| touchpoints | phase | A stage in the user journey where users touchpoints and progress through the journey with PAIN, POINT | user_journey |
| ticket | condition | A decision point that evaluates criteria to determine the appropriate outcome with Core Commerce Platform, shipping | decision_tree |
| Secure_payment_processing_system | plan | A pricing tier in LocalPlate-mvp1 offering specific features and capabilities for target users with Local artisan product catalog, Subscription box service for seasonal produce | value_stream |
| logistics | condition | A decision point that evaluates criteria to determine the appropriate outcome with Core Commerce Platform, shipping | decision_tree |
| Commerce | phase | A stage in the user journey where users commerce and progress through the journey with PAIN, POINT | user_journey |
| carrier | condition | A decision point that evaluates criteria to determine the appropriate outcome with Core Commerce Platform, shipping | decision_tree |
| Platform | screen | A UI screen where users can view and interact with system features with PAIN, POINT | user_journey |
| PAIN | phase | A stage in the user journey where users pain and progress through the journey with POINT, Customer | user_journey |
| Warehouse_Staff | role | A stakeholder role in the LocalPlate-mvp1 system responsible for workflow activities and decision-making with Customer, Seller | swimlane |
| Vendor | default | A key element in the LocalPlate-mvp1 system related to system operations | unknown |
| Core | phase | A stage in the user journey where users core and progress through the journey with PAIN, POINT | user_journey |
| support | team | A functional team responsible for specialized tasks and deliverables with Core Commerce Platform, shipping in the workflow | decision_tree |
| Product | plan | A pricing tier in LocalPlate-mvp1 offering specific features and capabilities for target users | unknown |
| feature | condition | A decision point that evaluates criteria to determine the appropriate outcome with Core Commerce Platform, shipping | decision_tree |
| Approved | plan | A pricing tier in LocalPlate-mvp1 offering specific features and capabilities for target users with Verification Complete?, Approval Required? | business_process |
| Subscription_box_service_for_seasonal_produce | plan | A pricing tier in LocalPlate-mvp1 offering specific features and capabilities for target users with Local artisan product catalog, Same-day delivery scheduling system | value_stream |
| delivery | condition | A decision point that evaluates criteria to determine the appropriate outcome with Core Commerce Platform, shipping | decision_tree |
| Same-day_delivery_scheduling_system | step | A process step that same-day delivery scheduling system as part of the workflow with Local artisan product catalog, Subscription box service for seasonal produce in the workflow | value_stream |
| Shipping | default | A key element in the LocalPlate-mvp1 system related to system operations | unknown |
| Customer_Support | role | A stakeholder role in the LocalPlate-mvp1 system responsible for workflow activities and decision-making with Customer, Seller | swimlane |
| access | condition | A decision point that evaluates criteria to determine the appropriate outcome with Core Commerce Platform, shipping | decision_tree |
| score | condition | A decision point that evaluates criteria to determine the appropriate outcome with PAIN, POINT | user_journey |
| Local | phase | A stage in the user journey where users local and progress through the journey with PAIN, POINT | user_journey |
| Rejected | step | A process step that rejected as part of the workflow with Verification Complete?, Approval Required? in the workflow | business_process |
| Warehouse | default | A key element in the LocalPlate-mvp1 system related to system operations | unknown |
| Core_Commerce_Platform | screen | A UI screen where users can view and interact with system features with shipping, delivery | decision_tree |
| User_reviews_and_ratings_for_vendors | role | A stakeholder role in the LocalPlate-mvp1 system responsible for workflow activities and decision-making with Local artisan product catalog, Subscription box service for seasonal produce | value_stream |
| artisan | phase | A stage in the user journey where users artisan and progress through the journey with PAIN, POINT | user_journey |
| Local_artisan_product_catalog | plan | A pricing tier in LocalPlate-mvp1 offering specific features and capabilities for target users with Subscription box service for seasonal produce, Same-day delivery scheduling system | value_stream |
| emotional | phase | A stage in the user journey where users emotional and progress through the journey with PAIN, POINT | user_journey |
| Subscription | phase | A stage in the user journey where users subscription and progress through the journey with PAIN, POINT | user_journey |
| Complete | step | A process step that complete as part of the workflow with PAIN, POINT in the workflow | user_journey |
| System | default | A key element in the LocalPlate-mvp1 system related to system operations | unknown |
| Verification_Complete? | step | A process step that verification complete? as part of the workflow with Approval Required?, Local artisan product catalog in the workflow | business_process |
| Seller | role | A stakeholder role in the LocalPlate-mvp1 system responsible for workflow activities and decision-making with Customer, Warehouse Staff | swimlane |
| Customer | role | A stakeholder role in the LocalPlate-mvp1 system responsible for workflow activities and decision-making with PAIN, POINT | user_journey |
| User | role | A stakeholder role in the LocalPlate-mvp1 system responsible for workflow activities and decision-making | unknown |

---

## Entity Types


### component

- **service**: A system component that handles service operations with PAIN, POINT


### phase

- **catalog**: A stage in the user journey where users catalog and progress through the journey with PAIN, POINT
- **POINT**: A stage in the user journey where users point and progress through the journey with PAIN, Customer
- **touchpoints**: A stage in the user journey where users touchpoints and progress through the journey with PAIN, POINT
- **Commerce**: A stage in the user journey where users commerce and progress through the journey with PAIN, POINT
- **PAIN**: A stage in the user journey where users pain and progress through the journey with POINT, Customer
- **Core**: A stage in the user journey where users core and progress through the journey with PAIN, POINT
- **Local**: A stage in the user journey where users local and progress through the journey with PAIN, POINT
- **artisan**: A stage in the user journey where users artisan and progress through the journey with PAIN, POINT
- **emotional**: A stage in the user journey where users emotional and progress through the journey with PAIN, POINT
- **Subscription**: A stage in the user journey where users subscription and progress through the journey with PAIN, POINT


### plan

- **Approval_Required?**: A pricing tier in LocalPlate-mvp1 offering specific features and capabilities for target users with Verification Complete?, Local artisan product catalog
- **Secure_payment_processing_system**: A pricing tier in LocalPlate-mvp1 offering specific features and capabilities for target users with Local artisan product catalog, Subscription box service for seasonal produce
- **Product**: A pricing tier in LocalPlate-mvp1 offering specific features and capabilities for target users
- **Approved**: A pricing tier in LocalPlate-mvp1 offering specific features and capabilities for target users with Verification Complete?, Approval Required?
- **Subscription_box_service_for_seasonal_produce**: A pricing tier in LocalPlate-mvp1 offering specific features and capabilities for target users with Local artisan product catalog, Same-day delivery scheduling system
- **Local_artisan_product_catalog**: A pricing tier in LocalPlate-mvp1 offering specific features and capabilities for target users with Subscription box service for seasonal produce, Same-day delivery scheduling system


### default

- **Hr**: A key element in the LocalPlate-mvp1 system related to system operations
- **Vendor**: A key element in the LocalPlate-mvp1 system related to system operations
- **Shipping**: A key element in the LocalPlate-mvp1 system related to system operations
- **Warehouse**: A key element in the LocalPlate-mvp1 system related to system operations
- **System**: A key element in the LocalPlate-mvp1 system related to system operations


### agent

- **Delivery_Agent**: An AI agent that provides guidance and assistance with Customer, Seller for users


### step

- **Under_Review**: A process step that under review as part of the workflow with Verification Complete?, Approval Required? in the workflow
- **Same-day_delivery_scheduling_system**: A process step that same-day delivery scheduling system as part of the workflow with Local artisan product catalog, Subscription box service for seasonal produce in the workflow
- **Rejected**: A process step that rejected as part of the workflow with Verification Complete?, Approval Required? in the workflow
- **Complete**: A process step that complete as part of the workflow with PAIN, POINT in the workflow
- **Verification_Complete?**: A process step that verification complete? as part of the workflow with Approval Required?, Local artisan product catalog in the workflow


### condition

- **ticket**: A decision point that evaluates criteria to determine the appropriate outcome with Core Commerce Platform, shipping
- **logistics**: A decision point that evaluates criteria to determine the appropriate outcome with Core Commerce Platform, shipping
- **carrier**: A decision point that evaluates criteria to determine the appropriate outcome with Core Commerce Platform, shipping
- **feature**: A decision point that evaluates criteria to determine the appropriate outcome with Core Commerce Platform, shipping
- **delivery**: A decision point that evaluates criteria to determine the appropriate outcome with Core Commerce Platform, shipping
- **access**: A decision point that evaluates criteria to determine the appropriate outcome with Core Commerce Platform, shipping
- **score**: A decision point that evaluates criteria to determine the appropriate outcome with PAIN, POINT


### screen

- **Platform**: A UI screen where users can view and interact with system features with PAIN, POINT
- **Core_Commerce_Platform**: A UI screen where users can view and interact with system features with shipping, delivery


### role

- **Warehouse_Staff**: A stakeholder role in the LocalPlate-mvp1 system responsible for workflow activities and decision-making with Customer, Seller
- **Customer_Support**: A stakeholder role in the LocalPlate-mvp1 system responsible for workflow activities and decision-making with Customer, Seller
- **User_reviews_and_ratings_for_vendors**: A stakeholder role in the LocalPlate-mvp1 system responsible for workflow activities and decision-making with Local artisan product catalog, Subscription box service for seasonal produce
- **Seller**: A stakeholder role in the LocalPlate-mvp1 system responsible for workflow activities and decision-making with Customer, Warehouse Staff
- **Customer**: A stakeholder role in the LocalPlate-mvp1 system responsible for workflow activities and decision-making with PAIN, POINT
- **User**: A stakeholder role in the LocalPlate-mvp1 system responsible for workflow activities and decision-making


### team

- **support**: A functional team responsible for specialized tasks and deliverables with Core Commerce Platform, shipping in the workflow


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