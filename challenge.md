# Challenge Answers

1. htop shows live CPU and memory usage.
   Command: sudo apt install -y htop ; htop

2. apache2 version offered: (2.4.66-2ubuntu2.6)
   Command: apt show apache2 | head -4

3. Installed packages:(734 )
   Command: apt list --installed | wc -l

4. Printed Hello from Alpine.
   Command: sudo docker run --rm alpine echo "Hello from Alpine"

5. Docker key: /etc/apt/keyrings/docker.asc
   Docker sources: /etc/apt/sources.list.d/docker.sources
   Command: ls -l /etc/apt/keyrings/ ; ls /etc/apt/sources.list.d/

6. htop removed, now gives command not found.
   Command: sudo apt remove -y htop ; hash -r ; htop
