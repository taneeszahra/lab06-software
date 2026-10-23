## 1. Install and run htop
Command: sudo apt install -y htop
Command: htop
Answer:
htop displays runing processes, CPU usage, memory usage and system activity.
Command: sudo apt remove -y htop
Command: hash -r
Command: htop
Answer: After removal, htop shouuld no longer be available.

## 2. Find the apache2 version
Command: apt show apache2
Answer: Version offered by Ubuntu: 2.4.58-1ubuntu8.8

## 3. Count installed packages
Command: apt list --installed | wc -l
Answer: 734

## 4. Run Alpine using Docker
Command: sudo docker run --rm alpine echo "Hello from Alpine"
Answer: Hello from Alpine

## 5. Docker file paths
Command: ls -l /etc/apt/keyrings/docker.asc
Answer: /etc/apt/keyrings/docker.asc
Command: ls -l /etc/apt/sources.list.d/docker.sources

## 6. Remove htop and verify
Command: sudo apt remove -y htop
Command: hash -r
Command: htop
Answer: The command should not be dound after removal.

