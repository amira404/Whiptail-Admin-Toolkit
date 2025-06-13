# Whiptail-Admin-Toolkit
**An Interactive Linux User & Group Management Toolkit**  
Easy-to-use Bash scripts with a whiptail-based text GUI

![Made with Bash](https://img.shields.io/badge/Made%20with-Bash-blue?logo=gnubash)


# 🛠️ Whiptail Admin Toolkit

A Bash-based interactive admin panel for managing users and groups on Linux systems using `whiptail`.

## 📌 About the Project

This project provides a user-friendly interface built with **Whiptail** to simplify user and group management tasks for Linux administrators. It includes modular scripts to add, modify, list, lock, and unlock user accounts and groups — all from a text-based GUI.

---

## 📂 Features

✅ Add, modify, and list users  
✅ Lock and unlock user accounts  
✅ Change user passwords  
✅ Add groups individually or from a file  
✅ Modify group names and GIDs  
✅ View groups in short or detailed format  
✅ Easy navigation using whiptail menus  

---

## 🖥️ Modules Included

Each functionality is handled in a separate shell script for modularity:

| Script Name                          | Functionality                    |
|-------------------------------------|----------------------------------|
| `add_user_module.sh`                | Add a new user                   |
| `modify_user_module.sh`             | Modify username, UID, shell...   |
| `list_User_module.sh`               | View users (short or detailed)   |
| `lock_user_module.sh`               | Lock a user account              |
| `unlock_user_module.sh`             | Unlock a user account            |
| `change_user_password_module.sh`    | Change a user’s password         |
| `create_group_module.sh`            | Add a new group / from file      |
| `modify_group_module.sh`            | Modify group name or GID         |
| `list_groups_module.sh`             | View groups                      |

---

## 🚀 How to Run

> ⚠️ Must be run as **root** or with `sudo`.

```bash
sudo bash main_user_menu.sh
```
#Make sure all modules are in the same directory or update the path inside main_user_menu.sh

📎 Requirements
1-Linux system
2-whiptail installed (usually pre-installed)
3-Run with root privileges
4-To install whiptail (if missing):
```bash
sudo apt install whiptail   # Debian/Ubuntu
sudo yum install newt       # RedHat/CentOS
```
📁 File Structure
```bash
whiptailFunctions/
├── main.sh
├── add_user_module.sh
├── modify_user_module.sh
├── list_User_module.sh
├── lock_user_module.sh
├── unlock_user_module.sh
├── change_user_password_module.sh
├── create_group_module.sh
├── modify_group_module.sh
├── list_groups_module.sh
└── README.md
```
👩‍💻 Author
Amira Mohamed
Cybersecurity & Linux Enthusiast
Blue Team Path 👩‍💻🛡️SOC

📜 License
This project is open-source and available under the MIT License.
# 1. Navigate to your project directory
```bash 
cd /home/amiramohamed/whiptailFunctions
 ```

# 2. Initialize a new Git repository
```bash 
git init
```

# 3. Connect your local repo to GitHub (replace with your actual repo link if different)
```bash 
git remote add origin https://github.com/amiramohamed/whiptail-admin-tools.git
```

# 4. Add all files to the staging area
```bash
git add .
```
# 5. Commit the files with a message
```bash
git commit -m "Initial commit - admin tools with whiptail"
```
# 6. Rename the current branch to main
```bash
git branch -M main
```
# 7. Push the local repository to GitHub
```bash
git push -u origin main
```



