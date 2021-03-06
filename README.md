# PlexMediaServer


### Installation
---

```

$ sudo apt install curl
$ apt-get install sl 

$ git clone git@github.com:jonathankablan/plexmediaserver-docker-compose.git
$ cd plexmediaserver-docker-compose
$ ./install.sh


$ sudo dpkg -i plexmediaserver_1.19.3.2764-ef515a800_amd64.deb
$ sudo apt-get update


In this instance PUID=1000 and PGID=1000, to find yours use id user as below:

$ id username
  uid=1000(dockeruser) gid=1000(dockergroup) groups=1000(dockergroup)

$ sudo usermod -a -G abc abc
$ sudo usermod -a -G 1000 1000
$ sudo chown -R abc:abc /home/plexmediaserver-docker-compose/mediaserver  
$ sudo chown -R 1000:1000 /home/plexmediaserver-docker-compose/mediaserver 
```


Installation Docker

```
sudo apt-get remove docker docker-engine docker.io containerd runc

```


```

docker network create frontend-network

$ ssh-keygen -t rsa -b 4096 -C "jonathan.kablan@gmail.com"

$ sudo apt-get remove docker docker-engine docker.io containerd runc

$ sudo apt-get update

$ sudo apt-get install \
    apt-transport-https \
    ca-certificates \
    curl \
    gnupg-agent \
    software-properties-common

$ curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -

$ sudo apt-key fingerprint 0EBFCD88

$ sudo add-apt-repository \
   "deb [arch=amd64] https://download.docker.com/linux/ubuntu \
   $(lsb_release -cs) \
   stable"

$ sudo apt-get update
$ sudo apt-get install docker-ce docker-ce-cli containerd.io


```

Installation Docker Compose

```
$ sudo curl -L "https://github.com/docker/compose/releases/download/1.24.0/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose

$ sudo chmod +x /usr/local/bin/docker-compose

```


### Installation front-end
---

Installation des dépendances :

```
cd app/integration
yarn install
```

Pour plus d'informations, consulter le fichier [README.md](app/integration/README.md)

### Configuration
---

### Authors / Maintainers
---

- Jonathan Kablan
