# Devops

### Docker no space left in device
* Remove dangling volumes to clear space
* ```docker volume rm `docker volume ls -q -f dangling=true```
