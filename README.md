# Hello world site

A very basic hello world website and httpd based container image to serve it. Useful for demonstrative purposes in articles and other learning material.


## How to build

```s
docker build . -t sbracegirdle/hellosite
```


## How to test

```s
docker run -d --rm -p 8080:80 sbracegirdle/hellosite
```

Open http://localhost:8080 to test.


## How to publish

```s
docker push sbracegirdle/hellosite
```
