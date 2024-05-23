# Node Hello World

Simple node.js app that servers "hello world"

Great for testing simple deployments to the cloud

## Run It

`npm start`

# Run Node Hello Word Using Docker
To build The DockerFile
```
docker build -t nodeapp/v1 .
```
After Build 
```
docker run -d -p 3000:3000 nodeapp/v1
```
