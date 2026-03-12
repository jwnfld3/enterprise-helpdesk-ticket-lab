# Ticket 011 – User Unable to Reset Password

Ticket ID: HD-011  
Priority: Medium  
Category: Identity and Access Management  
Status: Resolved  
Assigned Team: IT Support  
Created Date: 2026-03-16  

## Issue Summary

A user reported being unable to reset their password through the self-service password reset portal.

## Environment

Microsoft Entra ID  
Active Directory Domain Services  
Windows 11 workstation  

## Investigation

### Step 1 – Verify Account Status

The user account was reviewed in Microsoft Entra ID.

Result  
Account was active.

### Step 2 – Review Self-Service Password Reset Settings

Self-service password reset configuration was reviewed in the Microsoft Entra admin center.

Result  
User was not included in the group allowed to use self-service password reset.

### Step 3 – Update Group Membership

User account was added to the password reset enabled group.

### Step 4 – Test Password Reset

User attempted the password reset again.

Result  
Password reset completed successfully.

## Root Cause

User account was not included in the self-service password reset policy group.

## Resolution

User was added to the correct policy group enabling password reset functionality.

## Lessons Learned

Self-service password reset group membership should be verified when users cannot reset their passwords.
