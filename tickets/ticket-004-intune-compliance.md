# Ticket 004 – Intune Device Non-Compliant
**Ticket ID:** HD-004  
**Priority:** Medium  
**Category:** Endpoint Management  
**Status:** Resolved  
**Assigned Team:** IT Support  
**Created Date:** 2026-03-10

## Issue Summary
A workstation was flagged as non-compliant in Microsoft Intune due to missing required security updates.

## Environment
Microsoft Intune  
Windows 11  
Microsoft Entra ID

## Investigation

### Step 1 – Review Device Compliance Status
The device compliance report in Microsoft Intune was reviewed.

Result  
Device marked as non-compliant.

### Step 2 – Review Compliance Policy
The compliance policy required the device to have the latest security updates installed.

### Step 3 – Check Windows Update Status
The workstation was checked for pending updates.

Result  
Several security updates were pending installation.

### Step 4 – Install Updates
Pending updates were installed and the device was restarted.

### Step 5 – Sync Device with Intune
The device was manually synced with Microsoft Intune.

Result  
Device compliance status updated to compliant.

## Root Cause
The workstation had not installed recent Windows security updates required by the compliance policy.

## Resolution
Installed pending updates and re-synced device with Microsoft Intune.

## Lessons Learned
Devices that fall behind on updates can quickly become non-compliant and should be monitored through Intune compliance reports.
