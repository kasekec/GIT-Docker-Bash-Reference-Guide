# GIT, Docker, PowerShell, and Bash Reference Guide
 A simple reference guide for GIT, Docker, PowerShell, and Bash commands
## GIT
- To copy a repository into the current local directory:
```
git clone *Repository Name*
```
- To compare the local directory to the current origin repository
```
git status 
```
- To create a new branch and makes it the active branch that commands will be written to
```
git checkout -b *branch name*
```
- To push the commits made on the local directory to the origin repository under the branch specified:
```
git push origin *branch name* 
```
- To see the last action made to the local repository:
```
git log --oneline
```

## Docker
- To list all containers that are currently running
```
docker ps
```

- To start a container
```
docker start *container name or ID*
```

- To stop a container
```
docker stop *container name or ID*
```
- To list all images
```
docker stop *container name or ID*
```


## PowerShell
- To view which version of Windows you are running
```
winver
```
- To show the current date and time
```
Get-Date
```
- To show the only the current time
```
Get-Date -DisplayHint Time
```
- To view which directory you are currently in 
```
Get-Location
```
Powershell also supports legacy CLI commands. A few of them are listed below
- To check the availability of an ip address
```
ping *IP address/ URL*
```
- To view your current IP address
```
ipconfig
```
