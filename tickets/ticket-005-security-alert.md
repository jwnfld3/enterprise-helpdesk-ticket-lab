# Ticket 005 – Suspicious Login Alert
**Ticket ID:** HD-005  
**Priority:** High  
**Category:** Security Incident  
**Status:** Resolved  
**Assigned Team:** IT Support  
**Created Date:** 2026-03-10

## Issue Summary
A security alert was generated indicating an unusual sign-in attempt for a user account in Microsoft Entra ID.

## Environment
Microsoft Entra ID  
Microsoft 365  
Windows 11

## Investigation

### Step 1 – Review Sign-In Logs
Sign-in logs in Microsoft Entra ID were reviewed.

Result  
Login attempt detected from an unfamiliar geographic location.

### Step 2 – Verify User Activity
The user was contacted to confirm whether the login attempt was legitimate.

Result  
User confirmed they did not attempt to log in from that location.

### Step 3 – Force Password Reset
The user's password was reset to prevent unauthorized access.

### Step 4 – Enforce Multi-Factor Authentication
Multi-Factor Authentication was verified and enforced for the account.

### Step 5 – Monitor Account Activity
Additional monitoring was enabled to watch for further suspicious login attempts.

## Root Cause
Unauthorized login attempt detected for the user account.

## Resolution
Password reset performed and Multi-Factor Authentication enforced.

## Lessons Learned
Monitoring sign-in logs and enforcing Multi-Factor Authentication are essential for detecting and preventing unauthorized account access.
