# Ticket 013 – Device Enrollment Failure in Intune

Ticket ID: HD-013  
Priority: Medium  
Category: Endpoint Management  
Status: Resolved  
Assigned Team: IT Support  
Created Date: 2026-03-18  

## Issue Summary

A newly issued workstation failed to enroll in Microsoft Intune during device setup.

## Environment

Microsoft Intune  
Microsoft Entra ID  
Windows 11 workstation  

## Investigation

### Step 1 – Verify Device Registration

Device registration status was reviewed in Microsoft Entra ID.

Result  
Device was not registered.

### Step 2 – Verify Intune Licensing

User license was reviewed.

Result  
Intune service was included in the license.

### Step 3 – Reinitiate Device Enrollment

Device enrollment process was restarted using company credentials.

Result  
Device successfully registered.

### Step 4 – Confirm Policy Deployment

Endpoint policies were reviewed.

Result  
Device compliance policies applied successfully.

## Root Cause

Initial device enrollment process was interrupted during setup.

## Resolution

Device enrollment was restarted and completed successfully.

## Lessons Learned

Enrollment failures can occur if device setup is interrupted during initial configuration.
