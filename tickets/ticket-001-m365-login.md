# Ticket 001 Microsoft 365 Login Issue

## Ticket Summary

Ticket ID: 001  
Category: Authentication Issue  
Platform: Microsoft 365  
Status: Resolved  
Assigned Team: IT Helpdesk

## User Reported Issue

The user reported that they were unable to sign in to their Microsoft 365 account. The login attempt resulted in an authentication failure message.

The issue prevented the user from accessing Microsoft Outlook, Microsoft Teams, and other Microsoft 365 services.

## Investigation

The helpdesk team began the investigation by reviewing authentication activity associated with the user account.

Microsoft Entra ID sign-in logs were used to analyze login attempts, authentication methods, and error messages associated with the failed login events.

During the investigation, the following information was reviewed:

- user account sign-in activity
- authentication results
- source IP addresses
- login timestamps
- potential error codes

The investigation determined that the login failure was caused by an expired password.

## Click by Click Learning Process

1. Signed in to the Microsoft 365 Admin Center.
2. Navigated to **Admin Centers**.
3. Selected **Microsoft Entra ID**.
4. Opened **Identity**.
5. Selected **Monitoring**.
6. Clicked **Sign-in Logs**.
7. Searched for the affected user account.
8. Reviewed authentication attempts and error messages.
9. Identified the authentication failure reason.
10. Verified the account status and password expiration.

## Resolution

The helpdesk administrator reset the user's password using the Microsoft Entra Admin Center.

Steps taken:

- reset the user password
- provided the temporary password to the user
- required the user to set a new password at next login

After resetting the password, the user successfully authenticated and regained access to Microsoft 365 services.

## Documentation Sources

Microsoft Entra Sign-in Logs  
https://learn.microsoft.com/en-us/entra/identity/monitoring-health/concept-sign-ins

Troubleshoot Microsoft Entra Sign-in Errors  
https://learn.microsoft.com/en-us/entra/identity/monitoring-health/howto-troubleshoot-sign-in-errors
