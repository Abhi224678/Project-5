
# Project 5: Secure Linux Server Permissions

## Task 1: Create Users and Groups

### Objective
I created Linux users and a group to implement user-based access restrictions.

### Implementation
1. Created the group `project5_group`.
2. Created the user `project5_user1` and added it to `project5_group`.
3. Created the user `project5_user2`.
4. Created the directory `/opt/project5`.
5. Assigned ownership to `root:project5_group`.
6. Set directory permissions to `770`.

## Task 2: Test Allowed and Denied Access

### Allowed Access
Executed:

```bash
sudo -u project5_user1 touch /opt/project5/allowed.txt
```

Result: Successfully created the file.

### Denied Access
Executed:

```bash
sudo -u project5_user2 touch /opt/project5/denied.txt
```

Result: Permission denied.

## Evidence
Screenshot has been attached
