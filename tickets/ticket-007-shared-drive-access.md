# Ticket 007 – User Unable to Access Shared Drive

Ticket ID: HD-007  
Priority: Medium  
Category: Active Directory / File Services  
Status: Resolved  
Assigned Team: IT Support  
Created Date: 2026-03-12  

## Issue Summary

A user reported that they were unable to access a department shared network drive used by their team.

## Environment

Windows Server 2022  
Active Directory Domain Services  
Windows 11 workstation  
File Server  

## Investigation

### Step 1 – Verify Network Connectivity

The user’s workstation connectivity to the file server was tested.

Result  
Network connectivity was confirmed.

### Step 2 – Verify Shared Drive Permissions

File share permissions and NTFS permissions were reviewed on the file server.

Result  
User account was not included in the required security group.

### Step 3 – Review Active Directory Group Membership

The user’s group membership was reviewed in Active Directory.

Result  
User was missing the department access group.

### Step 4 – Update Security Group

User account was added to the appropriate department security group.

Result  
User successfully accessed the shared drive.

## Root Cause

User account was not assigned to the department file access group.

## Resolution

User was added to the correct Active Directory security group.

## Lessons Learned

Shared drive access issues are commonly related to group membership and permissions configuration.
