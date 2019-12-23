# GIT, Docker, PowerShell, and Bash Reference Guide
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
- : pushes the commits made on the local directory to the origin repository under the branch specified:
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