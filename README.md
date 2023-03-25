## 👋 Welcome to debian 🚀  

debian README  
custom debian image with bash, tini, certbot installed  
  
## Run container

```shell
docker run casjaysdev/debian bash
```
  
  
## Install my system scripts  

```shell
 sudo bash -c "$(curl -q -LSsf "https://github.com/systemmgr/installer/raw/main/install.sh")"
 sudo systemmgr --config && sudo systemmgr install scripts  
```

## Get source files  

```shell
dockermgr download src debian
```

OR

```shell
git clone "https://github.com/casjaysdevdocker/debian" "$HOME/Projects/github/casjaysdevdocker/debian"
```

## Build container  

```shell
cd "$HOME/Projects/github/casjaysdevdocker/debian"
buildx 
```

## Authors  

📽 dockermgr: [Github](https://github.com/dockermgr) [Docker](https://hub.docker.com/r/casjaysdevdocker) 📽  
🤖 casjay: [Github](https://github.com/casjay) [Docker](https://hub.docker.com/r/casjay) 🤖  
⛵ CasjaysDevDocker: [Github](https://github.com/casjaysdevdocker) [Docker](https://hub.docker.com/r/casjaysdevdocker) ⛵  
