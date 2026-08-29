# Permissions & Access Control

Hands-on Red Hat Enterprise Linux (RHEL) labs focused on Linux file permissions, ownership, special permissions, and access control.

## Skills Practiced

- Linux file and directory permissions
- chmod, chown and chgrp
- User and group ownership
- SUID permissions
- SGID permissions
- Sticky Bit
- Shared directory access control
- Group-based permissions
- Permission verification with `ls -l` and `ls -ld`

## Practical Tasks

### SUID Configuration

Created and configured a `secure_backup` script and applied special permissions.

```bash
chmod 4755 /usr/local/bin/secure_backup
ls -l /usr/local/bin/secure_backup
```

### SGID Shared Directory

Created a shared directory for the `devops` group and configured SGID so newly created files inherit the directory's group ownership.

```bash
groupadd devops
mkdir -p /shared/devops
chmod g+s /shared/devops
```

### Sticky Bit

Configured a shared directory where users can create files but cannot delete files belonging to other users.

```bash
mkdir -p /project/tmp
chmod +t /project/tmp
```

## Lab Documentation

The attached lab document contains the implementation steps, terminal commands, verification results, and screenshots.

## Key Takeaways

This lab provided practical experience with Linux permission management and special permission mechanisms used to control access to files and shared directories.
