# Installing Docker Compose

```
sudo curl -L https://github.com/docker/compose/releases/download/1.21.0/docker-compose-`uname -s`-`uname -m` | sudo tee /usr/local/bin/docker-compose > /dev/null
sudo chmod +x /usr/local/bin/docker-compose
sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose
docker-compose --version
```

> Clone the following repo
```
git clone https://github.com/rgaino/docker-node-react-mysql-boilerplate.git
cd docker-node-react-mysql-boilerplate

```

> Build using docker build
Change version from 3.7 to 3.3
```
docker-compose up
```

> Check if the services are up
```
docker-compose ps
```
