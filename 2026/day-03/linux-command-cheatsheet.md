🐧 Linux Commands Cheat Sheet (DevOps Essentials)

This cheat sheet focuses on real troubleshooting, not memorization.

🔹 Process Management

| Command            | Usage                               |
| ------------------ | ----------------------------------- |
| `ps aux`           | Show all running processes          |
| `top`              | Live view of system processes       |
| `htop`             | Enhanced interactive process viewer |
| `pidof <process>`  | Get PID of a running process        |
| `kill <PID>`       | Terminate a process                 |
| `kill -9 <PID>`    | Force kill a process                |
| `nice -n 10 <cmd>` | Start process with priority         |
| `renice -5 <PID>`  | Change priority of running process  |
| `uptime`           | Check system running time & load    |
| `watch <cmd>`      | Run a command repeatedly            |

🔹 File System & Disk

| Command                 | Usage                     |
| ----------------------- | ------------------------- |
| `ls -lh`                | List files with size      |
| `pwd`                   | Show current directory    |
| `cd <dir>`              | Change directory          |
| `du -sh <dir>`          | Check directory size      |
| `df -h`                 | Disk usage                |
| `find / -name file`     | Search for files          |
| `stat <file>`           | File metadata             |
| `chmod 755 file`        | Change file permissions   |
| `chown user:group file` | Change ownership          |
| `mount`                 | Show mounted file systems |

🔹 Networking & Troubleshooting

| Command             | Usage                        |
| ------------------- | ---------------------------- |
| `ping google.com`   | Check network connectivity   |
| `ip addr`           | Show IP addresses            |
| `ip route`          | View routing table           |
| `ss -tuln`          | Check listening ports        |
| `netstat -tuln`     | Network connections (legacy) |
| `curl <url>`        | Test API / HTTP endpoint     |
| `wget <url>`        | Download files               |
| `dig google.com`    | DNS lookup                   |
| `nslookup domain`   | Resolve DNS                  |
| `traceroute domain` | Trace network path           |

🔹 Logs & System Info

| Command            | Usage               |
| ------------------ | ------------------- |
| `tail -f file.log` | Live log monitoring |
| `journalctl -xe`   | View systemd logs   |
| `free -m`          | Memory usage        |
| `vmstat`           | System performance  |
| `uname -a`         | Kernel & OS info    |
