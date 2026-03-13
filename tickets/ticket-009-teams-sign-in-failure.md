# Ticket 009 Microsoft Teams Sign-in Failure

## Ticket Summary

Ticket ID: 009  
Category: Authentication Issue  
Platform: Microsoft Teams  
Status: Resolved  
Assigned Team: IT Helpdesk  

## User Reported Issue

The user reported that they were unable to sign in to Microsoft Teams. The application displayed an authentication error and repeatedly prompted the user to enter credentials.

The issue prevented the user from participating in meetings and accessing team collaboration channels.

## Investigation

The helpdesk team reviewed the user’s authentication activity and verified that the account was active in Microsoft Entra.

Sign-in logs were examined to determine whether authentication failures were occurring during the login process.

The investigation determined that cached credentials in the Teams application were causing the authentication failure.

## Click by Click Learning Process

1. Closed the Microsoft Teams application.
2. Opened **File Explorer**.
3. Navigated to the following directory:

   ```
   C:\Users\username\AppData\Roaming\Microsoft\Teams
   ```

4. Deleted the Teams cache folders.
5. Restarted the computer.
6. Reopened Microsoft Teams.
7. Entered the user’s credentials.
8. Completed the authentication process.

## Resolution

The Teams application cache was cleared and the user successfully signed in after restarting the application.

## Documentation Sources

Microsoft Teams Sign-in Troubleshooting  
https://learn.microsoft.com/microsoftteams/troubleshoot/
