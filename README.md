# pay4later/docker-phpcomodo

A docker container to run an apache/php web service to interact with Comodo Antivirus' cmdscan utility.

## Building the image

```sh
docker build -t pay4later/docker-phpcomodo .
```

## Running the image

```sh
docker run -p 80:80 pay4later/docker-phpcomodo
```