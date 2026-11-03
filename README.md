# ICT Cell Service Automation

A Software Requirements Specification (SRS) and system analysis document for a centralized service automation platform designed for the ICT Cell of the University of Dhaka.

## Overview

The ICT Cell Service Automation System aims to digitize and streamline the service management processes of the University of Dhaka's ICT Cell.

Traditionally, many of these processes rely on paper-based applications, phone calls, and direct communication. This proposed system introduces a centralized platform where university departments can submit service requests, request equipment, track approvals, manage procurement activities, and monitor technical support services.

The system is designed to improve transparency, accountability, communication, and efficiency across the entire service lifecycle.

## Objectives

- Digitize existing manual service request and equipment requisition processes.
- Provide a centralized platform for managing ICT-related services.
- Establish structured approval workflows for departments and university authorities.
- Improve the tracking and management of equipment procurement and installation.
- Organize technical support requests through a ticket-based system.
- Monitor service priorities, technician assignments, and Service Level Agreements (SLAs).
- Improve communication through automated email notifications.
- Maintain structured records of requests, approvals, procurement activities, and service history.

## Key Features

### 1. Registration and Access Management
- Department-based registration and account management.
- User authentication using email and password.
- Email-based One-Time Password (OTP) verification.
- OTP expiration after five minutes.
- Temporary account lockout after repeated unsuccessful verification attempts.
- Role-based access according to user responsibilities.

### 2. Equipment Requisition Management
- Digital equipment requisition forms.
- Dynamic forms for different equipment requirements.
- Supporting document and quotation attachments.
- Unique tracking IDs for submitted requisitions.
- Department Head (HoD) approval and rejection.
- Request for additional information.
- Identification of insufficient budget.

### 3. Budget and Financial Approval
- Structured financial approval workflows.
- Escalation of requests to the appropriate university authorities.
- Approval routing involving the Registrar, Treasurer, Vice-Chancellor (VC), and Pro-Vice-Chancellor (Pro-VC).
- Tracking of approval decisions and request status.

### 4. Procurement and Installation Management
- Procurement workflow after approval and funding confirmation.
- Vendor directory management.
- Collection and management of vendor quotations.
- Purchase order management.
- Delivery and installation tracking.
- Uploading installation evidence and relevant documents.
- Archiving completed procurement records.

### 5. Technical Service Request Management
- Digital submission of ICT-related technical service requests.
- Request classification based on titles and keywords.
- Automatic ticket generation.
- First-In, First-Out (FIFO) request queue management.
- Technician assignment based on availability and workload.
- Request reassignment and priority adjustment by administrators.
- Resolution summaries and service history.

### 6. Priority and SLA Management
- Four service priority levels:
  - Critical
  - High
  - Normal
  - Low
- Service Level Agreement (SLA) tracking.
- Monitoring of request progress and resolution timelines.
- Email alerts for SLA-related events.
- Support for collaborative tickets and subtasks.
- Detection of potential scheduling conflicts.

### 7. Notification Management
Automated email notifications for:
- OTP verification.
- Request submission acknowledgments.
- Approval and rejection decisions.
- Request status updates.
- Additional information requirements.
- SLA alerts and service-related updates.

### 8. Record and History Management
- Centralized storage of service requests.
- Tracking of requisition and procurement history.
- Approval decision records.
- Ticket and technician assignment history.
- Maintenance of service resolution records.

## Core Workflows

The system covers two major operational workflows.

### Equipment Requisition Workflow

1. A department submits an equipment requisition.
2. The request is forwarded to the Department Head for review.
3. The Department Head approves, rejects, requests additional information, or identifies insufficient budget.
4. Requests requiring financial approval are forwarded to the appropriate university authorities.
5. After approval and funding confirmation, procurement activities begin.
6. Procurement officers manage vendors, quotations, purchase orders, delivery, and installation.
7. Installation evidence and relevant documents are stored in the system.
8. The completed requisition is archived.

### Technical Service Request Workflow

1. A department submits a technical service request.
2. The system generates a ticket and classifies the request.
3. The request enters the service queue.
4. An ICT Cell administrator manages its priority and technician assignment.
5. The assigned technician works on the request.
6. The system monitors progress and SLA timelines.
7. The technician records the resolution summary.
8. The ticket is updated and maintained in the service history.

## System Stakeholders and Roles

| Stakeholder | Responsibilities |
|---|---|
| Department Head (HoD) | Reviews and approves department requests. |
| Lab Technician | Participates in technical service operations. |
| IT Support Staff | Handles ICT-related support activities. |
| ICT Cell Admin | Manages service requests, priorities, and assignments. |
| ICT Cell Technician | Handles assigned technical service requests. |
| Procurement Officer | Manages procurement, vendors, quotations, and installation activities. |
| Registrar | Participates in financial approval workflows. |
| Treasurer | Handles relevant financial approval responsibilities. |
| Vice-Chancellor (VC) | Participates in higher-level approval workflows. |
| Pro-Vice-Chancellor (Pro-VC) | Participates in relevant approval workflows. |
| Email System | Supports automated email communication and notifications. |

## Software Engineering and System Design

The project follows a structured Software Requirements Specification and system analysis approach.

The documentation covers:

- Stakeholder analysis.
- Quality Function Deployment (QFD).
- User stories.
- Functional and non-functional requirements.
- Use case modeling.
- Activity diagrams.
- Swimlane diagrams.
- Database and data modeling.
- Class diagrams.
- Class-Responsibility-Collaborator (CRC) modeling.
- State transition diagrams.
- Sequence diagrams.
- Data Flow Diagrams (DFDs).

These models describe the system's expected behavior, interactions, responsibilities, and information flow.

## Database Design

The system identifies several important data entities, including:

- Academic Department
- Department Staff
- Service Request
- Form
- Ticket
- Committee
- Procurement Officer
- ICT Cell Admin
- ICT Cell Technician
- Vendor

These entities support the management of departments, users, service requests, technical tickets, procurement activities, and related records.

## Security and Reliability

The proposed system incorporates several security and reliability considerations:

- Authentication through username and password.
- Email-based OTP verification.
- OTP expiration and temporary account lockout.
- Role-based access management.
- Controlled approval workflows.
- Centralized request and activity records.
- Automated notifications for important system events.

## Expected Outcomes

The proposed ICT Cell Service Automation System is expected to:

- Reduce dependency on manual paperwork and offline communication.
- Make service request submission and tracking more convenient.
- Improve transparency in approval and procurement processes.
- Provide better visibility into technical support activities.
- Support efficient technician assignment and workload management.
- Improve accountability through structured records and activity tracking.
- Strengthen communication between university departments and the ICT Cell.

## Project Scope and Status

This document represents the Software Requirements Specification (SRS) and system analysis of the proposed ICT Cell Service Automation System.

It describes the requirements, workflows, stakeholders, data models, and system design. It should not be interpreted as confirmation that the system has been fully implemented or deployed.

## Project Information

| Field | Details |
|---|---|
| Project Name | ICT Cell Service Automation |
| Institution | University of Dhaka |
| Department/Institute | Institute of Information Technology (IIT) |
| Course | SE-2206 |
| Document Type | Software Requirements Specification (SRS) and System Analysis |

## Documentation

The complete SRS document contains the detailed requirements, analysis, diagrams, workflows, and design models of the proposed system.
