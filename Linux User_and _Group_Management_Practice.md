# Linux User and Group Management Practice

In this lab I practiced managing users, groups, and file ownership in Linux using terminal commands.

## Commands Used

### Create a new user
```bash
sudo useradd researcher9
```

### Modify a user's primary group
```bash
sudo usermod -g research_team researcher9
```

### Change file ownership
```bash
sudo chown researcher9 /home/researcher2/projects/project_r.txt
```

### Add user to an additional group
```bash
sudo usermod -a -G sales_team researcher9
```

### Delete a user
```bash
sudo userdel researcher9
```

### Delete a group
```bash
sudo groupdel researcher9
```

## Skills Practiced

- Linux user management
- Group administration
- File ownership management
- User permission configuration
- Basic Linux system administration

<img width="711" height="362" alt="Знімок екрана 2026-05-21 о 1 56 51 пп" src="https://github.com/user-attachments/assets/19e2c11c-923a-4b93-b25a-daf7f7cbafe9" />
