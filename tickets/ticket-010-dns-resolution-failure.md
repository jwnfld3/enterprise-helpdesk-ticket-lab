# Ticket 010 DNS Resolution Failure

## Ticket Summary

Ticket ID: 010  
Category: Network Issue  
Platform: Windows Endpoint  
Status: Resolved  
Assigned Team: IT Helpdesk  

## User Reported Issue

The user reported that websites and internal services were not loading properly. Web browsers returned DNS related errors when attempting to access external sites.

## Investigation

The helpdesk team tested the user’s network connectivity and reviewed DNS configuration settings.

A DNS lookup test confirmed that the workstation was unable to resolve domain names.

## Click by Click Learning Process

1. Opened **Command Prompt**.
2. Ran the following command:

   ```
   ipconfig /all
   ```

3. Verified DNS server configuration.
4. Ran the following command:

   ```
   nslookup google.com
   ```

5. Confirmed that DNS resolution failed.
6. Cleared the DNS cache using:

   ```
   ipconfig /flushdns
   ```

7. Restarted the network adapter.

## Resolution

The DNS cache was cleared and the workstation was able to successfully resolve domain names.

## Documentation Sources

Windows DNS Troubleshooting  
https://learn.microsoft.com/windows-server/networking/dns/
