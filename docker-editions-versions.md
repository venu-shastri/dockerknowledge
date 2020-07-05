
# Docker-Editions-Versions

-  Docker Community Edition (free)
   - Aimed At developers and and DIY ops teams
   - Production ready
	- Opens source
-  Docker Enterprise Edition
   - Mission Critical Apps  
   - Certified Images and plugins
   - Docker Data Center
   - Vulnerability Scans
   - Official Support
   -  $750 to $1200 Per year

## Docker Versions
### Docker CE has Two release channels
- Edge Release
	- New Release Cycle Every Month
- Stable Release
	- New Releases for Every three months
![Version Chart](https://github.com/venu-shastri/dockerknowledge/blob/master/images.JPG)

# Installing docker
### docker toolbox
- docker CE / EE
- docker compose
- docker machine
- virtual box
- docker quick start terminal
- kitematic
### docker for windows / mac
- No Virtual Box is required
- Uses Hyper - v

docker tools      | docker for windows 
 -------- | ---
 Need a type 2 Hypervisor | Need a type 1 hyper-v
 docker deamon remote | docker deamon local 
 Access Using Ip address | Access using local address
 docker quick start terminal | Any terminal

## Verifying docker installation
- Go terminal and type following command
	- **docker info**
	- **docker-compose --version**
	- **docker run hello-world**
	- **docker run -it alpine sh**
  
 
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTU5NTgzMzQ5MiwtMTYzMTUzMjY3OCwtMT
YyNjkwNjI5LC0xNzcyNzE0MjEsLTIwNjY0ODEwNjQsMTcyMzcz
NTA3NiwtMTI2NjkyMzgwMywxOTE5ODUyNzQ1LDExNzMxNjE5Nz
FdfQ==
-->