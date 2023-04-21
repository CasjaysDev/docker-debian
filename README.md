## 👋 Welcome to debian 🚀  

custom debian image with bash, tini, certbot installed  
  
  
## Run container

```shell
docker run --name -casjaysdev-debian casjaysdev/debian bash
```
  
  
## Install my system scripts  

```shell
 sudo bash -c "$(curl -q -LSsf "https://github.com/systemmgr/installer/raw/main/install.sh")"
 sudo systemmgr --config && sudo systemmgr install scripts  
```

## Get source files  

```shell
dockermgr download src casjaysdev/docker-debian
```

OR

```shell
git clone "https://github.com/casjaysdev/docker-debian" "$HOME/Projects/github/casjaysdev/docker-debian"
```

## Build container  

```shell
cd "$HOME/Projects/github/casjaysdev/docker-debian"
buildx 
```

## Authors  

🤖 casjay: [Github](https://github.com/casjay) 🤖  
⛵ casjaysdev: [Github](https://github.com/casjaysdev) [Docker](https://hub.docker.com/r/casjaysdev) ⛵  
