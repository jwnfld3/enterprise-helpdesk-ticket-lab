# Ticket 015 – Wireless Network Authentication Failure

Ticket ID: HD-015  
Priority: High  
Category: Network Connectivity  
Status: Resolved  
Assigned Team: IT Support  
Created Date: 2026-03-20  

## Issue Summary

A user reported being unable to connect to the corporate wireless network.

## Environment

Corporate wireless network  
Windows 11 workstation  
Active Directory authentication  

## Investigation

### Step 1 – Verify Wireless Signal

Wireless connectivity and signal strength were verified.

Result  
Signal strength was normal.

### Step 2 – Verify User Authentication

Authentication logs were reviewed.

Result  
Authentication attempts were failing.

### Step 3 – Reset Wireless Profile

Existing wireless network profile was removed and recreated.

### Step 4 – Test Wireless Connection

User attempted to reconnect.

Result  
Connection successful.

## Root Cause

Corrupted wireless network profile on the workstation.

## Resolution

Wireless profile was recreated and authentication succeeded.

## Lessons Learned

Recreating wireless profiles often resolves authentication issues.
