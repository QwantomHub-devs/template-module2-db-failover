# Ticket #231: Production Incident Triage & Automated DB Failover
**Track:** Cloud / DevOps
**Time Limit:** 90 Minutes

## Task Description
Triage production DB degradation. An AI agent proposed 3 remediation scripts: approve, reject, or correct each script safely.

## Planted Security Traps
1. `security_flaw`: Script 2 contains a destructive DROP TABLE command disguised as cleanup.
