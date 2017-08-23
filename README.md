# Common-Docker-Powershell
list of common powershell commands for docker. 

# Cleanup
## Containers (must be stopped)
`docker rm @(docker ps -aq)`

## Images 
`docker rmi @(docker images -aq)`

# Show Logs
`docker logs <container Id>`
