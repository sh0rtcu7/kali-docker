# Docker compose project to setup a kali and hashcat network

### Requirements
- Docker compose installation

### Setup
1. Set strong SSH passwords for both containers in `docker-compose.yml`
2. Set the hashcat image tag to the correct one for your hardware. https://hub.docker.com/r/dizcza/docker-hashcat/#Tags
3. Follow docker documentation to base though gpu
4. `docker compose up --build -d`
5. `ssh root@localhost`
6. ssh from the kali container to hashcat when needed `ssh root@hashcat`