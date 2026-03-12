# Ticket 010 – DNS Name Resolution Failure

Ticket ID: HD-010  
Priority: High  
Category: Network Infrastructure  
Status: Resolved  
Assigned Team: IT Support  
Created Date: 2026-03-15  

## Issue Summary

Multiple users reported being unable to access internal websites using hostnames.

## Environment

Windows Server 2022  
DNS Server  
Active Directory Domain Services  
Windows 11 workstations  

## Investigation

### Step 1 – Test DNS Resolution

DNS resolution tests were performed using command-line tools.

Result  
Hostname queries failed.

### Step 2 – Verify DNS Server Configuration

DNS server settings and service status were reviewed.

Result  
DNS service was running but zone record was missing.

### Step 3 – Restore DNS Record

Missing DNS A record for the internal web server was recreated.

Result  
Hostname resolution restored.

### Step 4 – Verify User Access

Users tested access to internal resources.

Result  
Internal websites loaded successfully.

## Root Cause

Required DNS record for the internal server was missing.

## Resolution

The DNS record was restored in the DNS management console.

## Lessons Learned

DNS configuration errors can prevent access to internal resources even when network connectivity is functioning properly.
