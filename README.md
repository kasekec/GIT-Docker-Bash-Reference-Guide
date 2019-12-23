# GIT, Docker, PowerShell, and Bash Reference Guide
 A simple reference guide for GIT, Docker, PowerShell, and Bash commands.

## GIT
Git is a version control software. It is used to keep track of changes made to a group project. The software can be used to track various files but is most popular in software development
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
Docker is an application used to create and maintain containers. It uses OS level virtualiztion to containerize applications. Unlike hypervisors, docker containers only consume the system resources that are needed by a container.
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
docker images
```
- To pull an image from docker hub
```
docker pull *user/image*
```

## PowerShell
PowerShell is a task automation and configuration management framework craeted by Microsoft.
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

## Bash
Bash is a Unix shell and command language created for the GNU operating system
- To view which directory you are currently in 
```
pwd
```

- To list the contents of the directory you are currently in
```
ls
```

- To enter the parent directory of the directory you are currently in
```
cd ..
```
- To create a textfile in the directory you are currently in and open it
```
notepad *Textfile Name*
```



