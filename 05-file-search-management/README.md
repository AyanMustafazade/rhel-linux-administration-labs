# Linux File Search & Management

Hands-on Red Hat Enterprise Linux (RHEL) labs focused on locating and managing files using Linux command-line tools.

## Skills Practiced

- File and directory searching
- Searching by file name
- Searching by file type
- Searching by file size
- Searching by modification time
- Searching by file owner
- Searching by permissions
- Using the `find` command
- Linux filesystem navigation

## Practical Tasks

### Search by Name

Located configuration files using filename patterns.

```bash
find / -name "*.conf"
```

### Search by Size

Located files based on their size.

```bash
find / -type f -size +100M
```

### Search by Modification Time

Located files modified within a specified period.

```bash
find / -type f -mtime -7
```

### Search by Owner

Located files belonging to a specific Linux user.

```bash
find / -user <username>
```

### Search by Permissions

Located files according to their permission settings.

```bash
find / -type f -perm <permissions>
```

## Lab Documentation

The attached lab document contains practical file-search exercises, commands, verification results, and screenshots.

## Key Takeaways

This lab provided hands-on experience with Linux file discovery and filesystem management using different search criteria such as name, size, modification time, ownership, and permissions.
