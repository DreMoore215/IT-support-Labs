# Ticket 001 – Unable to Connect to EC2 Instance via SSH

## Issue Summary
User was unable to connect to an EC2 instance via SSH.

## Impact
Remote administrative access to the system was unavailable.

## Troubleshooting Steps
- Verified EC2 instance was running
- Attempted SSH connection and confirmed failure
- Reviewed security group inbound rules
- Identified missing SSH (port 22) rule

## Root Cause
SSH access was blocked due to a missing inbound security group rule.

## Resolution
Re-added SSH (port 22) inbound rule to the security group, restoring connectivity.

## Prevention
Ensure critical access ports are documented and validated after security group changes.
