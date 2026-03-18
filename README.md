## User Stories

**User Story 1: Admin**  
As an admin, I want to manage user accounts so that I can control access to the system.

**User Story 2: Kitchen Staff**  
As a kitchen staff member, I want to view and update the menu so that I can keep it current.

**User Story 3: Customer**  
As a customer, I want to view the menu and place orders so that I can purchase food items.

## Use Cases

| Use Case ID | Use Case Name   | Description                          | Actors       | Pre-conditions | Post-conditions |
|-------------|-----------------|--------------------------------------|--------------|----------------|-----------------|
| UC1         | Create Account  | Admin creates a new user account.    | Admin        | Admin logged in| Account created |
| UC2         | Edit Account    | Admin edits an existing user account.| Admin        | Admin logged in| Account updated |
| UC3         | View Menu       | Customer views the available menu items.| Customer | None           | Menu displayed  |
| UC4         | Update Menu     | Kitchen staff updates the menu items.| Kitchen Staff| Staff logged in| Menu updated    |
| UC5         | Place Order     | Customer places an order for food items.| Customer | Customer logged in| Order placed  |
| UC6         | Approve Account | Admin approves a new user account.   | Admin        | Admin logged in| Account approved|



![Sequence Diagram for Campus Bites](CampusBites/diagrams/sequenceDiagramCampusBites.png)





# Project Charter for Campus Bites

**Version 1.0 approved**

**Prepared by:**
- Valentin-Mihai Ghiţă
- Adrian Ilie Boabeş
- Dorian Crudu
- Andrei Adiaconiţei

**ULBS**

**19.10.2024**

---

## Table of Contents
1. [Project Description](#1-project-description)
2. [Business Objectives and Success Criteria](#2-business-objectives-and-success-criteria)
3. [Stakeholders](#3-stakeholders)
4. [Vision](#4-vision)
5. [Project Scope](#5-project-scope)
6. [Assumptions and Dependencies](#6-assumptions-and-dependencies)
7. [Constraints](#7-constraints)
8. [Milestones](#8-milestones)
9. [Business Risks](#9-business-risks)
10. [Resources](#10-resources)
11. [Approvals](#11-approvals)
12. [Revision History](#12-revision-history)

---

## 1. Project Description
Campus Bites is an ordering application for the campus cafeteria, from which students and teachers can order meals with afferent discounts based on their role within the University. The application provides an easy-to-use UI for searching, selecting, and ordering from the cafeteria menu. It has both customer-based and management portals. From the management side, the employees of the cafeteria can manage the quantity of different items from the menu and add or remove existing items to represent the real inventory.

## 2. Business Objectives and Success Criteria
- **Improve efficiency:** Cutting down on time wasted by the staff for placing orders, at least by 30%.
- **Improve revenue:** Reduced waiting time will boost customer retention, which in turn should provide a revenue boost of at least 20%.
- **Cutting costs:** By following a statistical-led business strategy in the following quarters, the costs for products sold in small amounts will be cut to prevent waste and items with a tendency of running out will be prioritized. This in turn will reduce costs by at least 10%.

## 3. Stakeholders
- **ULBS Campus Cafeteria**
  - **Major Benefits:** Streamlined operations, higher revenue
  - **Attitudes:** Supportive
  - **Win Conditions:** Increased profitability
  - **Constraints:** Limited budget
- **Students/Faculty**
  - **Major Benefits:** Reduced wait times, discounts
  - **Attitudes:** Enthusiastic
  - **Win Conditions:** User-friendly interface
  - **Constraints:** Internet connectivity
- **Project Sponsor**
  - **Major Benefits:** Meets strategic goals
  - **Attitudes:** Invested
  - **Win Conditions:** Timely delivery
  - **Constraints:** Budget adherence
- **Project Manager**
  - **Major Benefits:** Clear deliverables, resource allocation
  - **Attitudes:** Proactive
  - **Win Conditions:** On-time execution
  - **Constraints:** Team availability

## 4. Vision
For the professors and students at ULBS who order food regularly at the cafeteria, the Campus Bites app is a portal that saves time spent on ordering and paying for food. Unlike the traditional tray pushing and cashier-led ordering/payment system, our product leaves the freedom of selecting or browsing the menu to the customers who pay before interacting with the staff and can be called once their order is done, not being required to stand in line the whole time.

## 5. Project Scope
- **In Scope:**
  - Development of a customer app for menu browsing, ordering, and payments.
  - Management portal for cafeteria staff to manage inventory and menu items.
  - Integration with payment gateways and notification systems.
  - Role-based discount application.
- **Out of Scope:**
  - Delivery services.
  - Integration with external food platforms (e.g., Uber Eats).

## 6. Assumptions and Dependencies
- **Assumptions:**
  - Users will have access to smartphones and internet connections.
  - Cafeteria management will provide up-to-date inventory data.
  - Cafeteria will have a running server.
- **Dependencies:**
  - Syncfusion: UI components.
  - Bootstrap: Responsive front-end design.

## 7. Constraints
| Dimension | Constraint | Driver | Degree of Freedom |
|-----------|------------|--------|-------------------|
| Features  | 70-80% of high-priority features in v1.0 | On-time delivery | Minor feature adjustments |
| Quality   | 90% user acceptance test pass rate | Usability and reliability | Incremental improvements |
| Cost      | Max 15% budget overrun | Budget adherence | Limited additional funds |
| Schedule  | Release by 10/01/2025 | Release 1.0 to be available by 10/1, release 1.1 by 12/1 | Limited buffer time |
| Staff     | Team of 4 fullstack developers | Efficient execution | Resource sharing |

## 8. Milestones
| Event or Deliverable | Target Date | Responsibility |
|----------------------|-------------|----------------|
| Project charter approved | | |
| Project plan completed | | |
| Project plan approved | | |
| Project team assembled | | |
| Project execution initiated | | |
| Project execution completed | | |
| Customer acceptance | | |
| Project closed out | | |

## 9. Business Risks
| Risk | Probability | Impact | Mitigation |
|------|-------------|--------|------------|
| Low user adoption | Medium | High | Marketing and awareness campaigns |
| Payment gateway integration issues | Low | High | Early vendor communication |
| System downtime during launch | Medium | Medium | Backup servers and stress testing |
| Data privacy concerns | Medium | High | Compliance with GDPR and encryption |

## 10. Resources
| Resource | Description and Source |
|----------|------------------------|
| Human Resources | 6 developers, 4 testers |
| Tools | Syncfusion, Bootstrap, GitHub, Visual Studio, IntelliJ (Java), Figma, Draw.io |
| Hardware | Servers, client devices |
| Funding | Not provided, team made out of slaves |

## 11. Approvals
This section documents the status of the charter following submission for approval. Listed below are the names and roles of individuals responsible for approving the charter. Approval signifies agreement with the charter's content, acknowledgment that it serves as the foundation for the project, and commitment to keeping its information current and relevant throughout the project's lifecycle.

**Approval Decision:**
- [ ] Approved, development of detailed project plan is authorized
- [ ] Approved, project execution is authorized
- [ ] Approved, but project is on hold until future notice
- [ ] Revise charter and resubmit for approval
- [ ] Charter and project proposal are rejected

| Role or Title | Name and Signature | Date |
|---------------|--------------------|------|
| Project Sponsor | Dorobantiu Alexandru | |
| Project Manager | Ghita Valentin-Mihai | |
| Developer 1 | Boabes Adrian-Ilie | |
| Developer 2 | Crudu Dorian | |
| Developer 3 | Adiaconitei Andrei | |

## 12. Revision History
| Name | Date | Reason For Changes | Version |
|------|------|--------------------|---------|
|      |      |                    |         |
# first-test-repository
