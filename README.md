Task 7 – Monitor System Resources Using Netdata

Internship Track: Data Analyst
Objective: Install and use Netdata to monitor system and application performance using a lightweight Docker container.



Tools Used

● AWS EC2 (Ubuntu 22.04)
● Docker
● Netdata (Open-source monitoring tool)
● GitHub



Part 1 – Launch EC2 Instance

● A new EC2 instance was launched using Ubuntu 22.04 LTS.
● A security group was configured to allow inbound traffic on port 22 for SSH and port 19999 for the Netdata dashboard.



Part 2 – Install Docker on EC2

● The system was updated using apt.
● Docker was installed and the service was started and enabled.
● Docker installation was verified using the version command.



Part 3 – Run Netdata Container

● The official Netdata container was pulled and run using Docker.
● The container was exposed on port 19999 for dashboard access.
● Docker processes were verified to ensure the container was running.



Part 4 – Access Netdata Dashboard

● The Netdata dashboard was accessed using the EC2 public IP on port 19999.
● The live metrics interface displayed real-time system and application statistics.



Part 5 – Explore System Metrics

● Key performance indicators such as CPU usage, memory utilization, disk activity, and Docker container stats were monitored through the dashboard.



Part 6 – Check Alerts

● The alerts panel in the Netdata dashboard was checked to identify any active system alerts or issues.



Part 7 – Check Logs

● Attempted to access logs from inside the Netdata container to check for any internal errors.
● Found that the log file was either empty or not generated due to absence of errors.



Part 8 – Stop and Remove Container

● The Netdata container was stopped and removed using Docker commands to clean up the environment.



Part 9 – Local Folder Setup

● All relevant files and screenshots were organized in a local folder for upload.
● The folder was prepared for pushing to a GitHub repository.



Summary

Netdata was successfully deployed and used to monitor system performance on an AWS EC2 instance via Docker. The task demonstrated the ability to set up and use lightweight monitoring tools in a real-time environment.

