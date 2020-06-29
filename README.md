# Hello World Example
This application simply shows 'Hello World' on a web browser.

## Docker build
```
docker build -t ${YOUR_DOCKER_HUB_ID}/helloworld .
```

## Docker run
```
docker run -p 80:80 -d ${YOUR_DOCKER_HUB_ID}/helloworld
```
Now the server is available at http://localhost.

Note that the docker image can be deployed using any docker-based deploy platform (e.g. [ainize.ai](https://ainize.ai)).

