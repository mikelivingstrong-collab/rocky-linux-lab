# Rocky Linux Infrastructure & Security Lab

## Project Overview

This project is a hands-on Rocky Linux infrastructure and security home lab built in VirtualBox.

The purpose of the lab is to develop practical Linux administration, networking, infrastructure, and cybersecurity skills through real system configuration, troubleshooting, and service deployment.

---

## Technologies Used

- Rocky Linux 10
- VirtualBox
- OpenSSH
- Apache HTTP Server
- firewalld
- Git/GitHub

---

## Skills Practiced

- Linux system administration
- SSH remote administration
- Linux permissions and ownership
- Firewall management
- Apache web hosting
- Service management with systemctl
- Log analysis with journalctl
- Networking fundamentals
- Troubleshooting methodology

---

## Infrastructure Overview

- Rocky Linux VM running in VirtualBox
- Bridged networking configured
- Remote SSH administration from Windows host
- Apache web server hosting internal website
- Firewall configured for SSH and HTTP traffic

---

## Major Concepts Learned

### NAT vs Bridged Networking

Learned the difference between VirtualBox NAT networking and bridged networking and how bridged mode allows the VM to function as a real device on the local network.

### SSH Administration

Configured and managed OpenSSH for secure remote administration.

### Linux Permissions

Practiced chmod, chown, ownership, and directory traversal permissions.

### Firewall Management

Configured firewalld service rules and tested temporary vs permanent firewall configurations.

### Apache Hosting

Installed and configured Apache HTTP Server and hosted a custom internal website.

---

## Troubleshooting Scenarios

### Permission Denied Errors

Encountered Linux directory traversal permission issues and resolved them using proper chmod permissions on parent directories.

### SSH Hardening

Modified SSH configuration safely using backup procedures, syntax validation, and service restart testing.

### Apache Access Issues

Tested and resolved Apache permission and firewall access issues.

---

## Future Improvements

- SSH key authentication
- Fail2ban
- SELinux investigation
- Docker containers
- Reverse proxy setup
- HTTPS with self-signed certificates
- Monitoring and alerting
- Bash scripting automation
