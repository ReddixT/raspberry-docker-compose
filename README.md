# raspberry-docker-compose
These are all docker-compose.yml files that I use on my raspberry.

If you have any questions about setting these containers up, you can create an [issue](https://github.com/ReddixT/raspberry-docker-compose/issues).
## Install Docker
```bash
curl -sSL https://get.docker.com | sh
sudo usermod -aG docker ${USER}
```
## Install Docker Compose
```bash
sudo apt-get install -y libffi-dev libssl-dev python3-dev python3 python3-pip
sudo pip3 install docker-compose
```
## Create Docker Stack
1. Update `<VARIABLES>` in docker-compose.yml
2. Create a directory including the docker compose file. The directory name will be the stack name
3. Run this command
```bash
docker compose up -d
```
## Templates
- [Bitwarden](https://github.com/ReddixT/raspberry-docker-compose/tree/main/bitwarden)
- [Filerun](https://github.com/ReddixT/raspberry-docker-compose/tree/main/filerun)
- [GoDaddy DDNS](https://github.com/ReddixT/raspberry-docker-compose/tree/main/godaddy-ddns)
- [Nginx Proxy Manager](https://github.com/ReddixT/raspberry-docker-compose/tree/main/nginx-proxy-manager)
- [PiHole](https://github.com/ReddixT/raspberry-docker-compose/tree/main/pihole)
- [Portainer](https://github.com/ReddixT/raspberry-docker-compose/tree/main/portainer)