# Lab 02: Linux Command Basics

## Objective
Practice core Linux commands and learn how to inspect files and permissions.

## Tools
- terminal
- Linux shell

## Steps
1. Open a Linux terminal.
2. Run `pwd` and note the current directory.
3. Run `ls -l` to inspect files and permissions.
4. Use `cat` to read a file.
5. Use `grep` to search for text inside a file.
6. Use `chmod` to change permissions on a test file.
7. Check the result with `ls -l`.

## Example Commands
```bash
pwd
ls -l
cat /etc/hosts
grep "root" /etc/passwd
chmod 600 testfile
ls -l testfile
```

## Reflection
- What do the permission bits mean?
- Why is proper file permission important for security?
- What is the effect of changing file permissions?

## Notes
- Permissions limit user capabilities
- Linux depends on ownership and privilege rules
- Logs and configuration files contain important system metadata

## Outcome
You should be comfortable with basic Linux command-line navigation and access control.
