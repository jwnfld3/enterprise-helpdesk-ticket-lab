# Ticket 002 – New Employee Account Provisioning
**Ticket ID:** HD-002  
**Priority:** Low  
**Category:** User Account Provisioning  
**Status:** Resolved  
**Assigned Team:** IT Support  
**Created Date:** 2026-03-10

## Issue Summary
The Human Resources department submitted a request to create system access for a newly hired employee. The employee required access to Microsoft 365 services and domain resources.

## Environment
Active Directory Domain Services  
Microsoft 365  
Microsoft Entra ID  
Windows 11 workstation  

## Request Details

Department: Finance  
Requested Access:
- Domain login
- Microsoft 365 email
- SharePoint access
- Department security group membership

## Provisioning Process

### Step 1 – Create Active Directory User Account
A new user account was created in Active Directory Users and Computers.

The account was placed in the appropriate organizational unit for the Finance department.

### Step 2 – Assign Initial Password
A temporary password was created and configured to require password change at first login.

### Step 3 – Assign Security Groups
The user was added to the following groups:

Finance Department  
Microsoft 365 Licensed Users

### Step 4 – Assign Microsoft 365 License
The appropriate Microsoft 365 license was assigned in Microsoft Entra ID.

This enabled:

Outlook email  
SharePoint access  
Microsoft Teams access

### Step 5 – Verify Account Synchronization
User synchronization between Active Directory and Microsoft Entra ID was confirmed.

### Step 6 – Test Login
The user successfully authenticated and accessed Microsoft 365 services.

## Root Cause
Not applicable. This ticket represents a standard onboarding request.

## Resolution
New employee account successfully created and provisioned with required access.

## Lessons Learned
Standardized onboarding procedures ensure that new employees receive system access quickly while maintaining proper access control.
