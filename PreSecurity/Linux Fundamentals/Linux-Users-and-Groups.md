# Linux Users and Groups

## Overview
Linux is a multi-user operating system where
users and groups control access to system resources.

## Users
- Each user has a unique User ID (UID)
- Root user (UID 0) has full system privileges
- Regular users have limited permissions

## Groups
- Groups organize users
- Each group has a Group ID (GID)
- Permissions can be assigned to groups

## Important Files
- `/etc/passwd` – User account information
- `/etc/shadow` – Encrypted passwords
- `/etc/group` – Group information

## Useful Commands
- `whoami` – Show current user
- `id` – Display user and group IDs
- `groups` – Show group memberships
- `su` – Switch user
- `sudo` – Execute commands as root

## What I Learned
- Users and groups control system access
- Misconfigured sudo permissions can be exploited
- User enumeration helps attackers

## Why This Matters in Cybersecurity
Attackers target:
- Weak user permissions
- Improper sudo access
- Exposed user information

## Key Takeaway
Understanding users and groups is essential
for managing access and exploiting misconfigurations.
