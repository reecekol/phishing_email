# Incident Report: DBS Bank Phishing Threat


## Report ID: INC-2026-0212-DBSDate: 12 February 2026
## Risk Level: HighStatus: Resolved1.
## Executive Summary

On 12 February 2026, a customer reported a suspicious email impersonating DBS/POSB Bank. The message claimed that the recipient's digital token had expired and requested an immediate update via a link.The sender address (noreply@substackss.firebaseapp.com) did not match DBS Bank, and the link directed users to an untrusted external site (email.notify.thinkific.com) designed to collect credentials.

## Key Findings & Indicators

Indicator Details Sender Addressnoreply@substackss.firebaseapp.comPhishing Linkemail.notify.thinkific.comBypass MethodUsed Google Firebase infrastructure to pass initial email security filters.Threat GoalCredential Harvesting

## Incident Response Steps

Quarantine & Removal: Identified and removed matching phishing emails from all user mailboxes.Access Block: Blocked the sender domain and destination link across email and web gateways.User Audit: Investigated whether any users clicked the link or submitted information.Account Protection: Reset passwords and revoked active sessions for any affected accounts.


## Conclusion & Next Steps

Classification: Confirmed Credential Phishing Campaign.
Action Items: Maintain domain blocks and reinforce security awareness training regarding generic sender addresses.
