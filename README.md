# Basic Project for getting started with Docker

![Untitled design (1)](https://user-images.githubusercontent.com/23248726/219093382-a1874751-a2f0-4be6-8bed-3c266276b57c.png)

This is a repository for a Docker project using Node, Express, and Express

[Video Link](https://youtu.be/b8ZUb_Okxro)

What is Docker

- Virtualisation software that makes developing and deploying applications easier
- It packages app with all necessary dependencies, configuration, system tools and runtime into one container

### Prerequisites

**Node version 14.x**

### Install packages

```shell
npm i
```

### Install Docker desktop app

[Docker Installation link](https://docs.docker.com/get-docker/)

```js
const MONGO_URL = ''; // DB URI
```

### Build Docker Image on your local

```shell
docker build -t node-app:1.0 .
```

### run the docker image that you created

```shell
docker run -d -p 3000:3000 node-app:1.0
```

## Navigate to local host 3000

```shell
http://localhost:3000/
```

## Open your terminal and type following to see the running docker container

```shell
docker ps
```

## Learn more by following this video

[Video Link](https://www.youtube.com/watch?v=pg19Z8LL06w&ab_channel=TechWorldwithNana)
