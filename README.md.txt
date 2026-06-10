# Cloud Identity & Access Management (IAM) Lab with Microsoft Entra ID

## Overview

This project demonstrates the implementation of a cloud-based Identity & Access Management (IAM) environment using Microsoft Entra ID (formerly Azure Active Directory).

The lab was designed to simulate real world IAM operations including identity administration, Role-Based Access Control (RBAC), Joiner-Mover-Leaver (JML) lifecycle management, access reviews, audit monitoring, privileged access management, and authentication governance.

The goal was to gain hands-on experience with cloud identity management while documenting IAM processes using enterprise-style standards.

---

## Architecture Diagram

![Microsoft Entra ID Architecture](Architecture/EntraID-Architecture-Diagram.png)

---

## Lab Environment

| Component             | Details                          |
| --------------------- | -------------------------------- |
| Platform              | Microsoft Entra ID               |
| Environment Type      | Cloud IAM Lab                    |
| Identity Provider     | Microsoft Entra ID               |
| Administrative Role   | Global Administrator             |
| Access Model          | Role-Based Access Control (RBAC) |
| Departments Simulated | HR, Finance, SOC, IT             |

---

## Key IAM Capabilities Demonstrated

### Identity Administration

* User provisioning
* User modification
* User deprovisioning
* Group membership management

### Role-Based Access Control (RBAC)

* Department-based security groups
* Group-based access assignments
* Least privilege implementation
* Access segregation

### Joiner-Mover-Leaver (JML)

* New user onboarding
* Role change management
* User offboarding
* Access revocation

### Identity Governance

* Access reviews
* Access certification
* Membership validation
* Governance controls

### Audit & Compliance

* Audit log monitoring
* Administrative activity tracking
* Identity lifecycle auditing
* Governance visibility

### Authentication & Security

* Authentication methods review
* Multi-Factor Authentication (MFA) concepts
* Passwordless authentication concepts
* Privileged access security

---

## Project Components

### Architecture

Designed and documented a Microsoft Entra ID architecture illustrating users, departments, security groups, RBAC assignments, administrative roles, and governance controls.

### User Management

Created and managed users representing multiple business departments while maintaining structured identity administration practices.

### RBAC Implementation

Implemented Role-Based Access Control using Microsoft Entra ID security groups to simplify access management and support least privilege principles.

### JML Lifecycle Management

Simulated Joiner-Mover-Leaver processes to demonstrate user provisioning, role transitions, and secure offboarding procedures.

### Access Reviews

Performed access validation activities to ensure group memberships remained aligned with business requirements.

### Audit Monitoring

Reviewed Microsoft Entra ID audit logs to verify administrative actions and identity lifecycle events.

### Administrative Roles

Reviewed privileged role assignments and administrative access management concepts.

### Authentication Methods

Explored available authentication methods and identity protection capabilities within Microsoft Entra ID.

---

## Repository Structure

```text
Cloud-IAM-EntraID-Lab

├── README.md

├── Architecture
│   ├── EntraID-Architecture-Diagram.drawio
│   └── EntraID-Architecture-Diagram.png

├── Screenshots
│   ├── 01-TenantSetup
│   ├── 02-UserManagement
│   ├── 03-RBAC
│   ├── 04-JML
│   ├── 05-AccessReviews
│   ├── 06-AuditLogs
│   ├── 07-AdminRoles
│   └── 08-AuthenticationMethods

├── Documentation

└── Lessons-Learned
```

---

## Skills Demonstrated

* Identity & Access Management (IAM)
* Microsoft Entra ID Administration
* Role-Based Access Control (RBAC)
* Identity Governance & Administration (IGA)
* User Provisioning & Deprovisioning
* Joiner-Mover-Leaver (JML)
* Access Reviews
* Audit Log Analysis
* Authentication Management
* Privileged Access Concepts
* Security Documentation
* Technical Documentation

---

## Key Takeaways

This project provided practical experience implementing cloud IAM concepts within Microsoft Entra ID and strengthened my understanding of identity governance, access management, authentication security, auditability, and lifecycle management within modern enterprise environments.

---

## Author

**Destiny Akhabue**

Aspiring Identity & Access Management (IAM) Professional

Focused on Identity Governance, Access Management, Microsoft Entra ID, Active Directory, and Cybersecurity.
