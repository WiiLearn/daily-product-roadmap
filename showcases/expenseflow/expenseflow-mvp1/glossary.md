# Domain Glossary: Expenseflow Mvp1

> **Generated**: 2025-12-10 12:52:47  
> **Version**: 1.0.0

---

## Overview

Domain terminology extracted from MAS artifacts for **Expenseflow Mvp1**.

| Term | Type | Definition | Source |
|------|------|------------|--------|
| Integration_with_user_bank_statements | role | A stakeholder role in the ExpenseFlow-mvp1 system responsible for workflow activities and decision-making with ExpenseFlow, Automated receipt scanning system | decision_tree |
| Automated_Receipt_Scanning_System | role | A stakeholder role in the ExpenseFlow-mvp1 system responsible for workflow activities and decision-making with Expense Categorization Engine, User-Friendly Expense Dashboard | swimlane |
| Small_Business_Owner | role | A stakeholder role in the ExpenseFlow-mvp1 system responsible for workflow activities and decision-making | unknown |
| Ensures | phase | A stage in the user journey where users ensures and progress through the journey with Aligns, Addresses | user_journey |
| User_Bank_Statement_Integration | role | A stakeholder role in the ExpenseFlow-mvp1 system responsible for workflow activities and decision-making | unknown |
| Finance | default | A key element in the ExpenseFlow-mvp1 system related to system operations | unknown |
| Tax_report_generator | artifact | A tangible output representing analysis results and insights with ExpenseFlow, Automated receipt scanning system | decision_tree |
| Addresses | phase | A stage in the user journey where users addresses and progress through the journey with Aligns, Ensures | user_journey |
| Compliance | default | A key element in the ExpenseFlow-mvp1 system related to system operations | unknown |
| Product | plan | A pricing tier in ExpenseFlow-mvp1 offering specific features and capabilities for target users | unknown |
| Accounting_Software | step | A process step that accounting software as part of the workflow with Receipt Management System, Expense Categorization Engine in the workflow | business_process |
| Accountant | default | A key element in the ExpenseFlow-mvp1 system related to system operations | unknown |
| MVP1 | phase | A stage in the user journey where users mvp1 and progress through the journey with Aligns, Addresses | user_journey |
| Incorporates | phase | A stage in the user journey where users incorporates and progress through the journey with Aligns, Addresses | user_journey |
| Reflects | phase | A stage in the user journey where users reflects and progress through the journey with Aligns, Addresses | user_journey |
| Expense_categorization_engine | condition | A decision point that evaluates criteria to determine the appropriate outcome with ExpenseFlow, Automated receipt scanning system | decision_tree |
| ExpenseFlow | phase | A stage in the user journey where users expenseflow and progress through the journey with Aligns, Addresses | user_journey |
| User-friendly_expense_dashboard | role | A stakeholder role in the ExpenseFlow-mvp1 system responsible for workflow activities and decision-making with ExpenseFlow, Automated receipt scanning system | decision_tree |
| Receipt_Management_System | step | A process step that receipt management system as part of the workflow with Expense Categorization Engine, Tax Report Generator in the workflow | business_process |
| Receipt_Scanning_System | default | A key element in the ExpenseFlow-mvp1 system related to system operations | unknown |
| Expense_Dashboard | screen | A UI screen where users can view and interact with system features with Receipt Management System, Expense Categorization Engine | business_process |
| System | default | A key element in the ExpenseFlow-mvp1 system related to system operations | unknown |
| Hr | default | A key element in the ExpenseFlow-mvp1 system related to system operations | unknown |
| Financial_Manager | role | A stakeholder role in the ExpenseFlow-mvp1 system responsible for workflow activities and decision-making | unknown |
| User | role | A stakeholder role in the ExpenseFlow-mvp1 system responsible for workflow activities and decision-making | unknown |
| Aligns | phase | A stage in the user journey where users aligns and progress through the journey with Addresses, Ensures | user_journey |

---

## Entity Types


### role

- **Integration_with_user_bank_statements**: A stakeholder role in the ExpenseFlow-mvp1 system responsible for workflow activities and decision-making with ExpenseFlow, Automated receipt scanning system
- **Automated_Receipt_Scanning_System**: A stakeholder role in the ExpenseFlow-mvp1 system responsible for workflow activities and decision-making with Expense Categorization Engine, User-Friendly Expense Dashboard
- **Small_Business_Owner**: A stakeholder role in the ExpenseFlow-mvp1 system responsible for workflow activities and decision-making
- **User_Bank_Statement_Integration**: A stakeholder role in the ExpenseFlow-mvp1 system responsible for workflow activities and decision-making
- **User-friendly_expense_dashboard**: A stakeholder role in the ExpenseFlow-mvp1 system responsible for workflow activities and decision-making with ExpenseFlow, Automated receipt scanning system
- **Financial_Manager**: A stakeholder role in the ExpenseFlow-mvp1 system responsible for workflow activities and decision-making
- **User**: A stakeholder role in the ExpenseFlow-mvp1 system responsible for workflow activities and decision-making


### phase

- **Ensures**: A stage in the user journey where users ensures and progress through the journey with Aligns, Addresses
- **Addresses**: A stage in the user journey where users addresses and progress through the journey with Aligns, Ensures
- **MVP1**: A stage in the user journey where users mvp1 and progress through the journey with Aligns, Addresses
- **Incorporates**: A stage in the user journey where users incorporates and progress through the journey with Aligns, Addresses
- **Reflects**: A stage in the user journey where users reflects and progress through the journey with Aligns, Addresses
- **ExpenseFlow**: A stage in the user journey where users expenseflow and progress through the journey with Aligns, Addresses
- **Aligns**: A stage in the user journey where users aligns and progress through the journey with Addresses, Ensures


### default

- **Finance**: A key element in the ExpenseFlow-mvp1 system related to system operations
- **Compliance**: A key element in the ExpenseFlow-mvp1 system related to system operations
- **Accountant**: A key element in the ExpenseFlow-mvp1 system related to system operations
- **Receipt_Scanning_System**: A key element in the ExpenseFlow-mvp1 system related to system operations
- **System**: A key element in the ExpenseFlow-mvp1 system related to system operations
- **Hr**: A key element in the ExpenseFlow-mvp1 system related to system operations


### artifact

- **Tax_report_generator**: A tangible output representing analysis results and insights with ExpenseFlow, Automated receipt scanning system


### plan

- **Product**: A pricing tier in ExpenseFlow-mvp1 offering specific features and capabilities for target users


### step

- **Accounting_Software**: A process step that accounting software as part of the workflow with Receipt Management System, Expense Categorization Engine in the workflow
- **Receipt_Management_System**: A process step that receipt management system as part of the workflow with Expense Categorization Engine, Tax Report Generator in the workflow


### condition

- **Expense_categorization_engine**: A decision point that evaluates criteria to determine the appropriate outcome with ExpenseFlow, Automated receipt scanning system


### screen

- **Expense_Dashboard**: A UI screen where users can view and interact with system features with Receipt Management System, Expense Categorization Engine


---

## Source References

| Source Diagram | Entities Count |
|----------------|----------------|
| user_journey | 7 |
| swimlane | 5 |
| decision_tree | 6 |
| value_stream | 6 |
| business_process | 5 |

---

*Generated by MAS Compiler Glossary Generator*