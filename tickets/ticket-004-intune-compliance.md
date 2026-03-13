# Ticket 004 Intune Compliance Issue

## Ticket Summary

Ticket ID: 004  
Category: Device Compliance  
Platform: Microsoft Intune  
Status: Resolved  
Assigned Team: IT Helpdesk  

## User Reported Issue

The user reported that their device was marked as **Non-Compliant** in Microsoft Intune, preventing access to corporate resources protected by Conditional Access policies.

## Investigation

The helpdesk team reviewed the device status in Microsoft Intune and identified the compliance policy failure.

The device was missing required security updates.

## Click by Click Learning Process

1. Signed in to **Microsoft Intune Admin Center**.
2. Navigated to **Devices**.
3. Selected **All Devices**.
4. Located the affected device.
5. Opened **Device Compliance** status.
6. Reviewed failed compliance policies.
7. Identified missing security updates.
8. Triggered **Sync** for the device.
9. Verified compliance status after updates were installed.

## Resolution

The device was updated and synchronized with Intune. Once the required updates were installed, the device returned to a compliant state.

## Documentation Sources

Microsoft Intune Device Compliance  
https://learn.microsoft.com/mem/intune/protect/device-compliance-get-started
