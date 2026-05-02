# linux notes

## core concepts

- linux is a multi-user operating system  
- everything (files, devices, processes) is treated as a file  
- permissions control who can access and modify files  
- the terminal (command line) is a primary way to interact with the system  

---

## file system structure

- `/` = root directory  
- `/home` = user directories  
- `/etc` = configuration files  
- `/var` = logs and variable data  
- `/bin` = essential commands  

---

## file permissions

- read (r) → view file contents  
- write (w) → modify file  
- execute (x) → run file  

example:
```bash
-rwxr-xr-x
