# Interview questions

How can you check the kernel version of a Linux system?
```uname -a```
```uname -v``` (version)
```uname -r``` (release)

How can you check your current ip address?
```ifconfig```
```ip addr show``` (newer)

How do you check for free disk space?
```df -ah``` (all file systems, human redable)

Hod do you manage/ check services?
```service <service> status```
```systemctl status <service>```

How would you check the total size of everything in a directory?
```du -sh <directory>```

How would you check for open ports/ listening on tcp or udp …?
```netstat - tulpn``` (tcp, udp, listening?)

How do you check the cpu usage of a given process?
```ps aux | grep nginx```
```top```
```htop```

How would you mount a new volume in your system?
```ls /mnt ```(where you mount volumes)
```mount /dev/sda2 /mnt```
```mount ```(existing mounts)

 How do you find help for a command in linux?
The man pages ```man <command>```