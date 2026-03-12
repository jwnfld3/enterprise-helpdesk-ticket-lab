# Ticket 014 – SharePoint Site Permission Issue

Ticket ID: HD-014  
Priority: Medium  
Category: Microsoft 365 / SharePoint  
Status: Resolved  
Assigned Team: IT Support  
Created Date: 2026-03-19  

## Issue Summary

A user reported receiving an access denied error when attempting to open a SharePoint team site.

## Environment

Microsoft 365  
SharePoint Online  
Windows 11 workstation  

## Investigation

### Step 1 – Verify SharePoint Site Permissions

Site permissions were reviewed in SharePoint administration settings.

Result  
User account was not included in the site member group.

### Step 2 – Add User to Site Group

User account was added to the SharePoint site members group.

### Step 3 – Test Access

User attempted to access the SharePoint site again.

Result  
Access successful.

## Root Cause

User was not assigned to the correct SharePoint permission group.

## Resolution

User account added to the SharePoint site membership group.

## Lessons Learned

SharePoint site access issues are frequently related to missing group permissions.
