# Install Docker and Docker Compose

```
sudo apt install apt-transport-https ca-certificates curl software-properties-common -y && 
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add - && 
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu jammy stable" && 
sudo apt-get update && 
sudo apt-get install docker-ce docker-ce-cli containerd.io docker-compose-plugin -y
```
# Check Version
```
docker version
```
```
docker compose version
```
# Check Active Containers
```
docker ps
```
# Check All Containers
```
docker ps -a
```
# Stop Container
```
docker stop CONTAINER_NAME
```
# Restart Container
```
docker restart CONTAINER_NAME
```
# Remove Container
```
docker rm CONTAINER_NAME
```
# Check All Images
```
docker images -a
```
# Remove Images
```
docker rmi IMAGE_ID
```
# Check All Volumes
```
docker volume ls
```
# Remove Volumes
```
docker volume rm VOLUME_NAME
```
# Remove all Inactive Containers
```
docker container prune
```
# Remove all Unused Images
```
docker image prune -a
```
# Remove all Inactive Volumes
```
docker volume prune
```
# Remove all Remaining Builds
```
docker builder prune
```
# Remove all Inactive Components
```
docker system prune
```
