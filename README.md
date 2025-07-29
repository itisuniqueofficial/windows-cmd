# Windows CMD Prompt

Here's a well-organized list of **important CMD (Command Prompt) commands** — especially for **Windows maintenance, updates, system info, networking, and file management** — that can help you work efficiently like a pro:

---

## 🛠️ **System Maintenance & Updates**

| Command                                      | Description                            |
| -------------------------------------------- | -------------------------------------- |
| `winget upgrade --all`                       | Updates all apps installed via Winget  |
| `sfc /scannow`                               | Scans & repairs corrupted system files |
| `chkdsk /f /r`                               | Checks and repairs disk errors         |
| `DISM /Online /Cleanup-Image /RestoreHealth` | Repairs Windows image                  |
| `shutdown /r /t 0`                           | Restarts PC immediately                |
| `shutdown /s /t 0`                           | Shuts down PC immediately              |
| `taskmgr`                                    | Opens Task Manager                     |
| `msconfig`                                   | Opens System Configuration             |
| `cleanmgr`                                   | Opens Disk Cleanup utility             |
| `control`                                    | Opens Control Panel                    |

---

## 🌐 **Networking Commands**

| Command                                             | Description                            |
| --------------------------------------------------- | -------------------------------------- |
| `ipconfig`                                          | Displays IP address and network config |
| `ipconfig /flushdns`                                | Clears DNS cache                       |
| `ping example.com`                                  | Tests network connection               |
| `tracert example.com`                               | Traces route to a host                 |
| `netstat -an`                                       | Shows all active connections and ports |
| `netsh wlan show profiles`                          | Lists saved Wi-Fi networks             |
| `netsh wlan show profile name="WiFiName" key=clear` | Shows Wi-Fi password                   |
| `nslookup example.com`                              | DNS lookup for a domain                |

---

## 📂 **File & Folder Management**

| Command                     | Description                      |
| --------------------------- | -------------------------------- |
| `dir`                       | Lists files in current directory |
| `cd`                        | Changes directory                |
| `mkdir foldername`          | Creates new folder               |
| `del filename.ext`          | Deletes a file                   |
| `copy file1.txt D:\Backup`  | Copies file to location          |
| `xcopy source dest /s /e`   | Copies folder and subfolders     |
| `robocopy source dest /mir` | Advanced file copy (mirror mode) |

---

## 🔐 **User & System Info**

| Command                                       | Description                     |
| --------------------------------------------- | ------------------------------- |
| `whoami`                                      | Displays current logged-in user |
| `systeminfo`                                  | Shows full system specs         |
| `hostname`                                    | Shows PC name                   |
| `wmic bios get serialnumber`                  | Shows BIOS serial number        |
| `net user`                                    | Lists user accounts             |
| `net user username /add`                      | Adds new user                   |
| `net localgroup administrators username /add` | Makes user an admin             |

---

## 🧪 **Bonus - Developer & Misc**

| Command      | Description                      |
| ------------ | -------------------------------- |
| `cls`        | Clears the CMD screen            |
| `echo Hello` | Prints "Hello" in CMD            |
| `start .`    | Opens current folder in Explorer |
| `assoc`      | Lists file type associations     |
| `powershell` | Launches PowerShell from CMD     |
