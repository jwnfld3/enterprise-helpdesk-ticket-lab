# Ticket 003 – Department Printer Not Responding

## Issue Summary
Multiple users reported that the department network printer was not responding. Print jobs were being sent but were not printing.

## Environment
Windows Server Print Services  
Active Directory Domain  
Windows 11 Workstations  
Network Printer

## Investigation

### Step 1 – Verify Network Connectivity
The printer was tested using a network ping to confirm that the device was reachable.

Result  
Printer responded to network ping.

### Step 2 – Check Printer Queue
The print queue on the print server was reviewed.

Result  
Multiple print jobs were stuck in the queue.

### Step 3 – Restart Print Spooler Service
The Print Spooler service on the print server was restarted.

### Step 4 – Clear Print Queue
Stuck print jobs were cleared from the queue.

### Step 5 – Test Printing
A test page was sent to the printer.

Result  
Printer successfully printed the test page.

## Root Cause
The Print Spooler service became unresponsive causing print jobs to remain in the queue.

## Resolution
Restarted the Print Spooler service and cleared the print queue.

## Lessons Learned
When multiple users experience printing issues, the print server or spooler service should be investigated first.
