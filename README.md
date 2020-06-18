# express-and-docker
🐳 docker image for node web app

## Install

1. Build image
```
$ docker build -t <your username>/node-web-app .
```

2. Now, you can see the image:
```
$ docker images
```

3. Run image
```
$ docker run -p 49160:8080 -d <your username>/node-web-app
```

Note: port `49160` of your machine is mapped to docker's internal port `8080`.


## GET /
When opening a browser and going to `localhost:49160` you should see a page with `🚀 Hello World`.
