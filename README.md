# MonitoringServer
# monitors various system resources CPU, memory, disk usage, network traffic, system load, active processes, and essential services. The script can run continuously in a dashboard.
# CPU and Memory Usage - Shows the top 10 applications by CPU and memory usage.
# Network Monitoring -  Provides statistics on network traffic, concurrent connections, packet drops.
# Disk Usage  -   Displays disk usage statistics.
# System Load -  Shows system load and CPU usage breakdown.
# Memory Usage -  Memory and swap usage.
# Process Monitoring  - Displays the number of active processes and the top 5 processes by CPU and memory usage.
# Service Monitoring  - Checks the status of essential services and attempts to start them if they are not running.
# Display a full dashboard  ./mycustom.sh -all  -- Commands
# Check only CPU usage   ./mycustom.sh -cpu  -- Commands
# Monitor network only    ./mycustom.sh -network -- commands
