# User & Group Management

Hands-on Red Hat Enterprise Linux (RHEL) administration exercises focused on user accounts, groups, authentication, password policies, and privilege management.

## Skills Practiced

- Creating and managing Linux users
- Creating and managing groups
- UID and GID configuration
- Primary and supplementary group management
- Password configuration
- Password expiration policies
- User account restrictions
- sudo and sudoers configuration
- Administrative privilege management

## Lab Evidence

The screenshots below demonstrate practical implementation and verification of user and group management tasks performed in a RHEL environment.

### 1. User Account Management

Created and configured Linux user accounts using command-line administration tools.

**Commands used:**

```bash
useradd <username>
passwd <username>
id <username>
```

### 2. Group Management

Created groups and configured user group memberships.

**Commands used:**

```bash
groupadd <groupname>
usermod -aG <groupname> <username>
id <username>
```

### 3. Password Policy Management

Configured password expiration and account policies.

**Commands used:**

```bash
chage <username>
chage -l <username>
```

### 4. Sudo Privilege Management

Configured restricted administrative privileges using the sudoers configuration.

## Screenshots

Screenshots demonstrating the configuration and verification steps will be added below.

## Key Takeaways

This lab provided hands-on experience with Linux identity and access management, including user lifecycle management, group-based access control, password policies, and administrative privilege configuration.
