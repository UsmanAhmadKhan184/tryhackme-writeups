# Linux Permissions

## Overview
Linux permissions control who can read, write,
or execute files and directories.

## Permission Types
- **Read (r)** – View file content
- **Write (w)** – Modify file content
- **Execute (x)** – Run file or access directory

## Permission Groups
- **Owner** – File creator
- **Group** – Group members
- **Others** – All other users

## Permission Representation
Example: `-rwxr-xr--`

- Owner: read, write, execute  
- Group: read, execute  
- Others: read only  

## Important Commands
- `ls -l` – View permissions
- `chmod` – Change permissions
- `chown` – Change ownership

## What I Learned
- Incorrect permissions cause vulnerabilities
- Executable files can be abused
- SUID files can lead to privilege escalation

## Why This Matters in Cybersecurity
Many Linux exploits rely on:
- Misconfigured permissions
- SUID binaries
- Writable configuration files

## Key Takeaway
Understanding permissions is essential
for exploiting and securing Linux systems.
