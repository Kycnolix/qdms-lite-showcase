# QDMS Lite Showcase

QDMS Lite is a lightweight and modular document management system developed to manage internal corporate document processes.

This repository does not include the source code of the project. It was created to showcase the application’s screenshots, module structure, and overall product flow.

> Source code is private. This repository is a showcase/demo repository.

---

## Overview

QDMS Lite is an intranet-based web application that supports core corporate document management processes such as document creation, publishing, revision management, approval workflows, user authorization, template management, and audit logging.

The project was developed based on real internal document management needs, with a focus on simplicity, usability, modularity, and role-based access control.

---

## Key Features

* Document listing, search, and advanced filtering
* Document detail pages with version and status tracking
* Online document viewing
* Multi-step document preparation flow
* Document creation by file upload or template selection
* Approval, rejection, and send-back-for-revision actions
* Document revision management
* Task assignment and task tracking
* Document template creation and versioning
* Organization unit / application area management
* Role-based user access management
* Approval flow configuration
* Security and audit logs
* LDAP login integration
* Active Directory account-based authentication
* Custom SSO authentication / authorization layer
* Docker-based application setup

---

## Screenshots

### Dashboard

Summary cards for pending actions and user-related document tasks.

![Dashboard](assets/screenshots/qlite1.png)

---

### Navigation and Module Structure

Main navigation structure for document management, system infrastructure, and pending tasks.

![Navigation Menu](assets/screenshots/qlite2.png)

---

### Document Listing and Filtering

Documents can be filtered by document code, title, status, type, date, folder, and reading status.

![Document List Filter](assets/screenshots/qlite3.png)

---

### Online Document Viewer

Documents can be viewed directly inside the system in read-only mode.

![Online Viewer](assets/screenshots/qlite4.png)

---

### Document Detail

General document information, publication/version data, and reading status can be tracked from a single screen.

![Document Detail](assets/screenshots/qlite5.png)

---

### Document Preparation Flow

The document preparation process is designed with a step-by-step structure.

#### 1. Document Information

![Document Create Step 1](assets/screenshots/qlite6.png)

#### 2. Related Areas

![Document Create Step 2](assets/screenshots/qlite7.png)

#### 3. Source Selection

![Document Create Upload](assets/screenshots/qlite8.png)

---

### Draft and Approval Process

Draft documents can be edited, deleted, or submitted to the approval workflow.

![Draft Detail](assets/screenshots/qlite9.png)

Approval actions allow users to approve, reject, or send documents back for revision.

![Approval Actions](assets/screenshots/qlite10.png)

---

### Revision Management

Published documents can be revised, and revision reasons can be tracked.

![Revision Management](assets/screenshots/qlite11.png)

---

### Task Assignment

Administrators can assign document preparation or revision tasks to users.

![Assignment Admin](assets/screenshots/qlite12.png)

Users can track their assigned tasks from a dedicated task screen.

![My Tasks](assets/screenshots/qlite13.png)

---

### Template Management

Document templates can be listed, viewed in detail, and versioned.

![Template List](assets/screenshots/qlite14.png)

![Template Detail](assets/screenshots/qlite15.png)

---

### System Infrastructure

Organization units, user access, and approval flows can be managed through system infrastructure screens.

![Organization Units](assets/screenshots/qlite16.png)

![User Access Management](assets/screenshots/qlite17.png)

![Approval Flow Builder](assets/screenshots/qlite18.png)

---

### Audit Logs

Security-critical actions and system activities can be tracked through audit logs.

![Audit Logs](assets/screenshots/qlite19.png)

---

## Technology Stack

* Frontend: React.js
* Backend: C# / .NET 9
* Database: Microsoft SQL Server
* Authentication / Authorization: Custom SSO layer
* Directory Integration: LDAP / Active Directory
* Document Viewer: ONLYOFFICE Document Server on Docker
* Deployment: Docker
* Environment: Internal corporate intranet

---

## My Role

I designed and developed this project end-to-end.

My responsibilities included:

* User interface design and development
* Modeling document management processes
* Designing approval and revision workflows
* Building role-based access control logic
* Developing listing, filtering, and detail screens
* Implementing task assignment and tracking flows
* Creating template management screens
* Developing the custom SSO authentication / authorization layer
* Integrating LDAP login with Active Directory accounts
* Preparing the application to run with Docker
* Integrating document viewing through ONLYOFFICE
* Presenting audit and activity logs in the user interface

---

## Repository Purpose

This repository was created only for portfolio and product showcase purposes.

It does not include:

* Source code
* Internal business rules
* Private integrations
* Credentials
* Sensitive technical details
* Production configuration

---

## Note

QDMS Lite is designed for internal corporate intranet usage and is not publicly accessible as a live application.

Screenshots are shared only to demonstrate the module structure, user flows, and overall product scope.

---

## License / Usage

This repository is for showcase purposes only.
All rights reserved.
