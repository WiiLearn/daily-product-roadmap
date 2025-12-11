# Domain Glossary: Greenthread Mvp3

> **Generated**: 2025-12-11 11:24:57  
> **Version**: 1.0.0

---

## Overview

Domain terminology extracted from MAS artifacts for **Greenthread Mvp3**.

| Term | Type | Definition | Source |
|------|------|------------|--------|
| Approval_Required? | plan | A pricing tier in GreenThread-mvp3 offering specific features and capabilities for target users with Verification Complete?, Approved | business_process |
| Hr | default | A key element in the GreenThread-mvp3 system related to system operations | unknown |
| POINT | phase | A stage in the user journey where users point and progress through the journey with USING, MVP1 | user_journey |
| Delivery_Agent | agent | An AI agent that provides guidance and assistance with Customer, Seller for users | swimlane |
| Under_Review | step | A process step that under review as part of the workflow with Verification Complete?, Approval Required? in the workflow | business_process |
| Third-party_service_integrations | component | A system component that handles third-party service integrations operations with Partnership interface, Loyalty rewards program | value_stream |
| USING | phase | A stage in the user journey where users using and progress through the journey with MVP1, MVP2 | user_journey |
| PAIN | phase | A stage in the user journey where users pain and progress through the journey with USING, MVP1 | user_journey |
| Warehouse_Staff | role | A stakeholder role in the GreenThread-mvp3 system responsible for workflow activities and decision-making with Customer, Seller | swimlane |
| HIGH | condition | A decision point that evaluates criteria to determine the appropriate outcome with Marketplace Ecosystem, condition | decision_tree |
| Marketplace_Ecosystem | condition | A decision point that evaluates criteria to determine the appropriate outcome with condition, action | decision_tree |
| MEDIUM | condition | A decision point that evaluates criteria to determine the appropriate outcome with Marketplace Ecosystem, condition | decision_tree |
| condition | condition | A decision point that evaluates criteria to determine the appropriate outcome with Marketplace Ecosystem, action | decision_tree |
| Approved | plan | A pricing tier in GreenThread-mvp3 offering specific features and capabilities for target users with Verification Complete?, Approval Required? | business_process |
| action | step | A process step that action as part of the workflow with Marketplace Ecosystem, condition in the workflow | decision_tree |
| Standard_threshold | condition | A decision point that evaluates criteria to determine the appropriate outcome with Marketplace Ecosystem, condition | decision_tree |
| Customer_Support | role | A stakeholder role in the GreenThread-mvp3 system responsible for workflow activities and decision-making with Customer, Seller | swimlane |
| LOW | condition | A decision point that evaluates criteria to determine the appropriate outcome with Marketplace Ecosystem, condition | decision_tree |
| Sustainable_Brands | default | A key element in the GreenThread-mvp3 system related to system operations | unknown |
| Third-party_Service_Providers | plan | A pricing tier in GreenThread-mvp3 offering specific features and capabilities for target users | unknown |
| Collaborative_marketplace_features | step | A process step that collaborative marketplace features as part of the workflow with Third-party service integrations, Partnership interface in the workflow | value_stream |
| Rejected | step | A process step that rejected as part of the workflow with Verification Complete?, Approval Required? in the workflow | business_process |
| CRITICAL | condition | A decision point that evaluates criteria to determine the appropriate outcome with Marketplace Ecosystem, condition | decision_tree |
| Social_sharing_features | step | A process step that social sharing features as part of the workflow with Third-party service integrations, Partnership interface in the workflow | value_stream |
| Warehouse | default | A key element in the GreenThread-mvp3 system related to system operations | unknown |
| Loyalty_rewards_program | plan | A pricing tier in GreenThread-mvp3 offering specific features and capabilities for target users with Third-party service integrations, Partnership interface | value_stream |
| Partnership_interface | step | A process step that partnership interface as part of the workflow with Third-party service integrations, Loyalty rewards program in the workflow | value_stream |
| MVP1 | phase | A stage in the user journey where users mvp1 and progress through the journey with USING, MVP2 | user_journey |
| Support | team | A functional team responsible for specialized tasks and deliverables in the workflow | unknown |
| System | default | A key element in the GreenThread-mvp3 system related to system operations | unknown |
| Verification_Complete? | step | A process step that verification complete? as part of the workflow with Approval Required?, Approved in the workflow | business_process |
| Seller | role | A stakeholder role in the GreenThread-mvp3 system responsible for workflow activities and decision-making with Customer, Warehouse Staff | swimlane |
| Customer | role | A stakeholder role in the GreenThread-mvp3 system responsible for workflow activities and decision-making with Seller, Warehouse Staff | swimlane |
| MVP2 | phase | A stage in the user journey where users mvp2 and progress through the journey with USING, MVP1 | user_journey |

---

## Entity Types


### plan

- **Approval_Required?**: A pricing tier in GreenThread-mvp3 offering specific features and capabilities for target users with Verification Complete?, Approved
- **Approved**: A pricing tier in GreenThread-mvp3 offering specific features and capabilities for target users with Verification Complete?, Approval Required?
- **Third-party_Service_Providers**: A pricing tier in GreenThread-mvp3 offering specific features and capabilities for target users
- **Loyalty_rewards_program**: A pricing tier in GreenThread-mvp3 offering specific features and capabilities for target users with Third-party service integrations, Partnership interface


### default

- **Hr**: A key element in the GreenThread-mvp3 system related to system operations
- **Sustainable_Brands**: A key element in the GreenThread-mvp3 system related to system operations
- **Warehouse**: A key element in the GreenThread-mvp3 system related to system operations
- **System**: A key element in the GreenThread-mvp3 system related to system operations


### phase

- **POINT**: A stage in the user journey where users point and progress through the journey with USING, MVP1
- **USING**: A stage in the user journey where users using and progress through the journey with MVP1, MVP2
- **PAIN**: A stage in the user journey where users pain and progress through the journey with USING, MVP1
- **MVP1**: A stage in the user journey where users mvp1 and progress through the journey with USING, MVP2
- **MVP2**: A stage in the user journey where users mvp2 and progress through the journey with USING, MVP1


### agent

- **Delivery_Agent**: An AI agent that provides guidance and assistance with Customer, Seller for users


### step

- **Under_Review**: A process step that under review as part of the workflow with Verification Complete?, Approval Required? in the workflow
- **action**: A process step that action as part of the workflow with Marketplace Ecosystem, condition in the workflow
- **Collaborative_marketplace_features**: A process step that collaborative marketplace features as part of the workflow with Third-party service integrations, Partnership interface in the workflow
- **Rejected**: A process step that rejected as part of the workflow with Verification Complete?, Approval Required? in the workflow
- **Social_sharing_features**: A process step that social sharing features as part of the workflow with Third-party service integrations, Partnership interface in the workflow
- **Partnership_interface**: A process step that partnership interface as part of the workflow with Third-party service integrations, Loyalty rewards program in the workflow
- **Verification_Complete?**: A process step that verification complete? as part of the workflow with Approval Required?, Approved in the workflow


### component

- **Third-party_service_integrations**: A system component that handles third-party service integrations operations with Partnership interface, Loyalty rewards program


### role

- **Warehouse_Staff**: A stakeholder role in the GreenThread-mvp3 system responsible for workflow activities and decision-making with Customer, Seller
- **Customer_Support**: A stakeholder role in the GreenThread-mvp3 system responsible for workflow activities and decision-making with Customer, Seller
- **Seller**: A stakeholder role in the GreenThread-mvp3 system responsible for workflow activities and decision-making with Customer, Warehouse Staff
- **Customer**: A stakeholder role in the GreenThread-mvp3 system responsible for workflow activities and decision-making with Seller, Warehouse Staff


### condition

- **HIGH**: A decision point that evaluates criteria to determine the appropriate outcome with Marketplace Ecosystem, condition
- **Marketplace_Ecosystem**: A decision point that evaluates criteria to determine the appropriate outcome with condition, action
- **MEDIUM**: A decision point that evaluates criteria to determine the appropriate outcome with Marketplace Ecosystem, condition
- **condition**: A decision point that evaluates criteria to determine the appropriate outcome with Marketplace Ecosystem, action
- **Standard_threshold**: A decision point that evaluates criteria to determine the appropriate outcome with Marketplace Ecosystem, condition
- **LOW**: A decision point that evaluates criteria to determine the appropriate outcome with Marketplace Ecosystem, condition
- **CRITICAL**: A decision point that evaluates criteria to determine the appropriate outcome with Marketplace Ecosystem, condition


### team

- **Support**: A functional team responsible for specialized tasks and deliverables in the workflow


---

## Source References

| Source Diagram | Entities Count |
|----------------|----------------|
| user_journey | 5 |
| swimlane | 5 |
| decision_tree | 8 |
| value_stream | 7 |
| business_process | 5 |

---

*Generated by MAS Compiler Glossary Generator*