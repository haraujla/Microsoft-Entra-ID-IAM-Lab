# Microsoft Entra ID IAM Lab

## Overview

This project is a hands-on Microsoft Entra ID lab designed to demonstrate practical Identity and Access Management skills in a cloud environment.

The lab simulates a small organization with multiple departments, users, security groups, administrative roles, guest identities, enterprise applications, and authentication monitoring.

## Skills Demonstrated

* User provisioning
* Security group management
* Role-Based Access Control (RBAC)
* Principle of least privilege
* Guest/B2B identity management
* Enterprise application access
* App registrations
* Microsoft Graph permissions
* Audit log analysis
* Sign-in log investigation

## Lab Environment

The environment included the following test users:

* John Smith — IT
* Sarah Jones — HR
* Mike Brown — Finance
* Test User — IT
* External Test User — Guest

Security groups created:

* SG-IT
* SG-HR
* SG-Finance
* SG-External-Users

## User Provisioning

Created multiple Microsoft Entra ID users and assigned department and job information to simulate a small business environment.

## Security Groups

Created department-based security groups and assigned users according to their job function.

Example:

* SG-IT

  * John Smith
  * Test User

* SG-HR

  * Sarah Jones

* SG-Finance

  * Mike Brown

## Role-Based Access Control

Assigned John Smith the Helpdesk Administrator role instead of Global Administrator.

This demonstrated the principle of least privilege by granting only the administrative permissions required for the user's responsibilities.

## Guest Access

Created an external guest identity using Microsoft Entra B2B collaboration.

The guest user was added to SG-External-Users to demonstrate controlled access for external identities.

## Enterprise Application Access

Created a non-gallery enterprise application named Contoso HR Portal.

Assigned Sarah Jones access to the application to simulate role-based application access for an HR employee.

## App Registration

Registered an application called Contoso Helpdesk App.

Reviewed:

* Application ID
* Tenant ID
* Microsoft Graph permissions
* Delegated permissions

Configured Microsoft Graph User.Read permission to demonstrate least-privilege API access.

## Monitoring and Auditing

Reviewed Microsoft Entra audit logs to identify administrative actions such as:

* User creation
* Group membership changes
* Role assignments
* Application changes

Reviewed sign-in logs to investigate authentication activity.

One sign-in event showed that the user was prompted to provide contact information to complete MFA registration.

## Key Takeaways

This lab provided hands-on experience with cloud identity administration and demonstrated how Microsoft Entra ID can be used to manage users, groups, administrative permissions, external identities, application access, and authentication monitoring.

