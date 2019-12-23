# GIT, Docker, PowerShell, and Bash Reference Guide
 A simple reference guide for GIT, Docker, PowerShell, and Bash commands.

## GIT
Git is a version control software. It is used to keep track of changes made to a group project. The software can be used to track various files but is most popular in software development
![Sample GIT command](http://techgenix.com/tgwordpress/wp-content/uploads/2019/03/1067-02-05.png?ezimgfmt=rs:848x267/rscb1)
- To copy a repository into the current local directory
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
- To push the commits made on the local directory to the origin repository under the branch specified
```
git push origin *branch name* 
```
- To see the last action made to the local repository:
```
git log --oneline
```

## Docker
Docker is an application used to create and maintain containers. It uses OS level virtualiztion to containerize applications. Unlike hypervisors, docker containers only consume the system resources that are needed by a container.
![Sample Docker Command](https://stefanscherer.github.io/content/images/2015/08/docker-version-png-shadow.png)
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
![Sample Powershell command](https://www.faqforge.com/wp-content/uploads/2017/08/Untitled.png)
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
Bash is a Unix shell and command language created for the GNU operating system.
![Sample Bash Command](https://www.varonis.com/blog/wp-content/uploads/2016/09/powershell-ls.png)
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



