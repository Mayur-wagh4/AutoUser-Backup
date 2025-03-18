# AutoUser-Backup

## Overview
AutoUser-Backup is a **Shell Scripting project** designed to automate **user management** and **backup operations** in a Linux environment. This script simplifies administrative tasks such as **creating, deleting, and managing users** while ensuring automated backups of critical data.

## Features
- **User Management** → Add, modify, and delete user accounts.
- **Group Management** → Assign and manage user groups.
- **Automated Backups** → Securely backup important directories.
- **Error Handling & Logging** → Ensures stability and debugging ease.
- **Security Features** → File permissions and access control.

## Installation & Usage

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Mayur-wagh4/AutoUser-Backup.git
cd AutoUser-Backup
```

### 2️⃣ Run the Script
```bash
chmod +x user_backup.sh
./user_backup.sh
```

## Advanced Features
- **Automated Scheduling with Cron**
  ```bash
  crontab -e
  0 2 * * * /path/to/user_backup.sh  # Runs backup daily at 2 AM
  ```
- **Secure Remote Backup Using SCP**
  ```bash
  scp backup.tar.gz user@remote-server:/backup/destination/
  ```
- **User Activity Monitoring**
  ```bash
  last -a | head -10  # Shows last 10 user logins
  ```

## Contribution
Contributions are welcome! Fork the repository, make changes, and submit a pull request.

## License
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.
