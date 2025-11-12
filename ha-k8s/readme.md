## Chuẩn bị sẵn môi trường để triển khai
- 2 Load Balancer (2 CPU 2GB)
- 3 Node Master K8S (4GB)
- 3 Node Worker K8S (4-8GB)
- 1 Server Ansible Control (2 CPU 2GB)
 ## Cài đặt trên các máy 
 1. Ansible Control 
 - python3 
 - ansible-galaxy
 2. Load balancer
 - python3
 - Ha proxy 
 - Keepalived
 3. K8S master,worker
 - python3