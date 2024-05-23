# Node Hello World

Simple node.js app that servers "hello world"

Great for testing simple deployments to the cloud

## Run It

`npm start`

# Run Node Hello World Using Docker
To build The DockerFile
```
docker build -t nodeapp/v1 .
```
After Build 
```
docker run -d -p 3000:3000 nodeapp/v1
```

# Run Node Hello World Using Docker-Compose
```
docker compose up -d --build
``` 

# Quick Set-Up In Ubuntu
Copy setup.sh In Linux Server and Give Permission;
```
chmod +x setup.sh
```
and Then Run;
```
sudo ./setup.sh
```
