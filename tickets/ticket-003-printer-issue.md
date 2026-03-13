# Ticket 003 Printer Issue

## Ticket Summary

Ticket ID: 003  
Category: Hardware / Printing  
Platform: Windows Endpoint  
Status: Resolved  
Assigned Team: IT Helpdesk  

## User Reported Issue

The user reported that documents sent to the office printer were not printing. The printer appeared online but print jobs remained stuck in the queue.

## Investigation

The helpdesk team reviewed the user's printer configuration and verified the device connection. The print queue was checked to determine whether jobs were stalled or failing to process.

The investigation revealed that the print spooler service had stopped on the user’s workstation.

## Click by Click Learning Process

1. Opened **Control Panel**.
2. Selected **Devices and Printers**.
3. Right clicked the affected printer.
4. Selected **See what’s printing**.
5. Checked the print queue for stalled jobs.
6. Opened **Services**.
7. Located **Print Spooler**.
8. Restarted the Print Spooler service.
9. Cleared the print queue.
10. Sent a test print.

## Resolution

The print spooler service was restarted and the print queue was cleared. The printer resumed normal operation and the user was able to successfully print documents.

## Documentation Sources

Microsoft Print Spooler Troubleshooting  
https://learn.microsoft.com/windows-hardware/drivers/print/
