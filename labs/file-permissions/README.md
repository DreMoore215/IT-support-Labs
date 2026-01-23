# Linux File Permissions & Access Control Lab

## Objective
Implement secure file ownership and permission management in a multi-user Linux environment.

## Environment
- Platform: AWS EC2
- OS: Ubuntu 24.04 LTS
- Access: SSH (Termius on iPad)

## Scenario
Simulated a help desk environment where sensitive, shared, and executable files require controlled access.

## Tasks Performed
- Created protected system directory
- Configured file ownership using chown
- Modified permissions using chmod
- Created support group
- Implemented group-based access
- Verified access restrictions

## Commands Used
```bash
sudo su
mkdir /opt/helpdesk_lab
touch report.txt logs.txt script.sh
chown
chmod
groupadd
usermod
chgrp
