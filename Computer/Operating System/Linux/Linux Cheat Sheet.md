**[[Linux]] [[Cheat sheet]] for daily use**
#computer

---
# File & Directory Management
- `ls` - List files and directories
- `cd [dir]` - Change directory
- `pwd` - Print current directory
- `mkdir [dir]` - Create a new directory
- `rmdir [dir]` - Remove an empty directory
- `rm [file]` - Remove a file
- `rm -r [dir]` - Remove a directory and its contents
- `cp [src] [dest]` - Copy files or directories
- `mv [src] [dest]` - Move or rename files or directories
- `find [dir] -name [file]` - Search for a file in a directory
- `locate [file]` - Find a file by name (requires `updatedb`)

# File Permissions & Ownership
- `ls -l` - View file permissions
- `chmod [mode] [file]` - Change file permissions
- `chown [user]:[group] [file]` - Change file owner and group
- `umask [value]` - Set default permissions for new files

# File Viewing & Editing
- `cat [file]` - View file contents
- `less [file]` - View file contents page by page
- `head [file]` - Show first 10 lines of a file
- `tail [file]` - Show last 10 lines of a file
- `nano [file]` - Edit a file using Nano editor
- `vim [file]` - Edit a file using Vim editor

# Process Management
- `ps aux` - List running processes
- `top` - Display active processes
- `htop` - Interactive process viewer (requires installation)
- `kill [PID]` - Terminate a process by ID
- `pkill [name]` - Terminate a process by name
- `jobs` - Show background jobs
- `bg [job]` - Resume a job in the background
- `fg [job]` - Resume a job in the foreground

# User Management
- `whoami` - Display current user
- `id` - Show user ID and group ID
- `who` - Show logged-in users
- `adduser [user]` - Add a new user
- `deluser [user]` - Delete a user
- `passwd [user]` - Change user password
- `usermod -aG [group] [user]` - Add user to a group

# Networking
- `ip a` - Show IP addresses
- `ping [host]` - Check network connectivity
- `wget [URL]` - Download a file from the web
- `curl [URL]` - Fetch data from a URL
- `netstat -tulnp` - Show open ports (deprecated)
- `ss -tulnp` - Show open ports (replacement for netstat)

# Disk Management
- `df -h` - Show disk space usage
- `du -sh [dir]` - Show directory size
- `mount [device] [dir]` - Mount a filesystem
- `umount [device]` - Unmount a filesystem
- `fdisk -l` - List disk partitions

# Package Management
- **Debian/Ubuntu:**
  - `apt update` - Update package lists
  - `apt upgrade` - Upgrade installed packages
  - `apt install [package]` - Install a package
  - `apt remove [package]` - Remove a package

- **RedHat/CentOS:**
  - `yum update` - Update system
  - `yum install [package]` - Install a package
  - `yum remove [package]` - Remove a package

- **[[Arch Linux]]:**
  - `pacman -Syu` - Update system
  - `pacman -S [package]` - Install a package
  - `pacman -R [package]` - Remove a package

# System Monitoring & Logs
- `uptime` - Show system uptime
- `free -h` - Display memory usage
- `dmesg` - Show system logs
- `journalctl -xe` - Show detailed logs
- `history` - Show command history
- `clear` - Clear terminal screen

# Miscellaneous
- `echo "text"` - Print text to terminal
- `date` - Display current date and time
- `cal` - Show calendar
- `alias ll='ls -lah'` - Create an alias
- `uname -r` - Show kernel version
- `shutdown -h now` - Shutdown system immediately
- `reboot` - Restart system

This cheat sheet covers essential Linux commands applicable across distributions. Always check `man [command]` for detailed usage.
