# Conditional Access Policy – Admin Device Compliance

## Project Overview

I configured and tested a Microsoft Entra Conditional Access policy requiring administrators to access organizational resources from compliant devices.

## Business Scenario

South West Tech needed to strengthen administrative access security by restricting privileged accounts from accessing company resources through non-compliant devices.

## Tools Used

- Microsoft Entra ID
- Conditional Access
- Microsoft Intune

## What I Built

- Created a Conditional Access policy named **Admin Device Requirement**
- Targeted users assigned the Cloud Application Administrator role
- Applied the policy to all resources
- Configured the grant control to require a compliant device
- Enabled and verified the policy
- Tested with Arjun Patel and confirmed access was blocked from a non-compliant device

## Screenshots

Configuration and testing evidence is available in the [Screenshots](Screenshots/) folder.

## Security Lessons Learned

Requiring compliant devices helps protect privileged accounts by preventing administrative access from devices that do not meet organizational security requirements.

## Documentation

Detailed implementation notes are available in [docs/lab-notes.md](docs/lab-notes.md).
