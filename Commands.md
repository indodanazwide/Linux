# Linux Commands Cheat Sheet

Linux commands are essential for navigating, managing files, controlling processes, and configuring systems. Here’s a categorized list of common Linux commands:  

---

## 🔹 **Basic Commands**
| Command | Description |
|---------|-------------|
| `pwd` | Print current working directory |
| `ls` | List files and directories |
| `cd [dir]` | Change directory |
| `mkdir [dir]` | Create a new directory |
| `rm [file/dir]` | Remove file (`-r` for directories) |
| `cp [src] [dest]` | Copy file/directory |
| `mv [src] [dest]` | Move or rename file/directory |
| `touch [file]` | Create an empty file |
| `clear` | Clear terminal screen |

---

## 🔹 **File Viewing Commands**
| Command | Description |
|---------|-------------|
| `cat [file]` | Display file content |
| `less [file]` | View file page by page |
| `more [file]` | Similar to `less`, but limited scrolling |
| `head -n [num] [file]` | Show first `n` lines of a file |
| `tail -n [num] [file]` | Show last `n` lines of a file |
| `nano [file]` | Open file in Nano text editor |
| `vi [file]` | Open file in Vi text editor |

---

## 🔹 **User Management**
| Command | Description |
|---------|-------------|
| `whoami` | Show current user |
| `who` | Show logged-in users |
| `id` | Show user ID (UID) and group ID (GID) |
| `adduser [username]` | Add a new user |
| `passwd [username]` | Change user password |
| `su [user]` | Switch user |
| `sudo [command]` | Run command as superuser |
| `logout` | Logout from session |

---

## 🔹 **Process Management**
| Command | Description |
|---------|-------------|
| `ps aux` | List running processes |
| `top` | Display real-time process info |
| `htop` | Like `top`, but more user-friendly (install separately) |
| `kill [PID]` | Kill process by Process ID |
| `killall [name]` | Kill all processes with a given name |
| `pkill [name]` | Kill process by name |
| `bg` | Resume stopped job in the background |
| `fg` | Resume stopped job in the foreground |
| `jobs` | List background jobs |

---

## 🔹 **Networking Commands**
| Command | Description |
|---------|-------------|
| `ifconfig` | Show IP and network details (deprecated) |
| `ip a` | Show IP address (modern alternative) |
| `ping [host]` | Check connectivity to a host |
| `wget [url]` | Download file from URL |
| `curl [url]` | Fetch URL data |
| `netstat -tulnp` | Show open ports and connections |
| `ss -tulnp` | Faster alternative to `netstat` |
| `nslookup [domain]` | Get DNS info for a domain |
| `traceroute [host]` | Show network path to a host |

---

## 🔹 **Disk & Storage**
| Command | Description |
|---------|-------------|
| `df -h` | Show disk usage (human-readable) |
| `du -sh [dir]` | Show directory size |
| `mount [device] [dir]` | Mount a storage device |
| `umount [device]` | Unmount a storage device |
| `lsblk` | Show block devices (disk partitions) |
| `fdisk -l` | Show partition table |
| `mkfs.ext4 [device]` | Format a partition to ext4 |

---

## 🔹 **Permissions & Ownership**
| Command | Description |
|---------|-------------|
| `chmod 777 [file]` | Change file permissions |
| `chown user:group [file]` | Change ownership of a file |
| `ls -l` | Show file permissions |

---

## 🔹 **Compression & Archiving**
| Command | Description |
|---------|-------------|
| `tar -cvf archive.tar [files]` | Create a tar archive |
| `tar -xvf archive.tar` | Extract tar archive |
| `zip -r archive.zip [dir]` | Create zip archive |
| `unzip archive.zip` | Extract zip archive |

---

## 🔹 **Searching**
| Command | Description |
|---------|-------------|
| `find /path -name "*.txt"` | Find files by name |
| `grep "word" file.txt` | Search for text inside a file |
| `locate filename` | Find file quickly using index |
| `which [command]` | Show command location |

---

## 🔹 **System Monitoring**
| Command | Description |
|---------|-------------|
| `uptime` | Show system uptime |
| `free -h` | Show memory usage |
| `vmstat` | Show system performance |
| `iostat` | Show CPU and disk statistics |
| `sar` | Monitor system performance over time |

---

## 🔹 **Shutdown & Reboot**
| Command | Description |
|---------|-------------|
| `shutdown -h now` | Shutdown system immediately |
| `reboot` | Reboot system |
| `shutdown -r now` | Shutdown and restart |

---

