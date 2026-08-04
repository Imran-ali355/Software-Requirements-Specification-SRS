# 📄 Software Requirements Specification (SRS) Documentation

## 📌 Project Overview
This repository serves as a centralized hub for the **Software Requirements Specification (SRS)** documentation, requirement analysis, functional solutions, and review records. It outlines the foundational software engineering specifications, user expectations, and technical constraints required for development and quality evaluation.

---

## 📂 Document Architecture & Files

| Document Name | Description | Status |
| :--- | :--- | :---: |
| **`SRS_Document.pdf`** | Primary Software Requirements Specification detailing functional & non-functional requirements. | 📤 Uploaded |
| **`SRS_Solution_Document.pdf`** | Comprehensive solution architecture, workflow maps, and requirement resolution details. | ⏳ Pending / Next |
| **`SRS_Highlighted_Review.pdf`** | Annotated and highlighted document focusing on key constraints, review points, and critical gaps. | ⏳ Pending / Next |

---

## 🎯 Key Scope & Requirement Coverage

### 1. Functional Requirements
- **User Roles & Authorization:** Module-level access controls and user authentication rules.
- **System Workflows:** Detailed feature flows, business logic, and error scenarios.
- **Data Input & Validations:** Form structures, mandatory parameters, and data formatting rules.

### 2. Non-Functional Requirements
- **Performance:** System response times, load capacities, and throughput benchmarks.
- **Security:** Data encryption standards, session management, and authentication security.
- **Usability & UI/UX:** Interface standards, accessibility, and cross-platform responsiveness.

---

## 🛠️ Tools & Technologies Used
* **Documentation & Analysis:** MS Word / Google Docs / Adobe Acrobat
* **Requirement Tracking:** GitHub / Markdown / SQA Traceability Matrix

* # 📑 SRS Review Report - Smart Campus Attendance & Leave Management System

## 📌 Overview & Scope
This repository branch contains the comprehensive **Software Requirements Specification (SRS) Review Report** for the **Smart Campus Attendance & Leave Management System**. 

The purpose of this exercise is to perform a rigorous Software Quality Assurance (SQA) review on the provided SRS document, identifying critical requirement defects, ambiguities, security risks, and feasibility issues prior to system implementation.

---

## 🌟 Document Strengths
- **Structured Layout:** Follows standard SQA sections (Introduction, Scope, Functional/Non-Functional Requirements, Security, Business Rules, and Acceptance Criteria).
- **Identified Identifiers:** Most requirements are tagged with requirement IDs for tracking.
- **Clear Categorization:** Functional and Non-Functional requirements are properly separated.
- **Contextual Detail:** Stakeholder roles, external interfaces, and business rules are explicitly documented.

---

## 📊 Summary of Review Findings

| Defect Category | Finding Summary | Impact | Recommendation |
| :--- | :--- | :--- | :--- |
| **Ambiguity** | Uses subjective terms like `'simple'`, `'urgent'`, and `'works as expected'`. | Cannot be tested or implemented consistently. | Replace subjective language with measurable, quantitative metrics. |
| **Contradiction** | Conflicting rules in authentication, training, audit, leave, and scope. | Developer confusion and inconsistent system behavior. | Conduct stakeholder alignment meetings to resolve conflicting rules. |
| **Incompleteness** | Missing approval workflow, age verification, translation ownership, and integration logic. | Incomplete system implementation and execution gaps. | Formally document missing business rules and interface parameters. |
| **Feasibility** | Unrealistic claims (e.g., 100% face recognition accuracy, notifications after app uninstall). | High implementation risk and potential project failure. | Revise expectations to align with real-world technical boundaries. |
| **Testability** | Terms like `'fast'` or `'expected'` lack concrete benchmarks. | QA team cannot objectively pass/fail test execution. | Define explicit SLA response times and clear pass/fail rules. |
| **Security** | Plain-text password storage requirements and conflicting session rules. | Critical security vulnerability and data breach exposure. | Enforce password hashing (e.g., bcrypt) and standard session timeouts. |
| **Usability** | Accessibility goals conflict with excluded keyboard/screen-reader support. | Poor user experience and failure to meet accessibility standards. | Adopt standard accessibility guidelines (WCAG compliance). |
| **Data Quality** | Duplicate Student IDs and inconsistent status definitions. | Data corruption and integrity issues in the database. | Define unique primary keys and standardized status values. |
| **Traceability** | Duplicate Requirement IDs and absence of a Traceability Matrix. | Requirement tracking across the lifecycle becomes impossible. | Enforce unique Requirement IDs and create a Requirement Traceability Matrix (RTM). |
| **Acceptance Criteria** | Subjective criteria for system sign-off. | Difficult to achieve formal project acceptance. | Define clear, verifiable criteria for each user story and scenario. |

---

## 📝 Overall Assessment & Conclusion
The SRS document serves as a practical exercise containing intentional defects for review practice. While the structural framework is solid, significant high-risk issues exist across **security, feasibility, data integrity, and testability**. 

> **Recommendation:** All identified findings should be logged in the defect tracking system and resolved with stakeholders before proceeding to design and architecture phases.

---

## 📂 File Architecture
- `SRS_Review_Report.docx` — Complete detailed review findings and analysis report.
- 
