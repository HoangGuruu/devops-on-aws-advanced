# DevOps on AWS Real Project - All In One

## Containerization Microservices Project

### Install Docker 

- You can reference this way
[Install Docker on Ubuntu](https://www.google.com)
- Or this way
```sh
# Install Docker by script
curl -fsSL https://get.docker.com -o get-docker.sh
sh get-docker.sh

docker --version

sudo usermod -aG docker $USER
sudo chmod 660 /var/run/docker.sock
newgrp docker

```
