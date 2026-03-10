# Ticket 001 – User Unable to Sign In to Microsoft 365

## Issue Summary
A user reported being unable to access Microsoft 365 services including Outlook and SharePoint. The user received an authentication error when attempting to sign in.

## Environment
Microsoft 365  
Microsoft Entra ID  
Windows 11 workstation  

## Investigation

### Step 1 – Verify User Account Status
The user account was reviewed in Microsoft Entra ID to confirm that the account was active.

Result  
Account was active.

### Step 2 – Check License Assignment
The user's Microsoft 365 license assignment was reviewed.

Result  
No license assigned to the user account.

### Step 3 – Assign License
The correct Microsoft 365 license was assigned to the user account.

### Step 4 – Test Login
The user attempted to sign in again.

Result  
Login successful.

## Root Cause
User account did not have a Microsoft 365 license assigned.

## Resolution
Assigned Microsoft 365 license and verified successful login.

## Lessons Learned
When users cannot access Microsoft 365 services, license assignment should be verified early in troubleshooting.
