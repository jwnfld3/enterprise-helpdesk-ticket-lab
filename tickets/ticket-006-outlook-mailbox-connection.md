# Ticket 006 – Outlook Unable to Connect to Mailbox

Ticket ID: HD-006  
Priority: Medium  
Category: Microsoft 365 / Email Services  
Status: Resolved  
Assigned Team: IT Support  
Created Date: 2026-03-11  

## Issue Summary

A user reported that Microsoft Outlook was unable to connect to their mailbox. The application displayed a message indicating that it could not establish a connection to the Exchange server.

## Environment

Microsoft 365  
Exchange Online  
Windows 11 workstation  
Microsoft Outlook  

## Investigation

### Step 1 – Verify Microsoft 365 Service Status

The Microsoft 365 service health dashboard was reviewed to confirm that Exchange Online services were operational.

Result  
No service outages were reported.

### Step 2 – Verify User Mailbox Status

The user account was reviewed in Microsoft Entra ID and Exchange Admin Center.

Result  
Mailbox was active and properly provisioned.

### Step 3 – Test Outlook Profile

The existing Outlook profile was reviewed and tested.

Result  
Profile appeared corrupted.

### Step 4 – Recreate Outlook Profile

A new Outlook profile was created through the Windows Control Panel mail configuration.

Result  
Outlook successfully connected to the mailbox.

## Root Cause

The user's Outlook profile was corrupted.

## Resolution

A new Outlook profile was created and the mailbox connection was restored.

## Lessons Learned

When Outlook cannot connect to Exchange Online and services are operational, recreating the Outlook profile should be considered early in the troubleshooting process.
