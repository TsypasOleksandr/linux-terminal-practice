# Linux Permissions Management Practice

In this lab I practiced viewing and modifying file and directory permissions in Linux using terminal commands.

## Commands Used

### Navigate to the projects directory
```bash
cd projects
```

### Display file permissions
```bash
ls -l
```

### Display all files including hidden files
```bash
ls -la
```

### Remove write permission for others
```bash
chmod o-w project_k.txt
```

### Remove read permission for group
```bash
chmod g-r project_m.txt
```

### Modify multiple permissions on a hidden file
```bash
chmod u-w,g-w,g+r .project_x.txt
```

### Remove execute permission from a directory
```bash
chmod g-x drafts
```

## Skills Practiced

- Linux terminal usage
- Viewing file permissions
- Managing user, group, and other permissions
- Working with hidden files
- Basic Linux security administration

$\color{red}{\textsf{---------------------------------------------------------------------------------------------------------------------------------------}}$
<img width="834" height="842" alt="Знімок екрана 2026-05-21 о 1 46 42 пп" src="https://github.com/user-attachments/assets/14105abd-41c4-4b75-a898-af525b92b3f6" />
