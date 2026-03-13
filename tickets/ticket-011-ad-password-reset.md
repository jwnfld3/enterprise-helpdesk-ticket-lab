# Ticket 011 Active Directory Password Reset

## Ticket Summary

Ticket ID: 011  
Category: Password Reset  
Platform: Active Directory  
Status: Resolved  
Assigned Team: IT Helpdesk  

## User Reported Issue

The user reported being locked out of their account after entering the incorrect password multiple times.

The user required assistance resetting their password to regain access.

## Investigation

The helpdesk team verified the user’s account status in Active Directory and confirmed that the account was locked due to failed login attempts.

## Click by Click Learning Process

1. Opened **Active Directory Users and Computers**.
2. Navigated to the user’s organizational unit.
3. Located the affected user account.
4. Right-clicked the account.
5. Selected **Reset Password**.
6. Entered a new temporary password.
7. Enabled **User must change password at next login**.
8. Clicked **OK**.

## Resolution

The user’s password was reset and the account was unlocked. The user successfully logged in and created a new password.

## Documentation Sources

Active Directory Password Reset  
https://learn.microsoft.com/windows-server/identity/ad-ds/
