## Antivirus  
- Antivirus software quarantines malware.  
- "Quarantine" means isolating the infected file so it cannot spread or damage the system.

---

## Types of Malware Analysis

1. **Static Analysis**  
   - The malware is examined **without running it**.  
   - Used to inspect the code and understand its structure or function.

2. **Dynamic Analysis**  
   - The malware is **executed in a safe environment** (sandbox).  
   - Observes real-time behavior like network connections, file changes, etc.

---

## Basic Linux Terminal Commands

| Command  | Description |
|----------|-------------|
| `pwd`    | Print the current working directory path |
| `cd`     | Change directory (used for navigating folders) |
| `mkdir`  | Create a new directory |
| `ls`     | List the contents of the current directory |
| `man`    | Display the manual/help for a command |
| `clear`  | Clear the terminal screen |
| `rm`     | Remove a file |
| `touch`  | Create a new empty file |
| `echo`   | Print a message to the terminal |
| `chmod`  | Change access permissions for files/directories |

---

## File Permissions in Linux

Linux file permissions are divided into 3 user categories:

- **User**: The file owner  
- **Group**: Users in the same group as the owner  
- **Others**: Everyone else

### Permission Types:
- `r` = read  
- `w` = write  
- `x` = execute  

### Example:
-rwxrwxr-x 1 kali kali 0 Jul 22 09:16 hacker.txt

- First `rwx` → permissions for the **user**  
- Second `rwx` → permissions for the **group**  
- Third `r-x` → permissions for **others**

This means:
- **User**: can read, write, and execute  
- **Group**: can read, write, and execute  
- **Others**: can read and execute only

---
