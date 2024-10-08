# MonitoringServer
# monitors various system resources CPU, memory, disk usage, network traffic, system load,Monitor processes, and Monitoring services. The script can run continuously in a dashboard.
# CPU and Memory Usage - Shows the top 10 applications by CPU and memory usage.
# Network Monitoring -  Provides statistics on network traffic, concurrent connections, packet drops.
# Disk Usage  -   Displays disk usage statistics.
# System Load -  Shows system load and CPU usage breakdown.
# Memory Usage -  Memory and swap usage.
# Process Monitoring  - Displays the number of active processes and the top 5 processes by CPU and memory usage.
# Service Monitoring  - Checks the status of services and attempts to start them if they are not running. 
Display a full dashboard  ./mycustom.sh -all  -- Commands   This function continuously refreshes the display every 5 seconds, showing the current status of all monitored resources and all resource updates and every 5 Seconds.
Check only CPU usage   ./mycustom.sh -cpu  -- Commands
Monitor network only   ./mycustom.sh -network -- commands
output
![mycustom](https://github.com/user-attachments/assets/83e020c7-b372-4238-8a2a-6f19f31ff7c1)
![mycustom2](https://github.com/user-attachments/assets/de8709bd-0135-4c8f-bb0a-e814e93dc736)
![mycustom4](https://github.com/user-attachments/assets/23402fd7-9cf3-4d5c-b518-0ff3b4910a75)
# Script for Automating Security Audits.
This Bash script automates security audits and server hardening on Linux servers  It is designed to be reusable, modular, and easily deployable across multiple servers,stringent security standards.
User and Group Audits  Lists all users and groups, checks for users.
File and Directory Permissions  Scans for world-writable files and directories, checks .ssh directory permissions.
Service Audits Lists running services, checks critical services.
Custom Security Checks  Allows extension with custom security checks via a configuration file.
Reporting and Alerting  Generates a summary report and optionally sends email alerts.  
Reporting and Alerting Check  to commands ./mysecurity --report
Output
![2 Task output](https://github.com/user-attachments/assets/a54d1452-0062-4ae2-8e8d-346e1a5ba255)
![3 output](https://github.com/user-attachments/assets/2719a607-c771-4125-93ee-f0f3133eeff8)
![5 output](https://github.com/user-attachments/assets/b931a0c7-06a9-4fd1-a9d0-6e49fc8fe1b5)
