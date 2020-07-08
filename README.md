# Android on Docker

I'm learning through building an android app on docker.

I started with [this article](https://medium.com/@AndreSand/building-android-with-docker-8dbf717f54d4) and then I'll follow [this tutorial](https://developer.okta.com/blog/2018/08/10/basic-android-without-an-ide).

## Docker

This is intended to be used:

```
docker build -t android-docker -f Dockerfile .
docker run -it android-docker bash # run interactively for development
```
